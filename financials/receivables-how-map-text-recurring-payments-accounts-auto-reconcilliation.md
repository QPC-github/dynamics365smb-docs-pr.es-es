---
title: "Configurar la asignación de cuenta a texto para pagos periódicos | Documentos de Microsoft"
description: "Puede vincular el texto de los pagos con cuentas específicas, de modo que los pagos se registren en las cuentas al registrar el diario de conciliación de pagos."
services: project-madeira
documentationcenter: 
author: SorenGP
ms.service: dynamics365-financials
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: account linking, direct payment posting, automatic payment processing, reconcile payment, recurring expense, recurring cash receipt
ms.date: 03/29/2017
ms.author: sgroespe
ms.translationtype: Human Translation
ms.sourcegitcommit: 81636fc2e661bd9b07c54da1cd5d0d27e30d01a2
ms.openlocfilehash: deb05c6294edeb892606154b38de2aa406abf6a2
ms.contentlocale: es-es
ms.lasthandoff: 07/07/2017


---
# <a name="how-to-map-text-on-recurring-payments-to-accounts-for-automatic-reconciliation"></a>Asignación de texto en pagos periódicos a cuentas para conciliación automática
En la ventana **Asignación de texto a cuenta**, que se abre desde la ventana **Diario de conciliación de pagos**, puede configurar asignaciones entre el texto de los pagos y las cuentas de débito, crédito y saldo específicas para que los pagos se contabilicen en las cuentas específicas cuando contabilices el diario de conciliación de pagos.

> [!NOTE]  
>   El tema también se aplica a cuando utiliza la función **Asignar texto a cuenta** desde un registro de documento entrante para ayudar a convertir documentos electrónicos recibidos desde servicios externos a documentos en [!INCLUDE[d365fin](includes/d365fin_md.md)]. Para obtener más información, vea [Procedimiento: Usar el servicio OCR para convertir archivos PDF y de imagen en documentos](across-how-use-ocr-pdf-images-files.md).   

La funcionalidad similar existe para conciliar el exceso de importes en las líneas del diario de conciliación de pagos sobre una base ad hoc. Para obtener más información, vea [Procedimiento: Conciliar pagos que no pueden liquidarse automáticamente](receivables-how-reconcile-payments-cannot-apply-auto.md).

Los pagos registrados según la asignación de texto a cuenta no se aplican a movimientos pendientes, sino que simplemente se registran en las cuentas especificadas además de crear movimientos de bancos. Por consiguiente, la asignación de texto a cuenta es adecuada para recibos de cobro o gastos periódicos, como las compras frecuentes de combustible para vehículos u honorarios bancarios e intereses que se producen normalmente en el extracto bancario y no necesitan un documento empresarial relacionado. Para más información, consulte la sección “Ejemplo: asignación de texto a cuenta para gasto de combustible” de este tema.

> [!NOTE]  
>   Los pagos en las líneas de diario de conciliación solo están configuradas para el registro según la asignación de texto a cuenta si la función de liquidación automática únicamente puede proporcionar una confianza de correspondencia de **Baja** o **Media**. Si la función de aplicación automática proporciona confianza de la correspondencia Alta, el pago se liquida automáticamente a uno o más movimientos pendientes y no se contabiliza en las cuentas especificadas en la ventana **Asignación de texto a cuenta**. En otras palabras, una confianza de correspondencia **Alta** invalida la asignación de texto a cuenta.

En una línea del diario de conciliación de pagos en la que el pago se estableció en contabilizarse según la asignación de texto a cuenta, el campo **Confianza de la correspondencia** contiene **Asignación de texto a cuenta: Alta** y los campos **Tipo de cuenta** y **N.º cuenta**. contienen las cuentas asociadas.

## <a name="to-map-text-on-recurring-payments-to-accounts-for-automatic-reconciliation"></a>Para asignar texto en pagos periódicos a cuentas para conciliación automática
1. Seleccione el icono ![Buscar página o informe](media/ui-search/search_small.png "icono Buscar página o informe"), escriba **Diarios de conciliación de pagos** y, a continuación, seleccione el vínculo relacionado.
2. Abra un diario de conciliación de pagos. Para obtener más información, vea [Procedimiento: Conciliar pagos con liquidación automática](receivables-how-reconcile-payments-auto-application.md).
3. Seleccione la acción **Asociar texto a cuenta**. Se abre la ventana **Asignación de texto a cuenta**.
4. En el campo **Asignar texto**, introduzca cualquier texto de los pagos que quiera registrar en unas cuentas específicas sin aplicarlo a un movimiento pendiente. Puede escribir hasta 50 caracteres.

    > [!NOTE]  
>   Si no existen otros pagos o documentos entrantes con la asignación de texto en cuestión, la asignación tendrá lugar incluso cuando solo una parte del texto en el pago o el documento entrante exista como texto asignado.
5. En el campo **N.º proveedor**, introduzca el proveedor para el que se crearán documentos entrantes que contienen texto de asignación o se registrarán dichos documentos. Para obtener más información, vea [Procedimiento: Usar el servicio OCR para convertir archivos PDF y de imagen en documentos](across-how-use-ocr-pdf-images-files.md).      
6. En el campo **N.º cta. débito**, introduce la cuenta a la que se contabilizarán los pagos con texto asignado en caso de haber pagos entrantes. Para los pagos entrantes, el signo de valor en el campo **Importe extracto** es positivo.
7. En el campo **N.º cta. crédito**, introduce la cuenta a la que se contabilizarán los pagos con texto asignado en caso de haber pagos salientes. Para los pagos salientes, el signo de valor en el campo **Importe extracto** es negativo.
8. En el campo **Tipo origen contr.**, especifique si el pago se contabilizará en una cuenta contable o en una cuenta de cliente o proveedor.
9. En el campo **N.º origen contr.**, especifique la cuenta a la que se contabilizará el pago dependiendo de su elección en el campo **Tipo origen contr**.
10. Repita los pasos del 4 al 8 para todo el texto de los pagos que desea asignar a las cuentas para el registro directo sin liquidación.

La próxima vez que importe un archivo de un extracto bancario o seleccione la función **Liquidar automáticamente** de la ventana **Diario de conciliación de pagos**, las líneas de diario de los pagos que contienen el texto asignado especificado, incluirán las cuentas asignadas en **Tipo de cuenta** y **N.º cuenta**. . El campo **Confianza de la correspondencia** contendrá **Asignación de texto a cuenta: Alta** Esto es así siempre que la función de liquidación automática solo pueda proporcionar una confianza de correspondencia **Baja** o **Media**.

## <a name="example-text-to-account-mapping-for-fuel-expense"></a>Ejemplo: Asignación de texto a cuenta para gasto de combustible
Para que los gastos de combustible de las estaciones de servicio Shell siempre se contabilicen a la cuenta contable para la gasolina (cuenta 8510), rellene una línea en la ventana **Asignación de texto a cuenta** como se indica a continuación.

| Asignando texto | Cta. débito N.º | Cta. crédito N.º | Contrap. Tipo origen | Contrap. Cód. procedencia mov. |
| --- | --- | --- | --- | --- |
| Shell |EN BLANCO |8510 |Cuenta |EN BLANCO |

> [!TIP]  
>   Para obtener más información sobre cómo usar campos y columnas, consulte [Trabajar con [!INCLUDE[d365fin](includes/d365fin_long_md.md)]](ui-work-product.md). Para obtener más información sobre la búsqueda de páginas específicas, consulte [Buscar](ui-search.md).

## <a name="see-also"></a>Consulte también
[Administrar cobros](receivables-manage-receivables.md)  
[Ventas](sales-manage-sales.md)  
[Configuración del servicio de fuentes de banco de Envestnet Yodlee](bank-how-setup-bank-statement-service.md)  
[Personalizar [!INCLUDE[d365fin](includes/d365fin_md.md)] con extensiones](ui-extensions.md)  
[Trabajar con [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

---
title: "Cómo corregir prepagos | Documentos de Microsoft"
description: "Puede corregir un pedido después de haber registrado una factura de prepago para el mismo. Puede agregar nuevas líneas a un pedido después de emitir un prepago y, a continuación, registrar otra factura de prepago, pero no puede eliminar una línea de un pedido una vez que se haya facturado un prepago para la línea."
services: project-madeira
documentationcenter: 
author: SorenGP
ms.service: dynamics365-financials
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/04/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: bec0619be0a65e3625759e13d2866ac615d7513c
ms.openlocfilehash: 278e400970cb919ec25e21064c2ed58cdb0965cf
ms.contentlocale: es-es
ms.lasthandoff: 01/30/2018

---
# <a name="correct-prepayments"></a>Corregir prepagos
Puede corregir un pedido después de haber registrado una factura de prepago para el mismo. Puede agregar nuevas líneas a un pedido después de emitir un prepago y, a continuación, registrar otra factura de prepago, pero no puede eliminar una línea de un pedido una vez que se haya facturado un prepago para la línea.  

## <a name="to-correct-a-prepayment"></a>Para corregir un prepago
El procedimiento siguiente muestra cómo emitir una abono de prepago para cancelar todos los pagos adelantados facturados para un pedido de venta.  
1. Seleccione el icono ![Buscar página o informe](media/ui-search/search_small.png "icono Buscar página o informe"), escriba **Pedidos de venta** y, a continuación, seleccione el vínculo relacionado.  
2. Abra el pedido de venta correspondiente.
3. Elija la acción **Prepago** y **Registrar abono prepago** o **Registrar e imprimir abono prepago**.  
4. En la ventana **Abono venta**, corrija los movimientos correspondientes, en función de cualquier abono de venta. Para obtener más información, vea [Procesar devoluciones de ventas o cancelaciones](sales-how-process-sales-returns-cancellations.md).     

    > [!NOTE]  
    > Para reducir la cantidad del campo **Importe de línea**, antes debe aumentar el porcentaje de prepago de la línea, para que el valor del campo **Importe línea prepago** no se reduzca por debajo del valor del campo **Importe prepago facturado**.

5. Para crear una factura prepago para las nuevas líneas en el abono de ventas, elija las acciones **Prepago** y **Registrar factura prepago** o **Registrar e imprimir factura prepago**.  
6. Para emitir una factura de prepago adicional, aumente la cantidad de prepago de una o varias líneas y registre la factura de prepago. Se creará una nueva factura con la diferencia entre las cantidades de prepago facturadas y las nuevas cantidades de prepago.  

## <a name="see-also"></a>Consulte también  
[Facturación de prepagos](finance-invoice-prepayments.md)  
[Tutorial: Configuración y facturación de prepagos de ventas](walkthrough-setting-up-and-invoicing-sales-prepayments.md)  
[Finanzas](finance.md)  
[Trabajar con [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

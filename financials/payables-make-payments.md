---
title: Resumen de tareas para administrar los pagos a proveedores | Documentos de Microsoft
description: "Describe las tareas para administrar los pagos a proveedores o acreedores, incluido el registro de líneas de pago, y obtener un resumen de saldo vencido."
services: project-madeira
documentationcenter: 
author: SorenGP
ms.service: dynamics365-financials
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: print check, vendor payment, creditor, debt, balance due, AP
ms.date: 06/06/2017
ms.author: sgroespe
ms.translationtype: Human Translation
ms.sourcegitcommit: 81636fc2e661bd9b07c54da1cd5d0d27e30d01a2
ms.openlocfilehash: d0b9020596484a8910db2f5720adfe159ad96fe7
ms.contentlocale: es-es
ms.lasthandoff: 07/07/2017


---
# <a name="make-payments"></a>Hacer los pagos
Cuando efectúa pagos a proveedores, registra las líneas de pago relacionadas en la ventana **Diario de pagos**. Puede usar la función **Proponer pagos a proveedores** para buscar los pagos vencidos. También puede usar el informe **Proveedor - Pagos por periodos** para obtener una visión general de los pagos vencidos.

Desde el diario de pagos, puede imprimir cheques automáticos o registrar cuándo se escriben los cheques. Si selecciona **Cheque automático** en el campo **Tipo pago por banco**, las líneas que representan cheques se deben imprimir antes de que se pueda registrar el diario de pagos.

Cuando se registran los pagos, puede exportarlos a un archivo de banco que se cargará al sitio de banco electrónico para su procesamiento.

Cuando se hayan efectuado los pagos en su banco, debe liquidarlos a sus movimientos de proveedor abiertos relacionados. Puede hacerlo manualmente o importando un archivo de extracto bancario y liquidando los pagos automáticamente. Para obtener más información, vea [Liquidar pagos automáticamente y conciliar cuentas bancarias](receivables-apply-payments-auto-reconcile-bank-accounts.md).

En la tabla siguiente se indican una serie de tareas con vínculos a los temas que las describen.

| Para | Vea |
| --- | --- |
| Use una función para sugerir pagos de proveedores según los criterios seleccionados, como la fecha de vencimiento, la posibilidad de aplicar descuentos o su liquidez. |[Propuesta de pagos a proveedores](payables-how-suggest-vendor-payments.md) |
| Emita cheques para realizar pagos, ya sea como copias impresas o como cheques automáticos. Anule los cheques antes o después del registro. |[Trabajar con cheques](payables-how-work-checks.md) |
| Asegúrese de que su banco solo compensa cheques e importes validados enviándoles un archivo que contenga la información de proveedor, cheque y pago. |[Exportar un archivo de Positive Pay](finance-how-positive-pay.md) |
|Exporte los pagos desde la ventana **Diario de pagos** a un archivo de banco que envíe a su banco para su procesamiento, incluido EFT (transferencia electrónica de fondos) en Norteamérica. |[Exportación de pagos a un archivo de banco](payables-how-export-payments-bank-file.md)|  

## <a name="see-also"></a>Consulte también
[Administrar pagos](payables-manage-payables.md)  
[Compras](purchasing-manage-purchasing.md)  
[Administrar cobros](receivables-manage-receivables.md)  
[Trabajar con [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  

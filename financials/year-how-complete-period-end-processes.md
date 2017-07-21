---
title: Actividades opcionales para periodos de cierre | Documentos de Microsoft
description: En este tema se describen los procesos y las actividades opcionales para cerrar periodos contables en Financials.
services: project-madeira
documentationcenter: 
author: jswymer
ms.service: dynamics365-financials
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: year closing, close accounting period, close fiscal year, aging, creditor payments, vendor payments
ms.date: 06/02/2017
ms.author: jswymer
ms.translationtype: Human Translation
ms.sourcegitcommit: 81636fc2e661bd9b07c54da1cd5d0d27e30d01a2
ms.openlocfilehash: 678cebc065594ed0ed6fea897676f109ff2c1dce
ms.contentlocale: es-es
ms.lasthandoff: 07/07/2017


---
# <a name="overview-of-tasks-to-close-accounting-periods"></a>Resumen de tareas para cerrar periodos contables
[!INCLUDE[d365fin](includes/d365fin_md.md)] no le fuerza a cerrar los períodos, pero numerosas actividades de fin de período (fin de mes) que puede realizar. Este tema proporciona una visión general de procesos y actividades opcionales para cerrar períodos.  

## <a name="general-ledger"></a>Contabilidad
* Especifique períodos de registro para todo el sistema y específicos para el usuario.  

    Esto especifica las fechas entre las cuales puede efectuar registros. En función de su empresa, puede permitir el registro al inicio del periodo o hacia el final. Para obtener más información, vea [Procedimiento: Especificar periodos de registro](finance-how-specify-posting-periods.md).  
* Lleve a cabo todos los ajustes de contabilidad necesarios.  
* Actualice y registre los Diarios periódicos.  
  <!--* Process Consolidations-->
* Ejecute los esquemas de cuentas como se indica a continuación:  
  * Abra la ventana **Esquema cuentas** y, a continuación, seleccione la acción **Imprimir**.  

## <a name="sales-and-receivables"></a>Ventas y cobros
* Registre todos los pedidos, facturas, abonos y devoluciones de ventas.  
* Registre todo los diarios de recibo cobros.  
* Actualice y registre los diarios periódicos relativos a ventas y cobros.  
* Concilie los cobros en el libro de contabilidad.  
* Ejecute el proceso **Eliminar peds. venta factdos**.  

## <a name="purchases-and-payables"></a>Compras y pagos
* Registre todos los pedidos, facturas, abonos y devoluciones de compra.  
* Registre todos los registros de pagos.  
* Actualice y registre los diarios periódicos que son relativos a compras y pagos.  
* Ejecute el informe **Antigüedad pagos** y concilie las cuentas por pagar en el libro de contabilidad.  
* Ejecute el proceso **Eliminar peds. compra factdos**.  

<!-- ### Fixed Assets
* Post all maintenance costs have been posted through the fixed asset journals or invoices.
* Post adjustments.
* Post appreciation.
* Post depreciation.
* Update and post the recurring fixed asset journal.-->

<!--### Intercompany
* Process Intercompany Postings.-->

## <a name="calculate-and-process-sales-tax"></a>Calcular y procesar los impuestos de venta
* Realice los extractos de impuesto.  

## <a name="see-also"></a>Consulte también
[Cerrar años y periodos](year-close-years-periods.md)  
[Cierre de libros](year-close-books.md)  
[Trabajar con [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

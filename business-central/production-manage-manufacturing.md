---
title: "Ejecutar producción | Documentos de Microsoft"
description: "Cuando se ha planificado un pedido y se han emitido los materiales de acuerdo con la L.M. de producción, entonces, pueden iniciarse las operaciones de producción y se pueden ejecutar en la secuencia definida por la ruta de órdenes de producción."
services: project-madeira
documentationcenter: 
author: SorenGP
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/26/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: d7fb34e1c9428a64c71ff47be8bcff174649c00d
ms.openlocfilehash: c97cdafceb5fbf8df403309dddda0faeac7a26b6
ms.contentlocale: es-es
ms.lasthandoff: 03/22/2018

---
# <a name="manufacturing"></a>Fabricación
Cuando se ha planificado un pedido y se han emitido los materiales de acuerdo con la L.M. de producción, entonces, pueden iniciarse las operaciones de producción y se pueden ejecutar en la secuencia definida por la ruta de órdenes de producción.  

Una parte importante de la ejecución de la producción, desde el punto de vista del sistema, es el registro de la salida de la producción en la base de datos, para notificar el progreso y actualizar el inventario con los productos terminados. El registro de la salida se puede realizar manualmente, rellenando y registrando las líneas del diario después de las operaciones de producción. O bien, se puede efectuar de forma automática, utilizando la baja retroactiva. En ese caso, el consumo de material se registra automáticamente junto con la salida cuando el pedido de producción cambia a terminado.  

Como alternativa al diario de lotes para el registro de salida de varias órdenes de producción, es posible utilizar la ventana **Diario de producción** para registrar el consumo y la salida de una línea de orden de producción.

Antes de que pueda comenzar a producir elementos, debe realizar varias configuraciones, como centros de trabajo, rutas y listas de materiales de producción. Para obtener más información, vea [Configurar fabricación](production-configure-production-processes.md).

En la tabla siguiente se indican una serie de tareas con vínculos a los temas que las describen.   

|**Para**|**Vea**|  
|------------|-------------|  
|Conocer cómo funcionan las órdenes de producción.|[Sobre los pedidos de producción](production-about-production-orders.md)|
|Crear órdenes de producción de forma manual.|[Crear ordenes de producción](production-how-to-create-production-orders.md)|
|Externalice todas o las operaciones seleccionadas en una orden de producción a un subcontratista.|[Subcontratación de fabricación](production-how-to-subcontract-manufacturing.md)|
|Registrar y contabilizar la salida de la producción, junto con el consumo de tiempo y material, para una única línea de orden de producción lanzada.|[Registrar el consumo y la salida de una línea de orden de producción lanzada](production-how-to-register-consumption-and-output.md)|  
|Registre por lotes el número de componentes utilizados por operación en un diario que pueda procesar múltiples órdenes de producción planificadas.|[Registre consumibles por lotes](production-how-to-post-consumption.md)|
|Registre el número de productos terminados y el tiempo empleado por operación en un diario que pueda procesar múltiples órdenes de producción lanzadas.|[Registrar por lotes el resultado y los tiempos de ejecución](production-how-to-post-output-quantity.md)|  
|Contabilizar el número de artículos producido en cada operación terminada que no se cualifican como salida terminada, sino como material rechazado.|[Registrar material de rechazo](production-how-to-post-scrap.md)|
|Ver la carga de planta como resultado de órdenes de producción planificadas y lanzadas.|[Visualizar la carga en centros de trabajo y de máquina](production-how-to-view-the-load-on-work-centers.md)|      
|Utilizar la ventana **Diario de capacidad** para registrar capacidades consumidas que no están asignadas a una orden de producción, como el trabajo de mantenimiento.|[Registrar capacidades](production-how-to-post-capacities.md)|  
|Calcular y ajustar el coste de artículos de producción terminados y componentes consumidos para la reconciliación financiera.|[Sobre los costes de la orden de producción terminada](finance-about-finished-production-order-costs.md)|  

## <a name="see-also"></a>Consulte también  
[Configuración de fabricación](production-configure-production-processes.md)  
[Planificación](production-planning.md)      
[Grupos contables inventario](inventory-manage-inventory.md)  
[Compras](purchasing-manage-purchasing.md)  
[Trabajar con [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

## [!INCLUDE[d365fin](includes/free_trial_md.md)]  
## [!INCLUDE[d365fin](includes/training_link_md.md)]

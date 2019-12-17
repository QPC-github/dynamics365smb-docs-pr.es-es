---
title: Configuración de los métodos de envío | Documentos de Microsoft
description: Puede configurar un código para cada uno de los métodos de envío ofrecidos, por ejemplo, e introducir información sobre ellos.
author: SorenGP
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: incoterms
ms.date: 10/01/2019
ms.author: sgroespe
ms.openlocfilehash: 75a3e689083e64f446e84b2bc3b1d26961e3d898
ms.sourcegitcommit: cfc92eefa8b06fb426482f54e393f0e6e222f712
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 12/03/2019
ms.locfileid: "2877548"
---
# <a name="set-up-shipment-methods"></a>Configuración de métodos de envío
Los métodos de envío, también llamados incoterms, a menudo dependen de los productos, los clientes y los proveedores. Por ejemplo, si el cliente reside en una isla, puede elegir que le envíen siempre los productos por barco o por avión. Algunos clientes pueden requerir la entrega al día siguiente. Algunos pueden querer recoger el pedido. Puede especificar el tipo de entrega deseado en las fichas de cliente y de proveedor.

En la página **Métodos de envío**, configure la descripción y el código correspondiente a cada método de envío. Por ejemplo, puede configurar el código FAB e introducir Franco a bordo en el campo **Descripción**. A continuación, puede introducir el código en los campos **Código de método de envío** en otra parte del sistema, como en una ficha cliente. A continuación, cuando cree nuevos pedidos, facturas, abonos, etc., el sistema introducirá la descripción incluida en el código. Se puede modificar en el documento según sea necesario.

## <a name="to-set-up-a-shipment-code"></a>Para configurar un código de envío
1. Elija el icono ![Bombilla que abre la función Dígame](media/ui-search/search_small.png "Dígame qué desea hacer"), escriba **Métodos de envío** y luego elija el enlace relacionado.
2. En la página **Métodos de envío**, seleccione la acción **Nuevo**.
3. En la nueva línea especifique un código y una descripción para el método de envío.

## <a name="see-also"></a>Consulte también
[Incoterms](https://iccwbo.org/resources-for-business/incoterms-rules)  
[Configurar transportistas](sales-how-to-set-up-shipping-agents.md)  
[Hacer un seguimiento de los paquetes](sales-how-track-packages.md)    
[Gestión de almacenes](warehouse-manage-warehouse.md)  
[Inventario](inventory-manage-inventory.md)  
[Configuración de la gestión del almacén](warehouse-setup-warehouse.md)     
[Gestión de ensamblaje](assembly-assemble-items.md)    
[Detalles de diseño: Gestión de almacén](design-details-warehouse-management.md)  
[Trabajar con [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  
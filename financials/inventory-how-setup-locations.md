---
title: "Configurar una ficha de almacén y definir las rutas de transferencia | Documentos de Microsoft"
description: "Puede crear una ficha de almacén para cada lugar donde almacene productos de inventario, por ejemplo, un almacén o un centro de distribución, y configurar rutas para transferir los productos entre almacenes."
services: project-madeira
documentationcenter: 
author: SorenGP
ms.service: dynamics365-financials
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: warehouse, distribution center
ms.date: 06/02/2017
ms.author: SorenGP
ms.translationtype: Human Translation
ms.sourcegitcommit: 81636fc2e661bd9b07c54da1cd5d0d27e30d01a2
ms.openlocfilehash: 146fc08f389a5c068044358c59b7d8911f0b3343
ms.contentlocale: es-es
ms.lasthandoff: 07/07/2017


---
# <a name="how-to-set-up-locations"></a>Configuración de almacenes
Si compra, almacena o vende productos en más de un sitio o almacén, debe configurar cada ubicación con una ficha de almacén y definir las rutas de transferencia.

Así podrá crear las líneas de documento para un almacén específico, consultar la disponibilidad por almacén y transferir inventario entre almacenes. Para obtener más información, vea [Administrar inventario](inventory-manage-inventory.md).

> [!NOTE]  
>   Esta funcionalidad requiere que la experiencia esté definida en **Conjunto de aplicaciones**. Para obtener más información, consulte [Personalizar la experiencia de [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-experiences.md).

## <a name="to-create-a-location-card"></a>Para crear una ficha de almacén
1. Seleccione el icono ![Buscar página o informe](media/ui-search/search_small.png "icono Buscar página o informe"), escriba **Almacenes** y, a continuación, seleccione el vínculo relacionado.
2. Seleccione la acción **Nuevo**.
3. En la ventana **Ficha de almacén**, rellene los campos según sea necesario. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
4. Repita los pasos 2 y 3 para cada almacén en el que desea guardar el inventario.

## <a name="to-create-a-transfer-route"></a>Para crear una ruta de transferencia
1. Seleccione el icono ![Buscar página o informe](media/ui-search/search_small.png "icono Buscar página o informe"), escriba **Rutas de transferencia** y, a continuación, seleccione el vínculo relacionado.
2. Opcionalmente, desde cualquier ventana **Ficha almacén**, elija la acción **Rutas de transferencia**.
3. Seleccione la acción **Nuevo**.
4. En la ventana **Ficha de almacén**, rellene los campos según sea necesario. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

Ahora puede transferir productos de inventario entre dos almacenes. Para obtener más información, vea [Procedimiento: Transferir el inventario entre almacenes](inventory-how-transfer-between-locations.md).    

## <a name="see-also"></a>Consulte también
[Gestionar inventario](inventory-manage-inventory.md)  
[Cadena de suministro](madeira-supply-chain.md)  
[Transferir el inventario entre almacenes](inventory-how-transfer-between-locations.md)    
[Trabajar con [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  
[Personalizar la experiencia de [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-experiences.md)  
[Funciones empresariales generales](ui-across-business-areas.md)

---
title: P+F sobre aplicaciones móviles
description: Consulte las respuestas a las preguntas frecuentes sobre el uso de Business Central en su teléfono o tableta.
author: edupont04
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: phone, tablet
ms.date: 10/15/2020
ms.author: edupont
ms.openlocfilehash: e551bb66131c4c5b472f6088e283e9ba8dab4014
ms.sourcegitcommit: 2e7307fbe1eb3b34d0ad9356226a19409054a402
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 12/17/2020
ms.locfileid: "4756797"
---
# <a name="mobile-apps-faq"></a>P+F sobre aplicaciones móviles

Este artículo responde las preguntas que nuestros usuarios avanzados suelen hacer sobre las aplicaciones móviles para [!INCLUDE [prod_short](includes/prod_short.md)].  

## <a name="is-there-an-app-for-my-device"></a>¿Existe una aplicación para mi dispositivo?

¡Probablemente! Instale la aplicación [!INCLUDE[prod_short](includes/prod_short.md)] en su dispositivo móvil descargándola desde la Tienda Windows, el App Store o Google Play.

- [Tienda de Windows](https://go.microsoft.com/fwlink/?LinkId=734848) (Solo PC)
- [Tienda de aplicaciones](https://go.microsoft.com/fwlink/?LinkId=734847)
- [Google Play](https://go.microsoft.com/fwlink/?LinkId=734849)

## <a name="is-it-the-same-experience-in-the-apps-as-in-the-browser"></a>¿Es la misma experiencia en las aplicaciones que en el navegador?

No, no exactamente. Por ejemplo, mostramos solo el grupo de actividades **Casa** debido al tamaño limitado de la pantalla en los dispositivos móviles. Del mismo modo, los atajos de teclado no están disponibles porque utiliza principalmente el tacto en lugar de un teclado para navegar en dispositivos móviles.

La siguiente tabla describe algunas de las diferencias y limitaciones más comunes que puede experimentar al usar [!INCLUDE [prod_short](includes/prod_short.md)] en dispositivos móviles, en comparación con el navegador.

| Concepto | En tabletas | En teléfonos | Ejemplo del navegador |
|--|--|--|--|
| Grupos de actividades | Solo se muestra el grupo de actividades **Casa**. | Solo se muestra el grupo de actividades **Casa**. | **Casa** y **Documentos publicados** en el Centro de funciones de `Sales Order Processor`. |  |
| Seleccionar varios registros en listas | No disponible. | No disponible. | `Ctrl+A` o `Ctrl+Click` en filas en una lista en el navegador. |
| Acciones en la barra de acciones | Solo se muestran las acciones promocionadas. | Solo se muestran las acciones promocionadas. |  |
| Cuadros informativos | No se muestra en las páginas de la lista ni en las hojas de trabajo. | No se muestra en las páginas de la lista ni en las hojas de trabajo. | Lista `Customer` en el área de trabjao `Small Business`. |
| Filtros avanzados | No está disponible ningún filtrado específico de columna. | No está disponible ningún filtrado específico de columna. | Sobre la página de lista `Customer`. |
| Dígame | No disponible todavía. | No disponible todavía. | Vea [Búsqueda de páginas e información con Dígame](ui-search.md). |  |
| Explorador de roles | No disponible todavía. | No disponible todavía. | Vea [Búsqueda de páginas con el explorador de roles](ui-role-explorer.md). |
| Campos de fichas desplegables | No se muestran los campos en FastTabs en las páginas de lista. Solo el control del repetidor se muestra en el área de contenido de la página. | No disponible. |  |
| Seleccionar de la lista completa | No disponible en búsquedas. Los usuarios no pueden ejecutar acciones en una página de búsqueda y no pueden acceder al conjunto completo de registros. | No disponible en búsquedas. Los usuarios no pueden ejecutar acciones en una página de búsqueda y no pueden acceder al conjunto completo de registros. | En `Item Card` al seleccionar **Unidades de medida base**. |
| Buscar en las columnas de la lista | Compatible parcialmente. La búsqueda no incluirá FlowFields. | Compatible parcialmente. La búsqueda no incluirá FlowFields. | Vea ejemplos en la página de lista `Customers`. |
| Búsquedas | Disponible. | Disponible, con la diferencia de que las búsquedas avanzadas y simples se comportan de manera similar en el teléfono. La búsqueda no mostrará la tarjeta, no mostrará FactBoxes ni ningún grupo de campos. | Vea ejemplos en la página `Customer Card`. |
| Controles de matriz | No disponible. | No disponible. | Vea el ejemplo en `G/L Budget`. |
| Descarga de archivos | Disponible. No se pueden descargar varios archivos al mismo tiempo. | Disponible. No se pueden descargar varios archivos al mismo tiempo. | Informe `Trial Balance` en la casilla **Imprimir en Excel**. |
| Páginas de hoja de trabajo | Disponible. | No disponible; se muestra un mensaje de error. | Hoja de trabajo `Sales Price` o `Cash Flow`. |
| Listas | Disponible. | Disponible, con la diferencia de que se muestran en un diseño de ladrillo. | Páginas de clientes o pedidos de venta. |
| Sangría en los controles del repetidor | Disponible. | No disponible. El control del repetidor se representará como un diseño de ladrillo plano normal. | Páginas de plan de cuentas y lista de contactos. |
| Enfoque de entrada automático en el primer campo editable de una página | No disponible. | No disponible. | Página `Customer Card`.<BR /><BR />En el navegador, el foco estará automáticamente en el primer campo editable (como el campo `Name`), lo que le permite cambiar el valor de inmediato.<BR /><BR />En las aplicaciones para tabletas y teléfonos, este campo no estará enfocado; en su lugar, primero tendrá que seleccionar manualmente el campo para realizar cambios.|

## <a name="is-it-the-same-experience-on-tables-and-phones"></a>¿Es la misma experiencia en tabletas y teléfonos?

Casi, pero no del todo. Vea la lista en la sección [¿Es la misma experiencia en las aplicaciones que en el navegador?](#is-it-the-same-experience-in-the-apps-as-in-the-browser).  

## <a name="can-i-connect-the-app-to-our-on-premises-solution"></a>¿Puedo conectar la aplicación a nuestra solución local?

Sí que puede. Es una forma ligeramente diferente de iniciar sesión, eso es todo. Para obtener más información, consulte [Usar Business Central local](install-mobile-app.md#using-business-central-on-premises).  

## <a name="see-also"></a>Consulte también .

[Obtener Business Central en el dispositivo móvil](install-mobile-app.md)  
[Instalar la aplicación Business Central para Microsoft Teams](across-install-app-for-teams.md)  
---
title: Acerca de las acciones de Buscar y Filtrar en Business Central
description: "Respuestas a las preguntas más frecuentes sobre las acciones de Buscar y Filtrar."
author: mikebcMSFT
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: keyboarding, productivity, how do i, filter pane
ms.date: 10/01/2018
ms.author: mikebc
ms.translationtype: HT
ms.sourcegitcommit: 9dbd92409ba02281f008246194f3ce0c53e4e001
ms.openlocfilehash: b34acf29e142ef1a892f6c3c5a0ce2b6b8f7cb29
ms.contentlocale: es-es
ms.lasthandoff: 09/28/2018

---

# <a name="about-searching-and-filtering-in-included365finincludesd365finmdmd"></a>Acerca de las opciones de Buscar y Filtrar en [!INCLUDE[d365fin](includes/d365fin_md.md)]
Este artículo responde a preguntas comunes que puede tener acerca de las acciones buscar y filtrar.

## <a name="is-there-a-difference-between-searching-and-filtering"></a>¿Hay alguna diferencia entre buscar y filtrar?
Sí.
- La búsqueda es simple y amplia: coincide con los registros que contienen el texto de búsqueda en los campos visibles de la página y no distingue entre mayúsculas y minúsculas.
- El filtrado es muy flexible y se puede aplicar a campos específicos, incluidos aquellos que no están visibles en la página: muestra registros con coincidencias exactas, que distinguen entre mayúsculas y minúsculas, pero se puede ajustar con símbolos potentes de búsqueda, tokens y fórmulas. Para obtener más información sobre cómo usar estas funciones, consulte [Ordenar, buscar y filtrar en listas](ui-enter-criteria-filters.md)

## <a name="is-there-a-keyboard-experience-for-search-and-filter"></a>¿Hay alguna experiencia de teclado para buscar y filtrar?
Las acciones de buscar y filtrar se han optimizado para los usuarios que prefieren la interacción sin mouse para trabajar de manera eficiente con sus datos. Hay varias teclas de método abreviado que se pueden usar en secuencia para trabajar a alta velocidad. Para obtener más información, consulte [Métodos abreviados de teclado](keyboard-shortcuts.md#KeyboardFilter).

## <a name="is-the-filter-pane-available-on-all-lists"></a>¿El panel de filtros está disponible en todas las listas?
El panel de filtros está disponible en las pantallas donde la lista es el contenido principal de la página, como hojas de cálculo y páginas de lista, incluidas las listas accesibles desde la barra de navegación. El panel de filtro aún no está disponible para listas integradas, como líneas de venta en pedidos de ventas o para listas con columnas dinámicas (a menudo denominadas páginas de matriz). 

## <a name="how-can-i-save-my-filters"></a>¿Cómo puedo guardar mis filtros?
Los filtros y ajustes a los filtros predefinidos se recuerdan a lo largo de la sesión (mientras permanece conectado), incluso si sale de la página. Actualmente no es posible guardar los filtros de forma permanente.
A diferencia de los filtros, el texto de búsqueda no se recuerda cuando sale de una página.

## <a name="is-this-the-same-as-advanced-filters-and-limit-totals-in-microsoft-dynamics-nav"></a>¿Es lo mismo que los filtros avanzados y los totales límite de Microsoft Dynamics NAV?
[!INCLUDE[d365fin](includes/d365fin_md.md)] se basa en estas características populares y ofrece una experiencia moderna y muy útil para encontrar y analizar sus datos. Con más métodos abreviados de teclado y la introducción de la búsqueda, [!INCLUDE[d365fin](includes/d365fin_md.md)] supera la funcionalidad provista en Dynamics NAV.

## <a name="can-i-search-and-filter-using-the-companion-apps-and-outlook-addin"></a>¿Puedo buscar y filtrar con las aplicaciones complementarias y Outlook AddIn?
En la mayoría de casos, en diferentes factores de forma, como dispositivos móviles u Outlook, puede buscar en listas pero no puede filtrar campos individuales.

## <a name="is-the-filter-pane-available-for-filtering-reports"></a>¿El panel de filtros está disponible para filtrar informes?
No. El diálogo de filtro de informe, conocido como la página de solicitud, actualmente utiliza una experiencia diferente que proporciona algunas, pero no todas, las capacidades del panel de filtros.

## <a name="will-microsoft-extend-the-filter-pane-experience"></a>¿Extenderá Microsoft la experiencia del panel de filtros?
En Microsoft, escuchamos constantemente los comentarios de nuestra comunidad diversa de usuarios y actuamos siguiendo las mejores sugerencias de la comunidad. Si está interesado en ampliar el panel de filtros a más factores de forma, más tipos de listas e informes, o si tiene una gran idea sobre cómo mejorarlo, agregue una idea nueva o vote las ideas existentes en [aka.ms/BusinessCentralIdeas](https://aka.ms/businesscentralideas).

## <a name="can-i-do-anything-about-the-searching-for-rows-is-taking-too-long-message"></a>¿Puedo hacer algo con el mensaje "La búsqueda de filas está tardando demasiado tiempo"?

Una operación de búsqueda tiene un límite de tiempo para llevarse a cabo. En primer lugar, intente cambiar los criterios de búsqueda y busque de nuevo. Si está utilizando [!INCLUDE[prodshort](includes/prodshort.md)] local, póngase en contacto con el administrador del sistema, ya que un administrador puede aumentar el límite de tiempo para las búsquedas.

Como administrador local, aumente el límite de tiempo en las búsquedas mediante la configuración de **Tiempo de espera de búsqueda** del servidor de [!INCLUDE[prodshort](includes/prodshort.md)]. Para obtener más información, consulte [Configuración de Business Central Server](https://docs.microsoft.com/en-us/dynamics365/business-central/dev-itpro/administration/configure-server-instance?#Database) en la Ayuda de Business Central Developer e IT Pro.

## <a name="see-also"></a>Consulte también .
[Introducción](product-get-started.md)  
[Ordenar, buscar y filtrar en listas](ui-enter-criteria-filters.md)

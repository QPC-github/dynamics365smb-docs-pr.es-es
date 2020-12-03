---
title: Agregar empresas al hub de empresas
description: Aprenda a agregar empresas de otros entornos de Business Central al hub de empresas para poder administrar el trabajo en todos los entornos.
author: edupont04
ms.service: dynamics365-business-central
ms.topic: article
ms.search.keywords: accountant, accounting, company hub
ms.date: 10/01/2020
ms.author: edupont
ms.openlocfilehash: 773731ecc860e7d1ea0d13bbf9e6896a746544be
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 10/01/2020
ms.locfileid: "3927729"
---
# <a name="add-companies-to-your-company-hub"></a>Agregar empresas al hub de empresas

Con el hub de empresas, puede acceder a su trabajo de varias empresas desde múltiples entornos [!INCLUDE [prodshort](includes/prodshort.md)]. Puede agregar entornos y empresas manualmente, si sus empresas no aparecen automáticamente en el hub de empresas.  

Justo en la página de aterrizaje del hub de la empresa, encontrará el menú **Configurar**, desde donde puede acceder a la página **Vínculos de entorno**. Simplemente, elija **Nuevo** y, a continuación, rellene los campos. [!INCLUDE [tooltip-inline-tip_md](includes/tooltip-inline-tip_md.md)]  

## <a name="environment-links"></a>Vínculos de entorno

Un vínculo de entorno es una tarjeta en la que especifica el entorno de [!INCLUDE [prodshort](includes/prodshort.md)] que hospeda una o más empresas en las que trabaja. Los datos de la tarjeta para cada entorno los especifica usted y puede cambiarlos según sea necesario. Sin embargo, el campo **Vínculo de entorno** es fundamental, ya que así es como puede acceder a cada empresa en [!INCLUDE [prodshort](includes/prodshort.md)]. Utilice la acción **Probar la conexión** de la cinta para comprobar que ha introducido el vínculo correcto. El vínculo que debe introducir apunta al entorno que hospeda la empresa que está agregando, y debe incluir el Id. de Azure Active Directory (Azure AD) o el nombre de dominio de la organización. Por ejemplo, si han especificado un dominio como MyBusiness.com, entonces el vínculo a su [!INCLUDE [prodshort](includes/prodshort.md)] es ```https://businesscentral.dynamics.com/mybusiness.com?redirectedfromsignup=1```. De lo contrario, se verá así: ```https://businesscentral.dynamics.com/1a23b456-789c-0123-45de-678910fg12h/production?redirectedfromsignup=1```  

El vínculo se utiliza cuando elige la empresa en el hub de empresas.  

:::image type="content" source="media/company-hub-company-list-actions.png" alt-text="Acciones para una empresa que figura en el centro empressarial":::

> [!TIP]
> Si está trabajando en la versión de prueba gratuita de [!INCLUDE [prodshort](includes/prodshort.md)], es fácil agregar las empresas en su suscriptor. Puede encontrar el vínculo del entorno copiando el Id. de Azure Active Directory de la sección **Solución de problemas** de la página de Ayuda y soporte. El nombre del entorno es probablemente el valor predeterminado, PRODUCCIÓN. Agregue esta información al campo **Vínculo de entorno**, como ```https://businesscentral.dynamics.com/1a23b456-789c-0123-45de-678910fg12h/production?redirectedfromsignup=1``` y luego elija **Probar la conexión**. La empresa de evaluación se agregará a la lista.
>
> Si ha pasado a la empresa de prueba de treinta días, Mi empresa, puede agregarla a la lista seleccionando la acción **Recargar/Recargar todas las empresas** de la lista.

## <a name="load-companies"></a>Cargar empresas

Cuando haya agregado sus entornos, sus empresas aparecerán automáticamente. Sin embargo, si sabe que se ha agregado una nueva empresa a un entorno, puede elegir la acción **Recargar todas las empresas** para actualizar la lista. Utilice la misma acción para actualizar los datos de todas sus empresas.  

> [!TIP]
> Para actualizar los datos en el hub de empresas, debe tener acceso a los datos de las empresas de las que provienen los datos.

## <a name="see-also"></a>Consulte también .

[Administrar el trabajo de varias empresas en el hub de empresas](company-hub.md)  
[Recursos de ayuda y soporte técnico](product-help-and-support.md)  
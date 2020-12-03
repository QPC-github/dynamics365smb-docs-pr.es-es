---
title: Extensión de experiencia básica | Microsoft Docs
description: Esta extensión es una alternativa modernizada a Microsoft Dynamics C5.
author: bholtorf
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: C5, financials, extension
ms.date: 10/01/2020
ms.author: bholtorf
ms.openlocfilehash: e7377d1413e2f1969543374f1b819e6fc8a2a263
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 10/01/2020
ms.locfileid: "3927723"
---
# <a name="the-basic-experience-extension"></a>Extensión de la experiencia básica
Si ha estado usando Microsoft Dynamics C5, los socios de Microsoft pueden ayudarle a realizar la transición a una solución más moderna basada en [!INCLUDE[d365fin](includes/d365fin_md.md)], para que pueda seguir disfrutando de las mismas capacidades optimizadas que con Dynamics C5.

Esta extensión está destinada a pequeñas empresas y puede admitir hasta tres usuarios. Si necesita más usuarios, debe actualizar a una licencia de [!INCLUDE[d365fin](includes/d365fin_md.md)] y desinstalar esta extensión.

> [!NOTE]
> A partir de ahora, esta extensión está disponible solo para clientes de Dinamarca e Islandia. 

## <a name="whats-available"></a>Que hay disponible
La siguiente tabla describe las capacidades que están disponibles si instala la extensión Experiencia básica.

|Área  |Funcionalidad  |
|---------|---------|
|**Contabilidad** |Finanzas básicas, Programaciones de cuentas, Activos fijos, Gestión bancaria, Conciliación de banco, Pagos, Débito directo, Dimensiones, Múltiples divisas, Presupuestos, Flujo de trabajo, Gestión de documentos/OCR, Consolidación, Empresas ilimitadas|
|**Cuenta de cobros/ventas** |Cuentas de cobros básicas, facturación de ventas, descuentos de ventas, precios, impuestos sobre las ventas, gestión de contactos |
|**Cuentas de pagos/compras** |Cuentas de pagos básicas, facturación de compras |
|**Administración de proyectos** |Trabajos, precios de trabajos, hojas de horas, asignaciones, tareas, recursos |
|**Inventario** |Inventario básico, sustituciones de productos, referencia cruzada de productos |

## <a name="getting-started"></a>Introducción
Esta extensión es un poco diferente a la mayoría, y necesitará la ayuda de un socio de Microsoft para instalarla y configurarla. Para que sepa qué puede esperar, aquí tiene una vista de alto nivel de lo que hará el socio de Microsoft.

1. Crear un nuevo suscriptor de [!INCLUDE[d365fin](includes/d365fin_md.md)]. Puede ser una versión de prueba o CSP.
2. Agregar al menos un usuario asignado a una licencia de Experiencia Básica en su cuenta de Azure Active Directory.
3. Eliminar todas las empresas, incluida la empresa de muestra Cronus.
4. Crear una nueva empresa que no contenga datos de muestra ni configuraciones.
5. Agregar el paquete **Demostrción de RapidStart**. <!--what does the pockage contain?-->
6. Descargar e instalar la extensión Experiencia básica desde AppSource.

## <a name="migrating-data"></a>Migración de datos
Lleve consigo sus datos de Dynamics C5. Después de que su socio de Microsoft instale la extensión Experiencia básica, tendrá una empresa vacía. Una forma fácil de mover sus datos de Dynamics C5 a Experiencia básica es usar la extensión Migración de datos de C5, que se incluye en [!INCLUDE[d365fin](includes/d365fin_md.md)]. La extensión migra clientes, proveedores, productos, sus cuentas de contabilidad y sus movimientos.

## <a name="see-also"></a>Consulte también
[Extensión de migración de datos de C5](ui-extensions-c5-data-migration.md)
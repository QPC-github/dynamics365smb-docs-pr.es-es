---
title: Configuración y asiento de la regularización
description: Puede utilizar cuentas de regularización para saldar y realizar el seguimiento de varias cuentas al mismo tiempo.
services: project-madeira
documentationcenter: ''
author: SorenGP
ms.topic: conceptual
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: null
ms.date: 04/01/2021
ms.author: edupont
---
# <a name="set-up-and-close-income-statement-balances" />Configuración y asiento de la regularización
Puede utilizar cuentas de regularización para saldar y realizar el seguimiento de varias cuentas al mismo tiempo. El proceso **Asiento regularización** transfiere las cuentas de regularización a una cuenta del balance y las cierra. Cuando se ejecuta el proceso **Asiento regularización**, los movimientos se registran automáticamente.  

> [!NOTE]  
>  Antes de ejecutar el proceso, se debe cerrar el ejercicio.  

## <a name="to-set-up-the-income-statement-balance-account" />Para configurar la cuenta de regularización

1.  Elija el icono ![Bombilla que abre la función Dígame.](../../media/ui-search/search_small.png "Dígame qué desea hacer") , escriba **Plan de cuentas** y luego elija el enlace relacionado.  
2.  Seleccione una cuenta de contabilidad existente y después seleccione **Editar** para abrir la página **Ficha cuenta**.  
3.  Amplíe la ficha desplegable **General**.  
4.  En el campo **Cta. regularización**, seleccione la cuenta de ajuste para la cuenta comercial auxiliar.  

    > [!NOTE]  
    >  Dicha cuenta será en la que se cargarán o abonarán los saldos al ejecutar el proceso de regularización.  

5.  Escriba la información en los campos requeridos y, a continuación, elija el botón **Aceptar**.  

## <a name="to-close-income-statement-balances" />Para el asiento de la regularización

1.  Elija el icono ![Bombilla que abre la función Dígame.](../../media/ui-search/search_small.png "Dígame qué desea hacer") , escriba **Asiento regularización** y luego elija el enlace relacionado.  
2.  En la ficha desplegable **Opciones**, rellene los campos tal como se describe en la tabla siguiente.  

    |Campo|Description|  
    |---------------------------------|---------------------------------------|  
    |**Fecha final ejercicio**|Seleccione la fecha del ejercicio cerrado.|  
    |**Libro del diario general**|Seleccione el libro del diario general requerido.|  
    |**Sección diario general**|Seleccione la sección del diario general requerida.|  
    |**Nº documento**|Escriba el número de documento.|  
    |**Cta. ajtes. red. div. adic**|Seleccione la cuenta de movimientos de remanente.|  
    |**Texto de registro**|Escriba la descripción requerida.|  

3.  En la sección **Cerrado por**, rellene los campos tal como se describe en la tabla siguiente.  

    |Campo|Description|  
    |---------------------------------|---------------------------------------|  
    |**Código de empresa**|Seleccione esta opción para crear un movimiento para cada código de empresa.|  
    |**Dimensiones**|Seleccione esta opción para crear un movimiento para cada dimensión de contabilidad.|  
    |**Periodo inventario cerrado**|Seleccione esta opción para indicar que el periodo de inventario con fecha final igual o posterior a la fecha final del periodo contable está cerrado.|  

4.  Elija el botón **Aceptar**.  

## <a name="see-also" />Consulte también
 [Funcionalidad local para España](spain-local-functionality.md)


[!INCLUDE[footer-include](../../includes/footer-banner.md)]

---
title: 'Crear el informe 349 [ES]'
description: "Lea sobre cómo utilizar la versión en español de Business Central para enviar electrónicamente la declaración del Informe 349\_a las autoridades fiscales."
author: SorenGP
ms.topic: conceptual
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: null
ms.search.form: 10736
ms.date: 06/21/2021
ms.author: edupont
---
# <a name="create-report-349-in-the-spanish-version" />Crear informe 349 en la versión en español
Debe presentar un informe periódico de comercio con otros países o regiones de la UE a las autoridades fiscales. Este modelo, el Informe 349, debe enviarse a las autoridades fiscales electrónicamente en la página web de la Agencia Tributaria o en un CD-ROM. Para obtener más información, consulte el sitio web de la [Agencia Tributaria](https://go.microsoft.com/fwlink/?LinkId=238181).  

## <a name="to-create-report-349" />Para crear el informe 349

1.  Elija el icono ![Bombilla que abre la función Dígame.](../../media/ui-search/search_small.png "Dígame qué desea hacer") , escriba **Modelo 349** y luego elija el enlace relacionado.  
2.  En la ficha desplegable **Opciones**, rellene los campos tal como se describe en la tabla siguiente.  

    |Campo|Description|  
    |---------------------------------|---------------------------------------|  
    |**Ejercicio**|Especifique el año del período de notificación.|  
    |**Periodo**|Seleccione el periodo que cubrirá el informe. Puede ser un año, un mes o un trimestre.|  
    |**Cambio de frecuencia de periodo**|Seleccione esta opción para cambiar la frecuencia del periodo del informe.|  
    |**Nombre contacto**|Especifique el nombre de contacto de la empresa.|  
    |**Número de teléfono**|Especifique el número de teléfono del contacto.|  
    |**Nº modelo**|Especifique el número de la declaración. Por ejemplo, si es su primer Modelo 349, el número será **3490000000000**.|  
    |**País/región empresa**|Introduzca el país/región de la empresa.|  
    |**Tipo de medio modelo**|Seleccione el tipo de medio del modelo.<br /><br /> Para enviar la declaración electrónicamente, seleccione **Telemático**.<br /><br /> Para enviar la declaración en CD-ROM, seleccione **Soporte físico**. Si desea enviar el modelo 349 en CD-ROM, también debe imprimir etiquetas para el disco. Para obtener más información, consulte Etiquetas modelo.|  
    |**Grupos contables productos excluidos**|Especifique el grupo contable de producto que no desea incluir en la declaración.|  

3.  Elija el botón **Aceptar**.  

Si el periodo incluye un abono, aparece un mensaje y, si elige el botón **Aceptar**, se abre la página **Advertencias 349 Cliente/Proveedor** y se mostrarán todos los abonos del periodo.  

Los movimientos relacionados con abonos se muestran en la página **Advertencias 349 Cliente/Proveedor** ya que puede ser interesante incluirlos como correcciones a las facturas. Por ejemplo, si registra una factura de ventas en octubre y envía un abono en noviembre que corrige la factura de octubre, aparecerá una advertencia. A continuación, puede realizar los cambios necesarios en la página **Advertencia 349 Cliente/Proveedor**. Debe especificar la sección del importe total del cliente que se debe incluir en el modelo 349 de noviembre.  

## <a name="to-correct-warnings-for-report-349" />Para corregir las advertencias del informe 349

1.  En la página **Advertencias 349 Cliente/Proveedor**, seleccione la línea del cliente correspondiente.  
2.  Realice los cambios necesarios en la línea.  

    En la tabla siguiente se describen los campos clave para corregir un modelo 349 que incluye un abono.  

    |Campo|Description|  
    |---------------------------------|---------------------------------------|  
    |**Incluir corrección**|Seleccione esta opción para aceptar la corrección que ha generado el abono.|  
    |**Código operación entrega**|Especifica el tipo de entrega de exportación para la transacción de IVA.<br /><br /> Si selecciona un mes en el campo **Periodo de ejercicio y de la factura que se rectifica**, el campo **Código operación entrega** le permite identificar el importe apropiado, que se muestra en el campo **Importe declarado anterior**.|  
    |**Importe declarado anterior**|Especifica el importe total que se ha incluido en el modelo 349.<br /><br /> Este campo se calcula únicamente si ha modificado el campo **Periodo de ejercicio y de la factura que se rectifica**. Se calcula basándose en el código de operación de entrega especificado.|  
    |**Año fiscal y periodo de la factura que se rectifica**|Especifica el año fiscal en el que se envió el modelo 349 original a las autoridades fiscales con la factura que corrige este abono. **Advertencia:** No cambie este campo si el abono se aplica a una factura que aún no se ha declarado a las autoridades fiscales porque forma parte del modelo 349 actual.|  
    |**Periodo de ejercicio y de la factura que se rectifica**|Especifica el mes, como **01** para el mes de enero, para el modelo 349 original que incluye la factura que corrige este abono. **Advertencia:** No cambie este campo si el abono se aplica a una factura que aún no se ha declarado a las autoridades fiscales porque forma parte del modelo 349 actual.|  
    |**Importe declarado inicial**|Especifica la corrección para la transacción original.<br /><br /> Para una abono a una factura que se incluyó en un modelo 349 anterior, escriba el importe que debería haber declarado con este cliente o proveedor. Este importe es el importe facturado menos el importe del abono.<br /><br /> Para una abono a una factura que forma parte del modelo 349 actual, introduzca el importe del abono.|  

3.  Una vez realizados los cambios necesarios, elija la acción **Proceso**.  

    Aparecerá una página donde deberá confirmar que desea actualizar el modelo 349 para los movimientos en los que se selecciona la casilla **Incluir corrección**.  

Para correcciones de importes que se incluyeron en un modelo 349 anterior, la página puede mostrar más de una advertencia para un cliente o proveedor con los mismos valores en los campos **Año fiscal y periodo de la factura que se rectifica** y **Periodo de ejercicio y de la factura que se rectifica**. En ese caso, debe combinar las correcciones realizadas en una sola línea para incluir los importes correspondientes del campo **Importe declarado anterior** e **Importe declarado inicial** del modelo 349.  

## <a name="see-also" />Consulte también
[Informe 349](report-349.md)   


[!INCLUDE[footer-include](../../includes/footer-banner.md)]

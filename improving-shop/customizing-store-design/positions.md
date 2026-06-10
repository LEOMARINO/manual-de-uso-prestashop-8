# Positions

* [Posiciones de recepción](positions.md#Positions-FrontofficePositions)
  * [Mover un módulo dentro de un gancho](positions.md#Positions-Movingamodulewithinahook)
  * [Colocar un módulo a un gancho: Trasplantar](positions.md#Positions-Attachingamoduletoahook:Transplanting)
  * [Editando un módulo adjunto](positions.md#Positions-Editinganattachedmodule)
  * [Extracción de un módulo de un gancho](positions.md#Positions-Removingamodulefromahook)
  * [Trasplantar un módulo modificando su código](positions.md#Positions-Transplantingamodulebymodifyingitscode)
  * [Widgets](positions.md#Positions-Widgets)

Un módulo puede tener dos vistas: una en el back office (its options, or even a configuration screen) y otra en el front office. La vista de front office es cómo y dónde se muestra el módulo dentro del tema de su tienda.

La posición de un módulo en su tema se puede cambiar, porque es posible que desee que el bloque de un módulo se coloque mucho más arriba en la página (or lower) que los demás. En el lenguaje de PrestaShop, esto se llama "trasplantar" y se realiza mediante la herramienta disponible en la página "Posiciones", en el menú "Diseño". De hecho, esto le permite adjuntar un módulo a uno de los muchos enlaces disponibles en el tema actual, sin escribir ningún código.

La página "Posiciones" muestra todos los ganchos disponibles y sus módulos adjuntos. Muchos están vacíos por defecto, pero algunos de los más útiles pueden tener una docena de módulos.

![](<../../.gitbook/assets/64225563 (6).png>)

En la parte superior de la página, un menú desplegable le permite mostrar solo el módulo que le interesa. Alternativamente, también puedes buscar un gancho específico. De forma predeterminada, esta página solo muestra los ganchos en los que puede colocar funciones. Al marcar la casilla "Mostrar ganchos no posicionables" a continuación se muestran todos los ganchos, incluso los invisibles, que están vinculados a una acción para una instancia.

El encabezado de la tabla para cada gancho muestra el nombre del gancho, una descripción rápida (when available) y la cantidad de módulos conectados. La tabla enumera los módulos que están conectados a ese gancho. Los módulos se muestran en el orden en que aparecen en el gancho.

## Mover un módulo dentro de un gancho <a href="#positions-movingamodulewithinahook" id="positions-movingamodulewithinahook"></a>

Tienes dos formas de cambiar la posición de un módulo dentro de un gancho:

* Haga clic en la flecha hacia arriba o hacia abajo. La página se recargará y mostrará el nuevo pedido.
* Arrastre y suelte la fila del módulo:
  1. Coloque el cursor del mouse en el número de posición para que se convierta en un cursor de "mover elemento".
  2. Haga clic y mantenga presionado mientras mueve el cursor sobre la fila/posición donde desea que esté el módulo: la fila del módulo cambia de posición en consecuencia.
  3. Suelte el botón del ratón: se guarda la posición actual del módulo.

Para la mayoría de los módulos, el trasplante se puede realizar fácilmente directamente a través del back office. Algunos módulos requieren que usted modifique su código para poder trasplantarlos.

## Fijación de un módulo a un gancho: Trasplante <a href="#positions-attachingamoduletoahook-transplanting" id="positions-attachingamoduletoahook-transplanting"></a>

En PrestaShop, "trasplantar" es la acción de fijar un módulo a un gancho. Puede agregar un módulo a más de un gancho.

Dos cosas que debe saber antes de trasplantar un módulo:

* Algunos módulos están escritos para conectarse únicamente a un conjunto determinado de ganchos.
* Algunos ganchos están escritos para no aceptar algunos tipos específicos de módulos.

Por lo tanto, tenga en cuenta que no siempre se puede trasplantar ningún módulo a cualquier gancho.

Asegúrese de desactivar el caché cuando pruebe el efecto de un nuevo módulo en el front-end. Puede hacer esto en la página "Rendimiento", en el menú "Parámetros avanzados".

El proceso de trasplante tiene su propia interfaz:

1. Vaya al menú "Diseño" y a su página "Posiciones".
2. Haga clic en el botón "Transplantar un módulo" en la parte superior derecha. Aparece la interfaz de trasplante.
3. En la lista desplegable "Módulo", seleccione el módulo que desea trasplantar.
4. En la lista desplegable "Transplantar a", seleccione dónde desea trasplantar el módulo. Hay muchos ganchos disponibles. Puede cambiar su configuración más tarde si es necesario.
5. En el campo "Excepciones", escriba el nombre del archivo (s) de las páginas en las que no desea que aparezca el módulo.\
   Puede realizar múltiples selecciones simplemente haciendo clic en los nombres de los archivos mientras mantiene presionada la tecla Ctrl. Puede anular la selección de archivos de la misma manera: Ctrl+clic.
6. No olvide guardar los cambios.\
   \


![](<../../.gitbook/assets/51839907 (4) (3).png>)

El menú desplegable "Transplantar a" le da una buena idea de dónde se pueden colocar los módulos.

Aunque la lista desplegable "Transplantar a" ofrece una descripción general completa de los ganchos disponibles, es posible que no siempre esté claro cuál es al que desea adjuntar su módulo. No dudes en probar con otro anzuelo si el resultado de tu selección no es el que esperas. La lista proporciona algunos detalles: algunos ganchos tienen una descripción después del nombre del gancho, por ejemplo, "Agregar campos al formulario 'valor de atributo'" para `displayAttributeForm`. Examínelos todos para elegir su anzuelo correctamente.

## Edición de un módulo adjunto <a href="#positions-editinganattachedmodule" id="positions-editinganattachedmodule"></a>

Cada módulo tiene un botón de acción en el lado derecho de su fila, con dos opciones posibles: una para editar su configuración y la otra para eliminar el módulo.

La edición de la configuración de un módulo utiliza la misma interfaz que la utilizada para trasplantar un módulo. La única diferencia es que no puede cambiar el campo "Módulo", ya que está deshabilitado y, por lo tanto, atenuado. Puede editar tanto la configuración "Transplantar a" como las excepciones, que funcionan tal como se describe en el método "Adjuntar un módulo a un gancho" anterior.

![](<../../.gitbook/assets/64225504 (4) (5) (7).png>)

Siempre revise su oficina principal para asegurarse de que el módulo esté realmente donde pretendía que estuviera.

## Extracción de un módulo de un gancho <a href="#positions-removingamodulefromahook" id="positions-removingamodulefromahook"></a>

Hay dos formas de quitar un módulo de un gancho:

* Eliminar un solo módulo: haga clic en el icono de la papelera a la derecha de la fila del módulo.
* Eliminación de un lote de módulos: seleccione los módulos marcando la casilla a la izquierda de su fila y luego haga clic en el botón "Desenganchar la selección", que se encuentra en la parte superior e inferior de la lista de ganchos.

## Trasplantar un módulo modificando su código <a href="#positions-transplantingamodulebymodifyingitscode" id="positions-transplantingamodulebymodifyingitscode"></a>

Esto es sólo para expertos: debes tener un buen conocimiento de PHP y HTML antes de intentar cualquier cosa con el código de un módulo.

Algunos módulos no se pueden trasplantar a otras secciones de la oficina principal simplemente porque carecen del código necesario. Por ejemplo, algunos módulos contienen plantillas para mostrar columnas y encabezados, mientras que otros tienen un archivo de plantilla que solo funciona con la sección de encabezado.&#x20;

Si desea mostrar módulos simples en una posición para la cual no fue creado, deberá editar sus archivos de plantilla. También se pueden hacer módulos más complejos para que se muestren en otras secciones de la página, pero es posible que sea necesario reescribirlos parcialmente para que su diseño funcione con esa nueva ubicación.

Para personalizar la capacidad de trasplante de un módulo, debe darle la función PHP correcta para el nuevo enlace de destino. Por ejemplo, para un módulo que tenga esta función:

```
function hookTop($params) { ... } 
```

Para trasplantar su bloque a la columna de la derecha, por ejemplo, necesita agregar la función `hookRightColumn()`:

```
function hookRightColumn($params) { ... } 
```

Luego, debes escribir el código que muestra el contenido en la página principal. En el mejor de los casos, eso significa copiar/pegar el contenido de la función `hookTop()`; en el peor de los casos, necesitará reelaborar el contenido de la función `hookTop()` en algo que funcione para la nueva ubicación.

## Widgets <a href="#positions-widgets" id="positions-widgets"></a>

PrestaShop 1.7 ha introducido un nuevo sistema para enganchar módulos: los widgets. Gracias a los widgets, se puede utilizar un módulo y trasplantarlo a cualquier gancho de visualización.

Los widgets funcionan solo con los módulos 1.7 (for PrestaShop modules, their technical names start with "ps\_") y no se pueden utilizar en todos los módulos. Lea más sobre los widgets aquí: [https://devdocs.prestashop.com/1.7/modules/concepts/widgets](https://devdocs.prestashop.com/1.7/modules/concepts/widgets/)

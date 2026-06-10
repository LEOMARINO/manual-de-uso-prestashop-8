# Resumen de acciones

Esta pestaña contiene una tabla que presenta el stock de sus productos, así como opciones de búsqueda y le permite editar directamente las cantidades de sus productos.

![](<../../../.gitbook/assets/56688695 (3) (3).png>)

Una tabla le permite tener una visión general del stock de su catálogo de un vistazo.

![](<../../../.gitbook/assets/56688697 (3) (3) (2).png>)

Cada línea representa un producto (ya sea estándar, virtual o paquete) o una de sus combinaciones. La única diferencia es que los atributos combinados se muestran justo debajo del nombre del producto.

La tabla contiene las siguientes columnas:

* Miniatura de imagen, para ayudar a un rápido reconocimiento visual.
* Nombre del producto y cuando es una combinación, valores de sus atributos.
* Referencia del producto. En caso de que una combinación tenga su propia referencia, se utilizará en lugar de la referencia principal.
* Proveedor. En caso de que se asignen varios proveedores a un producto, aquí solo se mostrará el proveedor predeterminado.
* Estado, para saber si el producto está habilitado o no.
* **Stock físico**, que representa la cantidad que realmente tienes físicamente en tu almacenamiento.
* **Stock reservado**, que representa la cantidad de productos que se encuentran actualmente en un pedido de cliente abierto y que aún no ha sido enviado.
* **Stock disponible**, que es la cantidad disponible para la venta.
* Editar cantidad. Esta entrada permite modificar la cantidad manualmente. Consulte [a continuación](stock-overview.md#Stockoverview-qty\_edition).

Comprender las nociones de stock físico, reservado y disponible A partir de la versión 1.7.2.0, PrestaShop introduce tres nociones diferentes de stock, diferentes a las utilizadas en la Gestión Avanzada de Stock en las versiones 1.6.

* **El stock físico** representa la cantidad que realmente tienes físicamente en tu almacenamiento. Puede agregar o eliminar stock físico, por ejemplo, al recibir un pedido de suministro o al realizar un ajuste de inventario.
* **Stock reservado** representa la cantidad de productos que se encuentran actualmente en un pedido de cliente abierto y que aún no se ha enviado. En otras palabras, estos productos están físicamente en su almacenamiento pero ya no están disponibles para la venta. No se puede cambiar directamente el stock reservado. El stock reservado sólo depende de los pedidos de los clientes.
* **Stock disponible** es la cantidad disponible para la venta. A diferencia de la Gestión Avanzada de Stock en la versión 1.6, no puedes modificar directamente el stock disponible a menos que cambies también el stock físico. Esta es la cantidad que se muestra en la página ["Producto"](../managing-products.md).

Relación entre stock físico, reservado y disponible

En todo momento, estas 3 nociones de acción están unidas por la siguiente ecuación:

_Stock físico - Stock reservado = Stock disponible_

La edición del stock físico también afectará al stock disponible y viceversa.

&#x20;De forma predeterminada, los productos se ordenan decrecientes product\_id, lo que significa que el producto creado más recientemente estará en la parte superior. Si hay más de 100 productos y combinaciones, entonces la tabla está paginada.

### Edición de cantidades <a href="#stockoverview-qty_editioneditionofquantities" id="stockoverview-qty_editioneditionofquantities"></a>

Las cantidades se pueden modificar directamente en la pestaña "Stock", con el campo de entrada ubicado en la columna del extremo derecho de la tabla de resumen de stock.

#### Edición sencilla <a href="#stockoverview-simpleedition" id="stockoverview-simpleedition"></a>

Para editar el stock de un solo producto, simplemente ingrese el cambio de cantidad deseada en el campo de entrada. Lo que estás escribiendo en esta entrada es un delta de cantidad, lo que significa que no es el valor final deseado del stock sino la cantidad que estás agregando o eliminando. Puede escribir la cantidad que desea agregar o eliminar (con un signo menos) o usar las flechas hacia arriba y hacia abajo para ajustar la cantidad.\
![](<../../../.gitbook/assets/54268490 (5) (1).gif>)To validate the new stock, simply click on the blue "Check" button inside the input field, or use the "Apply new quantities" button at the top of the stock overview table.

Mientras edita la cantidad, verá una descripción general del stock final resultante:![](<../../../.gitbook/assets/56688698 (3) (3) (2).png>)Esta característica está aquí para ayudarlo a ver al mismo tiempo el punto inicial, el punto final y la diferencia entre ellos antes de validar. Recuerda que, dado que el stock físico y el disponible siempre están vinculados por la ecuación mostrada anteriormente, editarás ambos al mismo tiempo.

#### Edición múltiple <a href="#stockoverview-multipleedition" id="stockoverview-multipleedition"></a>

Si desea editar varias cantidades al mismo tiempo, también puede editar las cantidades de varios productos y luego validarlo todo con el botón “Aplicar nueva cantidad”.![](<../../../.gitbook/assets/54266290 (3) (5) (1).gif>)

#### Edición masiva <a href="#stockoverview-bulkedition" id="stockoverview-bulkedition"></a>

Desde PrestaShop 1.7.3, la información del stock de productos ahora se puede actualizar de forma masiva en lugar de uno por uno. Y es muy fácil, sólo tienes que marcar (en la columna de la izquierda) todos los productos que deseas editar, ingresar la cantidad a sumar o restar al stock ya disponible y ¡confirmar!

### Alertas de existencias bajas <a href="#stockoverview-lowstockalerts" id="stockoverview-lowstockalerts"></a>

Además, cuando un producto tiene pocas existencias, puedes pedirle a PrestaShop que te envíe alertas. Puede configurar el umbral de stock bajo y alternar la notificación globalmente en la página "[Product](http://doc.prestashop.com/display/PS17/Managing+Products)" o por producto. Y luego, en esta página de descripción general de existencias, ahora se resaltan los productos con una cantidad por debajo del nivel de existencias bajo. También se ha agregado un filtro rápido, que le permite ver rápidamente los productos con poco stock colocándolos en la parte superior de la lista.

![](<../../../.gitbook/assets/55607508 (4) (3).png>)

### Opciones de búsqueda y filtrado <a href="#stockoverview-searchandfilteroptions" id="stockoverview-searchandfilteroptions"></a>

En la parte superior de la pestaña, encontrará dos funciones para buscar rápidamente cualquier producto. La barra de búsqueda está diseñada para casos de uso en los que sabes qué producto estás buscando porque tienes en mente su referencia, nombre o proveedor. Mientras que los filtros avanzados le permiten explorar más opciones para afinar su búsqueda.

#### Barra de búsqueda <a href="#stockoverview-stock_search_barsearchbar" id="stockoverview-stock_search_barsearchbar"></a>

La barra de búsqueda busca:

* nombre del producto
* referencia del producto
* proveedor
* valores de los atributos. Esto le permite buscar un valor de atributo específico como el color. Al escribir "verde", verá todos los productos que comparten este valor de atributo de color. Sin embargo, esto todavía está en versión beta y es posible que no funcione con valores de atributos demasiado cortos, como con los tamaños: "S", "M", "L".

![](<../../../.gitbook/assets/54266294 (3) (5) (3).gif>)

#### Filtros avanzados <a href="#stockoverview-advancedfilters" id="stockoverview-advancedfilters"></a>

En la pestaña "Stock", los filtros avanzados contienen:

* un filtro de proveedores, que le permite explorar rápidamente los proveedores disponibles y elegir uno o varios.
* un filtro de categoría con un árbol expandible.

![](<../../../.gitbook/assets/56688700 (3) (3) (2).png>)

## Importar/Exportar <a href="#stockoverview-import-export" id="stockoverview-import-export"></a>

Debido a que su tienda maneja una gran cantidad de datos, PrestaShop le permite importar o exportar la información que se muestra en la página Resumen de existencias en un archivo CSV. ¿Por qué? Para que puedas trabajar en ello con tu ordenador, conectarte a tu propio sistema de gestión de stock… ¡lo que sea! Sólo necesita hacer clic en los íconos de la nube azul en el lado derecho de la pantalla y estará en camino al sistema de importación/exportación.

## Multitienda <a href="#stockoverview-multi-store" id="stockoverview-multi-store"></a>

Este nuevo sistema de gestión de stock es compatible con multitienda. Por razones obvias, si tiene varias tiendas dentro de un grupo donde las existencias no se comparten, no puede administrar su stock en el contexto de "todas las tiendas" o "grupo". Si intenta hacerlo, es posible que vea el siguiente mensaje de error:

![](<../../../.gitbook/assets/56688701 (3) (3) (1).png>)

En su lugar, debes seleccionar una tienda en la que puedas trabajar para editar su stock.\


Si estás utilizando un grupo de tiendas que comparten las mismas cantidades, también tendrás que seleccionar un contexto de tienda único en lugar de un grupo, pero cualquier cambio que realices en una tienda también afectará a las otras tiendas.

![](<../../../.gitbook/assets/56688702 (3) (3) (3).png>)

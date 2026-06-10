# Configuración del producto

Esta página contiene las preferencias relativas a cómo PrestaShop debe manejar y mostrar sus productos.

## General preferences <a href="#productsettings-generalpreferences" id="productsettings-generalpreferences"></a>

<figure><img src="../../.gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure>

* **Modo catálogo**. Habilitar el modo catálogo convierte su tienda en una simple galería de productos, sin posibilidad de comprar los artículos de ningún tipo.
* **Número de días durante los cuales el producto se considera 'nuevo'**. Cuando agregas un producto a tu tienda, se considera nuevo y está disponible en la página "Nuevos productos". El campo le permite especificar cuántos días el producto permanecerá visible en esta página. Con esta función, tú eliges cómo mostrar y actualizar las novedades de tu tienda. La página "Nuevos productos" suele ser la que más acceden sus clientes habituales.
* **Tamaño máximo del resumen del producto**. Su producto tiene dos descripciones: un "resumen" y una descripción normal. El resumen, que aparece en los motores de búsqueda y en la descripción de la categoría de tu producto, está limitado a 800 caracteres por defecto.
* **Descuento por cantidad basado en**. Esta configuración indica en qué debe basarse PrestaShop los descuentos por cantidad: por producto o por combinación (which can feature multiple products).
* **Forzar actualización de URL amigable**. De forma predeterminada, la URL descriptiva de la página de un producto se genera a partir del título del producto y permanece igual aunque el título del producto cambie, porque para estar bien referenciada, sus URL deben ser estables. Al habilitar esta opción, PrestaShop actualizará la URL amigable cada vez que cambies el nombre del producto o el título de la página.
* **Activado de forma predeterminada**.  Si habilitas esta opción, los nuevos productos se activarán automáticamente cuando los crees.

## Pagination preferences <a href="#productsettings-paginationpreferences" id="productsettings-paginationpreferences"></a>

<figure><img src="../../.gitbook/assets/image (18) (1).png" alt=""><figcaption></figcaption></figure>

* **Productos por página**. Indique cuántos productos se muestran en las páginas de sus categorías.
* **Pedido predeterminado por**. Indica el orden de los productos en las categorías de tu tienda. Hay 6 opciones disponibles:
  * _Nombre del producto._ Muestra sus productos según el orden alfabético.
  * _Precio del producto._ Muestra tus productos según sus precios.
  * _Fecha de adición del producto._ Muestra tus productos según la fecha en que se agregaron a tu tienda.
  * _Fecha de modificación del producto._ Cuando editas un producto, se cambia su fecha de modificación. Esta opción hace que aparezcan en orden de fecha de modificación.
  * _Posición dentro de la categoría._ Muestra sus productos tal como están ubicados en las categorías de su catálogo. La posición de los productos se puede modificar directamente en el catálogo de tu tienda mediante las flechas de posición. De esta manera tendrás tus productos de la forma más atractiva para tus clientes.
  * _Marca._ Muestra tus productos en orden alfabético de los nombres de sus marcas.
  * _Cantidad de producto._ Muestra sus productos según su cantidad disponible.
  * _Referencia del producto._ Muestra tus productos según su número de referencia.
* **Método de pedido predeterminado**. Las opciones anteriores se pueden ordenar en orden ascendente o descendente.

## Preferencias de la página del producto <a href="#productsettings-productpagepreferences" id="productsettings-productpagepreferences"></a>

<figure><img src="../../.gitbook/assets/image (20).png" alt=""><figcaption></figcaption></figure>

* **Mostrar cantidades disponibles en la página del producto**. Al habilitar esta función, sus visitantes pueden ver las cantidades de cada producto disponible en stock. Mostrar esta información se puede utilizar para estimular las ventas en el caso de que la cantidad en stock sea baja. Las cantidades mostradas son los atributos y la combinación seleccionados.
* **Mostrar las cantidades restantes cuando la cantidad es inferior a**. Puede optar por mostrar una alerta cuando el stock restante disponible para un producto esté por debajo de cierto nivel. Esta opción es particularmente útil para promocionar compras. El texto y la ubicación de la alerta dependen del tema; en el tema predeterminado, es "Últimos artículos en stock" y se coloca al lado del botón "Agregar al carrito".
* **Mostrar atributos de producto no disponibles en la página del producto**. Sus productos pueden estar compuestos de muchas combinaciones o atributos diferentes: color, tamaño, capacidad, etc. Los atributos se pueden editar en la página "Atributos" del menú "Catálogo". Cuando uno o varios atributos ya no están disponibles, tienes dos posibilidades:
  * _Primera posibilidad:_ Dejar activa esta preferencia. Ejemplo: El "iPod Shuffle" ya no está disponible en color "Azul" en nuestra tienda. Al mantener habilitada esta opción, la combinación del producto permanecerá visible en la tienda. Un mensaje indicará que el producto ya no está disponible en la opción elegida, e invitará a los clientes a elegir otra combinación. Si habilitó la opción "Permitir pedidos de productos agotados" (see below), podrán agregar la combinación no disponible a sus carritos.
  * _Segunda posibilidad:_ Desactivar esta preferencia. Si la combinación "Azul" del producto "iPod Shuffle" ya no está disponible, esa selección no se muestra en la oficina principal y el cliente no puede seleccionarla. Esta característica ayuda a mostrar claramente la disponibilidad de sus productos.
* **Muestra el botón "añadir al carrito" cuando un producto tenga atributos**. Esta opción evita que los clientes agreguen un producto a su carrito directamente desde la página de categoría si ese producto tiene combinaciones. Esto obliga a los clientes a visitar la página del producto y elegir una combinación, en lugar de solo agregar la predeterminada al carrito. Tenga en cuenta que los productos sin combinación seguirán teniendo el botón "Agregar al carrito" en la página de categoría.
* **Separador de anclaje de atributos en los enlaces del producto**. Elija el separador, entre "," y "-".
* **Mostrar precio con descuento**. Cuando utilice el tablero de descuentos por volumen, muestre el precio con descuento en lugar del porcentaje de descuento.

## Preferencias de stock de productos <a href="#productsettings-productsstockpreferences" id="productsettings-productsstockpreferences"></a>

<figure><img src="../../.gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>

* **Habilitar gestión de stock**. Esta opción le brinda acceso a opciones y funciones básicas de gestión de stock: puede establecer la cantidad actual de producto, hacer que PrestaShop la reduzca para cada pedido y "reabastecer" para cada pedido cancelado o devuelto. De forma predeterminada, debes dejar esta función habilitada, ya que deshabilitarla afecta toda la gestión del inventario de tu tienda. Sólo si no tienes ningún inventario físico debes desactivarlo (por ejemplo, si solo tienes productos virtuales).
*   **Gestión de stock de packs por defecto**. Cuando vendes packs de productos, la forma en que se actualiza tu stock depende de esta opción. Tienes tres posibilidades:

    * _Solo paquete de disminución._ Cuando se vende un paquete, solo se verá afectado el stock del paquete.
    * _Disminuir productos solo en un paquete._ Cuando se vende un paquete, solo se verá afectado el stock de cada producto.
    * _Disminuir ambos._ Cuando se vende un paquete, tanto el stock del paquete como el stock de cada producto se verán afectados.

    Esta configuración la puedes cambiar para cada uno de tus packs en la propia página de producto, en la pestaña "Cantidades".

    * **Mostrar atributos no disponibles en la página del producto.** Esto se aplica a productos que solo tienen una combinación o cuando un atributo no tiene ningún producto en todas las combinaciones posibles.
      * Por ejemplo, el atributo blanco no se mostrará en la página del producto en el siguiente caso:

| <p>S - White => 0<br>S - Black => 1</p> |
| --------------------------------------- |
| <p>M - White => 0<br>M - Black => 1</p> |

*   **Mostrar las cantidades restantes cuando la cantidad es inferior a.** Puede elegir una cantidad inicial para que el mensaje de productos restantes se muestre a los clientes.&#x20;

    * Por ejemplo, si está configurado en 3 y el stock de su producto es 2 o menos, se mostrará la advertencia "Últimos artículos en stock" debajo del botón "Agregar al carrito" en su oficina principal.

    &#x20;

    <figure><img src="../../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

Sin embargo, si se establece en 0, las cantidades restantes no se mostrarán a los clientes y la función se desactivará. Esto ya no mostrará el mensaje "Últimos artículos en stock".

* **Permitir pedidos de productos agotados**. Si un producto ya no tiene stock disponible, el cliente aún puede pedirlo.
* **Etiqueta de productos en stock.** Mostrar una etiqueta para productos en stock.
* **Etiqueta de productos agotados con pedidos pendientes permitidos**. Muestre una etiqueta para productos agotados con pedidos pendientes permitidos.
* **Etiqueta de productos agotados con pedidos pendientes denegados**. Mostrar una etiqueta para productos agotados con pedidos pendientes denegados.&#x20;
* **Plazo de entrega de productos en stock.** Recomendado a comerciantes europeos para cumplir con la legislación. La función se desactivará si se deja vacía.
* **Tiempo de entrega de productos agotados con pedidos pendientes permitidos**. Recomendado a comerciantes europeos para cumplir con la legislación. La función se desactivará si se deja vacía.
* **Mostrar etiqueta de agotado en las páginas de listado de productos.** Esta función ayuda a sus clientes a ver de un vistazo si un producto está disponible en su tienda al mostrar una etiqueta de agotado junto al listado de su producto.

<figure><img src="../../.gitbook/assets/image (1) (1).png" alt=""><figcaption></figcaption></figure>

# Movimientos bursátiles

La tabla de movimientos de acciones le proporciona un registro de todos los cambios de acciones. Al tratarse de un historial de movimientos bursátiles anteriores, esta tabla sólo tiene una función informativa y por tanto no se puede editar.

![](<../../../.gitbook/assets/56688704 (3) (3) (2).png>)

## Resumen de movimientos <a href="#stockmovements-movementsoverview" id="stockmovements-movementsoverview"></a>

### Estructura <a href="#stockmovements-structure" id="stockmovements-structure"></a>

La estructura es similar a la tabla de existencias, pero aquí cada línea corresponde a un cambio en la cantidad física de un producto o combinación. Contiene las siguientes columnas:

* Miniatura de imagen, para ayudar a un rápido reconocimiento visual.
* Nombre del producto y cuando es una combinación, valores de sus atributos.
* Referencia del producto. En caso de que una combinación tenga su propia referencia, se utilizará en lugar de la referencia principal.
* Tipo de movimiento. Representa la razón por la cual la cantidad física de un producto ha cambiado.
* Cantidad agregada o eliminada. Este delta tiene el formato de una etiqueta + o - para facilitar el reconocimiento visual.
* Fecha y hora, que es la marca de tiempo exacta del servidor cuando se produjo el cambio.
* Empleado, que es el nombre del responsable del cambio.

\
De forma predeterminada, los movimientos de acciones se ordenan por fecha descendente, de modo que los movimientos de acciones más recientes estén en la parte superior.

### Tipos de movimientos de stock <a href="#stockmovements-stockmovementtypes" id="stockmovements-stockmovementtypes"></a>

A partir de la versión 1.7.2.0, se pueden crear tres tipos de movimiento cuando se activan mediante los siguientes eventos:

* Edición manual por parte de un empleado, cuando por ejemplo modificas la cantidad de un producto dentro de la tabla de stock.
* Pedido del cliente, cuando un pedido pasa de un estado equivalente a "no enviado" a otro estado equivalente a "enviado" (y viceversa). Por ejemplo, cuando envías un pedido que estaba en preparación, esto creará un movimiento de stock, ya que la cantidad física de artículos enviados sale literalmente de tu almacén.
* Productos devueltos, cuando recargas el stock de un producto después de recibir y aceptar la devolución de la mercancía.

En los dos últimos casos, el tipo de movimiento en la tabla se convierte en un hipervínculo al pedido del cliente correspondiente, por lo que tiene más contexto sobre este tipo de movimiento y no tiene que verificar las marcas de tiempo entre las tablas de movimientos de stock y pedidos.

## Opciones de búsqueda y filtrado <a href="#stockmovements-searchandfilteroptions" id="stockmovements-searchandfilteroptions"></a>

### Barra de búsqueda <a href="#stockmovements-searchbar" id="stockmovements-searchbar"></a>

La búsqueda tiene exactamente el mismo comportamiento que en la pestaña "[Stock](stock-overview.md)".

### Filtros avanzados <a href="#stockmovements-advancedfilters" id="stockmovements-advancedfilters"></a>

En la pestaña 'Movimientos', los filtros avanzados contienen:

* un filtro de tipo de movimiento, que le permite, por ejemplo, buscar movimientos de stock relacionados con pedidos de clientes.
* un filtro de empleados.
* un filtro de rango de fechas, si busca movimientos de acciones que ocurrieron durante un período específico.
* un filtro de categoría, como en la pestaña "Stock".
* un filtro de estado.

![](<../../../.gitbook/assets/56688706 (3) (3) (2).png>)

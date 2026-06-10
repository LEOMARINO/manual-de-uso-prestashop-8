# SQL Manager

El administrador de SQL es una característica compleja, que debe reservarse para los técnicos que saben cómo explorar una base de datos utilizando el lenguaje SQL. A cambio de esta complejidad, puede ser extremadamente poderoso y resulta inmensamente útil para quienes lo dominan.

![](<../../../.gitbook/assets/23789878 (4) (4) (4).png>)

Esta herramienta le permite realizar consultas SQL directamente en la base de datos de PrestaShop y guardarlas para usarlas en cualquier momento posterior. De hecho, PrestaShop presenta los datos de su base de datos de muchas maneras, pero es posible que necesite algo más, o más simplemente, algo más sencillo que la limpia interfaz de PrestaShop. Con el administrador de SQL, puede realizar consultas complejas que se basan en tablas de datos de la forma en que USTED las necesita.\
Por ejemplo, utilizando esta herramienta y su conocimiento de SQL, puede crear una consulta reutilizable que le brinde una lista actualizada de los clientes que están suscritos a su boletín u obtener una lista de productos en formato HTML o CSV.

Por motivos de seguridad no se permiten algunos tipos de consultas: ACTUALIZAR, ELIMINAR, CREAR TABLA, DROP, etc. En definitiva, solo se pueden leer datos (SELECT query).

Also, secure keys or passwords are hidden (\*\*\*\*\*\*\*\*\*\*\*).

## Creating a new query <a href="#sqlmanager-creatinganewquery" id="sqlmanager-creatinganewquery"></a>

Como es habitual, el botón "Agregar nueva consulta SQl" conduce al formulario de creación. Tiene dos campos principales:

* **Nombre de la consulta SQL**. Haga que el nombre sea tan largo y descriptivo como sea necesario.
* **consulta SQL**. La consulta SQL en sí. Eres libre de realizar JOINs u otras selecciones complejas.

![](<../../../.gitbook/assets/30965765 (1) (3).png>)

Además, la sección "Lista de tablas MySQL" le ayuda a explorar la base de datos y le facilita la creación de consultas. Le brinda un selector práctico y en el que se puede hacer clic de todas las tablas de bases de datos disponibles actualmente. Seleccione una tabla para que PrestaShop muestre sus atributos y tipos, luego haga clic en "Agregar atributo a la consulta SQL" para enviar su nombre al campo "Solicitar".

![](<../../../.gitbook/assets/30965766 (2) (2).png>)

Al guardar el formulario, volverá a la página principal, con su lista de consultas.

## Starting a query <a href="#sqlmanager-startingaquery" id="sqlmanager-startingaquery"></a>

Cada consulta guardada en la tabla tiene cuatro iconos a la derecha de su fila:

* **Exportar**. Realiza la consulta y la descarga en formato CSV.
* **Vista**. Realiza la consulta y la muestra en una tabla HTML, directamente dentro de la interfaz de PrestaShop.
* **Editar**. Puede editar una consulta tantas veces como sea necesario para refinarla y obtener mejores resultados.
* **Borrar**. Una vez que una consulta ya no se utiliza (or simply because it does not work), puede eliminarla haciendo clic en este botón y confirmando su elección.

![](<../../../.gitbook/assets/23789883 (2) (1).png>)

## Configuración <a href="#sqlmanager-settings" id="sqlmanager-settings"></a>

There is only one setting at this time:

* **Seleccione su codificación de archivo predeterminada**. Puede configurar la codificación de caracteres del archivo CSV descargado. Se recomienda el valor predeterminado, UTF-8, pero puede seleccionar ISO-8859-1 si es necesario.

![](<../../../.gitbook/assets/23789886 (4) (2).png>)

## Some sample queries <a href="#sqlmanager-somesamplequeries" id="sqlmanager-somesamplequeries"></a>

Las posibilidades son infinitas, pero aquí hay algunos ejemplos de consultas que le ayudarán a crear la suya propia.

### Listado de todas las direcciones de correo electrónico de todos los clientes <a href="#sqlmanager-listingallthee-mailsaddressofallthecustomers" id="sqlmanager-listingallthee-mailsaddressofallthecustomers"></a>

| `SELECT email FROM ps_customer` |
| ------------------------------- |

### Listado de todas las direcciones de correo electrónico de todos los clientes que están suscritos a su newsletter <a href="#sqlmanager-listingallthee-mailsaddressofallthecustomerswhoaresubscribedtoyournewsletter" id="sqlmanager-listingallthee-mailsaddressofallthecustomerswhoaresubscribedtoyournewsletter"></a>

| `SELECT emailFROM ps_customerWHERE newsletter = 1` |
| -------------------------------------------------- |

### Listando todos los productos que están activos y tienen una descripción en francés (id\_lang = 4) <a href="#sqlmanager-listingalltheproductswhichareactiveandhaveadescriptioninfrench-id_lang-4" id="sqlmanager-listingalltheproductswhichareactiveandhaveadescriptioninfrench-id_lang-4"></a>

| `SELECT p.id_product,` [`pl.name`](http://pl.name/)`, pl.link_rewrite, pl.descriptionFROM ps_product pLEFT JOIN ps_product_lang pl ON (p.id_product = pl.id_product)WHERE p.active = 1AND pl.id_lang = 4` |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |

### Listado de todos los pedidos, con detalles sobre transportista, moneda, pago, total y fecha <a href="#sqlmanager-listingalltheorders-withdetailsaboutcarrier-currency-payment-totalanddate" id="sqlmanager-listingalltheorders-withdetailsaboutcarrier-currency-payment-totalanddate"></a>

| <p><código>SELECCIONE o.`id_order` AS `id`, CONCAT(LEFT(c.ZXQ2QXZ, 1), '. ', c.`lastname`) AS `Customer`, ca.`name` AS `Carrier`, cu.`name` AS `Currency`, o.`payment`, CONCAT(o.ZXQ10QXZ, ' ', cu.ZXQ11QXZ) AS `Total`, o.`date_add` AS `Date`FROM `ps_orders` oLEFT JOIN `ps_customer` c ON (o.ZXQ17QXZ = c.ZXQ18QXZ)LEFT UNIRSE `ps_carrier` ca ON (o.id_carrier = ca.id_carrier)LEFT UNIRSE `ps_currency` cu ON (o.ZXQ21QXZ = cu.ZXQ22QXZ)</code><br><code></code></p> |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |

# Usos de muestra y detalles

## Intercambio de datos entre tiendas <a href="#sampleusagesandspecifics-dataexchangebetweenstores" id="sampleusagesandspecifics-dataexchangebetweenstores"></a>

### Compartir productos y categorías <a href="#sampleusagesandspecifics-sharingproductsandcategories" id="sampleusagesandspecifics-sharingproductsandcategories"></a>

Cuando crea una nueva tienda dentro de un grupo, puede elegir que todas (o algunas) de las categorías de la nueva tienda sean duplicados exactos de las categorías de cualquier otra tienda en su instalación de PrestaShop.

Al crear una categoría, ya sea para una tienda específica o para todas las tiendas en la instalación de PrestaShop, PrestaShop registra la categoría para todas las tiendas; simplemente se oculta en cualquier tienda donde no se haya configurado.

Al asociar las nuevas tiendas con una categoría determinada, cualquier cambio en esta categoría afectará a todas las tiendas asociadas a ella, incluso si las tiendas pertenecen a diferentes grupos de tiendas.&#x20;

Por lo tanto, puedes cambiar el contenido de la categoría de una vez por todas desde un solo lugar, incluidos sus productos.

**Categorías**: Un producto solo puede aparecer en una categoría determinada de una tienda si ha sido asociado con esta categoría en el contexto de esa tienda. En otras palabras: si la tienda A y la tienda B tienen la categoría C en común, puedes asociar el producto P a la categoría C para el contexto de la tienda A; y el producto P no aparecerá en la categoría C de la tienda B:

<figure><img src="../.gitbook/assets/image (43).png" alt=""><figcaption></figcaption></figure>

**Transportistas**: Puede administrar la asociación de transportistas por tienda, por grupo de tiendas o para todas las tiendas; pero no puedes personalizar un transportista por tienda. Debe duplicar el transportista si desea utilizar el mismo transportista con diferentes rangos de precios en dos tiendas.

### Compartir clientes y grupos de clientes <a href="#sampleusagesandspecifics-sharingcustomersandcustomergroups" id="sampleusagesandspecifics-sharingcustomersandcustomergroups"></a>

Como se indicó anteriormente, las tiendas dentro del mismo grupo de tiendas pueden compartir clientes: todo lo que tiene que hacer es configurar la opción adecuada al crear el grupo de tiendas.

Si desea tener diferentes grupos de clientes para cada tienda, deberá crear un nuevo grupo y utilizar el selector "Configuración multitienda para" para asociar el grupo a la tienda o grupo de tiendas actual.

Si la opción "Compartir clientes" ha sido deshabilitada, entonces su lista de clientes deberá estar vacía antes de poder habilitarla.

Si prefiere mantener su lista de clientes, puede hacer lo siguiente:

* **Vaya a su software de administración de bases de datos** como phpMyAdmin.
* **Buscar la tabla** `ps_customer`. Puede ser diferente, dependiendo del prefijo de su base de datos.
* **Exportar** esta tabla.
* **Vaciar la mesa. NO lo sueltes.** Si quieres eliminarlo, asegúrate de volver a crear la tabla después.
* **Vuelva a la configuración de varias tiendas** para el grupo de tiendas.
* Habilite la opción **"Compartir clientes"**.
* **Importar la tabla.**

Ahora se ha habilitado compartir clientes entre el grupo de tiendas sin perder información del cliente.

### Usar un tema diferente para cada tienda/grupo de tiendas <a href="#sampleusagesandspecifics-usinga Differentthemeforeachshop-shopgroup" id="sampleusagesandspecifics-usinga Differentthemeforeachshop-shopgroup"></a>

Una vez que un tema está instalado en su PrestaShop, puede usar la página "Tema y logotipo" en el menú "Diseño" para cambiar el tema de la tienda actual, o del grupo de tiendas actual, dependiendo del contexto seleccionado en el selector desplegable o en el encabezado.

## Utilizando configuraciones específicas para cada tienda o grupo de tiendas.

Si desea que sus modificaciones se apliquen a una tienda, un grupo de tiendas o una tienda específica, consulte el selector desplegable "Configuración multitienda para". Este es el primer elemento a tener en cuenta cuando se carga el back office: PrestaShop mostrará diferentes configuraciones disponibles dependiendo del contexto en el que te encuentres (tienda, grupo de tiendas, todas las tiendas).

Esto le permite:

* Utilice un formato de imagen diferente para cada tienda/grupo de tiendas
* Habilitar/Configurar módulos para cada tienda.
* Muestra y mueve bloques en la oficina principal de cada tienda.
* ¡Y mucho más...!

## Administrar páginas en modo multitienda <a href="#sampleusagesandspecifics-managingpagesinmultistoremode" id="sampleusagesandspecifics-managingpagesinmultistoremode"></a>

Al ver la lista de páginas de contenido en el contexto "Todas las tiendas", se muestran todas las páginas de todas las tiendas. Del mismo modo, cuando se encuentra en el contexto de un grupo de tiendas, se muestran las páginas de todas las tiendas de ese grupo.

Al crear una página en el contexto de un grupo de tiendas, todas las tiendas de este grupo mostrarán esta página, pero la página será única: editarla en una tienda aplicará los cambios en todas las tiendas de este grupo.\
En la página de creación, aparece una sección con una lista que indica cuáles se verán afectados.

## Gestión de descuentos en modo multitienda <a href="#sampleusagesandspecifics-managingdiscountsinmultistoremode" id="sampleusagesandspecifics-managingdiscountsinmultistoremode"></a>

Al crear reglas de carrito o reglas de precios de catálogo en un contexto multitienda, está disponible una condición adicional, con la que puedes elegir las tiendas en las que la regla debe estar disponible.

## Servicio web y multitienda <a href="#sampleusagesandspecifics-web-serviceandmultistore" id="sampleusagesandspecifics-web-serviceandmultistore"></a>

El acceso al servicio web también es altamente configurable, tanto a nivel de tienda como a nivel de grupo de tiendas. Al crear una clave de servicio web, puede optar por asociarla con todas las tiendas, algunos grupos de tiendas o tiendas seleccionadas.

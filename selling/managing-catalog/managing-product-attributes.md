# Gestionar los atributos del producto

Los atributos son la base de las variaciones de productos (o "combinaciones" en la interfaz de PrestaShop): sólo puedes crear variaciones de un producto si al menos uno de sus atributos cambia. Debes pensar en los atributos como propiedades de un producto que pueden cambiar entre variaciones manteniendo el mismo nombre del producto: color, capacidad, tamaño, peso, etc. Puedes usar cualquier cosa que varíe entre versiones del mismo producto, excepto el precio.

La diferencia entre un atributo y una característica depende del producto en sí. Algunos productos pueden compartir la misma propiedad, uno es un atributo creado para crear variaciones de productos y otro es simplemente una característica invariable. Por ejemplo, un cliente puede comprar una variación del iPad basándose en atributos (color, espacio en disco) pero no en características (peso, tamaño).

Del mismo modo, otra tienda podría vender variaciones de camisetas basadas en atributos (color, talla, género) pero no en características (peso). En su tienda, las características se muestran en una tabla, brindando información adicional sobre el producto; mientras que los atributos permiten seleccionar entre combinaciones de productos.

Los atributos se configuran por producto, desde la página "Productos" en el menú "Catálogo". Sin embargo, primero deben registrarse en su tienda utilizando la herramienta en la pestaña "Atributos" de la página "Atributos y características", en el menú "Catálogo".

Esta página presenta una lista de todos sus atributos registrados actualmente. Puede editar o eliminar cada uno usando las acciones a la derecha de la tabla, o mostrar sus valores haciendo clic en la acción "Ver", que abre una nueva tabla.

![](<../../.gitbook/assets/51839263 (3) (3) (1).png>)

También puede configurar el orden de presentación de los atributos en la oficina principal haciendo clic en los íconos de flecha o arrastrando y soltando cada fila cuando el mouse pasa por encima de la columna "Posición".

## Creando atributos <a href="#managingproductattributes-creatingattributes" id="managingproductattributes-creatingattributes"></a>

Para agregar un atributo, o lo que es lo mismo, agregar un grupo de posibilidades de variación (colores, capacidad, material, etc.), haga clic en "Agregar nuevo atributo". Aparece una nueva página.

![](<../../.gitbook/assets/64225526 (3) (3).png>)

Llene el formulario:

* **Nombre**. La descripción exacta del atributo. Debe ser breve pero preciso, para no confundirlo con otro atributo.
* **Nombre público**. El nombre del atributo, tal como se muestra a los clientes en la página del producto. Dado que algunos atributos pueden tener el mismo nombre para diferentes contenidos, este campo le permite presentarlos correctamente dentro del contexto del producto, al mismo tiempo que puede distinguir fácilmente un atributo de otro con un nombre similar pero significado diferente.
* **URL.** Defina la URL de la página del atributo.
* **Metatítulo.** Asigne un título a esta página.
* **Indexable.** Actívelo para indexar esta página en el módulo de búsqueda por facetas.
* **Tipo de atributo**. Le permite elegir si la página del producto debe mostrar los valores de este atributo como una lista desplegable, una lista de botones de opción o un selector de color (o textura).

Guarde su nuevo atributo para volver a la lista de atributos. Ahora debes agregar valores a tu atributo.

## Creando un nuevo valor <a href="#managingproductattributes-creatinganewvalue" id="managingproductattributes-creatinganewvalue"></a>

Haga clic en "Agregar nuevo valor". Aparece una nueva página.

![](<../../.gitbook/assets/64225527 (3) (3).png>)

Llene el formulario:

* **Grupo de atributos**. En la lista desplegable, seleccione uno de los atributos disponibles.
* **Valor**. Asigne un valor al atributo: "Rojo", "16 Gb", "1,21 gigavatios", etc.
* **URL.** Defina la URL de la página del valor del atributo.
* **Metatítulo.** Asigne un título a esta página.

Los siguientes campos solo se muestran si el atributo es un tipo de color.

* **Color**. Si el atributo es un color, puede ingresar su valor en un código de color HTML (es decir, "#79ff52" o "azul claro"), o usar el selector de color para mostrar con precisión el tono correcto.
* **Textura**. Si su producto no utiliza un color sólido sino uno texturizado (es decir, rayas de tigre), puede cargar un pequeño archivo de imagen que se mostrará en la página del producto. Tenga en cuenta que esto reemplazará el color HTML del campo de arriba. Haga clic en el botón "Guardar" para iniciar la carga.\
  También puedes utilizar esta opción para permitir que el cliente elija la variedad de color a partir de una imagen de tu producto en lugar de un color. La forma en que se muestra en el front-end depende del tema que estés usando...
* **Textura actual**. Una vez que haya cargado un archivo de textura, se muestra en esta sección como recordatorio.

Puede agregar más valores para el mismo tipo de atributo guardando los cambios con el botón "Guardar y luego agregar otro valor". Una vez que sus atributos estén en su lugar y sus valores estén establecidos, puede crear variaciones de productos (o "combinaciones") en la pestaña "Combinaciones" de cada producto, desde la página "Productos" en el menú "Catálogo".

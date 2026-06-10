# Gestión de productos

Puedes gestionar los productos de tu tienda utilizando la página **"Producto"**, en el menú **"Catálogo"**.

{% hint style="info" %}
**PrestaShop 8.1 se beneficia de una nueva página de producto**: lea la documentación aquí si desea obtener más información:
{% endhint %}

{% content-ref url="new-product-page-prestashop-8.1.md" %}
[página-de-nuevo-producto-prestashop-8.1.md](new-product-page-prestashop-8.1.md)
{% endcontent-ref %}



## **Secciones de este capítulo:**

* [Introducción a la página del producto](managing-products.md#ManagingProducts-Introductiontotheproductpage)
* [Creando un producto](managing-products.md#ManagingProducts-Creatingaproduct)
* [Creando un producto con combinaciones](managing-products.md#ManagingProducts-Creatingaproductwithcombinations)
* [Creando un producto virtual](managing-products.md#ManagingProducts-Creatingavirtualproduct)
* [Creando un paquete de productos](managing-products.md#ManagingProducts-Creatingapackofproducts)

## Introducción a la página del producto <a href="#managingproducts-introductiontotheproductpage" id="managingproducts-introductiontotheproductpage"></a>

Para crear un nuevo producto, desde la página "Catálogo", haga clic en "Nuevo producto" (o escriba CTRL + P): se abrirá lo que se llama la página del producto, donde podrá crear nuevos productos o editar los existentes.

### Pestañas <a href="#managingproducts-tabs" id="managingproducts-tabs"></a>

En PrestaShop 8, la página del producto está organizada en pestañas:

* **Configuraciones básicas**: contiene todo lo que necesitas para crear un producto de forma rápida y sencilla. Sin embargo, si necesita agregar más detalles a su producto, debería echar un vistazo a las otras pestañas.
* **Cantidades**, **Combinaciones** o **Producto virtual**: define las cantidades de tus productos y otras opciones relacionadas con el stock. Cuando su producto tenga combinaciones, la pestaña pasará a llamarse Combinaciones. Aquí es donde gestionas todas tus combinaciones. Por otro lado, si tienes un producto virtual, aquí es donde subes su archivo asociado si lo hubiera.
* **Envío**: proporcione detalles que puedan afectar la entrega del producto.
* **Precios**: refine sus precios con precios específicos o precio por unidad (entre otras opciones de precios).
* **SEO**: gestiona la meta descripción o la URL del producto para asegurarte de que esté optimizada para los motores de búsqueda.
* **Opciones**: funcionalidades adicionales para gestionar la visibilidad de tu producto, referencias específicas, archivos adjuntos o proveedores. También es aquí donde puedes configurar la personalización.

![](<../../.gitbook/assets/51185085 (3).png>)

### Nombre del producto <a href="#managingproducts-productname" id="managingproducts-productname"></a>

El primer campo a rellenar es el nombre del producto, que aparecerá en los resultados del buscador y en la URL de tu ficha de producto de forma predeterminada. Al lado del campo, encontrará un selector de idioma que le permitirá elegir el idioma en el que desea editar o crear el producto.

![](<../../.gitbook/assets/51185086 (2) (1).png>)

**Debes** darle al producto un nombre al menos en el idioma predeterminado antes de poder guardarlo. No podrás guardarlo hasta que tenga un nombre.

Asegúrese de traducir cada campo a todos los idiomas admitidos por su tienda. Para hacer eso, haga clic en el selector de idioma al lado del campo tipo de producto y elija el idioma en el que desea editar el producto.

### Tipo de producto <a href="#managingproducts-typeofproduct" id="managingproducts-typeofproduct"></a>

Esta segunda opción es imprescindible: indicar si el producto es un pack (combinación de al menos dos productos existentes), un producto virtual (archivo descargable, servicio, etc.) o simplemente un producto clásico enviado por correo. Por ahora, solo exploraremos el producto estándar sin combinaciones y trataremos los productos con combinaciones, paquetes y productos virtuales en sus propias secciones de este capítulo.

### Idioma <a href="#managingproducts-language" id="managingproducts-language"></a>

Es posible que hayas activado varios idiomas en tu tienda, para vender en más países. Si desea interactuar con sus clientes en el extranjero, todo su contenido (descripción del producto, subtítulos, etc.) debe traducirse a estos idiomas.

Para traducir el contenido de tu producto a otro idioma, simplemente selecciona en qué idioma te gustaría trabajar junto al tipo de selector de producto. La página del producto se actualizará con el contenido disponible en el idioma seleccionado. Puede cambiar de un idioma a otro sin guardar su trabajo en el medio. Solo asegúrate de editar el contenido en el idioma correcto.

De forma predeterminada, la página del producto mostrará contenido en el idioma predeterminado de su tienda.

Para agregar nuevos idiomas a tu tienda, ve a la sección Internacional. Puedes agregar solo un idioma en "Traducciones" o agregar un paquete de localización en "Localización". Encontrarás más información en la [sección internacional de la documentación](http://doc.prestashop.com/display/PS17/Going+International).

### Botones globales <a href="#managingproducts-globalbuttons" id="managingproducts-globalbuttons"></a>

![](<../../.gitbook/assets/51185087 (3) (1).png>)

* **Ventas**. Te redirige a la página "Detalle del producto" del panel de estadísticas (menú "Estadísticas"), que te ofrece un gráfico tanto de las visitas a la página de este producto como de sus ventas.
* **Lista de productos**. Muestra una lista de todos sus productos para permitirle navegar rápidamente de un producto a otro.
* **Ayuda**. Abre la ayuda contextual en una columna, correspondiendo la página de la Guía del Usuario a la página del producto.

En la parte inferior de la página se pueden realizar varias acciones:

* **Eliminar** (icono de papelera). Elimina todos los datos del producto actual y lo elimina, incluidas sus imágenes, combinaciones, características, etc.
* **Avance**. Muestra la página principal de su producto. Esto es muy útil, ya que funciona incluso si el producto está desactivado.
* **En línea / Fuera de línea**. Aquí es donde habilita o deshabilita su producto. Por defecto está deshabilitado, por lo que tus clientes no podrán verlo en tu tienda.
*   **Duplicado**. Guarde el producto actual, luego crea una copia exacta del producto actual y lo lleva a la página del nuevo producto. Esto es muy útil cuando prefiere utilizar los datos del producto actual como plantilla para otro producto nuevo y no tener que crear todos los datos del nuevo producto a mano. Por ejemplo, dos productos pueden ser muy diferentes pero pueden compartir las mismas asociaciones, transportistas o configuraciones de proveedores.

    ¡No duplique demasiado!

    Si necesita crear diferentes versiones del mismo producto, debido a su variedad de colores, capacidad, tamaño, etc., entonces debe crear una combinación de productos para el producto actual en lugar de duplicarla X veces. Consulta la opción "Combinaciones" en la pestaña "Configuraciones básicas", que se explica en la sección "Crear un producto con combinaciones" de este capítulo.
* **Ir al Catálogo**. Esto guarda cualquier cambio que haya realizado en cualquiera de los datos del producto actual y lo lleva de regreso a la lista de productos.
* **Agregar nuevo producto.** Esto guarda cualquier cambio que haya realizado en cualquiera de los datos del producto actual y abre una nueva página para crear un nuevo producto.
* **Ahorrar**. Esto guarda cualquier cambio que haya realizado en cualquiera de los datos del producto actual y lo mantiene en la pestaña actual. Esto es particularmente útil cuando desea cambiar de pestaña sin perder los cambios en la pestaña actual, o para ver que los cambios se apliquen de inmediato.&#x20;

![](<../../.gitbook/assets/51185088 (3) (2) (4).png>)

Atajos de teclado

Se han introducido algunos atajos de teclado en PrestaShop 1.7 para ayudarle a ahorrar tiempo al crear varios productos seguidos. El comportamiento es el mismo que el descrito anteriormente y funciona para las siguientes opciones:

* Duplicar: ALT+MAYÚS+D
* Activar/Desactivar en tu tienda: ALT+SHIFT+O
* Agregar un nuevo producto: ALT+SHIFT+P
* Volver al catálogo: ALT+SHIFT+Q
* Guardar: ALT+MAYÚS+S
* Vista previa: ALT+MAYÚS+V

## Creando un producto <a href="#managingproducts-creatingaproduct" id="managingproducts-creatingaproduct"></a>

La página del producto facilita la creación de un producto gracias a pestañas mejoradas.

### Configuración básica <a href="#managingproducts-basicsettings" id="managingproducts-basicsettings"></a>

![](<../../.gitbook/assets/57081940 (3) (3).png>)

La pestaña "Configuración básica" proporciona las principales opciones necesarias para crear un producto básico: con unos pocos clics, podrá crear un nuevo producto. Desde allí también puede navegar por las otras pestañas para agregar más detalles a su producto.

#### Imágenes <a href="#managingproducts-images" id="managingproducts-images"></a>

La sección de imágenes se encuentra en la parte superior izquierda de la pestaña "Configuración básica". Debes subir todas las imágenes de este producto, incluidas todas sus combinaciones (color, tamaño, forma, etc.).

**Para agregar una o más imágenes a su producto:**

Arrastre y suelte sus imágenes directamente desde su carpeta, o haga clic en "seleccionar archivos" (o en cualquier lugar de la sección de imágenes, de hecho) para buscar y abrir la carpeta que contiene sus imágenes. Puede seleccionar tantas imágenes como sea necesario manteniendo presionada la tecla Ctrl mientras selecciona archivos, o puede hacer su selección una por una. PrestaShop establece el tamaño máximo predeterminado para un archivo de imagen de acuerdo con la configuración PHP de su servidor. Este tamaño se puede reducir en la página de preferencias "Imágenes", sección "Imágenes de producto".

![](<../../.gitbook/assets/51839124 (5) (5).png>)

**Imagen de portada**

Las imágenes cargadas aparecen como miniaturas. La primera será la imagen predeterminada/de portada del producto. Esa imagen de portada también aparecerá automáticamente en la página del producto de tu tienda.

Puedes cambiar qué imagen es tu imagen de portada haciendo clic en la miniatura de la imagen: aparecerá la configuración para esta imagen determinada. Allí podrás marcar o desmarcar "Imagen de portada" para definir si la imagen debe ser la portada o no.

![](<../../.gitbook/assets/51839131 (5) (2).png>)

**Zoom y subtítulo**

Al pulsar en "Zoom" la imagen aparecerá en su formato real, por si quieres verla más de cerca.

Cada imagen puede tener un título: utilícelo para describir brevemente la imagen (y el producto). Es importante para el SEO ya que se considera el atributo alt de la imagen y, por lo tanto, ayuda a los motores de búsqueda a clasificar mejor su producto. Si tienes varios idiomas, ¡no olvides traducirlo!

**Clasificación de imágenes**

Una vez que haya subido todas las imágenes de sus productos, puede modificar su orden arrastrando y soltando cada imagen. También puedes agregar más imágenes haciendo clic en el ícono "+" o soltándolo.

![](<../../.gitbook/assets/51839715 (3) (3) (2).gif>)

#### Resumen y descripción <a href="#managingproducts-summaryanddescription" id="managingproducts-summaryanddescription"></a>

Describir bien tu producto es fundamental, tanto para el cliente (cuanta más información, mejor) como para los buscadores (ayudará a que tu tienda aparezca en más solicitudes de búsqueda).

En la parte inferior de la pantalla, los dos campos de descripción tienen cada uno diferentes propósitos:

* El campo **Resumen** te permite escribir una breve descripción que aparecerá en los motores de búsqueda y en la descripción de tu producto. \
  Este campo está limitado a 400 caracteres por defecto: si superas ese límite, PrestaShop te avisará con un mensaje en rojo debajo del campo. Puedes cambiar ese límite en la página de preferencias "Productos", donde encontrarás la opción "Tamaño máximo del resumen del producto".
* El campo **"Descripción"** le permite escribir una descripción completa de su producto, que aparecerá directamente en la página del producto. El editor de texto ofrece una amplia gama de opciones para crear descripciones visualmente atractivas (fuente, tamaño, color del texto, etc.).\
  Si bien este segundo campo no tiene límites, existe demasiado contenido: esfuércese por proporcionar la información esencial de una manera convincente y su producto debería estar listo para funcionar.

![](<../../.gitbook/assets/51185084 (3) (3) (1).gif>)

#### Característica <a href="#managingproducts-feature" id="managingproducts-feature"></a>

Debajo de las descripciones de los productos, puede encontrar varias opciones. La opción "Agregar una característica" sirve para especificar las características de sus productos (es decir, peso, material, país de origen, etc.).

Cuando crea características y valores (es decir, tejidos de lana y materiales de microfibra), los asigna a los productos cuando es apropiado. Esto significa que no tiene que completar los campos de características para cada uno de sus productos, sino que simplemente complete los valores necesarios y aplíquelos más tarde.

Tenga en cuenta que **a diferencia de las combinaciones, estos valores no cambian y son válidos para el producto general** (es decir: todas sus combinaciones compartirán estas mismas características).

**Añadiendo una función**

Antes de agregar una característica a un producto, debes crearla para uso general en tu tienda. Para ello, debe ir a la página "Atributos y características" del menú "Catálogo".

Las características y la creación de valor de características se explican en detalle en la [sección dedicada de la guía](managing-product-features.md).

![](<../../.gitbook/assets/51839148 (5) (4).png>)

**Asignar un valor a una característica**

Asumiremos aquí que ya ha configurado todas sus funciones y valores de funciones.

Al hacer clic en "Agregar una función", aparece un menú desplegable que enumera todas las funciones de su tienda. Seleccione qué característica desea agregar. A continuación, puede asignar uno de los valores predefinidos (como se estableció al crear la función) si hay alguno disponible o establecer un valor manualmente en el campo "Valor personalizado".&#x20;

Si no hay ningún valor disponible para una función, aparece la mención "No se encontró ningún resultado".

Si elige utilizar un valor personalizado, no olvide configurarlo para cada idioma que admita su tienda. Utilice el selector de código de idioma en la parte superior de la página para cambiar el idioma.

Si hay valores predefinidos disponibles, aparecerán en una lista desplegable. Simplemente haga clic en él y elija el valor correcto.

Una vez que haya configurado todas las funciones relevantes, guarde los cambios para verlos aplicados inmediatamente en la página principal.

Remember: Si una característica no tiene ningún valor asignado, no se tendrá en cuenta para este producto y no será visible en su tienda.

#### Marca <a href="#managingproducts-brand" id="managingproducts-brand"></a>

De la misma manera que puedes agregar una característica, puedes agregar una marca. Haga clic en "Agregar una marca" y elija una marca en el menú desplegable.

Si la marca que desea no está disponible en el menú desplegable, vaya a la página "Marcas y proveedores" para crear una nueva marca.

Un producto sólo puede asociarse a una marca.&#x20;

![](<../../.gitbook/assets/51185096 (3).png>)

#### Producto relacionado <a href="#managingproducts- relatedproduct" id="managingproducts- relatedproduct"></a>

El campo "Agregar un producto relacionado" le brinda la opción de elegir productos relevantes para asociarlos con este producto y sugerirlos a sus clientes cuando visiten la página del producto (si el tema lo admite). Haga clic en "Agregar un producto relacionado", escriba las primeras letras del producto y selecciónelo. Luego se añade el producto en la parte inferior del campo.

![](<../../.gitbook/assets/51185097 (2) (3).png>)

Puedes asociar un producto con tantos otros productos como consideres necesario. Haga clic en el icono de la papelera para eliminar la asociación del producto.\
Una asociación tiene un solo sentido: el producto asociado no incluirá una asociación con el producto actual en su página de configuración.

#### Combinaciones <a href="#managingproducts-combinations" id="managingproducts-combinations"></a>

![](<../../.gitbook/assets/51185098 (3) (1).png>)

A menudo venderá el mismo producto en diferentes versiones: comparten el mismo nombre general, pero pueden diferir en color, capacidad, tamaño de pantalla y otros atributos. La mayoría de las veces, estos atributos se juntan: podrías tener disponible la versión roja del producto con 1 Gb de capacidad o 2 Gb, o con una pantalla de 12'' o de 15''. Por eso PrestaShop llama a estas versiones "combinaciones": su stock de productos puede estar formado por varias variaciones de un solo producto, que en realidad son simplemente sus atributos combinados de maneras específicas.

Si necesita combinaciones para su producto, seleccione "Producto con combinaciones". La pestaña "Cantidades" de la página del producto pasará a llamarse "Combinaciones" y le permitirá crear diversas combinaciones.

No puede crear combinaciones si aún no tiene los atributos del producto configurados correctamente en PrestaShop.\
&#x20;Además, no debe crear una combinación de funciones entre las que sus clientes no deberían poder elegir.

La creación de atributos se realiza en la página "Atributos y características" del menú "Catálogo" y se explica en detalle en este [capítulo dedicado de la documentación](managing-product-attributes.md).

Para obtener más información sobre las Combinaciones, lea la [sección dedicada al final de este capítulo](managing-products.md#ManagingProducts-Combinations).

#### Cantidad <a href="#managingproducts-quantity" id="managingproducts-quantity"></a>

Indique cuántos productos hay disponibles para la venta.

Esta opción no se mostrará si estás creando un producto con combinaciones: las cantidades de las combinaciones se gestionan en la pestaña "Combinaciones", ya que cada combinación puede tener un valor de cantidad diferente.&#x20;

Hay más opciones de cantidad disponibles en la pestaña "Cantidad".

#### Precio <a href="#managingproducts-price" id="managingproducts-price"></a>

![](<../../.gitbook/assets/51185099 (3) (2) (1).png>)

Define cuánto quieres vender este producto.

* **Precio – Impuestos excluidos**. Aquí es donde debes fijar tu precio. Es independiente de cálculos, impuestos y otros precios.
* **Precio – Impuestos incluidos.** Muestra el precio del producto con impuestos incluidos. Puede editar el valor y se actualizará automáticamente el campo "Impuesto excluido" según la regla impositiva que elija.
* **Regla fiscal**. El impuesto es aplicable al producto. Elige entre las diferentes tarifas que tienes registradas. Al cambiar la regla fiscal, el precio con impuestos incluidos cambiará en consecuencia.

Hay más opciones de precios disponibles en la pestaña "Precios". Ya sea que cambie su precio en la pestaña "Configuración básica" o "Precios" es lo mismo, ya que las pestañas están sincronizadas.

Las normas fiscales se pueden gestionar en el menú "Internacional", página "Impuestos".

#### Categorías <a href="#managingproducts-categories" id="managingproducts-categories"></a>

![](<../../.gitbook/assets/51185100 (5) (1) (6).png>)

La sección "Categorías" le permite seleccionar en qué categoría debe aparecer el producto. Puedes seleccionar más de uno, pero ten en cuenta que es mejor para el cliente si la categoría sólo contiene productos equivalentes y comparables. Por lo tanto, debe evitar seleccionar categorías raíz y preferir categorías secundarias.\
Por ejemplo, la categoría "teléfono" puede incluir subcategorías de "marcas" (Apple, Samsung, HTC, etc.) así como "características" (dual sim, Android, etc.). Depende de usted indicar la categoría más útil para sus clientes.

**Asociar categorías existentes**

Para asociar una categoría a su producto, puede usar la barra de búsqueda o expandir la lista de categorías y seleccionar la que desea asociar.

**Usando la barra de búsqueda**. Escriba las primeras letras de la categoría y la barra mostrará todas las categorías coincidentes y la ruta para acceder a ellas. Elige tu categoría y haz clic en ella. Se mostrará en el apartado “Categorías asociadas”.

**Usando la lista de categorías**. Al hacer clic en "Expandir", verás el árbol de categorías y desde allí podrás seleccionar las categorías que deseas asociar.

En la lista de categorías asociadas, si pasa el mouse sobre una categoría específica, verá la ruta que conduce a la categoría. Puede resultar útil si tiene varias categorías con el mismo nombre (como "Zapatos", que puede estar en las categorías "Niños" y "Mujeres").

**Categoría principal**

El selector de "categoría principal" es útil cuando un artículo se clasifica en varias categorías. Sirve principalmente para aclarar qué categoría utilizar en caso de que tu cliente llegue a tu sitio desde un buscador ya que el nombre de la categoría aparecerá en la URL del producto.

**Creando una nueva categoría**

Si cree que necesita agregar una categoría, guarde el estado actual de su producto antes de hacer clic en el botón "Crear nueva categoría".&#x20;

Haga clic en "Crear una categoría": y aparecerán las opciones de la categoría. Complete el nombre de la categoría y seleccione la categoría principal. Al hacer clic en crear, se creará la nueva categoría y automáticamente se asociará a su producto.

No olvide ir a la página "Categorías" más tarde para completar los detalles de esta nueva categoría. Para leer más sobre las categorías, [vaya a la sección relacionada de la documentación](managing-categories.md).

&#x20;Una nueva categoría no aparecerá automáticamente en el menú de tu tienda. Para mostrarlo, debe editar el menú con el módulo "Menú principal" (cuando use el tema predeterminado), o cualquier módulo personalizado que tenga para administrar el menú.

En este punto, ha terminado con la información esencial para una página de producto básica. Puedes guardarlo. Para tenerlo inmediatamente disponible para la venta en tu tienda, haz clic en "Sin conexión": su estado cambiará a "En línea" y será visible en tu tienda.

Sin embargo, debes seguir leyendo, ya que hay muchos más detalles que puedes agregar a tu producto para hacerlo más atractivo para los clientes.

### **Cantidades** <a href="#managingproducts-product_quantitiesquantities" id="managingproducts-product_quantitiesquantities"></a>

Las cantidades de productos se gestionan en una sola pestaña. PrestaShop utilizará esto para determinar cuándo un producto pronto estará agotado o ya no estará disponible.

![](<../../.gitbook/assets/57606479 (2) (1).png>)

#### Producto estándar <a href="#managingproducts-standardproduct" id="managingproducts-standardproduct"></a>

Para un producto estándar sólo tienes cuatro campos:

* **Cantidad.** Define cuántos productos están a la venta. Es el mismo valor que el de "Configuración básica".
* **Ubicación del stock.** Sabemos que siempre es útil poder saber dónde encontrar un producto. Así sea este campo.
* **Cantidad mínima para la venta.** Es posible que prefieras que este producto se venda al por mayor. Utilice este campo para establecer la cantidad de artículos que se venderán al por mayor. Esto significa que los clientes podrán comprar este producto solo cuando alcancen esta cantidad mínima.
* **Alertas de stock.** También puedes establecer una regla para productos con poco stock en esta sección. Indique un umbral y marque la casilla "Enviarme un correo electrónico cuando la cantidad sea inferior o igual a este nivel" para enviar un correo electrónico a todos los usuarios que pueden ejecutar la página de stock; los permisos se pueden modificar en [Parámetros avanzados > Equipo](http://doc.prestashop.com/display/PS17/Team).

#### Producto con Combinaciones <a href="#managingproducts-productwithcombinations" id="managingproducts-productwithcombinations"></a>

La forma en que funciona es bastante sencilla: la página le presenta una tabla con todas las combinaciones del producto actual (si no hay combinaciones, la tabla simplemente tiene una sola fila). Depende de usted establecer el stock inicial para todas las combinaciones.

Para obtener más información sobre combinaciones de productos, [lea la sección dedicada al final de la página](managing-products.md). Los packs y productos virtuales tienen diferentes configuraciones de stock, encontrarás todo lo que necesitas al final de este capítulo.

#### **Preferencias de disponibilidad** <a href="#managingproducts-availabilitypreferences" id="managingproducts-availabilitypreferences"></a>

**Comportamiento de falta de stock**

La opción "Comportamiento cuando no hay stock" le permite configurar el comportamiento de PrestaShop cuando el producto está agotado:

* Denegar pedidos (el producto ya no está disponible para la venta).
* Permitir pedido (en esencia, estás haciendo preventas).&#x20;
* Utilice el comportamiento predeterminado (Denegar pedidos). Esta tercera opción predeterminada simplemente utiliza la configuración predeterminada global (menú "Preferencias", página "Productos", sección "Stock de productos", opción "Permitir pedidos de productos agotados").

**Etiquetas**

* **Etiqueta cuando esté en stock**. Le permite mostrar un mensaje a sus visitantes cuando su producto está en stock, por ejemplo, "Artículo disponible". Les asegura que su tienda puede enviarles el producto inmediatamente.
* **Etiqueta cuando no hay existencias y el pedido pendiente está activo**. Le permite mostrar un mensaje a sus visitantes cuando su producto está agotado, pero aún pueden pedirlo (según se establece usando el selector "**Cuando está agotado**"), por ejemplo, "¡Haga su pedido ahora!". Les asegura que su tienda les enviará el producto inmediatamente una vez que esté disponible.
* **Fecha de disponibilidad**. Indique cuándo volverá a estar disponible el producto.

También puedes configurar los ajustes generales que se aplican a todos tus productos: la opción predeterminada es rechazar pedidos, pero esto se puede modificar en "Configuración de productos" en la sección "Parámetros de la tienda" (opción "Permitir pedidos de productos agotados").

### **Envío** <a href="#managingproducts-shipping" id="managingproducts-shipping"></a>

La pestaña "Envío" le permite brindar algunos detalles valiosos sobre el paquete de su producto. No está disponible en el caso de un producto virtual.

![](<../../.gitbook/assets/51185106 (3) (5) (3).png>)

*   **Dimensión del paquete (ancho, alto, profundidad y peso)**. Debes esforzarte por completar cada campo porque conocer el tamaño y el peso exactos de un paquete no solo te resultará útil, sino que PrestaShop también puede dirigir tamaños y pesos específicos a transportistas específicos de forma automática, en función de esta configuración. El precio final del pedido aparecerá al cliente una vez que PrestaShop (o el cliente) haya seleccionado un transportista.&#x20;

    Estos valores utilizan las unidades predeterminadas de peso, volumen, distancia y dimensión, tal como se establecen en la página "Localización" del menú "Localización".

    Estos valores no tienen que ser números enteros. Si sus productos pesan menos de 1 libra, simplemente puede usar un punto (.) para indicar las fracciones:

    * 123 libras
    * 1,23 libras
    * 0,23 libras (equivale a 3,68 onzas)
    * etc.\
      \

* **Gastos de envío (gastos de envío adicionales)**. Esto puede resultarle muy útil para productos específicos que son especialmente difíciles de envasar o muy pesados.
* **Transportistas disponibles**. Puede optar por que el producto actual solo sea enviado por una selección de transportistas. Si no se selecciona ningún transportista, todos los transportistas estarán disponibles para los pedidos de los clientes.

### **Precios** <a href="#managingproducts-pricing" id="managingproducts-pricing"></a>

La pestaña de precios permite perfeccionar su estrategia de precios, ya sea utilizando precios alternativos (precio por unidad) o creando algunas reglas de precios específicas para el producto.

#### **Precio minorista** <a href="#managingproducts-retailprice" id="managingproducts-retailprice"></a>

El precio de su producto antes de impuestos.

* **Precio – impuestos excluidos**. Aquí es donde puedes establecer un precio arbitrario, independiente de los cálculos y precios regulares. Mantenga este campo en "0" para utilizar el precio predeterminado.
* **Precio – impuestos incluidos.** Muestra el precio del producto con impuestos incluidos. Puede editar el valor y se actualizará automáticamente el campo "Precio minorista antes de impuestos" de acuerdo con la regla impositiva que elija.
* **Precio por unidad (sin IVA)**. El precio unitario del producto en el momento de la adición. Esto es para fines de valoración.
* **Regla fiscal**. El impuesto aplicable al producto. Elige entre las diferentes tarifas que tienes registradas. Un enlace lo redirigirá a las páginas de reglas fiscales si desea realizar algunos cambios. [Lea más sobre las normas fiscales en esta sección](http://doc.prestashop.com/display/PS17/Tax+Rules).
* **Muestre el mensaje "¡En oferta!" bandera en la página del producto y en el texto que se encuentra dentro de la lista de productos.** Marque esa casilla para mostrar que su producto está en oferta, tanto en la página del producto como en el texto de la lista de productos. Aparecerá un icono de "En oferta" debajo del producto. Puede modificar este logotipo cambiando el siguiente archivo: `themes/default/img/onsale_en.gif`
* **Precio de venta final**. Este precio, incluido el descuento obtenido, se actualizará a medida que escriba.

Puede completar el campo "Precio - impuestos excluidos" y elegir la tasa impositiva que se aplicará, y el campo calculará automáticamente el precio minorista con impuestos. La operación opuesta también está disponible.

#### **Precio de costo** <a href="#managingproducts-costprice" id="managingproducts-costprice"></a>

Ingresa el precio que pagaste por el producto (cuánto te costó adquirir o fabricar el producto), te permitirá compararlo con tu precio de venta para poder calcular fácilmente tu ganancia.

El precio de costo debe ser menor que su precio minorista.

#### Precios específicos: Gestión de descuentos <a href="#managingproducts-specificprices-managingdiscounts" id="managingproducts-specificprices-managingdiscounts"></a>

Puedes cambiar el precio total del producto en función del número de productos que compra tu cliente, el grupo de usuarios, el país, etc. Esto se hace desde el apartado "Precios específicos" de la pestaña "Precios". Haga clic en el botón "Agregar un precio específico" para revelar el formulario de creación:

![](<../../.gitbook/assets/51185109 (3) (7) (3).png>)

Esta es una manera muy sencilla de crear un precio de descuento para este producto (y todas sus combinaciones).

* **Para**. Esto le permite ser muy específico acerca de los distintos grupos a los que se aplica este precio, incluidas monedas, países e incluso sus grupos de clientes (que analizaremos en un capítulo posterior).
* **Cliente**. Puedes optar por ser aún más específico y establecer directamente a quién se dirige el descuento que estás creando. Comience a escribir las primeras letras del nombre o apellido del cliente y seleccione las que desee.
* **Combinaciones**. Puedes elegir que este precio específico se aplique a todas las combinaciones del producto o solo a una. Si deseas aplicar a más de una combinación pero no a todas, tendrás que crear un precio específico para cada combinación.
* **Disponible desde/hasta**. Aquí puedes definir un rango de fechas entre las cuales el precio de descuento está activo. Al hacer clic en cada selector se abrirá un calendario, lo que simplificará el proceso.
* **A partir de \[] unidad**. Contiene el valor a partir del cual se debe aplicar el descuento. El valor predeterminado es "1", que significa cualquier cantidad. Si ha seleccionado una combinación para la cual se aplica el precio específico y define más de una unidad, significa que el cliente tendrá que comprar esta cantidad de esta combinación determinada para beneficiarse del descuento.
* **Precio del producto (sin IVA)**. Aquí es donde puedes establecer un precio arbitrario, independiente de los cálculos y precios regulares. Esto anulará el precio minorista. Para habilitar este campo, primero debe deshacer clic en "Dejar precio inicial".
* **Dejar precio inicial**. Marque esta casilla para restablecer el campo "Precio del producto" y evitar editarlo.
* **Aplica un descuento de**. Utilice el selector para establecer el tipo de descuento (ya sea un monto específico en la moneda predeterminada o un porcentaje del precio predeterminado). En la ficha del producto aparecerá tachado el precio inicial junto al precio rebajado.

Una vez que haya elegido sus valores, haga clic en "Aplicar": el resumen de la configuración de su descuento aparece a continuación. El descuento será inmediatamente visible en la tienda.\
Si desea eliminar un valor, haga clic en el icono de la papelera en la tabla.

Si desea crear descuentos más complejos, lea sobre el menú "Descuentos" en el capítulo ["Administración de descuentos" de esta guía](managing-discounts/).

#### **Gestión de prioridades** <a href="#managingproducts-prioritymanagement" id="managingproducts-prioritymanagement"></a>

Un cliente puede encajar en múltiples precios o reglas de descuento, incluso cuando haya establecido precios detallados y descuentos por cantidad, con grupos y tiendas personalizados (si se encuentra en un contexto de varias tiendas). PrestaShop, por lo tanto, utiliza un conjunto de prioridades para aplicar una regla de precio único a dichos clientes. Por ejemplo, es posible que desee que el grupo de usuarios sea más importante que la moneda.

Puede cambiar la configuración predeterminada de PrestaShop utilizando la sección "Gestión de prioridades".

![](<../../.gitbook/assets/51185110 (3) (2) (3).png>)

El orden de importancia predeterminado es:

1. Tienda (cuando esté en un contexto multitienda).
2. Divisa.
3. País.
4. Grupo.

Una casilla de verificación en la parte inferior le permite actualizar la configuración de todos los productos. Si la casilla de verificación permanece sin marcar, sus cambios solo se aplican al producto actual.

### **SEO** <a href="#managingproducts-seo" id="managingproducts-seo"></a>

Para mejorar su listado de productos y aumentar la visibilidad de su tienda, le sugerimos que complete cuidadosamente los distintos campos de SEO: metatítulos, metadescripciones, palabras clave y URL amigables.

"SEO" en sí significa "Optimización de motores de búsqueda". Lea más en Wikipedia: [http://en.wikipedia.org/wiki/Search\_engine\_optimization](http://en.wikipedia.org/wiki/Search\_engine\_optimization)

¡Conozca las mejores prácticas de SEO para comercio electrónico! Descargue y lea la "Guía completa de SEO" gratuita de PrestaShop: [http://www.prestashop.com/en/white-paper-seo](http://www.prestashop.com/en/white-paper-seo)

Para acceder a la información SEO del producto, vaya a la pestaña "SEO".

![](<../../.gitbook/assets/57606471 (3) (3) (1).png>)

#### Optimización de motores de búsqueda <a href="#managingproducts-searchengineoptimization" id="managingproducts-searchengineoptimization"></a>

Los campos de esta página le permiten optimizar directamente la visibilidad de su catálogo en los motores de búsqueda.

* **Avance**. Con el lanzamiento de PrestaShop 1.7.5, ahora puede obtener una vista previa en tiempo real de los resultados de su motor de búsqueda para ayudarle a ver cómo se mostraría su página.
* **Metatítulo**. Este es el campo más importante, ya que el título aparecerá en todos los motores de búsqueda. Sea muy objetivo: debe convencer al usuario del motor de búsqueda de que haga clic en su enlace, no en uno de otro sitio. Asegúrese de que el título sea exclusivo de este producto dentro de su sitio.
  * Buen ejemplo: "Levi's 501® Original Jeans - Tidal Blue - Original Fit".
  * Mal ejemplo: "Artículo n.º 02769869B, bestseller".
* **Meta descripción**. Una presentación del producto en tan solo un par de líneas (idealmente, menos de 155 caracteres), destinada a captar el interés del cliente. Esto aparecerá en los resultados de algunos motores de búsqueda, dependiendo de la solicitud de búsqueda: algunos motores de búsqueda pueden optar por mostrar las palabras clave buscadas directamente en el contexto del contenido de la página. Asegúrese de que la descripción sea exclusiva de este producto dentro de su sitio.
* **URL amigable**. Este es otro campo extremadamente importante. Le permite reescribir las direcciones web de sus productos como desee. Por ejemplo, en lugar de tener una dirección como\
  [http://www.myprestashop.prestashop.com/index.php?id\_product=8\&controller=product](http://www.myprestashop.prestashop.com/index.php?id\_product=8\&controller=product)\
  puedes tener:\
  [http://www.myprestashop.prestashop.com/8-nombre-del-producto.html](http://www.myprestashop.prestashop.com/8-name-of-the-product.html).\
  Todo lo que necesitas hacer es indicar en el campo "URL amigable" las palabras que deseas que aparezcan en lugar del nombre predeterminado, separadas por guiones.\
  El botón "**Restablecer URL**" facilita la creación de una URL descriptiva adecuada basada en el nombre del producto. Una vez generada, puede editar la URL generada si es necesario.\
  \


Las URL amigables solo funcionarán si la reescritura de URL está habilitada. Puede hacer esto en la página de preferencias "SEO y URL" (en el menú "Tráfico"), en su sección "Configurar URL".

Encontrará más información en la página de preferencias "SEO y URL" en el capítulo ["Tráfico" de esta guía](http://doc.prestashop.com/display/PS17/Traffic).

#### &#x20;Página de redireccionamiento <a href="#managingproducts-redirectionpage" id="managingproducts-redirectionpage"></a>

Cuando su producto esté fuera de línea, su página de producto ya no estará disponible en su tienda. En su lugar, debes decidir qué quieres mostrar a tus visitantes:

* **Sin redirección (404).** Esto mostrará la página "Error 404 - No encontrado".
* **Redirección permanente (301).** Esto redirigirá permanentemente al visitante a otra página de producto o categoría. La URL actual de la página de su producto ya no será indexada por los motores de búsqueda: será reemplazada por la URL de la página del producto o categoría de su elección. Elija qué página desea mostrar en su lugar. Recuerde, esto es permanente, así que asegúrese de no necesitar más esta URL antes de activar la redirección 301.
* **Redirección temporal (302).** Esta es una redirección temporal a otra página de producto o categoría. Elija qué página de producto o categoría le gustaría mostrar en su lugar. Los motores de búsqueda seguirán indexando la URL de la página, por lo que podrás reutilizarla más adelante fácilmente, en caso de que reactives el producto, por ejemplo.

Si desea mostrar una página de categoría, debe seleccionar a qué categoría desea redirigir.

### **Opciones** <a href="#managingproducts-options" id="managingproducts-options"></a>

La pestaña "Opciones" proporciona configuraciones adicionales para administrar referencias de productos, proveedores, personalización de productos, visibilidad y archivos.&#x20;

#### **Visibilidad** <a href="#managingproducts-visibility" id="managingproducts-visibility"></a>

Puedes optar por tener el producto disponible a través de diferentes canales:

* **En todos lados**. Los clientes pueden acceder al producto navegando por el catálogo, buscando el nombre del producto o utilizando directamente su URL.
* **Solo catálogo**. Los clientes pueden acceder al producto navegando por el catálogo o directamente utilizando su URL.
* **Buscar sólo**. Los clientes pueden acceder al producto buscando su nombre o directamente utilizando su URL.
* **En ningún lugar**. Los clientes sólo pueden acceder al producto mediante su URL. No lo encontrarán navegando por el catálogo ni buscando su nombre. Esto es excelente para crear productos privados, a los que solo pueden acceder unos pocos visitantes confiables, incluso temporalmente (puede cambiar esta configuración en cualquier momento).

**Opciones**. Un par de opciones específicas.

* **evitandoDisponible para pedidos**. Si desmarca esta casilla, los clientes no podrán agregar este producto a su carrito. Esto lo hace más parecido a un modo de catálogo de un solo producto (en comparación con la preferencia "modo de catálogo").
* **Mostrar precio**. Si la opción "disponible para pedido" anterior no está marcada, puede elegir mostrar el precio del producto de todos modos (aunque los visitantes no podrán comprarlo) o elegir no mostrarlo.
* **Solo web (no se vende en su tienda minorista)**. Si su empresa tiene tiendas físicas, esta opción resultará invaluable cuando un producto solo se vende en línea, no en la tienda; esto evita que los clientes verifiquen el precio de un producto en línea y luego vayan a su tienda con la esperanza de comprarlo directamente y, por lo tanto, eviten los costos de envío.

#### Etiquetas <a href="#managingproducts-tags" id="managingproducts-tags"></a>

Las etiquetas son términos y palabras clave que ayudarán a sus clientes a encontrar fácilmente lo que buscan.  Cuando utilicen la barra de búsqueda para explorar su catálogo, escribirán algunas palabras clave específicas. Elija las palabras clave más relevantes para su producto para asegurarse de que el producto aparezca en los resultados cuando un visitante lo busque.

Para agregar varias etiquetas, simplemente sepárelas con una coma. Por ejemplo: "plato llano, vajilla, gres" para un plato llano.

![](<../../.gitbook/assets/51185117 (3) (5) (4).png>)

Todas las etiquetas se pueden ver en la página "Buscar", en el menú "Parámetros de la tienda". Encontrará más información sobre la gestión de etiquetas en este [capítulo dedicado](http://doc.prestashop.com/display/PS17/Tags).

Las etiquetas de producto no son lo mismo que las palabras clave de una página: no tienen un impacto directo en la ubicación en los motores de búsqueda.

#### Condición y referencias <a href="#managingproducts-condition-and-references" id="managingproducts-condition-and-references"></a>

**Condición**. No todas las tiendas venden productos nuevos y algunos mercados requieren que usted proporcione esta información. Esta opción le permite indicar el estado del producto:

* **y Nuevo**. El producto es nuevo y sellado en su embalaje original.
* **Usado**. El producto se vendió al menos una vez antes y probablemente lo haya usado otra persona (de segunda mano). Debe venir en su embalaje original, que podrá cerrarse con cinta adhesiva.
* **Renovar**. El producto ha sido devuelto por diversos motivos ("rayones, abolladuras u otras formas de daño cosmético que no afectan el rendimiento de la unidad"). Lea más en Wikipedia: [http://en.wikipedia.org/wiki/Refurbishment\_%28electronics%29](http://en.wikipedia.org/wiki/Refurbishment\_\(electronics\)).
* **Código de referencia**. Esta es su propia referencia interna. Puede ser un número, o su referencia del lugar de almacenamiento o su proveedor, o cualquier cosa que lo haga único.
* **ISBN.** El ISBN se utiliza internacionalmente para identificar libros y sus diversas ediciones. Si sus productos son libros o tienen derecho a tener un número ISBN, ingréselo aquí.
* **Código de barras UPC.** Este estándar para códigos de barras se utiliza principalmente en los Estados Unidos, Canadá, el Reino Unido, Australia y Nueva Zelanda.\

* **Código de barras EAN-13 o JAN**. Estos son los números del código de barras del producto, que se utilizan en todo el mundo para identificarlo. Puede utilizar un número EAN-13 o JAN.
  * Un EAN-13 es el número de artículo internacional de 13 dígitos del producto. Pídalo el [GS1](https://www.gs1.org/) tan pronto como se cree su producto para poder venderlo en Google Shopping o en los mercados. Lea más en Wikipedia: [http://en.wikipedia.org/wiki/International\_Article\_Number\_%28EAN%29](http://en.wikipedia.org/wiki/International\_Article\_Number\_\(EAN\)).
  * Un JAN es específico de Japón pero es compatible con el EAN internacional. Lea más en Wikipedia: [http://en.wikipedia.org/wiki/Japanese\_Article\_Number](http://en.wikipedia.org/wiki/Japanese\_Article\_Number).
* **MPN.** El MPN (número de pieza del fabricante) es una referencia única del fabricante. Le permite relacionar fácilmente un producto con el fabricante adecuado, lo que tiene múltiples ventajas tanto para el comerciante como para el cliente. \
  Los comerciantes pueden diferenciar fácilmente productos similares gracias a su identificador y gestionar el stock de productos por parte del fabricante. El producto también se puede encontrar en el buscador con el identificador. \
  El MPN también es útil para los clientes: el MPN puede indexarse ​​en los Marketplaces y, por lo tanto, los clientes podrán encontrar más rápidamente el producto que buscan. ¡Los clientes también obtendrán con seguridad el producto adecuado, lo que aumenta su confianza!

#### Personalización <a href="#managingproducts-customization" id="managingproducts-customization"></a>

PrestaShop permite a tus clientes personalizar el producto que comprarán.

Example: Eres un minorista de joyas y tus clientes tienen la posibilidad de grabar sus joyas con un texto o una imagen. Sus clientes pueden enviar el texto y/o la imagen cuando realizan su pedido.

La ventaja de esta función es que ofrece a tus clientes un servicio personalizado, que sin duda apreciarán.

Veamos cómo configurar esta función. Haga clic en "Agregar un campo de personalización" para indicar qué tipo de contexto (archivo y/o texto) se puede personalizar. Puede colocar tantos campos como permita que sus clientes carguen.

![](<../../.gitbook/assets/51185118 (3) (9) (1).png>)

Para cada campo de personalización, debe proporcionar dos datos:

* **Etiqueta**. Rellénelo con la etiqueta pública adecuada: esto será un indicador para el cliente, así que sea muy específico sobre lo que espera.
* **Tipo**. Indique si desea que el cliente escriba algún texto o proporcione un archivo.\
  \


Ejemplo 1: el cliente puede personalizar la portada de un libro proporcionando 3 imágenes. Puedes tener 3 campos de personalización:

| Etiqueta | Tipo |
| ---------------------------------------------- | ----- |
| Portada (20,95 x 27,31 cm, color) | Imagen |
| Contraportada (20,95 x 27,31 cm, blanco y negro) | Imagen |
| Lomo (20,95 x 1,716 cm, color) | Imagen |

Ejemplo 2: si los clientes pueden grabar palabras en un producto, podría utilizar lo siguiente:

| Etiqueta | Tipo |
| ------------------------------- | ---- |
| Primera línea (24 caracteres) | Texto |
| Segunda línea (24 caracteres) | Texto |
| Última línea, firma (16 caracteres) | Texto |

Una vez que se hayan completado todos los campos de la etiqueta, no olvide guardar los cambios.

**Del lado del cliente**

Una vez que un producto tiene propiedades personalizables configuradas, su página de producto frontal tiene un nuevo bloque, debajo de la descripción: "Personalización del producto".

El cliente debe elegir el(los) archivo(s) y/o agregar algún texto y guardarlos antes de agregar el producto al carrito.

Las imágenes y los textos personalizados aparecerán en el carrito final.

El resto del proceso de compra es el mismo de siempre.

**Del lado del comerciante**

Una vez que el cliente ha validado el pedido, el comerciante recibe una notificación del pedido en el back office.

Luego podrá consultar el pedido, que indicará la(s) imagen(es) y el(los) texto(s) en la lista de productos, para cada producto. Luego, el comerciante simplemente tiene que descargar la(s) imagen(es) (simplemente haciendo clic en la imagen en el pedido) o copiar/pegar el texto y usarlo en su herramienta de personalización.

El resto del proceso de pedido y entrega es el mismo de siempre.

#### **Adjuntando un archivo** <a href="#managingproducts-attachingafile" id="managingproducts-attachingafile"></a>

PrestaShop le permite poner algunos archivos a disposición de sus clientes antes de su compra.

Por ejemplo, digamos que vende productos electrónicos y le gustaría instar a sus clientes a leer un documento sobre cómo funciona un producto. Puede cargar un documento para ese propósito.\
También puede simplemente tener el manual en PDF del producto disponible para descargar directamente en la página del producto. El cliente puede acceder a él incluso si no compró el producto.

**Archivos adjuntos**

Si ya cargó algunos archivos para adjuntar, verá aquí la lista de los archivos disponibles para adjuntar al producto. Simplemente seleccione el archivo que desea adjuntar al producto.

**Adjuntar un archivo nuevo**

Si aún no ha adjuntado ningún archivo, puede cargar un archivo nuevo directamente en esta página:

1. Haga clic en "Adjuntar un archivo"
2. Haga clic en "Examinar" para seleccionar un archivo en su computadora para cargar.
3. Complete el título de su archivo adjunto (no tiene que ser el mismo que el nombre del archivo original).
4. Dale una descripción. Esto le ayudará a distinguir con certeza entre los archivos cargados y brindará información adicional a sus clientes.
5. Haga clic en "Agregar".
6. El archivo adjunto aparece en la lista "Archivos adjuntos", ya seleccionado para indicar que se adjuntará al producto.
7. Guarde su producto.

Aparecerá una nueva pestaña en la página del producto, junto a "Detalles del producto", donde sus clientes podrán descargar los archivos que acaba de cargar.

Si necesita eliminar un archivo adjunto de la página de este producto, simplemente debe deseleccionarlo en la tabla "Archivos adjuntos".

Puede ver todos los archivos adjuntos de su tienda, agregar algunos más y eliminar algunos, yendo a la página "Archivos" en el menú "Catálogo". Esto también permite utilizar los archivos que ya has subido para otros productos: si necesitas aplicar el archivo asociado a muchos productos, sólo tendrás que subirlo una vez.

#### **Proveedores** <a href="#managingproducts-suppliers" id="managingproducts-suppliers"></a>

Indicar el proveedor del producto no es realmente importante para tus clientes (mucho menos que su marca en cualquier caso), pero puede llegar a ser una parte esencial de tu propia gestión interna, sobre todo a la hora de gestionar tu stock: simplemente necesitas saber a quién has comprado el producto. El proveedor del producto actual se debe configurar desde la sección "Proveedores" de la pestaña "Opciones".

No puedes utilizar esta función si aún no tienes al menos un proveedor registrado en tu tienda. Los proveedores se crean desde la página "Marcas y proveedores", en el menú "Catálogo".

El proceso completo de registro de proveedores se explica en detalle en un [capítulo dedicado de esta guía](managing-suppliers.md).

Asociar el producto actual a uno o más proveedores es realmente sencillo: simplemente marca la casilla correspondiente al proveedor y guarda los cambios.

**Referencia(s) del proveedor**

La sección de proveedores también cuenta con una tabla que permite establecer la referencia precisa y el precio unitario/moneda de cada combinación de productos, por proveedor. Si el producto tiene más de un proveedor, la tabla mostrará cada proveedor uno tras otro.

Hay muchas más opciones relacionadas con el producto en la página "Configuración del producto" del menú "Parámetros de la tienda":

* Número de días durante los cuales el producto se considera "nuevo".
* Orden de producto predeterminado.
* Habilite la gestión avanzada de stock.
* etc.

Realmente deberías comprobar que estas configuraciones globales estén configuradas como deseas.

## Creando un producto con combinaciones <a href="#managingproducts-creatingaproductwithcombinations" id="managingproducts-creatingaproductwithcombinations"></a>

Para habilitar combinaciones de productos, primero debe elegir la opción "Producto con combinaciones" en la pestaña "Configuración básica". Verá que la pestaña "Cantidades" cambia a "Combinaciones", y aquí es donde podrá administrar sus combinaciones de productos.

No se pueden crear combinaciones para packs de productos o productos virtuales: sólo está disponible para productos estándar.

No puede crear combinaciones si aún no tiene los atributos del producto configurados correctamente en PrestaShop.\
&#x20;Además, no debe crear combinaciones de funciones entre las que sus clientes no deberían poder elegir.

La creación de atributos se realiza en la página "Atributos del Producto" del menú "Catálogo" y se explica detalladamente en el capítulo del mismo nombre de esta guía.

La forma en que se combinan los atributos de su producto depende de usted, y PrestaShop le ofrece dos métodos para lograrlo.

### Agregar combinaciones <a href="#managingproducts-addingcombinations" id="managingproducts-addingcombinations"></a>

#### Método manual <a href="#managingproducts-manualmethod" id="managingproducts-manualmethod"></a>

Este método te ayuda a crear combinaciones una tras otra. Por lo tanto, debe reservarse para productos con pocas combinaciones o para productos con combinaciones muy específicas que no se pueden crear de manera confiable utilizando el método automático (consulte la siguiente sección).

Agregar una nueva variación a su producto requiere solo unos pocos pasos.

1. En la barra de combinación, ingresa la combinación de atributos que necesitas crear, con sus valores correspondientes.&#x20;

Por ejemplo, si necesitas crear una combinación para una camiseta, talla M y color rojo, debes ingresar "talla m color rojo". A medida que escribe, verá sugerencias que aparecen debajo de la barra, simplemente seleccione los atributos y valores que necesita.

Puede agregar tantos pares atributo-valor como sea necesario a una combinación.\
Sólo puedes agregar un par por atributo a una combinación: es imposible tener "Color: Azul" y "Color: Rojo" en tus pares; si esto es necesario, tendrás que crear nuevos atributos, por ejemplo, "Color primario" y "Color secundario".

Puede eliminar un par atributo-valor haciendo clic en la cruz en su cuadro gris.&#x20;

&#x20;2\. Cuando tenga todos los atributos necesarios, haga clic en "Generar" a la derecha.

&#x20;3\. La combinación aparecerá en la siguiente tabla.

![](<../../.gitbook/assets/51185209 (3) (5) (2).gif>)

#### Método automático <a href="#managingproducts-automaticmethod" id="managingproducts-automaticmethod"></a>

Si tiene demasiadas versiones o variedades de productos diferentes, puede utilizar el "Generador de combinaciones de productos". Esta herramienta te permite generar automáticamente todas las combinaciones y posibilidades.

En lugar de escribir cada combinación que desee, puede utilizar el selector en el lado derecho de la página. Enumera todos los atributos y sus valores correspondientes.

Esto es lo que debes hacer:

1. Para cada atributo, marque los valores que desea agregar como combinaciones. Puede seleccionar varios valores para cada atributo para ahorrar algo de tiempo.
2. Automáticamente añadirá las combinaciones correspondientes en la barra de la izquierda.
3. Si estás satisfecho con tu selección, haz clic en "Generar": automáticamente creará tu combinación, con **todas las combinaciones posibles**.

Para una sola combinación, puedes editar su cantidad directamente en la tabla, editarla (haciendo clic en el ícono del lápiz) o eliminarla (con el ícono de la papelera).

### Gestión de combinaciones <a href="#managingproducts-managingcombinations" id="managingproducts-managingcombinations"></a>

#### Combinación predeterminada <a href="#managingproducts-defaultcombination" id="managingproducts-defaultcombination"></a>

Cuando tengas varias combinaciones disponibles, deberás elegir qué combinaciones serán la combinación predeterminada. Será la combinación que vean tus clientes cuando lleguen en la ficha del producto. Si quieren comprar otra combinación, tendrán que seleccionarla ellos mismos (ya sea cambiando el color, el tamaño o cualquier atributo que pueda tener).

#### Editar una combinación <a href="#managingproducts-editingacombination" id="managingproducts-editingacombination"></a>

Cada combinación se puede gestionar aún más haciendo clic en el icono de edición. Se abrirá una pequeña ventana cuando puedas cambiar los detalles de esta combinación específica.

* Detalles de combinación
  * **Establecer como combinación predeterminada**. Marque esta casilla si desea que la combinación que está creando sea realmente la principal para este producto.
  * **Cantidad**. Ingrese la cantidad disponible para la venta para esta combinación
  * **Fecha disponible**. Si la combinación está agotada, podrás indicar cuándo volverá a estar disponible.
  * **Cantidad mínima a la venta**. Es posible que prefieras que esta combinación solo se venda al por mayor. Utilice este campo para establecer la cantidad de artículos que se venderán al por mayor. Significa que los clientes podrán comprar este producto solo cuando alcancen esta cantidad mínima para esta combinación.
  * **Referencia y referencias específicas (ISBN, EAN-13 y UPC)**. Si es necesario, indica la referencia de la combinación, ISBN EAN-13 y/o números UPC en cada campo, como si estuvieras creando un producto nuevo en PrestaShop. Estos números pueden ser utilizados por su almacén o su transportista, así que asegúrese de completar estos campos, ya que a menudo son esenciales para su negocio.&#x20;
* Precio e impacto\

  * **Precio de coste**. Este campo es útil si el precio original del producto cambia simplemente porque se trata de una combinación.
  * **Impacto en precio/precio unitario/peso**. Si se supone que la combinación tendrá un impacto en el precio/peso/precio unitario original del producto, complete el campo que aparece con el valor de ese impacto (por ejemplo, "-2" si el precio debe reducirse en 2).
* **Imagen**. Se muestran las imágenes que están vinculadas al producto original (tal como se cargaron mediante el formulario en la pestaña "Imágenes" a la izquierda). Marque la casilla de las imágenes que mejor representen esta combinación.

Una vez que haya terminado de editar una combinación, puede:

* vaya a la combinación anterior o siguiente para editarla también, haciendo clic en "combinación anterior" o "combinación siguiente"
* volver al producto haciendo clic en "volver al producto" al final de la página

#### Acciones masivas <a href="#managingproducts-bulkactions" id="managingproducts-bulkactions"></a>

Puedes cambiar los detalles de todas o varias combinaciones a la vez.&#x20;

1. Selecciona las combinaciones que deseas editar. Haga clic justo debajo de "Seleccionar" para seleccionarlos todos.
2. Haga clic en "Acciones masivas" encima de la lista de combinaciones.
3. Edite las configuraciones que desea modificar. Se modificará para todas las combinaciones que hayas seleccionado.
4. Haga clic en "Aplicar" para editar las combinaciones.

Si desea eliminar todas las combinaciones que ha seleccionado, haga clic en "Eliminar combinaciones".

Cuando haya configurado todos los detalles de la combinación, guarde los cambios de su producto usando el botón "Guardar y permanecer". Su combinación aparecerá en la lista de atributos en la parte inferior de la pantalla.

## Creando un producto virtual <a href="#managingproducts-creatingavirtualproduct" id="managingproducts-creatingavirtualproduct"></a>

Su tienda puede ofrecer (parcial o exclusivamente) productos virtuales, es decir, productos que no se envían, sino que se descargan: entradas de entretenimiento, libros electrónicos/archivos PDF, servicios de la vida real...\
PrestaShop te facilita la creación de un producto virtual.

El proceso para hacer esto es similar al de crear un producto simple:

* Vaya a la página "Productos", en el menú "Catálogo".
* Haga clic en el botón "Nuevo producto".
* Junto al nombre del producto, cambie el tipo de producto a "Producto virtual".

La organización de la página cambiará:

* La pestaña "Cantidades" pasa a ser "Producto Virtual".
* La pestaña "Envío" desaparece.

La pestaña "Producto virtual" solo presenta una opción al principio: pregunta si el producto virtual que está creando tiene un archivo adjunto (es decir, si su cliente pagará para descargar algo).

* Si no, déjalo así: estás vendiendo un servicio y no es necesario descargar nada.
* En caso afirmativo, haga clic en la opción "Sí".

Al hacer clic en "Sí", PrestaShop abre un nuevo formulario dentro de la pestaña, desde el cual puedes cargar el archivo que deseas vender:

![](<../../.gitbook/assets/51185126 (3) (5).png>)

*   **Archivo**. Haga clic en el botón "Examinar" para encontrar el archivo en su disco duro. Tan pronto como haya seleccionado un archivo, comenzará la carga.

    La configuración del tamaño máximo de carga de archivos depende de la configuración de su servidor y no se puede aumentar desde PrestaShop.

    Si tiene acceso al archivo `php.ini` de su servidor, estos son los valores que debe cambiar:

    * `upload_max_filesize = 20M`
    * `post_max_size = 20M`

    Si no tiene acceso al archivo `php.ini`, comuníquese con su proveedor de alojamiento web al respecto.

    * **Nombre del archivo**. El nombre del archivo. Este campo se completa automáticamente después de cargar el archivo. No se recomienda cambiarlo a otro valor.

    Debe comprimir su archivo en formato zip para evitar que el navegador malinterprete los formatos de archivo `.exe` o `.jpg`. Los navegadores descargan automáticamente archivos zip para el cliente, sin hacer preguntas.

    Si vende una imagen de alta resolución, cargarla mediante este formulario no le impide cargar su miniatura en la pestaña "Imágenes" de la izquierda.
* **Número de descargas permitidas**. Puede establecer la cantidad de veces que se puede descargar el archivo una vez que el cliente lo haya comprado. Es posible que prefieras limitar esto a 1 o 5. Si deseas mantenerlo ilimitado, configura el campo de texto en 0.
* **Fecha de expiración**. Los archivos virtuales pueden tener carácter promocional o perder su valor de venta después de una fecha determinada. Si es así, puedes establecer la fecha de caducidad después de la cual el producto ya no estará disponible en tu tienda. Déjelo en blanco si no hay fecha de vencimiento.
* **Número de días**. Puede establecer el número de días después de los cuales el enlace de descarga deja de funcionar. Si no hay límite, establezca el campo de texto en 0.

Una vez que haya terminado con la pestaña "Producto virtual", podrá editar todas las demás pestañas disponibles como si lo hiciera con un producto normal.

## Creando un paquete de productos <a href="#managingproducts-creatingapackofproducts" id="managingproducts-creatingapackofproducts"></a>

Es posible que desee vender un paquete de productos compuesto por varios artículos. Es decir: un paquete de puesta en marcha del ordenador compuesto por el propio ordenador, un monitor y una impresora. PrestaShop te facilita la creación de un producto "pack" y añadir otros productos de tu catálogo a este pack.

Los packs te permiten simplificar la preparación de pedidos. También permiten a los clientes aprovechar precios y ofertas especiales.

Actualmente no puedes agregar combinaciones o productos virtuales a un paquete.\
&#x20;Si necesitas tener packs con combinaciones, tendrás que crear productos únicos para cada combinación. Esta es una limitación conocida que se solucionará en una próxima versión de PrestaShop.

No puede agregar un paquete existente dentro de un paquete nuevo ni importar el contenido de un paquete existente a un paquete nuevo.

El proceso para crear un pack es similar al de crear un producto normal:

1. Vaya a la página "Productos", en el menú "Catálogo".
2. Haga clic en el botón "Nuevo producto".
3. A continuación el nombre del producto en la parte superior, cambie el tipo de producto a "Paquete de productos".

Esto cambiará dos cosas:

* En "Configuración básica" podrás elegir qué productos forman parte del pack
* En "Cantidades" puede seleccionar cómo se deben gestionar las existencias.

### Agregar productos a su paquete <a href="#managingproducts-addingproductstoyourpack" id="managingproducts-addingproductstoyourpack"></a>

* El primer campo se utiliza para buscar productos que ya están registrados en tu tienda.
* El segundo campo se utiliza para indicar la cantidad de producto elegido que se debe añadir al pack.
* El botón añade el producto al pack.

![](<../../.gitbook/assets/51185208 (3) (3) (1).png>)

Puedes añadir tantos productos como quieras al pack.

Puede eliminar un producto del paquete simplemente haciendo clic en el icono de la papelera cuando pasa el cursor sobre él.

### Gestión de cantidades de paquetes <a href="#managingproducts-managingpackquantities" id="managingproducts-managingpackquantities"></a>

Cuando estás creando un pack de productos, PrestaShop necesita saber cómo gestionar el stock. En la pestaña "Cantidades", dentro de "Cantidades por pack", debes elegir una de las siguientes opciones:

* **Solo paquete de decremento** (comportamiento predeterminado). Cuando se vende un paquete, solo se verá afectado el stock del paquete.
* **Productos decrementales solo en pack**. Cuando se vende un pack, sólo se verá afectado el stock de cada producto.
* **Disminuye ambos**. Cuando se vende un paquete, tanto el stock del paquete como el stock de cada producto se verán afectados.
* **Comportamiento predeterminado**. Este es el comportamiento predeterminado establecido a nivel de tienda en la Configuración del producto. De forma predeterminada, tendrá "Solo paquete de decremento", pero cambiará según su elección.

Una vez que haya terminado con la pestaña "Paquete", puede editar el contenido de todas las demás pestañas disponibles como lo haría con un producto normal.

12 consejos esenciales para crear una página de producto eficiente

&#x20;Mire nuestro breve vídeo con 12 consejos sobre cómo crear una excelente página de producto:

<figure><img src="../../.gitbook/assets/51839720 (7) (7) (5).png" alt=""><figcaption></figcaption></figure>

# SEO y URL

Las herramientas de esta página le ayudarán a mejorar la presencia de su sitio PrestaShop en las búsquedas web y, por tanto, a llegar a más clientes potenciales.

SEO significa "optimización de motores de búsqueda". Representa un conjunto de técnicas y mejores prácticas destinadas a mejorar la visibilidad de un sitio web en los motores de búsqueda. Puede leer más sobre esto en [Wikipedia](http://en.wikipedia.org/wiki/Search\_engine\_optimization). URL es la abreviatura de "Localizador uniforme de recursos" o, simplemente, la dirección en línea de una página web. Puede leer más sobre qué es una URL en [Wikipedia](http://en.wikipedia.org/wiki/URL).

De forma predeterminada, las URL profundas (that is, specific pages rather than online the domain name) de PrestaShop no son informativas ni para los clientes ni para los motores de búsqueda: una URL como [http://www.myprestashop.com/product.php?id\_product=27](http://www.myprestashop.com/product.php?id\_product=27) no ayuda a los visitantes a saber qué producto hay en esa página. Las URL amigables son la forma de lograrlo y obtener, por ejemplo, [http://www.myprestashop.com/2-music-players/27-ipod-nano-green](http://www.myprestashop.com/2-music-players/27-ipod-nano-green).

Como puede ver en el segundo ejemplo anterior, tanto las categorías como los productos pueden tener una URL amigable: en el ejemplo anterior, `id_category=2` se convierte en `2-music-players` y `id_product=27` se convierte en `27-ipod-nano-green`. Si bien el número de identificación no se puede eliminar de forma predeterminada, las palabras pueden generarse a partir del nombre de la categoría/producto o escribirse a mano. Esto se hace directamente en la página de configuración del producto o categoría (in the "Catalog" menu): el campo "URL amigable" se puede encontrar directamente en la página de configuración principal de una categoría y en la pestaña "SEO" de la página de configuración de un producto.

Hay otras páginas individuales en su instalación de PrestaShop que sin duda se beneficiarían de URL amigables: páginas CMS, páginas de cuentas de usuario, páginas con contenido generado automáticamente. La página "SEO y URL" le presenta una lista de estas páginas y le permite editar sus URL amigables, así como sus metaetiquetas (title, description, keyword).

![](<../../../.gitbook/assets/64225659 (4) (4) (3).png>)

Las URL amigables solo funcionan con una configuración de servidor que admita la reescritura de URL (through the Apache Web Server ZXQ0QXZ feature, for instance). Asegúrese de verificar que su servidor funcione con (if needed, ask your hosting provider!), ya que puede hacer que su tienda no esté completamente disponible para los clientes si habilita URL amigables y el servidor no las admite.

### &#x20;Configuración SEO de la página de inicio <a href="#seoandurls-homepageseosettings" id="seoandurls-homepageseosettings"></a>

Para cambiar las metaetiquetas de la página de inicio, simplemente necesita abrir la página "SEO y URL" y hacer clic en "índice" para acceder a la configuración de la página y editar libremente su información SEO importante.

![](<../../../.gitbook/assets/64225660 (4) (4) (4).png>)

A few tips:

* El título predeterminado de la página de inicio es el nombre de la tienda y, por lo tanto, el campo de título del índice está vacío. Si coloca contenido en el campo, el título completo de la página de inicio será reemplazado por su entrada. El nombre de la tienda se establece durante la instalación de PrestaShop y se puede cambiar desde la pestaña "Detalles de contacto", disponible en la sección Parámetros de la tienda > Contacto del back office.
* Mantenga su descripción breve: un párrafo de texto es suficiente.
* Para agregar una meta palabra clave, haga clic en el campo y valide presionando "Regresar". Puede eliminar etiquetas haciendo clic en la cruz.
* No es necesario agregar una URL reescrita si ya existe una.

Tenga en cuenta que si su tienda ya ha sido indexada por Google o cualquier otro motor de búsqueda, es posible que los cambios tarden un poco en aparecer en los resultados de búsqueda... ¡quizás tenga que tener paciencia!

## Adding a new friendly URL <a href="#seoandurls-addinganewfriendlyurl" id="seoandurls-addinganewfriendlyurl"></a>

Las URL amigables se deben configurar en la página de configuración de cada producto, categoría o página de contenido estático. Esta página de creación sólo es útil para algunas páginas automáticas y la mayoría de las veces no tendrás que preocuparte por ellas.

Asegúrate de completar los campos para todos los idiomas disponibles en tu tienda: no sólo es inmensamente útil para los usuarios locales, sino que algunos motores de búsqueda pueden incluso hacer uso de esta información local.

![](<../../../.gitbook/assets/64225660 (4) (4) (4).png>)

Haga clic en el botón "Agregar nueva página" para acceder al formulario de creación de URL amigable. Tiene un puñado de campos:

* **Página**. La lista desplegable le brinda todas las páginas que pueden beneficiarse de una URL amigable.
* **Título de la página**. El título que aparecerá en los motores de búsqueda cuando se realice una solicitud.
* **Meta descripción**. Una presentación de la página en pocas palabras, destinada a captar el interés del cliente. Aparecerá en los resultados de la búsqueda.
* **Metapalabras clave**. Palabras clave que debe definir para que los motores de búsqueda hagan referencia a su sitio. Puedes ingresar varias de ellas: escribe las palabras, presiona la tecla "Regresar" y observa cómo la etiqueta queda encapsulada en un bloque azul, con un pequeño ícono de cruz para eliminarla.
* **URL reescrita**. Aquí es donde configuras la URL amigable. Hágalo breve y descriptivo, use solo letras y números y reemplace los espacios (" ") por guiones ("-").

## Set up URLs <a href="#seoandurls-setupurls" id="seoandurls-setupurls"></a>

Las principales opciones para URL amigables:

*   **URL amigable**. Cambie esta opción _si sabe que su servidor_ puede admitir la reescritura de URL. Si no, déjelo en "No".

    Es posible que vea un mensaje como "_La reescritura de URL (mod\_rewrite) no está activa en su servidor o no es posible verificar la configuración de su servidor. Si desea utilizar URL amigables, debe activar este mod_". En este caso, PrestaShop no puede detectar la configuración de su servidor, pero eso no significa que la función no funcionará. Debes probarlo tú mismo.
* **URL acentuada**. PrestaShop puede generar URL con caracteres especiales para productos con nombres que no sean ASCII. Puede desactivar esa opción aquí.
*   **Redirigir a la URL canónica**. Una página PrestaShop determinada puede tener muchas URL, generalmente cuando hay parámetros a considerar: por ejemplo, [`http://example.com/product.php?id=5&option1`](http://example.com/product.php?id=5\&option1) y [`http://example.com/product.php?id=5&option2`](http://example.com/product.php?id=5\&option2) apuntan al mismo producto, solo una diferencia. Como desea que su producto tenga una única URL y no muchas duplicadas, debe habilitar las URL canónicas.\
    \
    Las URL canónicas son una forma de eliminar el contenido duplicado creado por uno mismo, lo que puede reducir drásticamente la clasificación de su motor de búsqueda, ya que se considera spam. Para evitar que los motores de búsqueda piensen que está enviando spam a su índice, PrestaShop utiliza la etiqueta de enlace estándar `rel="canonical"` para indicar cuál es la URL base para un contenido determinado. Si bien es muy recomendable habilitar esta opción, también depende de que su tema implemente correctamente la etiqueta de encabezado `<link>`. Si es necesario, solicite más información al diseñador del tema.

    \
    _¡Nuevo desde 1.7.6!_ De forma predeterminada, es la URL canónica de un producto al que se llama y, en caso de combinaciones, la URL canónica apunta hacia la combinación predeterminada.\
    \
    There are three options:

    * _Sin redirección._ Es posible que obtenga URL duplicadas.
    * _301 Mover permanentemente._ Devuelve el código de estado HTTP 301, apuntando a la URL principal y notificando a los motores de búsqueda que esta es la única URL a tener en cuenta. Recomendamos esta opción una vez realizadas las modificaciones.
    * _302 Movido temporalmente._ Devuelve el código de estado HTTP 302, que apunta a la URL principal y notifica a los motores de búsqueda que la URL principal podría cambiar más adelante.
* **Deshabilite la opción MultiViews de Apache**. Apache es el servidor web más popular y probablemente sea el que utiliza su servidor web para su sitio (although you should check this for yourself). Multiviews es un sistema de negociación de contenido: cuando está habilitado, el servidor web intenta ofrecer al usuario una página en la que cree que es la versión de idioma que mejor se adapta, bajo la misma URL. Desafortunadamente, esto podría traer problemas a la función de URL amigables de PrestaShop. Si este es el caso, puedes intentar desactivar las vistas múltiples con esta opción.
* **Deshabilite el módulo mod\_security de Apache**. `mod_security` es un módulo del servidor web Apache, que actúa como un firewall, protegiendo su servidor de intrusiones. Sin embargo, puede bloquear algunas funciones clave o incluso producir errores en alguna configuración. En tal caso, desactive ese firewall aquí.\
  \


![](<../../../.gitbook/assets/64225661 (4) (4) (3).png>)

## Establecer URL de tienda <a href="#seoandurls-setshopurl" id="seoandurls-setshopurl"></a>

En esta sección, puede ver y editar algunas de las configuraciones predeterminadas del servidor:

* **Dominio de la tienda**. El nombre de dominio principal o la dirección IP de su tienda.
* **Dominio SSL**. El nombre de dominio seguro de su tienda (ZXQ0QXZ) o la dirección IP.
* **URI base**. La carpeta donde instaló PrestaShop. Si está en la raíz del dominio, utilice "`/`".

La mayoría de las veces recomendamos no tocar estos campos sin saber exactamente lo que estás haciendo. De hecho, un solo error a veces puede arruinar tu tienda.

![](<../../../.gitbook/assets/64225662 (3).png>)

## Schema of URLs <a href="#seoandurls-schemaofurls" id="seoandurls-schemaofurls"></a>

_Is displayed only if friendly URLs are enabled._

Puedes cambiar la forma en que se generan las URL amigables cambiando la ruta a un recurso en tu tienda. Por ejemplo, la ruta predeterminada para mostrar la página de un producto es `{category:/}{id}-{rewrite}{-:ean13}.html`, lo que da como resultado `/summer-dresses/7-printed-chiffon-dress.html`. Podrías cambiar esa ruta a `{manufacturer:/}{id}-{rewrite:/}` para obtener `/fashion-manufacturer//7-printed-chiffon-dress/`

Hay ocho campos disponibles de forma predeterminada y cada uno va acompañado de una lista de palabras clave disponibles. Algunas palabras clave son obligatorias y se indican con un "\*".

![](<../../../.gitbook/assets/64225664 (3) (4).png>)

Una vez actualizados tus campos, ¡no olvides guardar los cambios!

## SEO options <a href="#seoandurls-seooptions" id="seoandurls-seooptions"></a>

_¡Nuevo desde 1.7.5.1!_ PrestaShop ahora le permite habilitar la visualización de los atributos de su producto en su metatítulo.

![](<../../../.gitbook/assets/64225663 (2) (1) (4).png>)

## Robots file generation <a href="#seoandurls-robotsfilegeneration" id="seoandurls-robotsfilegeneration"></a>

Un archivo `robots.txt` le permite bloquear robots automatizados y arañas web específicos que rastrean la Web para encontrar más páginas web para agregar a los servidores de su empresa. Con algunos bots querrás tener acceso completo a tu sitio web, como los de Google o Yahoo!, y con otros preferirías que no, como los bots de spam, ladrones de contenido, recolectores de correo electrónico, etc. Ten en cuenta que los peores bots no respetan las directivas de este archivo, ya que es puramente informativo.

La herramienta de generación `robots.txt` de PrestaShop simplemente crea un archivo con directivas de exclusión para archivos y directorios que no deben ser públicos y no deben indexarse. Estas directivas se aplican a todos los bots, buenos o malos: el archivo generado usa la cadena "User-agent: \*".

Al hacer clic en el botón "Generar robots.txt", se reemplaza cualquier archivo `robots.txt` existente por uno nuevo. Por tanto, si quieres añadir tus propias reglas, hazlo después de que PrestaShop haya generado su versión del archivo.

![](<../../../.gitbook/assets/64225665 (4).png>)

Video: 4 consejos para comenzar bien el SEO para su sitio de comercio electrónico

[![](<../../../.gitbook/assets/51839782 (6) (6) (3).png>)](https://www.youtube.com/watch?v=NnPEoE3MuHk\&index=13\&list=PLyZYn1MMU7-xT-L\_zUyGnRBJmAuP6uc-c)

# Performance

Esta página combina muchas herramientas y consejos que podrían ayudarle a mejorar el rendimiento de su tienda en cuanto al servidor, no en cuanto a las ventas, aunque un servidor que funciona bien puede atender a más clientes y, por lo tanto, generar más ventas.

## Smarty <a href="#performance-smarty" id="performance-smarty"></a>

Smarty es el nombre del lenguaje de plantilla utilizado por los temas de PrestaShop. Puede obtener más información al respecto en [http://www.smarty.net/](http://www.smarty.net/).

![](<../../.gitbook/assets/51839999 (4) (4) (4).png>)

There are several options:

* **Caché de plantilla**. Para un mejor rendimiento del front-end, PrestaShop almacena en caché sus páginas HTML.
  * **Nunca vuelvas a compilar archivos de plantilla**. El comportamiento normal: las páginas HTML se compilan y almacenan en caché, luego se muestran tal cual, incluso si el tema ha cambiado mientras tanto.
  * **Vuelva a compilar las plantillas si los archivos se han actualizado**. PrestaShop puede ver cuándo ha cambiado un archivo de tema.
  * **Forzar compilación**. Habilite esto solo si está realizando ediciones en el tema y necesita ver los cambios cada vez que recarga su página.
* **Cache**. Esta opción le permite deshabilitar todos los cachés de archivos, y no solo el que pertenece a los archivos de plantilla. Desactive esto solo si está depurando un tema o módulo para PrestaShop. De lo contrario, deberías dejarlo habilitado.\
  El botón "Borrar caché" en la parte superior de la página permite eliminar el caché con un solo clic en lugar de tener que eliminar archivos en su servidor FTP.
* **Optimizaciones multifrontales**. Cuando tienes varios servidores, esta opción te ayuda con la sincronización de su caché.
* **Tipo de almacenamiento en caché**. De forma predeterminada, Smarty utiliza un mecanismo de almacenamiento en caché basado en archivos. Puede optar por que utilice MySQL como recurso de almacenamiento para el almacenamiento en caché de salida de Smarty.
* **Borrar caché**. Dependiendo de la frecuencia con la que cambie su tienda, es posible que desee no borrar nunca los archivos de caché o borrarlos cada vez que se modifique su tienda (either products or design).

## Debug mode <a href="#performance-debugmode" id="performance-debugmode"></a>

Cuando estás en modo de depuración, puedes optar por disminuir el impacto de ciertas funciones en PrestaShop, para identificar mejor de dónde proviene un error:

![](<../../.gitbook/assets/51840000 (4) (4).png>)

* **Desactivar módulos que no sean de PrestaShop**. El propio módulo de PrestaShop ha sido probado exhaustivamente y no debería presentar ningún problema. Si habilita esta configuración, podrá saber si el problema proviene del código propio de PrestaShop (core or module) o de un módulo de terceros.
* **Desactivar todas las anulaciones**. Muchas funciones de PrestaShop se pueden anular. Si habilita esta configuración, todo el código de anulación se deshabilitará y podrá saber si el problema proviene del propio código de PrestaShop o de una anulación de un tercero.
* **Modo de depuración**. Al habilitar esta opción, los mensajes de error técnicos serán visibles. Es útil cuando alguien que no tiene acceso a su tienda le ayuda pero necesita saber qué está pasando técnicamente.

## Optional features <a href="#performance-optionalfeatures" id="performance-optionalfeatures"></a>

Algunas funciones de PrestaShop se pueden desactivar si no las utilizas, ya que pueden ralentizar tu tienda.

Si su catálogo actualmente tiene productos que utilizan estas funciones, no podrá desactivarlas. Tendrás que eliminar algunos datos antes de poder desactivarlos.

Puede desactivar las siguientes funciones:

![](<../../.gitbook/assets/43417621 (4) (4).png>)

* **Combinaciones**. Las combinaciones de productos le permiten tener una línea completa de productos a partir de un solo producto: diferentes tamaños, colores, capacidades, etc.
* **Características**. Las características del producto permiten indicar información específica del producto: peso, material, país de origen, etc.
* **Grupos de clientes**. Los grupos de clientes le permiten agrupar clientes para otorgarles ciertos privilegios y restricciones: descuentos, restricciones de módulos, etc.

## Combinar, comprimir y almacenar en caché (CCC) <a href="#performance-combine-compressandcache-ccc" id="performance-combine-compressandcache-ccc"></a>

CCC es un conjunto de herramientas destinadas a minimizar la carga del servidor y el tiempo de carga de temas.

Hace lo que dice: combina archivos de texto del mismo tipo en un archivo más grande, lo que hace que se descarguen menos archivos; luego comprime el archivo usando el algoritmo Zip común, lo que acelera las descargas; finalmente, almacena en caché el archivo comprimido, para que el servidor no tenga que realizar este proceso cada vez que se carga una página, lo que alivia la carga del procesador del servidor.

![](<../../.gitbook/assets/51840001 (4) (4) (1).png>)

* **Caché inteligente para CSS**. Los archivos CSS están basados ​​en texto y se pueden combinar y comprimir de forma segura.
* **Smart cache for JavaScript**. JavaScript files are also text-based, but their combination can sometimes prove problematic. Make sure to test everything before leaving that setting enabled.
* **Optimización de Apache**. Esta configuración cambiará el archivo de configuración de su servidor web para hacerlo más eficiente para CCC.

## Media servers <a href="#performance-mediaservers" id="performance-mediaservers"></a>

Esta sección le permite redirigir parte de su tráfico (image and video files, for instance) a otros servidores bajo su control, a través de otros dominios o subdominios; la mayoría de las veces, los archivos están alojados en un CDN (Content Delivery Network). De forma predeterminada, PrestaShop admite un servidor de medios.

![](<../../.gitbook/assets/51840002 (4) (4) (2).png>)

Poner el nombre de dominio de su tienda en este campo no es la forma adecuada de obtener un rendimiento fantástico. Dicho esto, es fácil configurar un servidor de medios y los beneficios son reales y casi inmediatos. Así es como:

1. Abra una cuenta en un nuevo servidor, preferiblemente uno que sea especialista en contenido distribuido. Los más populares son Akamai ([http://www.akamai.com/](http://www.akamai.com/)), Amazon (with its AWS services, among which is CloudFront: [http://aws.amazon.com/](http://aws.amazon.com/)) o CloudFlare ([http://www.cloudflare.com/](http://www.cloudflare.com/)). También deberías preguntarle a tu propio proveedor de alojamiento, tal vez tenga un servicio CDN al que puedas suscribirte.
2. Copie sus archivos multimedia al servidor de ese host. Esto significa que el servidor CDN debe contener una copia exacta de las siguientes carpetas del servidor principal de su tienda: `/img`, `/themes` y `/modules`.\
   Recordatorio: debes hacer que estas carpetas estén siempre sincronizadas: incluso si agregas nuevos productos o cambias tu tema, el servidor CDN debe contener la última versión de todos estos archivos.
3. Una vez que el servidor CDN esté instalado, agregue la dirección web (as given by your CDN host) en el campo "Servidor de medios n.º 1". Si ese host permite más direcciones web, agréguelas.

En caso de que prefiera que sus archivos aún se descarguen visualmente desde su nombre de dominio en lugar de desde un nombre de dominio desconocido, siga este proceso:

1. Cree un subdominio para el nombre de dominio de su tienda, por ejemplo [`http://cdn1.example.com`](http://cdn1.example.com) (the way to do that depend on your host, ask him about it).
2.  Coloque un archivo `.htaccess` en la raíz del subdominio. Ese archivo debe contener una sola línea:

    ```
    Redirect Permanent / http://cdn-adress.com
    ```

    \
    Reemplace [`http://cdn-`](http://cdn-)`adress`.com con el de su servidor CDN. De esta manera, estás creando una redirección automática desde tu subdominio a tu servidor CDN.
3. Una vez que el subdominio esté en su lugar, agréguelo en el primer campo, "Servidor de medios n.º 1". Si ese host permite más direcciones web, cree tantos subdominios como sea posible para el nombre de dominio principal de su tienda.

Incluso si no tiene un servidor CDN, puede utilizar la función del servidor de medios para que el navegador del cliente descargue más archivos a la vez, acelerando así todo el proceso de carga de la página:

1. Configure su servidor web para que tenga subdominios virtuales, como [`images1.example.com`](http://images1.example.com), [`images2.example.com`](http://images2.example.com) y [`images3.example.com`](http://images3.example.com), que apunten a la carpeta principal de PrestaShop.
2. En la página Rendimiento de su back office, configure cada campo "Servidor de medios" en estos subdominios virtuales.

Una vez que esto esté implementado, PrestaShop cargará sus imágenes desde cualquiera de estos subdominios. En efecto, las imágenes provendrán de alguna carpeta (the main one), pero el navegador abrirá varios hilos de conexión más a su servidor web de los que abriría de forma predeterminada, lo que hará que toda la página se cargue más rápido.

## Caching <a href="#performance-caching" id="performance-caching"></a>

La caché de su servidor almacena versiones estáticas de su página web dinámica, para poder servirlas a sus clientes y así reducir la carga del servidor y el tiempo de compilación.

La mayoría de las veces, primero debe consultar con su proveedor de alojamiento web acerca de esta configuración, ya que requiere configuraciones especiales en el servidor.

Esta sección le permite elegir habilitar el almacenamiento en caché y luego elegir el método de almacenamiento en caché:

![](<../../.gitbook/assets/23789856 (4) (4) (2).png>)

* **Memcached**. Un sistema de almacenamiento en caché distribuido. Muy efectivo, sobre todo con múltiples servidores, pero necesita asegurarse de que sus servidores/hosts lo admitan; lo más probable es que, si su configuración de PHP incluye la extensión Memcached PECL, esté listo para comenzar (you can download it here: [http://pecl.php.net/package/memcache](http://pecl.php.net/package/memcache)). Puede agregar servidores Memcached haciendo clic en el enlace "Agregar servidor".
* **APC**. El caché PHP alternativo es gratuito, abierto y sólido, pero solo funciona con un servidor, lo cual es el caso habitual cuando inicias tu negocio en línea. Nuevamente, verifique la disponibilidad de la extensión APC PECL en su servidor: [http://pecl.php.net/package/APC](http://pecl.php.net/package/APC).
* **Xcaché**. Xcache es un nuevo sistema de caché, que es específico del servidor Lighttpd; por lo tanto, no funcionará con el popular servidor Apache. Lea más al respecto en [http://xcache.lighttpd.net/](http://xcache.lighttpd.net/).

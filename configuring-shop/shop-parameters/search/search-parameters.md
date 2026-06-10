# Search parameters

La página "Buscar" le permite configurar las funciones de búsqueda de su tienda.

## Aliases list <a href="#searchparameters-aliaseslist" id="searchparameters-aliaseslist"></a>

Cuando los clientes realizan una solicitud utilizando el motor de búsqueda interno de su tienda, pueden cometer errores de ortografía. Si PrestaShop no muestra los resultados correctos, la función "alias" puede solucionarlos. Podrá tomar palabras que contengan errores ortográficos y señalarles los productos reales buscados por los clientes.

![](<../../../.gitbook/assets/45580489 (4) (4) (4).png>)

Para crear un nuevo alias útil, primero debe encontrar los errores ortográficos que escriben con mayor frecuencia sus usuarios:

1. Vaya a la pestaña "Búsqueda de tienda" de la página "Estadísticas", en el menú "Estadísticas". Podrás ver las palabras escritas por tus clientes así como los errores más frecuentes.
2. Tome los más frecuentes y agréguelos a su lista de alias para indicar a los usuarios los productos correctos.
3. Haga clic en el botón "Agregar nuevo alias" en la página de parámetros de "Buscar".

El formulario de creación es muy sencillo: indica el error tipográfico que deseas corregir y la palabra correcta a la que debe conducir.

![](<../../../.gitbook/assets/45580490 (4) (2) (3).png>)

Por ejemplo, digamos que sus visitantes escriben con frecuencia "jugador" como "jugador" y "jugador". Puedes crear un alias para cada uno de estos errores tipográficos, que coincidirá con la palabra "Jugador". Sus alias se pueden utilizar tan pronto como se guarden.

También lo invitamos a consultar las secciones de esta guía sobre metaetiquetas de productos y categorías, para comprender mejor cómo mostrar productos en función de las palabras escritas por sus clientes.&#x20;

## Indexing <a href="#searchparameters-indexing" id="searchparameters-indexing"></a>

Esta sección proporciona información sobre la cantidad de productos que se pueden buscar a través de la función de búsqueda de su tienda y la compara con la cantidad de productos presentes en su catálogo. \
Si los valores no coinciden, debe hacer clic en el enlace "Agregar productos faltantes al índice". Sólo se indexarán los nuevos productos.\
Si ha realizado varios cambios en productos ya indexados, es posible que prefiera reconstruir todo el índice. El proceso "Reconstruir el índice completo" lleva más tiempo, pero es más completo.

![](<../../../.gitbook/assets/45580491 (4) (3) (1).png>)

PrestaShop también le proporciona la URL que le permitirá crear una tarea cron para la reconstrucción periódica del índice. Si no conoce cron y crontab, pregúntele a su proveedor de alojamiento web.

Finalmente, la opción "Indexación" le permite indexar un producto tan pronto como se crea/modifica, lo que hace que los enlaces anteriores y el enlace cron sean inútiles.

## Search options <a href="#searchparameters-searchoptions" id="searchparameters-searchoptions"></a>

Esta sección te permite configurar el comportamiento de la función de búsqueda de tu tienda:

![](<../../../.gitbook/assets/image (20) (1).png>)

* **Buscar dentro de una palabra:** Esta opción mejora la búsqueda al permitir al cliente realizar consultas que no solo coinciden con el inicio de la palabra de búsqueda; por ejemplo, "lou" para "blusa".
* **Buscar coincidencia exacta del final:** Con esta opción, la búsqueda puede dar resultados que coincidirán exactamente con el final de la palabra buscada. Por ejemplo, si un cliente busca "libro", verá "cuaderno", pero no "librería".
* **Búsqueda difusa:** Esta función mejora la funcionalidad de búsqueda de PrestaShop al tener en cuenta errores ortográficos o entradas de errores. Por ejemplo, si un cliente ingresa "colibrí" en la barra de búsqueda, el controlador de búsqueda encontrará la palabra más cercana, es decir, "colibrí", y mostrará los productos relevantes.
* **Palabras máximas aproximadas permitidas por la búsqueda difusa:** Puede determinar cuántas palabras puede manejar una consulta en una búsqueda difusa. De forma predeterminada, el valor está establecido en 4. Esto significa que en una búsqueda como “multienchufe del cargador de pared Samsung Galaxy”, solo se tendrán en cuenta las palabras “Samsung”, “Galaxy, “pared” y “cargador”. No se calculará 'Multiplug'.&#x20;

{% hint style="info" %}
Tenga en cuenta que PrestaShop establece esa limitación para evitar comportamientos ofensivos que podrían sobrecargar intencionalmente al servidor. Puedes modificar este número, pero la mayoría de las tiendas no tendrán que hacerlo.
{% endhint %}

* **Longitud máxima de palabra (in characters):** Esta opción define cuántos caracteres permite ejecutar una consulta de búsqueda aproximada. Recomendamos establecer la longitud máxima de palabras en 15 para mantener rápida la búsqueda difusa, incluso al procesar consultas largas. Esto no impedirá que sus clientes ingresen palabras más largas en la barra de búsqueda, pero solo se tendrán en cuenta para la búsqueda los primeros 15 caracteres de cada palabra ingresada. Por ejemplo, en "thisisaverylongword (19 char.) solo se tendrá en cuenta "thisisaverylongw" (15 char.). A la hora de modificar la longitud máxima de la palabra, ten en cuenta que cuanto más larga sea la palabra (in characters), más estresado estará el servidor. Así, cuanto más grande sea tu base de datos, más recursos consumirá una búsqueda y más larga será.&#x20;
* **Longitud mínima de palabra**. Puede elegir el tamaño mínimo en el que una palabra puede registrarse en el índice de búsqueda y ser encontrada por sus clientes. Esta característica permite eliminar palabras cortas en la búsqueda, como preposiciones o artículos (the, and, of, etc.).
* **Palabras en la lista negra**. Puede elegir los términos que sus visitantes no deben encontrar. Introdúcelos directamente en el campo, separados por "|" ("pipe" character, not lowercase L). Por defecto, PrestaShop llena la lista con palabras cortas comunes.

{% hint style="success" %}
La búsqueda difusa es una de las nuevas funciones de PrestaShop 1.7.7. ¡También es el resultado de la contribución de un miembro de la comunidad! 😍 Consulte el [artículo en el blog para desarrolladores de PrestaShop](https://build.prestashop.com/news/introduction-to-the-fuzzy-search/) para obtener más detalles sobre esta función.
{% endhint %}

## Weight <a href="#searchparameters-weight" id="searchparameters-weight"></a>

PrestaShop te permite priorizar ciertos datos cuando se realiza una búsqueda en tu tienda.

![](<../../../.gitbook/assets/51839994 (4) (4).png>)

Como se indica en la sección, el "peso" de búsqueda de un producto representa su importancia y relevancia para el ranking de los productos cuando los clientes intentan una nueva búsqueda. Un artículo con un peso de 8 tendrá 4 veces más valor que un artículo con un peso de 2.

Por ejemplo, de forma predeterminada, el "Peso del nombre del producto" está en 6, el "Peso de las etiquetas" está en 4 y tanto el "Peso de la descripción breve" como el "Peso de la descripción" están en 1. Esto significa que un producto con "ipod" en su nombre aparecerá más alto en los resultados de búsqueda que otro producto que tenga "ipod" solo en sus etiquetas. Mientras tanto, un producto que sólo tenga "ipod" en cualquiera de sus descripciones tendrá la clasificación más baja en los resultados de búsqueda.

Tiene muchos factores a los que puede asignar un peso: descripción breve, categoría, etiquetas, atributos, etc. Descubrirá que el orden de visualización de los resultados se puede invertir porque cambió el peso de los distintos campos. El ajuste de estas configuraciones será más visible en un catálogo grande con muchas referencias.

Una vez que se guardan los cambios, entran en vigor inmediatamente

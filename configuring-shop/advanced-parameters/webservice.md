# Webservice

En esta página puedes habilitar el servicio web de tu tienda, para que herramientas de terceros puedan acceder a tus datos. Potencialmente, esto hace posible que herramientas interesantes le ayuden a usted o a sus clientes a hacer un mejor uso de su tienda (such as mobile applications).

Un servicio web es un método de comunicación entre dos dispositivos electrónicos a través de una red. Se basa en un conjunto conocido de métodos, formatos y derechos de acceso, para poder utilizar el contenido del servicio web en cualquier otra herramienta autorizada y desarrollar el contenido original. Lea más sobre esto en Wikipedia: [http://en.wikipedia.org/wiki/Web\_service](http://en.wikipedia.org/wiki/Web\_service).

La página comienza enumerando las claves de servicio web actualmente existentes en una tabla, si las hay. Una clave de servicio web es un acceso único que le otorga a un desarrollador, que puede usarse para vincular una herramienta a su tienda. Compártelos con moderación, ya que es posible que no siempre quieras que todos accedan a tus datos.

<figure><img src="../../.gitbook/assets/image (1) (3).png" alt=""><figcaption></figcaption></figure>

No cualquier aplicación puede acceder a tu tienda a través del servicio web PrestaShop: tú decides cuáles pueden hacerlo y qué pueden hacer. Cada aplicación tiene una clave de conexión única, con derechos de acceso específicos.

## Adding a new key <a href="#webservice-addinganewkey" id="webservice-addinganewkey"></a>

El botón **"Agregar nueva clave de servicio web"** lo lleva al formulario de creación de clave de servicio web:

* **Llave**. Una clave única. Puede crear el suyo propio o elegir utilizar uno generado, por ejemplo haciendo clic en "¡Generar!". o utilizando cualquier generador de claves en línea. Las claves generadas suelen ser más seguras porque son más difíciles de adivinar.
* **Descripción clave**. Un recordatorio de para quién es esa clave y a qué da acceso.
* **Estado**. Puede desactivar una clave en cualquier momento. Esto le permite otorgar acceso solo temporalmente a sus datos desde una clave determinada.
* **Permisos**. No tienes que compartir TODOS tus datos con cada clave. Podrás elegir entre una amplia gama de permisos, ya sea por sección o por tipo de acceso. Es posible que desee que algunas aplicaciones solo puedan ver un puñado de elementos, mientras que otras deberían poder editar y eliminar casi todo. Elige sabiamente.

Haga clic en **"Guardar"** cuando su clave esté lista.

<figure><img src="../../.gitbook/assets/image (2) (1).png" alt=""><figcaption></figcaption></figure>

## Configuration <a href="#webservice-configuration" id="webservice-configuration"></a>

Por razones de seguridad, asegúrese de que el servidor de su tienda admita una conexión SSL segura.

La configuración del servicio web es bastante sencilla:

* **Habilitar el servicio web de PrestaShop**. Si no desea que nadie acceda a su tienda a través de herramientas y aplicaciones de terceros, simplemente manténgalo desactivado.
* **Habilite el modo CGI para PHP**. El modo CGI es una configuración especial para el servidor Apache, donde le indica que use PHP como un script CGI en lugar de un módulo Apache. Si bien el modo CGI tiene la reputación de ser más seguro, se descubrió que tiene una falla de seguridad en mayo de 2012. Pídale consejo a su proveedor de alojamiento web.

<figure><img src="../../.gitbook/assets/image (1) (2).png" alt=""><figcaption></figcaption></figure>

## Enable PrestaShop webservice <a href="#webservice-configuration" id="webservice-configuration"></a>

Al habilitar el servicio web de PrestaShop, el **estado y la URL del servicio web de su tienda** se muestran en la **parte superior de la página** en _Parámetros avanzados > Servicio web > Estado del servicio web._ Esta característica ayuda a solucionar problemas comunes.

<figure><img src="../../.gitbook/assets/image (4) (2).png" alt=""><figcaption></figcaption></figure>

## Perform partial updates <a href="#webservice-configuration" id="webservice-configuration"></a>

Puede **realizar actualizaciones parciales** en los puntos finales del servicio web utilizando el [método PATCH](https://en.wikipedia.org/wiki/PATCH\_\(HTTP\)). Esto significa que las integraciones pueden actualizar parte de un recurso, en lugar de todos los campos a la vez.

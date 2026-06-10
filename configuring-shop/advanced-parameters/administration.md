# Administration

La página "Administración" contiene opciones y configuraciones generales sobre el funcionamiento de PrestaShop. Tiene tres secciones.

## General <a href="#administration-general" id="administration-general"></a>

Esta sección es para las configuraciones más generales:

![](<../../.gitbook/assets/43089940 (4) (4) (2).png>)

* **Compruebe automáticamente si hay actualizaciones del módulo**. Puede pedirle a PrestaShop que compruebe periódicamente si hay nuevas versiones de sus módulos disponibles en el sitio web de Complementos. Si es así, la página "Módulos" mostrará un botón "Actualizar" para los módulos instalados, justo al lado del botón "Desinstalar".
* **Compruebe la dirección IP de la cookie**. Esta es una medida de seguridad añadida: puedes indicarle a PrestaShop que compruebe que el usuario procede de la IP almacenada en la cookie de su navegador.
* **Vida útil de la cookie de recepción**. Por defecto, la longevidad de una cookie de PrestaShop es de 480 horas (20 days). Puede reducirlo si cree que su seguridad lo necesita.
* **Vida útil de la cookie del back office**. Por defecto, la longevidad de una cookie de PrestaShop es de 480 horas (20 days). Puede reducirlo si cree que su seguridad lo necesita.

## Upload quota <a href="#administration-uploadquota" id="administration-uploadquota"></a>

Esta sección le ayuda a definir el tamaño autorizado de los archivos cargados por su propio equipo, no por sus clientes.

![](<../../.gitbook/assets/43089941 (4) (4) (1).png>)

Hay tres opciones, una general y las otras dos más específicas:

* **Tamaño máximo para el archivo adjunto**. El valor predeterminado se toma directamente de la configuración de su servidor, pero puede reducirlo si es necesario.
* **Tamaño máximo para un producto descargable**. Si vende productos virtuales (services, booking and downloadable products), esta configuración puede limitar el tamaño de los archivos que su equipo puede cargar y, por lo tanto, el tamaño del producto final. Planifica con antelación para no dejar nunca bloqueado a ningún miembro de tu equipo.
* **Tamaño máximo para la imagen de un producto**. Asimismo, puedes limitar el tamaño de las imágenes que tú o tu equipo pueden subir a tu tienda. Esto puede servir como un útil recordatorio de que los miembros del equipo deben esforzarse por reducir el tamaño de una imagen, ya que a menudo no es útil cargar nada más que 600x600 (which is roughly 200 kB when correctly compressed). Consulte la página "Imágenes" en el menú "Diseño" para conocer los tamaños de imagen que su tienda está configurada para usar. Esto tiene el beneficio adicional de ahorrar espacio en el servidor y uso de ancho de banda, así como potencia del procesador (since PrestaShop resizes uploaded image to give you thumbnails and more).

## Notifications <a href="#administration-notifications" id="administration-notifications"></a>

Las notificaciones se muestran en la parte superior de cualquier página de administración cuando la has cargado, justo al lado del nombre de la tienda. Muestran la cantidad de elementos nuevos desde la última vez que hizo clic en ellos.

Al hacer clic en el icono de la campana, se abrirá una pequeña tabla con los distintos tipos de notificaciones.

![](<../../.gitbook/assets/43089943 (4) (4) (4).png>)

Puedes optar por no recibirlos para algunos tipos de contenido:

* **Mostrar notificaciones de nuevos pedidos**. Muestra los números, cantidades y nombres de clientes del último pedido realizado en su tienda. A partir de ahí, puede abrir la página única de cualquier pedido o abrir la página "Pedidos" para obtener la lista completa.
* **Mostrar notificaciones para nuevos clientes**. Muestra el nombre de los clientes que se registraron desde la última vez. A partir de ahí, puede abrir la página única de cualquier cliente o abrir la página "Clientes" para obtener la lista completa.
* **Mostrar notificaciones de mensajes nuevos**. Muestra el correo electrónico de las personas que le enviaron un mensaje por última vez utilizando el formulario de contacto de su tienda. A partir de ahí, puede abrir cualquier mensaje o abrir la página "Servicio al cliente" para obtener la lista completa.

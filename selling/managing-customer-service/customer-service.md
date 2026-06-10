# Servicio al cliente

PrestaShop le permite centralizar todas las solicitudes de los clientes dentro de sus límites. Esto le ayuda a realizar un seguimiento de qué hilos de discusión necesitan respuesta, en lugar de tener que consultar con todos los destinatarios del correo para ver si alguien respondió.

En la práctica, el formulario de contacto de su tienda, disponible en el enlace "Contáctenos" en el pie de página, presenta al cliente dos contactos por defecto: "Servicio al Cliente" y "Webmaster". El cliente sólo tiene que elegir con quién contactar, y luego rellenar el resto de campos. Posteriormente, el mensaje se graba en la herramienta de atención al cliente de PrestaShop.

![](<../../.gitbook/assets/51839870 (3) (3) (1).png>)

Los hilos de discusión solo se incluyen en la herramienta de servicio al cliente si el contacto tiene la opción "¿Guardar mensajes?" opción habilitada. Puede cambiar esta configuración o agregar más contactos yendo a la página "Contacto", en el menú "Parámetros de la tienda". Encontrarás la opción al editar los contactos existentes.

Si la opción está deshabilitada para el contacto que elige el cliente, el mensaje simplemente se envía a la dirección de correo electrónico del contacto y no se almacena en PrestaShop.

También debe configurar correctamente sus ajustes IMAP, para que PrestaShop pueda recuperar las respuestas del cliente a los correos electrónicos enviados desde la herramienta de servicio al cliente. Esto se hace en la sección "Opciones de atención al cliente", en la parte inferior de la pantalla.

En esta página, cada contacto tiene su propia casilla, donde puedes ver rápidamente si hay mensajes nuevos (es decir, aquellos que aún no han sido leídos). De forma predeterminada, hay dos cuadros, y agregar más contactos moverá los cuadros "Significado del estado" y "Estadísticas" más hacia la izquierda y hacia abajo.

Estos dos últimos cuadros son útiles cuando necesitas manejar mensajes nuevos diariamente:

* **Significado del estado**. Un simple recordatorio de los códigos de colores que su equipo puede aplicar a un hilo de discusión.
* **Estadística**. Una visión general de la actividad global de su servicio de atención al cliente desde el principio.

Más abajo se muestra la lista de mensajes recibidos, tanto antiguos como nuevos.

Puedes editar un par de opciones en la parte inferior de la página, que se aplican a todos los contactos:

* **Permitir la carga de archivos**. Si el cliente puede adjuntar un archivo al mensaje. Esto puede resultar útil en caso de problemas visuales en la página principal, ya que el cliente puede enviarle capturas de pantalla.
* **Mensaje predeterminado**. La plantilla predeterminada para la respuesta de sus empleados. Mantenlo simple, para que pueda adaptarse a muchas situaciones, incluso si necesita un poco de edición para cada caso.\
  \


También puede contactar a sus clientes a través de la página de cada pedido, donde puede enviar mensajes predefinidos. Estos mensajes se gestionan en la página "Mensajes de pedido", también en el menú "Atención al cliente".

Finalmente, la parte inferior de la página presenta la sección "Opciones de servicio al cliente", donde puede configurar muchas opciones relacionadas con su servidor de correo (IMAP).

## Manejo de mensajes de servicio al cliente <a href="#customerservice-handlingcustomerservicemessages" id="customerservice-handlingcustomerservicemessages"></a>

Cada conversación con un cliente se puede gestionar íntegramente a través de la completa interfaz de PrestaShop, sin tener que utilizar un cliente de correo electrónico como Outlook o Thunderbird.

![](<../../.gitbook/assets/51839871 (3) (3) (1).png>)

En la lista de conversaciones, haga clic en una fila para ver los detalles de la conversación:

* Puede aplicar un puñado de acciones a una discusión para ordenarlas rápidamente y así manejarlas más rápidamente. Hay 4 acciones disponibles:\

  * **Marcar como "controlado"** o **"Reabrir"**. Cambia el estado de la discusión a "Cerrado" o "Abierto".
  * **Marcar como "pendiente 1"** y **Marcar como "pendiente 2"**. Estos dos estados son internos: su significado depende de tu equipo. Incluso puede optar por no utilizarlos y confiar únicamente en "Cerrado" y "Abierto".
  * **Reenvíe esta discusión a otro empleado**. Desde el momento en que un empleado comienza a responder el mensaje de un cliente, se hace cargo de la solicitud del cliente. Si durante la discusión resulta que otro empleado debe encargarse, puedes usar ese botón para atribuirlo a otro empleado a través de una lista desplegable. Ese otro empleado recibirá una notificación al respecto. Si la persona a la que desea reenviar esta discusión no está disponible en la lista, elija "Alguien más" en la lista desplegable y aparecerán dos opciones que le permitirán indicar la dirección de correo electrónico del destinatario y un comentario sobre su mensaje.
* **Responder al siguiente mensaje sin respuesta en este hilo**. Te lleva al siguiente mensaje sin respuesta del hilo para que puedas responderlo directamente.

Los detalles esenciales están disponibles:

* Nombre del cliente y correo electrónico, en el que podrá hacer clic para acceder a la información del cliente (cuando sea un cliente registrado).
* Número de pedidos, importe total gastado y fecha de registro del cliente (cuando es un cliente registrado).
* Hora y fecha del mensaje.
* Finalmente, el mensaje en sí.

Para responder a este hilo, simplemente use el formulario con su mensaje predeterminado (como se establece en la sección "Opciones de contacto" de la página "Servicio al cliente") y haga clic en "Enviar".

En la parte inferior de la página, la "Cronología de pedidos y mensajes" le brinda una vista cronológica clara de los eventos relacionados con este hilo de discusión. Cuando esté vinculado a un pedido, también tendrás los detalles del pedido.

![](<../../.gitbook/assets/23789570 (3) (3) (3).png>)

## Opciones de servicio al cliente <a href="#customerservice-customerserviceoptions" id="customerservice-customerserviceoptions"></a>

Básicamente, esta sección le permite configurar con precisión el acceso de PrestaShop a su servidor de correo electrónico a través de su interfaz IMAP. Debe asegurarse de que todos los campos estén completos para que la herramienta de servicio al cliente funcione correctamente. La mayor parte de esta información debe ser proporcionada por su proveedor de alojamiento web.

![](<../../.gitbook/assets/51839872 (3) (3) (1).png>)

* **URL IMAP**, **puerto IMAP**, **usuario IMAP** y **contraseña IMAP**. Detalles imprescindibles para acceder al servidor de correo electrónico mediante el protocolo IMAP.
* **Eliminar mensajes**. Si está habilitado, los mensajes en el servidor se eliminarán tan pronto como PrestaShop los recupere. Úselo con precaución: esto haría que sus mensajes no estuvieran disponibles para otros clientes de correo electrónico.
* **Crear nuevos hilos**. Esto creará nuevos hilos para correos electrónicos no reconocidos.
* **/pop3**. Si está habilitado, use POP3 en lugar de IMAP.
* **/norte**. Si está habilitado, la conexión a su servidor de correo electrónico no se autenticará previamente. No recomendado.
* **/ssl**. Si está habilitado, la conexión a su servidor de correo electrónico no estará cifrada. No recomendado.
* **/validar-certificado**. Si está habilitado, PrestaShop forzará la validación del certificado TLS/SSL del servidor.
* **/novalidate-cert**. Si está habilitado, PrestaShop nunca intentará validar el certificado TLS/SSL del servidor. Esencial para servidores con certificados autofirmados.
* **/tls**. Si está habilitado, PrestaShop forzará el uso de StartTLS para cifrar la conexión. Se rechazarán los servidores que no admitan StartTLS.
* **/notls**. Si está habilitado, PrestaShop no utilizará StartTLS para cifrar la sesión, incluso con servidores que lo admitan.

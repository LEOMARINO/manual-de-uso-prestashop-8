# Email

Su tienda envía muchos mensajes a lo largo de todos los pasos de registro y realización de un pedido. Aquí puede configurar cómo se enviarán estos mensajes y ver los mensajes enviados.

## Email <a href="#email-e-mail" id="email-e-mail"></a>

La primera sección de la página le presenta una lista de todos los correos electrónicos que se enviaron desde su tienda: el destinatario, la plantilla utilizada, el idioma del mensaje, el asunto del correo electrónico y la hora de envío.

![](<../../.gitbook/assets/38469764 (4) (4) (1).png>)

## Email <a href="#email-email" id="email-email"></a>

Aquí es donde usted decide cómo se envían y reciben sus correos electrónicos.

El formulario tiene tres conjuntos de opciones:

![](<../../.gitbook/assets/38469765 (4) (4).png>)

* **Enviar correo electrónico a**. Esta es una configuración de interfaz de usuario. Al final del proceso de pago, un cliente puede dejar un mensaje a su personal. Puede elegir a quién se enviará este mensaje seleccionándolo en la lista desplegable. Para agregar más direcciones, debes ir a Parámetros de la tienda > Contactos.
* Parámetros de correo electrónico: cómo se envían técnicamente los correos electrónicos. Elige entre los tres. Consulte a continuación para obtener más información.
* Formato de correo electrónico: cómo se envían visualmente los correos electrónicos. Elige entre los tres. Consulte a continuación para obtener más información.
* **Registrar correos electrónicos**. Desactívelo si ya no desea realizar un seguimiento de los correos electrónicos enviados por su tienda, como se muestra en la sección Correo electrónico anterior.

### Technical configuration <a href="#email-technicalconfiguration" id="email-technicalconfiguration"></a>

Configura PrestaShop para enviar correos electrónicos a tus clientes. Le recomendamos encarecidamente que consulte con su proveedor de alojamiento web para determinar qué configuración utilizar para esta función. Las opciones son:

* **Nunca envíes correos electrónicos**. Mantenga esta configuración para fines de prueba. Una vez que tu tienda sea pública, nunca debes usar esta configuración.
* **Utilice la función mail() de PHP**. Esta opción se recomienda de forma predeterminada. En caso de que esto no funcione, utilice la opción SMPT a continuación.
* **Establecer mis propios parámetros SMTP**. En este caso aparece una nueva sección, con más campos. La información para estos campos debe ser proporcionada por su proveedor de alojamiento web: nombre de dominio de correo, servidor SMTP, usuario SMTP, etc. Asegúrese de transcribir exactamente lo que le proporciona su proveedor de alojamiento web.

La información de configuración SMTP se la puede proporcionar:

* Su administrador de sistema,
* Tu anfitrión,
* Su ISP,
* Su proveedor de correo electrónico.

![](<../../.gitbook/assets/23789857 (4) (4) (2).png>)

Su proveedor de alojamiento web puede indicarle si su nombre de usuario es obligatorio o no, así como la información de la contraseña y el cifrado que debe utilizar.

Por ejemplo, en el caso de Gmail (the email service offered by Google), es posible que tengas que ingresar información como la siguiente:

* SMTP server: [smtp.gmail.com](http://smtp.gmail.com)
* User: [my.user.name@gmail.com](mailto:my.user.name@gmail.com) (example)
* Password: RT22UE87 (example)
* Encryption: SSL
* Port: 465

### Visual configuration <a href="#email-visualconfiguration" id="email-visualconfiguration"></a>

There are two formats available for e-mails: HTML is great to look at, but might not work everywhere; text is dull to look at, but works everywhere.

Puede optar por utilizar sólo uno de los dos o ambos. Ambas son las formas recomendadas.

### Using DKIM signatures for emails

[DKIM]Las firmas (https://en.wikipedia.org/wiki/DomainKeys\_Identified\_Mail) son firmas digitales invisibles insertadas en el encabezado de un correo electrónico. El receptor puede verificar esta firma, lo que le permite evitar la suplantación de correo electrónico, un tipo de ataque de phishing. Esto hará que sea menos probable que los correos electrónicos de su tienda se marquen como spam.

DKIM signing can be enabled in Advanced Parameters > Emails.

<figure><img src="../../.gitbook/assets/image (63).png" alt=""><figcaption></figcaption></figure>

Al habilitar la firma DKIM **se abrirá un formulario** y aparecerán los campos de dominio DKIM, selector DKIM y clave privada DKIM. Deberá completar esos campos manualmente para configurar la firma DKIM.&#x20;

Después de completar los campos, **asegúrese de guardar** la información usando el botón Guardar.

<figure><img src="../../.gitbook/assets/image (22).png" alt=""><figcaption></figcaption></figure>

## Pruebe su configuración de correo electrónico <a href="#email-testyouremailconfiguration" id="email-testyouremailconfiguration"></a>

Una vez que haya configurado sus correos electrónicos usando uno de los dos métodos disponibles, ingrese su propia dirección de correo electrónico en esta sección, luego haga clic en el botón "Enviar un correo electrónico de prueba".\
Ahora revisa la bandeja de entrada de la dirección proporcionada para verificar que efectivamente hayas recibido el correo electrónico de prueba, en el formato correcto. Si no lo has recibido, actualiza tu configuración con la información correcta.

![](<../../.gitbook/assets/38469768 (4) (4) (1).png>)

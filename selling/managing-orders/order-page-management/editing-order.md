---
descripción: >-
  Desde la página del pedido, no solo puede acceder a todos los detalles del pedido, sino que
  también editarlos y actualizarlos.
---

# Editar un pedido

## **Actualizando el estado del pedido**

Hay dos lugares en la página del pedido donde puede actualizar su estado:

* En la **esquina superior izquierda** de la página, junto a los botones de acción.
* En la **pestaña Estado**

Seleccione el estado que desee en la lista desplegable y haga clic en el botón "Actualizar estado".&#x20;

![](<../../../.gitbook/assets/image (16) (2).png>)

Puede elegir entre los siguientes estados:

![](https://lh6.googleusercontent.com/6UrdsTFPXoizMX\_PyjnMDRvnZ7yuqcdqRrboLt3v0W2XXalPe3lTD0Iuv4fbb-mVLzK0alGYtWtMQWmo7W5rlDsl03a42CyJjQgieEvfiV1c9ga1MXtFfiQGgkCLPXd-D9d1-tDa)

{% hint style="info" %}
Cualquier módulo que afecte el seguimiento de pedidos podría ampliar esta lista de estados.
{% endhint %}

Para tener una mejor visión de la actividad del pedido, cada cambio de estado se registra en la pestaña “Estado”, así como su autor y la fecha/hora de la actualización.

![](<../../../.gitbook/assets/image (1) (1) (1).png>)

{% hint style="warning" %}
Es muy importante **actualizar un estado sólo cuando se haya confirmado claramente**. Por ejemplo, no marques un pedido como "Entregado" cuando solo hayas enviado el paquete; utiliza "Enviado" en su lugar.&#x20;
{% endhint %}

:incoming\_envelope: Para algunas actualizaciones de estado, se envía un correo electrónico al cliente. Puede reenviar este correo electrónico haciendo clic en el botón junto al estado del pedido, en la pestaña Estado. Si ha editado el pedido en algún momento, el cliente recibirá un correo electrónico actualizado.

## Acceder a los documentos del pedido

Puede obtener muchos documentos PDF desde la página de pedido. Cuando están disponibles, se enumeran en la pestaña Documentos de la sección administrativa.‌

* **Imprimir/Descargar el pedido**&#x20;

Puede imprimir o descargar el pedido como PDF haciendo clic en el botón "**Imprimir pedido**" en la parte superior de la página del pedido.

* **Descargar/Generar una factura**&#x20;

Puede descargar la factura haciendo clic en el botón “**Ver factura**” en la parte superior de la página. También puedes acceder o generar la factura en la pestaña Documentos. ‌

:arrow\_right: En la sección Documentos, puede agregar una nota a la factura que aparecerá justo debajo de la tabla de impuestos en la factura.&#x20;

{% hint style="success" %}
Aquí hay un consejo para los comerciantes expertos en tecnología: puede **personalizar el diseño de la factura**: los archivos de plantilla PDF se encuentran en la carpeta /pdf. Estos archivos .tpl son en realidad archivos HTML con etiquetas Smarty para datos dinámicos. Puede cambiar el diseño de la factura editando el archivo llamado factura.tpl
{% endhint %}

* **Descarga el albarán de entrega**

Si el estado del pedido es "Procesamiento en curso", se genera automáticamente un PDF de albarán de entrega. Puede descargarlo desde la pestaña Documentos o hacer clic en el botón "Ver comprobante de entrega" en la parte superior de la página.&#x20;

## Editar artículos de pedido

### **Añadiendo un producto**

![](https://lh4.googleusercontent.com/pN61QdHvvYXsyffV5na9GBQpZ7Ak6mXf0U7wnr-UJopwjxxYLUAb9mKju2VgCfBbHutyW0AV8zpDC9J-sT-2A5-lBphPcKbmjol3jX49E6pIP5WXmzZx-xT-0vYM0NrzKR7rSk2f)

Al final de la lista de productos:

* Haga clic en el botón "Agregar un producto"
* Introduzca el nombre del producto
* Selecciona el producto que deseas agregar&#x20;
* Establecer la cantidad&#x20;
* Selecciona la factura en la que quieres que aparezca este producto y haz clic en el botón "Añadir"

{% hint style="warning" %}
Si la factura ya ha sido enviada al cliente, no deberás añadirle nuevos productos. En su lugar, debes crear otra factura: al agregar un nuevo producto, elige "crear una nueva factura" en la lista desplegable.&#x20;
{% endhint %}

Tenga en cuenta que no puede agregar más productos de los disponibles en stock. Cuando seleccionas un producto, la cantidad de artículos en stock aparece en la columna "Disponible".

:arrow\_right: Para agregar un producto que ya está presente en el pedido, haga clic en el botón “Editar” y modifique la cantidad.

### **‌Eliminar un producto**

**‌**Para eliminar un producto del pedido, vaya a la lista de productos y elimine el producto haciendo clic en el botón "Eliminar".&#x20;

:arrow\_right: Si solo deseas eliminar una determinada cantidad, haz clic en el botón “Editar” y modifica el campo “Cantidad”.

{% hint style="success" %}
También puedes cancelar o editar la cantidad de **varios productos al mismo tiempo**. \
\
Para hacerlo, haga clic en el botón “Cancelar productos”, en la parte superior de la página y seleccione los productos o la cantidad que desea eliminar. Este botón solo está disponible si las devoluciones de mercancía están habilitadas en el menú de Atención al Cliente y si el pedido aún no está pagado.
{% endhint %}

## **Editando detalles del pedido**&#x20;

### **Editando detalles de envío**

En la sección administrativa, haga clic en la pestaña Transportistas. Luego, haga clic en el botón “Editar” para modificar el número de seguimiento y el transportista.&#x20;

:arrow\_right: Tenga en cuenta que el transportista solo se puede modificar si el pedido aún no se ha enviado.&#x20;

### **Edición de la dirección de envío o la dirección de facturación**

La **dirección de envío** es la dirección a la que se enviará el paquete, mientras que la **dirección de facturación** es la dirección del comprador. Pueden ser diferentes (en el caso de que un cliente pida un regalo para un amigo, por ejemplo).&#x20;

Si un cliente le pide que modifique una de estas direcciones, vaya a la sección Cliente y haga clic en el menú de hamburguesas al lado de la etiqueta “Dirección de envío” o “Dirección de factura”.&#x20;

Puede editar la dirección existente o seleccionar otra dirección de la lista de direcciones proporcionada por el cliente.

![](<../../../.gitbook/assets/image (10) (1).png>)

Si la dirección que quieres vincular al pedido no está ya registrada en PrestaShop, primero deberás crearla. Para hacer esto:

* En la sección Cliente de la página de pedido, acceda a la ficha personal del cliente, haciendo clic en “Ver todos los detalles”
* En la parte inferior de la página, haga clic en “+” en la sección Direcciones.
* Rellena el formulario y guarda
* Regrese a la página de detalles del pedido y seleccione la dirección en la lista desplegable.

![Sección Direcciones de la página del Cliente](<../../../.gitbook/assets/image (13) (1).png>)

## **Gestión de pagos y descuentos**

### **Registrar un nuevo pago**

Para registrar un nuevo pago, vaya a la sección Pagos de la página del pedido.

* Seleccione la fecha del pago y el método de pago utilizado
* Ingrese el ID de la transacción
* Ingrese el monto y seleccione la moneda&#x20;
* Selecciona la factura en la que quieres que aparezca este pago
* Haga clic en el botón "Agregar" para guardar&#x20;

![](<../../../.gitbook/assets/image (19) (1) (1).png>)

### **Agregando un descuento**

‌En la sección Productos, en la parte inferior de la lista de productos del pedido, haga clic en el botón "Agregar un nuevo descuento" y complete el formulario:

![](https://lh4.googleusercontent.com/1WozYkYNQW2M0NuruC-5SGI5zbVsYheWGOC8elIvG6X6V1Qmw2G2iP25y1rZsLqeJgfMPzWQ8sqUti1B6WNYOSwLSXU473WpLn4YAKWiCdnBpl5uiM\_0SFEY1\_6lfXRXNDZ6jhWy)

* **Nombre:** Asigne un nombre corto al descuento. Esto será visible para el cliente.
* **Tipo:** Elija el tipo de descuento: "porcentaje", "monto" o "envío gratis".
* **Valor:** Para los tipos "porcentaje" o "monto", establezca el valor del descuento.&#x20;
* **Factura:** Selecciona la factura en la que quieres que se aplique este descuento. Cuando haya más de una factura, podrás marcar la casilla para aplicar el descuento a todas las facturas.

{% hint style="warning" %}
El descuento no se aplica a los gastos de envío a menos que marques envío gratuito.
{% endhint %}

## **‌Gestión de mensajes de pedidos y notas privadas de clientes**

### **Añadiendo una nota privada** :lock\_with\_ink\_pen:&#x20;

En la sección Cliente, puede agregar una nota privada sobre un cliente que solo será visible para usted y su equipo. Puede resultar muy útil informar a sus compañeros sobre información importante sobre el cliente: ¿es un cliente habitual? ¿Se debe prestar especial atención debido a un incidente anterior?&#x20;

### **Adjuntando un mensaje al pedido** :e-mail:&#x20;

Es posible que deba enviar un mensaje al cliente para mantenerlo informado sobre el progreso de su pedido o informarle sobre un evento imprevisto. **¡La comunicación es clave para una buena experiencia del cliente!** Y la buena noticia es que puedes hacerlo muy fácilmente desde la página de pedidos:

Escribe tu mensaje en el campo de mensaje y envíalo.&#x20;

* [x] Si desea que su cliente lo reciba, no olvide marcar la casilla "¿Mostrar al cliente?" caja. \

* [ ] Es posible que desees mantener este mensaje disponible **solo para ti y tu equipo**. Eso también es posible: simplemente deje el mensaje "¿Mostrar al cliente?" casilla sin marcar.&#x20;

#### **Enviar mensajes predefinidos**

Puede seleccionar un mensaje de pedido predefinido de la lista desplegable.&#x20;

Luego puede agregar más detalles al mensaje escrito previamente si es necesario.

Si desea escribir mensajes predefinidos personalizados, haga clic en el botón "Configurar mensajes predefinidos". Serás redirigido a la página Mensajes de pedidos, en el menú Servicio al cliente.

Para saber más:

{% content-ref url="../../managing-customer-service/order-messages.md" %}
[mensajes-de-pedido.md](../../managing-customer-service/order-messages.md)
{% endcontent-ref %}

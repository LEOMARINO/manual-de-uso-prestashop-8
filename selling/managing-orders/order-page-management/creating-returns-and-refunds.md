---
descripción: >-
  En esta página, aprenderá cómo crear devoluciones y reembolsos directamente desde
  la página de pedido.
---

# Crear devoluciones y reembolsos

## **Procediendo a un reembolso estándar**

:arrow\_right: Es posible proceder a reembolsos cuando el pedido esté pagado, o cuando al menos un pago esté vinculado al pedido.&#x20;

:arrow\_right:Solo se puede acceder a los reembolsos estándar cuando las devoluciones de mercancías están habilitadas en la página Servicio al cliente > Devoluciones de mercancías.&#x20;

:arrow\_right:Una vez enviado el pedido, ya no podrá realizar un reembolso estándar.

**Sigue los pasos:**

* Haga clic en el botón "Reembolso estándar"

_Aparece una nueva columna en la tabla Productos, titulada “Reembolso estándar”._

* Establece el importe y la cantidad de cada uno de los productos que quieres reembolsar
* Elija una de las opciones de reembolso\
  Consulte "[Elegir una opción de reembolso](creating-returns-and-refunds.md#choosing-a-refund-option)" a continuación para obtener más detalles.
* Haga clic en el botón “Reembolso estándar” para validar

## **Procediendo a un reembolso parcial**&#x20;

Debes proceder a un reembolso parcial si solo deseas reembolsar parte del pedido, ya sea porque el cliente devolvió uno de los productos pedidos, o simplemente como muestra de buena voluntad por un producto dañado que el cliente decidió conservar de todos modos.

:arrow\_right:Los reembolsos parciales solo están disponibles cuando se paga el pedido o cuando al menos un pago está vinculado al pedido.&#x20;

:arrow\_right:También es posible un reembolso parcial después de que el pedido haya salido del almacén.&#x20;

**Sigue los pasos:**

* Haga clic en el botón “Reembolso parcial”

_Aparece una nueva columna en la tabla Productos, titulada “Reembolso parcial”._

* Establece el importe y la cantidad de cada uno de los productos que quieres reembolsar
* Elija una de las opciones de reembolso\
  Consulte "[Elegir una opción de reembolso](creating-returns-and-refunds.md#choosing-a-refund-option)" a continuación para obtener más detalles.
* Haga clic en el botón "Reembolso parcial" para validar&#x20;

## **Registrar una devolución de producto**

:arrow\_right: Registrar una devolución de producto es posible solo una vez que se envía el pedido y si lo solicita el cliente.&#x20;

:arrow\_right:Las devoluciones de mercancías también deben habilitarse en la página Servicio al cliente > Devoluciones de mercancías.

Las solicitudes de devolución de mercancía del cliente están disponibles en la pestaña Devoluciones de mercancía.&#x20;

![Pestaña Devoluciones de Mercancía en la sección administrativa (Order page)](<../../../.gitbook/assets/image (24).png>)

**Sigue los pasos:**

Asegúrese de haber recibido los productos devueltos. Si todo está bien, puedes marcarlo como "devuelto" directamente desde la página del pedido:

* Haga clic en el botón “Devolver productos”

_Aparece una nueva columna en la tabla Productos, titulada “Productos devueltos”._

* Seleccione los productos y la cantidad devuelta
* Elija una de las opciones de reembolso\
  Consulte "[Elegir una opción de reembolso](creating-returns-and-refunds.md#choosing-a-refund-option)" a continuación para obtener más detalles.
* Haga clic en el botón "Devolver productos" para validar&#x20;

## **‌Elegir una opción de reembolso**

Cuando configura un producto como devuelto o para reembolso, hay cuatro opciones disponibles, según el estado del pedido:&#x20;

### **Reponer productos**&#x20;

Al registrar una devolución de producto, puede optar por reponer existencias de los productos en cuestión.

Si seleccionas esta opción, PrestaShop considerará que el producto devuelto está nuevamente disponible para la venta, por lo que aumentará el stock de este producto.&#x20;

{% hint style="warning" %}
Debes asegurarte de no marcar la casilla “Reabastecer productos” si el producto devuelto tiene un defecto de fabricación o está roto.
{% endhint %}

### **Generar un comprobante de crédito**&#x20;

Al proceder a un reembolso, puede optar por generar un comprobante de crédito.&#x20;

:arrow\_right: Un comprobante de crédito es un reconocimiento por parte de la tienda de que se ha emitido el reembolso de la mercancía. Esto se utilizará para fines contables.

Dependiendo de su política de reembolso, puede devolverle el dinero al cliente o generar un cupón para su próxima compra.

### **Generar un vale**

Al proceder a un reembolso, puede optar por generar un vale.

:arrow\_right:Un cupón toma la forma de un código de descuento que el cliente puede ingresar durante el proceso de pago. \
\
En PrestaShop, los vales forman parte de un tipo especial de función de descuento: "reglas del carrito". Se pueden crear y editar desde la página Descuentos > Reglas del carrito. También puede editar los vales existentes de los clientes directamente desde la página Cliente, en la sección Vales.\
\
Para saber más:

{% content-ref url="../../managing-catalog/managing-discounts/cart-rules.md" %}
[carro-rules.md](../../managing-catalog/managing-discounts/cart-rules.md)
{% endcontent-ref %}

### **Pagar los costos de envío**

Puedes optar por reembolsar los gastos de envío de los productos devueltos. ¡Siempre es un gesto apreciado!&#x20;

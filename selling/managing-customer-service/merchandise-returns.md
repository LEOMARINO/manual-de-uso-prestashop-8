# Devoluciones de Mercancía

La página "Devoluciones de Mercancía" le brinda una lista de todo el proceso RMA (Autorización de Devolución de Mercancía).

En la parte inferior de la página, tienes la posibilidad de permitir que los clientes te envíen productos (opción "Activar devoluciones"). Simplemente elija, indique el número de días durante los cuales se puede realizar una solicitud de devolución y guarde su configuración: los clientes ahora tienen la posibilidad de solicitar una autorización de devolución. También puede editar el prefijo del número de devolución o elegir no tener ninguno.

![](<../../.gitbook/assets/38109196 (3) (3) (3).png>)

## Proceso de devolución: cómo lo ve el cliente <a href="#merchandisereturns-returnprocess-howthecustomerseesit" id="merchandisereturns-returnprocess-howthecustomerseesit"></a>

Una vez que hayas activado la opción de devoluciones en tu back office, el cliente podrá optar por devolver un artículo (siempre que el pedido aún se encuentre en el tiempo de validez). Para ello deberá hacer lo siguiente:

1. Accede a la sección "Historial de pedidos" de su cuenta.
2. Seleccione el pedido del que desea devolver un artículo haciendo clic en "Detalles".
3. Seleccione el producto que desea devolver marcando la casilla junto a su nombre.
4. Añade la cantidad a devolver (en caso de que sea necesario devolver más de un producto).
5. (opcional) En la sección "Devolución de mercancía", agregue una explicación para que el equipo de la tienda comprenda mejor por qué el cliente quiere devolver este producto.
6. Haga clic en "Solicitar una devolución".

![](<../../.gitbook/assets/51839875 (3) (3).png>)

¿Cuándo es posible devolver un pedido?

1. Las devoluciones tienen que estar habilitadas (opción "Habilitar devoluciones").
2. El pedido tiene que estar en el tiempo de validez (= todavía es tiempo de devolver un producto).
3. Los pedidos deben haber tenido al menos los siguientes estados:

*
  * Al menos dos estados: uno con la condición "Establecer el pedido como pagado" habilitada y el segundo con la opción "Establecer el pedido como enviado" habilitada.\
    O
  * Un estado que tiene ambas condiciones ("Establecer el pedido como pagado" y "Establecer el pedido como enviado") habilitadas.

Los estados se pueden editar en la pestaña "Estados" en la página "Configuración de pedidos" del menú "Parámetros de la tienda".

Una vez que se completa el formulario, el cliente hace clic en "Solicitar una devolución" y la solicitud se envía al gerente de la tienda (usted). La solicitud aparece como "Esperando confirmación" en la página "Devoluciones de mercancía" del cliente, accesible desde la página de la cuenta.

![](<../../.gitbook/assets/51839876 (3) (3) (3).png>)

## Proceso de devolución: cómo lo ves <a href="#merchandisereturns-returnprocess-howyouseeit" id="merchandisereturns-returnprocess-howyouseeit"></a>

La solicitud de devolución aparece en su back office en la página "Devoluciones de Mercancía". Al principio, la solicitud de devolución tiene el estado "Esperando confirmación".

![](<../../.gitbook/assets/23038598 (3) (3) (3).png>)

El proceso de reembolso puede tomar varios pasos, que se indican en el estado de la devolución. Puede ser:

* Esperando confirmación.
* Esperando el paquete.
* Paquete recibido.
* Devolución denegada.
* Devolución completada.

![](<../../.gitbook/assets/51839877 (3) (3).png>)

Ahora depende de ti aceptarlo o rechazarlo:

1. Haga clic en el ID de la solicitud de devolución para ver más detalles.
2. Cambia el estado para continuar con el proceso de devolución o detenerlo.
   * Si desea detener el proceso de devolución (y negarle un reembolso al cliente), simplemente elija el estado "Devolución denegada".
   * Si está de acuerdo con la devolución del producto y el reembolso al cliente, siga cada paso con precisión:
     1. Elija el siguiente paso del proceso: "Esperando paquete". Esto enviará un correo electrónico al cliente indicándole que se le puede devolver el producto.
     2. Una vez que haya recibido el paquete, cambie el estado de la solicitud a "Paquete recibido".
     3. Finalmente, una vez finalizado todo el proceso (ya sea que el cliente haya recibido el reembolso o usted haya emitido un comprobante de crédito), cambie el estado a "Devolución completada".
3. Ahorrar.

## Reembolsar a un cliente <a href="#merchandisereturns-refundingacustomer" id="merchandisereturns-refundingacustomer"></a>

Un pedido puede ser reembolsado, ya sea parcial o totalmente. Esto se hace usando dos botones de acción ubicados en la barra superior de la página del pedido en lugar de en la página de devolución**.**

Los botones de acción cambian según el estado del pedido. Por ejemplo, una vez que el pedido está en el estado "Entregado", "Agregar un producto" y "Eliminar productos" se convierten en dos nuevos botones: "Devolver productos" y "Reembolso parcial".

Las devoluciones de productos no están activadas por defecto. Para activarlo, vaya a la página "Devoluciones de mercancía" en el menú "Servicio al cliente" y active la opción en la sección de opciones en la parte inferior de la página. Esto se aplicará a todos los productos y a todos los pedidos.

![](<../../.gitbook/assets/51839878 (3) (3).png>)

* **Devolución de productos**. Se utilizará únicamente cuando el cliente haya devuelto efectivamente los productos: una vez recibido el producto devuelto, podrá marcarlo como devuelto directamente en el formulario de pedido. \
  Haga clic en el botón "Devolver productos" y aparecerá una nueva columna en la lista de productos, titulada "Devolución". Marque la casilla de los productos afectados, indique la cantidad de artículos que se devolvieron y haga clic en "Devolver productos" en la parte inferior de la tabla.
* **Reembolso parcial**. Se utiliza cuando necesita reembolsar solo una parte del pedido y no todo el pedido, ya sea porque el cliente devolvió el producto solicitado o simplemente como señal de buena voluntad por un producto dañado que el cliente decidió conservar de todos modos. Haga clic en el botón "Reembolso parcial" y aparecerá una nueva columna en la lista de productos, titulada "Reembolso parcial". Establezca el monto y la cantidad para cada uno de los productos afectados, elija una de las opciones en la parte inferior de la lista (ver a continuación) y haga clic en el botón "Reembolso parcial" en la parte inferior de la tabla.\
  \


Cuando configura un producto como devuelto o para reembolso, hay cuatro opciones disponibles debajo de la lista de productos:

* **Reabastecimiento de productos**. Al marcar esta opción, PrestaShop considerará que el producto devuelto está nuevamente disponible para la venta, por lo que aumentará el stock de este producto. No debe hacer clic aquí cuando se devuelve un producto debido a que está roto...
* **Generar una boleta de crédito**. Cuando se marca, se creará un comprobante de crédito para los artículos seleccionados. Una boleta de crédito es un reconocimiento por parte de su tienda de que la mercancía ha sido devuelta y de que se ha emitido un reembolso. El cliente podrá utilizarlo como comprobante de crédito para su próxima compra.
* **Generar un bono**. Cuando se marca, se creará un vale por el importe de los artículos seleccionados. Un cupón toma la forma de un código de descuento que el cliente puede ingresar durante el proceso de pago. Puede editar los vales existentes del cliente viendo la página del cliente: desde la página del pedido actual, haga clic en el nombre del cliente en la sección "Cliente"; Una vez en la página del cliente, acceda a la sección "Vales". Puedes editar cada bono haciendo clic en el icono "Editar".
* **Pagar el costo de envío**. También puede optar por reembolsar el coste de envío del producto devuelto, lo cual siempre es un gesto apreciado.
  \


Si el cliente pagó el pedido con tarjeta de crédito, el sistema de pago puede reembolsar el carrito automáticamente o puede que tengas que hacerlo tú mismo. Si el pedido se pagó mediante cheque o transferencia bancaria, debe emitir el reembolso usted mismo y luego marcar el pedido como reembolsado manualmente en la oficina administrativa (en la página del pedido).

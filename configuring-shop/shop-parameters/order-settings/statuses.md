# Statuses

Tener diferentes estados de pedidos o devoluciones te permite gestionar fácilmente tus pedidos y devoluciones, y mantener a tus clientes informados de la evolución de su compra.

Los distintos estados disponibles son visibles y editables en la página "Estados", en el menú "Configuración del pedido".

![](<../../../.gitbook/assets/38109199 (2) (2).png>)

La página muestra una lista de los estados de pedidos registrados actualmente, junto con:

* Sus colores distintivos: los estados existentes tienen colores que ayudan a decidir rápidamente si hay algún problema con el pedido o si todo va bien.
* Their icons.
* Their ties to three PrestaShop behaviors (more are available):
  * ¿El cliente debería recibir un correo electrónico cuando el pedido obtenga este estado?
  * Is this a delivery status?
  * ¿Este estado permite al cliente descargar y ver una versión PDF de la factura del pedido?
* El nombre de su plantilla de correo electrónico: puede editar estas plantillas, idioma por idioma, en la página "Traducciones" en el menú "Internacional". En la sección "Modificar traducciones" de esa página, elija "Traducciones de plantillas de correo electrónico" en el menú desplegable y luego haga clic en el código de idioma del idioma en el que desea editar estas plantillas.
* Sus iconos de acción: "editar" y "eliminar".

La lista de estados de devolución presenta menos información porque esos estados son simplemente etiquetas sin ningún impacto en el pedido.

![](<../../../.gitbook/assets/23038627 (4) (4) (1).png>)

## Creando un nuevo estado de pedido <a href="#statuses-creatinganeworderstatus" id="statuses-creatinganeworderstatus"></a>

Puede crear un nuevo estado con el botón "Agregar nuevo estado de pedido" en la parte superior. Se abre el formulario de creación.

![](<../../../.gitbook/assets/51839969 (4) (4) (2).png>)

Llene el formulario:

* **Nombre de estado**. Mantenlo muy breve y distintivo.
* **Icono**. Puede utilizar cualquier icono de 16\*16; por ejemplo, el conjunto gratuito de iconos FamFamFam Silk: [http://www.famfamfam.com/lab/icons/silk/](http://www.famfamfam.com/lab/icons/silk/).
* **Color**. Debe esforzarse para que el color del estado coincida con los colores existentes (if relevant). Los usos de color predeterminados son:
  * Rojo/Naranja: pedidos cancelados o reembolsados,
  * Crimson red: payment error,
  * Azul: pedidos que aún están pendientes de pago,
  * Verde claro: pedidos pagados,
  * Verde oscuro: pedidos entregados,
  * Púrpura: pedidos enviados,
  * Rosa: pedidos pendientes.
* Options:
  * **Considerar el pedido asociado como validado**. Si está habilitado, este estado marca todos los pedidos asociados como "pagados" y los coloca en el mismo estado.
  * **Permitir que un cliente descargue y vea versiones en PDF de su factura**. Si está deshabilitado, usted mismo deberá enviar la factura a los clientes.
  * **Ocultar este estado en todos los pedidos de los clientes**. Esto le permite crear estados internos, para usted y su equipo. Los clientes nunca verán esto en la página de estado de su pedido.
  * **Enviar un correo electrónico al cliente cuando el estado de su pedido haya cambiado**. Cuando está habilitado, aparece un menú desplegable que le permite elegir qué plantilla de correo usar.
  * **Adjunte el PDF de la factura al correo electrónico**. Enviar un correo electrónico al cliente con la factura en formato PDF adjunta.
  * **Adjunte el PDF del comprobante de entrega al** correo electrónico. Enviar un correo electrónico al cliente con el albarán de entrega en formato PDF adjunto.
  * **Establecer el pedido como enviado**. Tenga cuidado: una vez que un pedido se establece como "enviado", no se puede volver al estado anterior.
  * **Establecer el pedido como pagado**. Lo mismo ocurre aquí: una vez que un pedido se establece como "pagado", no se puede volver al estado anterior.
  * **Mostrar PDF de entrega**. Muestra el PDF de entrega.

## Creating a new return status <a href="#statuses-creatinganewreturnstatus" id="statuses-creatinganewreturnstatus"></a>

Puede crear un estado de devolución con el botón "Agregar nuevo estado de devolución" en la parte superior. Se abre el formulario de creación.

![](<../../../.gitbook/assets/23038630 (4) (2).png>)

It only features two fields:

* **Nombre de estado**. Establezca el nombre de estado que desee.
* **Color**. Set its color

Finalmente, guarda tu creación.

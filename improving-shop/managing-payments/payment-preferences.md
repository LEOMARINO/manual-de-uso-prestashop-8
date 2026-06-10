# Payment Preferences

Las preferencias de pago están destinadas a ayudarle a decidir qué método de pago debería estar disponible para sus clientes según la moneda, el país, el grupo o el operador. ¡Presta atención a esta página si no quieres sorpresas!

## Restricciones del módulo de pago en monedas <a href="#paymentpreferences-paymentmodulerestrictionsoncurrencies" id="paymentpreferences-paymentmodulerestrictionsoncurrencies"></a>

Dependiendo del pago, la elección de moneda por parte del cliente puede variar. Puede limitar la elección de los métodos de pago disponibles según las monedas disponibles: es posible que desee que los clientes puedan pagar con cualquier moneda cuando utilicen PayPal, pero aquellos que paguen a través de Moneybookers solo deben pagar en dólares, por ejemplo.

![](<../../.gitbook/assets/64225552 (4).png>)

De forma predeterminada, solo está disponible la moneda predeterminada de tu tienda. Si necesitas más, sigue este proceso:

1. En la página "Localización" en el menú "Internacional", importe el paquete de localización para el país que tiene la moneda en la que está interesado. Por ejemplo, EE.UU. para dólares estadounidenses, Reino Unido para libras esterlinas, etc.
2. En la página "Monedas" en el menú "Localización", habilite las monedas que acaba de importar.

Si necesita restringir el uso del módulo de pago según la moneda del usuario, simplemente marque las casillas correspondientes y haga clic en "Guardar restricciones". Tenga en cuenta que las restricciones de moneda funcionan de diferentes maneras según el módulo de pago:

* Para algunos, como Pago contra reembolso, no puede cambiar su configuración predeterminada.
* Para otros, como pago por transferencia bancaria, pago con cheque, Skrill, Ogone, etc., puede cambiar cualquiera de sus configuraciones de moneda, excepto la "moneda del cliente" y la "moneda predeterminada de la tienda", que permanecen en su estado predeterminado.
* Luego, para otros módulos como Hipay o PayPal, puede cambiar cualquiera de sus configuraciones de moneda, pero puede elegir solo una opción entre "Moneda del cliente" y "Moneda predeterminada de la tienda", no ambas.

El cliente puede configurar su moneda usando el menú desplegable en la parte superior de cada página de la oficina principal. Puedes configurar la moneda predeterminada de la tienda en la página "Localización", en el menú "Internacional".

Si cambias la moneda predeterminada después de haber configurado algunos primeros productos, tendrás que restablecer el precio de todos estos productos. Debes configurar la moneda predeterminada de una vez por todas antes de agregar cualquier producto.

## Restricciones del módulo de pago en grupos <a href="#paymentpreferences-paymentmodulerestrictionsongroups" id="paymentpreferences-paymentmodulerestrictionsongroups"></a>

Puede limitar la elección de los métodos de pago disponibles según el grupo de clientes: puede tener un número determinado de grupos de clientes donde las personas pueden tener acceso a más métodos de pago que los clientes habituales.

![](<../../.gitbook/assets/64225553 (2) (1) (1).png>)

Por ejemplo, puede optar por que los clientes habituales paguen con PayPal, Skrill e Hipay, mientras que los profesionales sólo podrán pagar mediante transferencia bancaria. Dependiendo del tipo de clientes y de sus elecciones, los clientes sólo pagarán utilizando los métodos que coincidan con sus decisiones.

## Restricciones del módulo de pago en países <a href="#paymentpreferences-paymentmodulerestrictionsoncountries" id="paymentpreferences-paymentmodulerestrictionsoncountries"></a>

Puede limitar la elección de métodos de pago según el país de origen de su cliente. Por ejemplo, podría optar por aceptar todos los métodos de pago para clientes de Francia, España y Alemania, mientras que los clientes de Italia, Reino Unido y Suiza sólo podrían pagar mediante transferencia bancaria.

![](<../../.gitbook/assets/64225554 (3) (5).png>)

La tabla enumera todos los países conocidos. Si falta uno, puede agregarlo usando la página "Países", en el menú "Zonas".

Nuevamente, al igual que con las limitaciones de moneda, las opciones disponibles varían según el módulo de pago:

* Para algunos, la única opción es su propio país.
* Para otros, las únicas opciones son el conjunto de países soportados por el servicio: Austria, Bélgica, Francia, etc.
* Todos los demás módulos de pago nativos deberían funcionar con todos los países.

Busque el país que está buscando en la lista alfabética y marque las casillas para seleccionar o deseleccionar los métodos de pago que desea poner a disposición de los clientes de ese país. Una vez que se hayan configurado todas las configuraciones, haga clic en el botón "Guardar restricciones", que se encuentra en la parte inferior de la tabla. De forma predeterminada, todos los métodos de pago instalados están habilitados para el país de la tienda.

## Restricciones del módulo de pago para transportistas <a href="#paymentpreferences-paymentmodulerestrictionsoncarriers" id="paymentpreferences-paymentmodulerestrictionsoncarriers"></a>

Puede limitar la elección de métodos de pago disponibles según sus operadores.

![](<../../.gitbook/assets/64225554 (3) (5).png>)

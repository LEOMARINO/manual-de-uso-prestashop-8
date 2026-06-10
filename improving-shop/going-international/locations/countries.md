# Countries

Tu instalación de PrestaShop debe conocer todos los países existentes para que tus clientes indiquen claramente en qué parte del mundo viven.

Hay aproximadamente 200 países en el mundo, pero PrestaShop tiene 244 registrados. Esto se debe a que algunos países incluyen regiones de ultramar que forman parte del país propiamente dicho. Por ejemplo, los departamentos franceses anteriormente conocidos como DOM (Guadeloupe, Martinique, Mayotte, Reunion, and French Guiana) tienen hoy el mismo estatus que la región metropolitana francesa. Asimismo, Alaska y Hawaii son estados propiamente dichos de Estados Unidos. Aún así, enviar un paquete a Guadalupe no significa enviarlo a Francia, aunque sólo sea por los gastos de envío. Por lo tanto, la lista de países en PrestaShop separa el país del continente.

De forma predeterminada, sólo su propio país está habilitado en la lista de países. Debe habilitarlos uno por uno, según sea necesario para sus clientes. Si no está seguro de cuál habilitar, consulte sus estadísticas para ver los países con más visitantes.

Al final de la lista, la sección "Opciones de país" permite mostrar en su oficina principal solo los países que cubren sus operadores. Le recomendamos que habilite esta configuración, ya que evita que los clientes tengan que desplazarse por todos los nombres de países para encontrar el suyo.

![](<../../../.gitbook/assets/51839946 (4) (4) (1).png>)

## Adding a New Country <a href="#countries-addinganewcountry" id="countries-addinganewcountry"></a>

Normalmente, PrestaShop viene con todos los países actuales en la base de datos. Pero en el caso de que se creen nuevos, deberá agregar un nuevo país.

![](<../../../.gitbook/assets/51839947 (4) (4) (1).png>)

* **País**. El nombre oficial del país que desea agregar, en todos los idiomas admitidos. Consulte la página de Wikipedia del país si no está seguro del nombre.
* **Código ISO**. El código ISO-3166 del país, que puedes encontrar en la página oficial ISO: [http://www.iso.org/iso/country\_codes/iso\_3166\_code\_lists/country\_names\_and\_code\_elements.htm](http://www.iso.org/iso/country\_codes/iso\_3166\_code\_lists/country\_names\_and\_code\_elements.htm).
* **Prefijo de llamada**. Su código de llamada internacional, que puedes encontrar en [Wikipedia](http://en.wikipedia.org/wiki/List\_of\_country\_calling\_codes).
* **Moneda predeterminada**. Puedes utilizar la moneda predeterminada de tu tienda, (as set in the "Localization" page, under the "Localization" menu), o una de las otras monedas instaladas. Recuerda que si es necesario, puedes agregar una nueva moneda a tu tienda usando la página "Monedas".
* **Zona**. Subregión del mundo a la que está adscrito este país. Si es necesario, puede agregar nuevas zonas usando la página "Zonas", en el menú "Ubicación".
* **¿Necesita código postal?**. Indica si un usuario que vive en este país debe dar un código postal o no al registrarse en su tienda.
* **Formato de código postal**. También puede dar más detalles sobre el formato del código postal (or zip code). Si no pones nada, PrestaShop no verificará la validez del código postal cuando se te dé una nueva dirección para este país. Utilice los siguientes códigos para el código postal: "L" para una letra, "N" para un número y "C" para el código ISO del país (the one which you entered in the ISO field above).\
  Si no conoce el formato del código postal del país, puede confiar en [Wikipedia](http://en.wikipedia.org/wiki/List\_of\_postal\_codes). ¡Asegúrate de NO copiar/pegar la notación de Wikipedia, sino adaptarla! Por ejemplo, Wikipedia indica "AAA 9999\*" para Malta, por lo que la notación para PrestaShop se convierte en "LLL NNNN" (without the final \*).
* **Formato de dirección**. Proporcione detalles sobre el diseño de la dirección cuando se la muestre a los clientes. Puede hacer clic en los diversos enlaces de ayuda al costado del campo de texto para agregar más campos. En el uso real, PrestaShop los reemplaza automáticamente con los datos de la cuenta del cliente. Sus cambios solo se guardan cuando guarda la página completa. Si ha cometido un error, puede utilizar uno de los cuatro botones auxiliares en la parte inferior del formulario, dependiendo de su situación.
* **Activo**. Un país deshabilitado no se sugerirá como una opción cuando un visitante quiera registrarse y crear una nueva cuenta.
* **Contiene estados**. Indica si el país tiene "estados" o no. Esto agrega un nuevo campo al formulario de dirección de PrestaShop. Tenga en cuenta que los "estados" pueden ser regiones, provincias, departamentos... cualquier cosa que tenga sentido para el servicio postal de ese país.
* **¿Necesitas un número de identificación fiscal?**. Un Número de Identificación Fiscal es un número de identificación utilizado por el servicio de ingresos del país en la administración de las leyes fiscales. No todos los países necesitan ni siquiera tener ese número para hacer negocios. Infórmese sobre esto con el servicio de impuestos del país.
* **Mostrar etiqueta de impuestos (e.g. "Tax** incl**.")**. Elija si el estado fiscal (included or excluded) debe mostrarse junto a los precios o no.
* **Asociación de tiendas**. Puede hacer que el país solo esté disponible para una selección de sus tiendas, por ejemplo, tiendas orientadas a una ubicación específica.

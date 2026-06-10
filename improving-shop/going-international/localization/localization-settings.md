# Configuración de localización

La página principal en el menú "Localización" le permite configurar las unidades utilizadas para sus productos.

## Import a localization pack <a href="#localizationsettings-importalocalizationpack" id="localizationsettings-importalocalizationpack"></a>

Esta sección le proporciona una lista extensa de paquetes de localización existentes que puede importar. No sólo configura tu instalación de PrestaShop con tus unidades locales adecuadas, sino que también añade muchos otros datos:

* **Estados**. Al enviar un producto a un país, saber a qué estado se envía puede resultar importante, ya que esto podría tener un impacto en las aduanas e impuestos locales. Los estados agregados se pueden ver y editar en la página "Estados" en el menú "Ubicaciones".
* **Impuestos**. La verdadera importancia de la localización son los impuestos locales, que pueden ser numerosos y variados según el país o el estado. PrestaShop le proporciona un soporte básico para los principales impuestos y normas fiscales. Los impuestos y reglas impositivas agregados se pueden ver y editar en las páginas "Impuestos" y "Reglas impositivas" en el menú "Impuestos".
* **Monedas**. Los clientes extranjeros apreciarán poder convertir los precios de su tienda a su propia moneda. Al menos deberías tener dólares estadounidenses y euros disponibles junto con la moneda propia de tu país, (if not one of those two). Una vez agregada, debe activar una nueva moneda usando la página "Monedas" en el menú "Localización" y asegurarse de que la tasa de conversión sea correcta. Las monedas agregadas se pueden ver y editar en esa página "Monedas". Asegúrese de configurar también sus métodos de pago con respecto a estas nuevas monedas.
*   **Idiomas**. Todos los campos públicos de tu tienda se pueden crear en varios idiomas, y es importante que lo hagas, como mínimo, para el nombre y la descripción de tus productos. Tenga en cuenta que al importar un idioma también se importa su formato de fecha (d/m/Y, m/d/Y, d.m.Y, etc.), entre otras cosas. Los idiomas agregados se pueden ver y editar en la página "Idiomas" en el menú "Localización".

    Puedes agregar un solo idioma, sin moneda, impuestos y otros datos según el país, gracias a la página "Traducciones".
* **Unidades**. Peso, dimensión, volumen, distancia: estas unidades son esenciales para describir correctamente un producto a su cliente y para su propia información de embalaje. Se pueden visualizar y editar en esta misma página, en el apartado "Unidades locales".
*   **Cambiar el comportamiento de los impuestos mostrados a los grupos**. Estos no son datos para importar, sino una configuración que puede cambiar al realizar la importación. Reemplazará el método de visualización de precios para sus grupos de clientes (e.g. displaying price with tax included or not according to each customer group, as found in Shop Parameters > Customer Settings > Groups, when editing or creating a group) y activará en su lugar el comportamiento fiscal que se aplica generalmente en el país, para todos los grupos y todos los países. Por ejemplo, si está importando el paquete de localización para Estados Unidos y selecciona esta opción, los precios se mostrarán sin impuestos.&#x20;

    Debes seleccionar esta opción solo si estás importando un paquete de localización para el país predeterminado de tu tienda, ya que podría cambiar los métodos de visualización de impuestos para todos los grupos y todos los países.

    ![](<../../../.gitbook/assets/64225597 (2) (1) (1).png>)

Como puedes ver, estos datos adicionales son opcionales: puedes elegir importar la moneda y el idioma de un país determinado, y no sus impuestos, por ejemplo. Si bien no debes agregar demasiados datos locales por temor a abrumarte a ti y a tus clientes con ellos, puede ser útil importar el paquete de localización para los países más visitados (according to your stats).

Aparte de las unidades predeterminadas, **no puedes eliminar automáticamente todos los datos de un país determinado**; si necesita eliminar datos, deberá hacerlo manualmente, en sus respectivas páginas en el menú "Localización".

## Configuration <a href="#localizationsettings-configuration" id="localizationsettings-configuration"></a>

Esta sección agrupa cuatro configuraciones locales predeterminadas, de primordial importancia:

* **Idioma predeterminado**. Este es el idioma principal de tu tienda. Esta configuración influirá en el idioma de su back office (including the main language for your products), así como en el front office. Tenga en cuenta que el idioma de la oficina principal puede adaptarse a la configuración del navegador del cliente.
* **País predeterminado**. La ubicación de su negocio. Si tiene sede en muchos países, utilice su país principal u original.
* **Moneda predeterminada**. La moneda en la que se establecen por primera vez los precios de su producto. Las monedas se agregan importando y activando la moneda de un país. Tenga en cuenta que si cambia de moneda después de haber establecido algunos precios de productos, tendrá que actualizar manualmente todos los precios existentes. Asegúrese de establecer ese valor de una vez por todas.
* **Huso horario**. Tu propia zona horaria. Esto es útil, por ejemplo, para el descuento diario: sabes exactamente cuándo comienza y termina.

Las configuraciones "Idioma predeterminado" y "País predeterminado" tienen cada una una configuración adicional:

* Para "_Idioma predeterminado_": **Establecer idioma desde el navegador**. PrestaShop configurará el idioma de la tienda dependiendo del idioma del código local del navegador del visitante (for instance: fr\_CA gives French)
* Para "_País predeterminado_": **Establezca el país predeterminado desde el idioma del navegador**. PrestaShop establecerá el país de la tienda dependiendo del territorio del código local (for instance, fr\_CA gives Canada) del navegador del visitante.

![](<../../../.gitbook/assets/64225598 (3) (1) (4).png>)

## Local units <a href="#localizationsettings-localunits" id="localizationsettings-localunits"></a>

Las unidades físicas presentadas en esta sección (weight, distance, volume, dimension) se utilizan tanto en las fichas de producto como para sus propias necesidades de embalaje y, en última instancia, son esenciales en su relación con su transportista.

![](<../../../.gitbook/assets/64225599 (4) (3).png>)

Estos valores se pueden establecer cuando importa el paquete de localización para un país, pero luego puede editarlos manualmente. Por ejemplo, si prefiere utilizar centilitros en lugar de litros para la unidad de volumen, cambie la "L" predeterminada a "cL". Los valores deben ser símbolos de unidades del Sistema Internacional de Unidades: [http://en.wikipedia.org/wiki/International\_System\_of\_Units](http://en.wikipedia.org/wiki/International\_System\_of\_Units).

## Advanced <a href="#localizationsettings-advanced" id="localizationsettings-advanced"></a>

Esta última sección le pide que configure el idioma local y el país de su servidor, como código ISO:

* Para el idioma: código ISO 639-1 ([http://en.wikipedia.org/wiki/List\_of\_ISO\_639-1\_codes](http://en.wikipedia.org/wiki/List\_of\_ISO\_639-1\_codes)).
* Para el país: ISO 3166-1 Alfa 2 código ([http://en.wikipedia.org/wiki/ISO\_3166-1\_alpha-2](http://en.wikipedia.org/wiki/ISO\_3166-1\_alpha-2)).\
  \


![](<../../../.gitbook/assets/64225600 (4) (2) (1).png>)

Estos valores se pueden configurar cuando importa el paquete de localización para un país, pero puede editarlos manualmente en cualquier momento.

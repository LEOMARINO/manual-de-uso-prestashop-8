# Idiomas

PrestaShop viene multilingüe desde el primer momento: hay un idioma predeterminado, (the one you used to install it), y hay muchos más disponibles para descargar.

Take part in PrestaShop translations

Si PrestaShop no está completamente traducido a su idioma, puede ayudar a traducirlo uniéndose a nuestra comunidad abierta de traductores en [Crowdin](https://crowdin.com/project/prestashop-official) y contribuyendo en su idioma.

La página "Idiomas" gestiona los idiomas que verás en tu panel de administración y en tu tienda. La página muestra los idiomas ya instalados en su tienda, junto con cierta información: código ISO, código de idioma, formato de fecha (short and full). Puede habilitar o deshabilitar un idioma haciendo clic en el icono en la columna "Habilitado".

Añadir un nuevo idioma es simplemente cuestión de importar el paquete de localización de un país que utilice ese idioma (in the "Localization" page). Si resulta que esto no funciona, o que necesita algo personalizado, puede agregar un nuevo idioma manualmente, usando el formulario detrás del botón "Agregar nuevo".

También puede agregar un nuevo idioma desde la página "Traducciones", sección "Agregar/Actualizar un idioma". A diferencia de un paquete de localización, esto solo importará el idioma y no la configuración de localización (units, currency, etc.).

![](<../../../.gitbook/assets/64225603 (4) (4).png>)

## Agregar un nuevo idioma <a href="#languages-addinganewlanguage" id="languages-addinganewlanguage"></a>

Antes de crear un nuevo idioma, debe verificar si este idioma está disponible en la página "Traducciones" en la sección "Agregar/Actualizar un idioma". De hecho, incluso si no está completamente completado, importará las traducciones oficiales de PrestaShop y proporcionará una base para su trabajo de traducción.

Crear un nuevo idioma significa que tendrá que traducir todo el texto para el front office, back office, módulos, etc. de PrestaShop, o arriesgarse a utilizar las cadenas en inglés predeterminadas. Para completar su traducción, debe utilizar la opción "Modificar traducciones" en la página "Traducciones", en el menú "Internacional".

![](<../../../.gitbook/assets/64225604 (4) (4) (2).png>)

Para crear un nuevo idioma, debe completar tantos campos del formulario como sea posible:

* **Nombre**. El nombre es público. Si está creando ese idioma para un propósito regional, puede indicarlo en el nombre: "Francés (Quebec)", por ejemplo.
* **Código ISO**. Ingrese el código ISO 639-1 de 2 letras adecuado. Consulte [http://en.wikipedia.org/wiki/List\_of\_ISO\_639-1\_codes](http://en.wikipedia.org/wiki/List\_of\_ISO\_639-1\_codes) para obtener más información.\
  Si está importando un paquete de idioma, este código debe coincidir exactamente con el del paquete.
* **Código de idioma**. Ingrese el código de idioma adecuado de 4 letras, en el formato `xx-yy`, siendo `xx` el código ISO de idioma (same as above), y `yy` el código ISO del país, utilizando ISO 3166-1 alfa-2 ([http://en.wikipedia.org/wiki/ISO\_3166-1\_alpha-2](http://en.wikipedia.org/wiki/ISO\_3166-1\_alpha-2)). Consulte [http://en.wikipedia.org/wiki/IETF\_language\_tag](http://en.wikipedia.org/wiki/IETF\_language\_tag) para obtener más información.
* **Formato de fecha**. Los países no siempre comparten la misma representación de fecha (See [http://en.wikipedia.org/wiki/Date\_format\_by\_country](http://en.wikipedia.org/wiki/Date\_format\_by\_country)). Por lo tanto, cuando su tienda muestre 08/02/12, un cliente de Francia entenderá "2 de agosto de 2012", mientras que uno de EE. UU. entenderá "8 de febrero de 2012", y un cliente de Japón podría incluso leerlo como "12 de agosto de 2002". Por eso es importante indicar el formato de fecha vinculado a su idioma. Las letras utilizadas deben ser las de la función `date()` de PHP: [http://php.net/manual/en/function.date.php](http://php.net/manual/en/function.date.php).
* **Formato de fecha (full)**. Igual que el formato de fecha anterior, pero incluye el formato hora-minuto.
* **Bandera**. Sube una imagen de la bandera que mejor coincida con el idioma que deseas agregar. Debe tener 16\*11 píxeles. Le recomendamos utilizar el conjunto de imágenes gratuito FamFamFam Flags: [http://www.famfamfam.com/lab/icons/flags/](http://www.famfamfam.com/lab/icons/flags/).
* **Imagen "sin imagen"**. Sube una imagen que se mostrará cuando un producto aún no tenga imagen. Esa imagen es simplemente una imagen en blanco, con "No hay imagen" o "No hay imagen disponible" en este idioma. La imagen debe tener 250\*250 píxeles. Puede encontrar imágenes "Sin imagen" existentes en el directorio `/img/l` de su instalación de PrestaShop.
* **Idioma RTL**. Algunos idiomas se escriben de derecha a izquierda, sobre todo aquellos que utilizan la escritura árabe o el alfabeto hebreo (ZQQ0QXZ). Cuando un tema de PrestaShop está bien codificado, puede manejar lenguajes RTL, siempre que esté configurado como tal.
* **Estado**. Puede desactivar un nuevo idioma hasta que esté listo para traducir todo.
* **Asociación de tiendas**. Puede hacer que el idioma solo esté disponible para una selección de sus tiendas, por ejemplo, tiendas orientadas a una ubicación específica.

Una vez que su idioma esté guardado y habilitado, puede importar su paquete de idioma. Esto se hace en la página "Traducciones", en el menú "Localización". Utilice la herramienta "Importar un paquete de idioma manualmente". Finalmente, asegúrate de que todo funciona: ve a la recepción de tu tienda y haz clic en las banderas en la parte superior. De manera similar, los clientes ahora pueden seleccionar un idioma adicional usando estos íconos.

Compartiendo sus traducciones con la comunidad

Es posible que hayas traducido completamente un nuevo idioma directamente a través de tu interfaz de PrestaShop. Puedes compartirlo con la comunidad PrestaShop enviando una exportación a [translation@prestashop.com.](mailto:translation@prestashop.com.) ¡Subiremos tu contribución a nuestro [proyecto de traducción](https://crowdin.com/project/prestashop-official) para que otros comerciantes de tu país también puedan beneficiarse de él!

Para ver cómo puedes exportar tus traducciones, ve a la página "Traducciones" del menú "Internacional", en la sección "Exportar un idioma".

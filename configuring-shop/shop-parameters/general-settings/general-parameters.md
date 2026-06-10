# General parameters

La página "General" presenta algunas configuraciones específicas que no caben en los otros menús. No obstante, son esenciales:

* **Habilitar SSL**. SSL significa "Capa de sockets seguros" e incluye TSL (for "Transport Layer Security"). Ambos son protocolos criptográficos de Internet que protegen las comunicaciones web. Puede leer más sobre estos protocolos en Wikipedia: [http://en.wikipedia.org/wiki/Secure\_Sockets\_Layer](http://en.wikipedia.org/wiki/Secure\_Sockets\_Layer).\
  Proporcionar una conexión SSL a su tienda no sólo es excelente para cualquier intercambio de Internet, sino también una excelente manera de tranquilizar a sus clientes sobre la seguridad de sus propios datos (authentication, credit card, etc.) en su tienda, ya que los navegadores modernos ahora muestran señales visuales que muestran que la conexión está segura. Si su proveedor de alojamiento admite SSL, asegúrese de activar el soporte SSL de PrestaShop haciendo clic en el enlace. Esto revelará un selector, donde deberás elegir "Sí". SSL se habilitará en todas las páginas de pago y de cuenta.
* **Habilite SSL en todas las páginas**. Esta opción solo está disponible si ha habilitado SSL. Cuando esté activo, todas las páginas de su tienda estarán protegidas por SSL (and not only the checkout and account pages).
* **Aumentar la seguridad de la oficina principal**. Esto agrega tokens de seguridad a su tienda para mejorar su seguridad. De hecho, cada URL es específica de la sesión de un cliente y no se puede utilizar tal cual en otro navegador, protegiendo así cualquier información que haya almacenado durante esa sesión.
* **Permitir iframes en campos HTML**. La opción le permite colocar iframes en campos de texto, como la descripción del producto. Los iframes son elementos HTML que permiten cargar un contenido externo en el contenido propio de la página. Le recomendamos que deje esta opción desactivada a menos que sea necesario.
* **Utilice la biblioteca HTMLPurifier**. Los clientes pueden enviar información a su tienda utilizando los campos de texto (for instance, product descriptions or customer information), pero los piratas informáticos también pueden intentar utilizar estos campos para enviar código malicioso con el fin de intentar piratear su tienda. Esta opción garantiza que cualquier dato enviado a su tienda esté seguro. Sólo debes desactivarlo si sabes muy bien lo que estás haciendo.
* **Modo redondo**. Una vez que se aplican los impuestos y el descuento, un precio puede tener demasiados decimales, como $42,333333333. El modo redondo se utiliza en todo PrestaShop, en la visualización de precios de la recepción y durante el proceso de cálculo de precios (taxes, discount, etc.). Por sí mismas y fuera de ellas, cambian poco la forma en que se calculan las cosas, pero el impacto es mucho mayor una vez que se tienen en cuenta en el total de la factura, cuando muchos elementos se suman a los impuestos y descuentos.
  There are six modes:
  * **Redondea hacia arriba desde cero, cuando esté a la mitad**. Este es el modo recomendado. 42,55555555 se convierte en 42,56.
  * **Round down towards zero, when it is half way there**. 42.55555555 becomes 42.56.
  * **Redondea hacia el siguiente valor par**. 42,55555555 se convierte en 42,56.
  * **Redondea hacia el siguiente valor impar**. 42,55555555 se convierte en 42,56.
  * **Redondea al valor más cercano**. 42,55555555 se convierte en 42,56.
  * **Redondea hacia abajo al valor más cercano**. 42,55555555 se convierte en 42,55.
* **Tipo redondo**. Esta opción le permite elegir el tipo de redondeo, lo que puede afectar en gran medida el cálculo del total. Hay tres tipos disponibles, en orden progresivo:
  * **Ronda en cada artículo**. El precio de cada artículo se redondeará antes del cálculo del total. Si hay más de uno del mismo artículo, cada uno de ellos se redondeará por separado antes del cálculo.
  * **Redondear en cada línea**. Cada línea de artículos se redondeará antes del cálculo del total.  Si existieran más de uno del mismo artículo, el redondeo se realizará sobre su valor total.
  * **Redondea sobre el total**. El redondeo sólo se realizará en el cálculo final, después de que se hayan sumado los valores de todos los elementos.
* **Número de decimales**. Puede elegir el número de decimales al que se debe redondear el valor. Por ejemplo, si elige "3", 42.333333333 se convierte en 42.334.
* **Mostrar marcas y proveedores**.  Habilite las páginas de proveedores y marcas en su front office incluso cuando sus respectivos módulos estén deshabilitados.
* **Mostrar los más vendidos**. Habilite las páginas de los más vendidos en su front office incluso cuando el módulo "Productos más vendidos" esté deshabilitado.
* **Habilitar multitienda**. Esta pequeña opción tiene implicaciones importantes: convierte la instalación de PrestaShop en una única tienda en una instalación de varias tiendas. Esto le brinda acceso a la nueva página "Multitienda" en el menú "Parámetros avanzados", y cada página de administración se puede contextualizar para aplicar su configuración a todas las tiendas, a un grupo específico de tiendas o a una sola tienda.\
  Puede leer más sobre la función multitienda de PrestaShop leyendo el capítulo "Gestión de varias tiendas" de esta guía.
* **Actividad de la tienda principal**. Es posible que haya configurado la actividad de la tienda incorrecta al instalar PrestaShop. Puedes elegir la actividad correcta aquí.\
  \
  ![](<../../../.gitbook/assets/51839963 (4) (4) (2).png>)

# Facturas

Cada vez que se valida un pedido de tu tienda, se envía una factura al cliente. Esta página le permite configurar sus facturas y le permite descargar una selección de facturas.

## Generar factura en archivos PDF <a href="#invoices-generateinvoiceinpdffiles" id="invoices-generateinvoiceinpdffiles"></a>

Puedes descargar las facturas de un solo pedido desde la página del pedido. La página "Facturas" le permite descargar una selección de facturas de pedidos anteriores en formato PDF, todo al mismo tiempo (en el mismo archivo PDF).

![](<../../.gitbook/assets/51839182 (3) (3) (2).png>)

Puede obtener un archivo PDF que contenga varias facturas en función de dos criterios principales:

* **Por fecha**. Muy útil cuando necesitas imprimir todas las facturas de un mes o trimestre determinado. Seleccione la fecha de inicio y finalización y haga clic en el botón "Generar archivo PDF por fecha" en la barra superior.
* **Por estado del pedido**. Imprescindible cuando necesita imprimir con precisión qué pedidos se cancelan, reembolsan o se encuentran en espera. PrestaShop indica de forma útil entre paréntesis el número de facturas vinculadas a cada estado.

En ambos casos, las facturas se generan en un único archivo PDF, cada uno con sus propias páginas. No puede obtener un único archivo PDF para cada factura del período o estado determinado utilizando esta página.

Si desea personalizar el aspecto de las facturas de su tienda, debe cambiar sus archivos de plantilla.

Los archivos de plantilla PDF se encuentran en la carpeta `/pdf`. Abre el archivo `invoice.tpl` y edítalo a tu gusto: es un archivo HTML con etiquetas Smarty.

Cuando sus clientes soliciten sus facturas, puede redirigirlos a la sección "Historial de pedidos" de sus cuentas de usuario, que mantiene todas sus facturas disponibles para ellos.

## Opciones de factura <a href="#invoices-invoiceoptions" id="invoices-invoiceoptions"></a>

Puede elegir si las facturas deben estar disponibles para sus clientes tan pronto como se realiza el pedido, así como el prefijo de la factura y el número de factura que desea que aparezcan en la versión impresa de la factura. Esta función puede ayudarle a simplificar la gestión de su cuenta.

![](<../../.gitbook/assets/51839180 (3) (7) (7).png>)

* **Habilitar facturas**. Cuando está deshabilitado, su cliente no recibirá una factura después de su compra. Usted será responsable de manejar las facturas, si sus clientes lo solicitan.
* **Habilitar desglose de impuestos**. Cuando está habilitado, la factura enumera todos los impuestos que se aplicaron al pedido, en lugar de solo un porcentaje.
* **Habilitar imagen del producto**. Cuando esté habilitado, agregará la imagen del producto junto al nombre del producto en la factura.
* **Prefijo de factura**. Por defecto, PrestaShop tiene prefijos de factura adaptados al idioma: "IN" en inglés, "FA" en francés (para "_facture_"), "CU" en español (para "_cuenta_"), etc. Puedes elegir tener códigos de idioma en su lugar: "EN", "FR", "SP", etc. Por supuesto, también puedes elegir tener un único prefijo para cada idioma, o no tener ningún prefijo.\
  PrestaShop generará entonces el número de factura según su configuración: "#IN000001", "#FA000002", etc.
* **Agregue el año actual al número de factura**. Además del número de factura y el prefijo, en el número de factura también aparecerá el año.
* **Restablecer número progresivo de factura a principios de año**. Al comienzo de un nuevo año, el número de factura se restablece para comenzar nuevamente en 0.
* **Posición de la fecha del año**. Elija dónde mostrar la fecha del año en el número de factura, antes o después del número progresivo.
* **Número de factura**. Si su empresa ya tenía pedidos y facturas antes de comenzar a usar PrestaShop, puede usar esta opción para comenzar su número de factura desde un número mayor.
* **Texto libre legal.** Este campo le permite agregar contenido adicional a la factura, en caso de que su legislación local requiera que muestre información adicional. En la factura, aparecerá debajo del resumen de métodos de pago. Por supuesto, podrás utilizar este texto libre para mostrar cualquier texto que consideres necesario.
* **Texto de pie de página**. Puede usar esto para tener un texto personalizado en la parte inferior de todas sus facturas. El texto aparecerá debajo del nombre de tu tienda en la factura.
* **Modelo de factura**. Dependiendo de sus temas, es posible que pueda utilizar más de un estilo de factura. Pruébalos con un pedido falso para elegir el que prefieras. Si sabes codificar en HTML, puedes agregar tus propios modelos de factura o editar los existentes: se encuentran en la carpeta `/pdf/` de tu instalación de PrestaShop.
* **Utilice el disco como caché para facturas en PDF**. Puede optar por almacenar las facturas generadas en el disco del servidor de PrestaShop en lugar de en la caché del servidor. Si bien ahorra uso de memoria, ralentiza la generación del PDF, así que utilícelo con conocimiento de causa.

No olvides guardar tus cambios.

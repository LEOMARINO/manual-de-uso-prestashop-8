# Impuestos

Esta página enumera todos los impuestos ya creados en su tienda. También le permite crear nuevos impuestos si es necesario. Para cada impuesto, verá su nombre, tasa y estado. Puede activarlo o desactivarlo directamente desde la lista de impuestos, o puede editar o eliminar un impuesto usando el botón de acción en el extremo derecho.

![](<../../../.gitbook/assets/64225614 (4) (4) (3).png>)

## Opciones de impuestos <a href="#taxes-en-taxoptions" id="taxes-en-taxoptions"></a>

En la parte inferior de la página se encuentra la sección "Opciones de impuestos". Estas opciones se aplican a toda la tienda y a todos los pedidos.

![](<../../../.gitbook/assets/64225615 (4) (4) (2).png>)

* **Habilitar impuestos**. Si en cada compra se incluyen o no impuestos.
* **Mostrar impuestos en el carrito de compras**. Quizás prefieras que el cliente no esté al tanto de los impuestos que se aplican al pedido. En ese caso, deshabilite esta opción.
* **Residencia en**. El cliente puede optar por que el producto no se entregue en la misma dirección a la que debe enviarse la factura del pedido. Esto puede tener un gran impacto en los impuestos. De forma predeterminada, PrestaShop basa sus tipos impositivos en la dirección de entrega, pero usted puede elegir que se basen en la dirección de facturación.
* **Usa ecotasa**. El ecoimpuesto se refiere a "impuestos destinados a promover actividades ecológicamente sostenibles a través de incentivos económicos". Se trata de un impuesto que pagan los comerciantes para "sentir la carga social de sus acciones". Obtenga más información sobre la ecotasa en [Wikipedia](http://en.wikipedia.org/wiki/Ecotax). Una vez que haya habilitado el uso de ecotax, la página administrativa de todos sus productos contará con un campo "Ecotax (tax incl.)" en su pestaña "Precios". Debes completar ese campo con el valor exacto del impuesto, que depende de las leyes fiscales de tu país (it is probably based on the product's price).
* **Ecotasa**. Si has habilitado el uso de la ecotasa, aparecerá un nuevo campo con una lista desplegable. De hecho, dependiendo de las leyes fiscales de su país, el ecoimpuesto podría estar sujeto al IVA, de ahí que este campo le permita elegir el tipo de IVA asociado. &#x20;

Si decides habilitar la ecotasa después de haber agregado productos, tendrás que editarlos todos para establecer el impuesto correctamente para cada producto. Tenga en cuenta que si ya ha configurado ecoimpuestos para sus productos y elige desactivar los ecoimpuestos, todos sus productos perderán su configuración de ecoimpuestos. Volver a habilitar la ecotasa supondrá tener que volver a fijar las ecotasas de todos tus productos. La ecotasa también le aparecerá al cliente, en la página del producto.

## Agregando un nuevo impuesto <a href="#taxes-en-addinganewtax" id="taxes-en-addinganewtax"></a>

Agregar un nuevo impuesto es muy fácil porque las reglas tributarias eliminan toda la carga de tener que especificar los países donde se aplica el impuesto. Por tanto, el formulario de creación de impuestos es muy breve:

* **Nombre**. Sea muy específico, ya que esto le ayudará a crear normas fiscales más rápidamente. Recomendamos agregar recordatorios dentro del nombre, como el país/grupo/zona al que se aplica el impuesto y su tasa. Le ayuda a recordar qué impuesto se utilizará en una regla fiscal.
* **Tasa**. La tarifa exacta, en formato XX.XX.
* **Permitir**. Puede desactivar y volver a activar un impuesto en cualquier momento.

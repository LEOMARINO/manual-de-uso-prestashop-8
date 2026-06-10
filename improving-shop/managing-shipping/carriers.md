# Carriers

Debes tener transportistas agregados a tu instalación de PrestaShop, es decir, un indicador claro de quién entregará tus productos. Puede que sea solo usted o su tienda (for instance if you are selling downloadable products, or only work locally), pero tan pronto como envíe paquetes utilizando sellos y una entrega de terceros, como su servicio postal local, FedEx, UPS y demás, deberá agregar sus detalles a la base de datos de su tienda. Esto permitirá a sus clientes elegir mejor qué transportista utilizar, según sus rangos de entrega, tarifas y fechas.

La página "Operadores" le presenta una lista de todos sus proveedores actuales. Desde allí, puede cambiar directamente su estado, indicar por qué el envío es gratuito o no y cambiar su posición cuando se presenta a los clientes.

![](<../../.gitbook/assets/51839919 (4) (2) (3).png>)

De forma predeterminada, tiene dos operadores en su base de datos:

* Tu propia tienda: Representa tu tienda física, donde supuestamente los clientes pueden venir a recoger sus productos ellos mismos. No tiene rango de precios ni rango de peso establecido.
* "Mi transportista": Este es un transportista de muestra y no debe usarse en producción. Tiene un rango de precio (from $0 to $10,000) y un rango de peso (from 0 kg to 10,000 kg).

Depende de usted eliminar estos operadores predeterminados y agregar otros nuevos para sus clientes. Como mínimo, deberás editar el operador "Mi operador" y sustituir sus datos por los de un operador real: nombre, detalles y rangos. Le recomendamos que elimine el transportista "Mi transportista" y que utilice un módulo de transportista existente para registrar a su socio de envío.

Vídeo: 6 consejos para crear una política de entrega que atraiga clientes y fidelice

[![](<../../.gitbook/assets/51839792 (7) (7) (2).png>)](https://www.youtube.com/watch?v=QhTU\_eSrm7o\&list=PLyZYn1MMU7-xT-L\_zUyGnRBJmAuP6uc-c\&index=26)

## Agregar un nuevo transportista usando el Asistente de transportista <a href="#carriers-addinganewcarrierusingthecarrierwizard" id="carriers-addinganewcarrierusingthecarrierwizard"></a>

Si no puede encontrar un módulo para su socio de envío en los módulos nativos, debe registrar su transportista usted mismo utilizando el Asistente de transportistas: haga clic en "Agregar nuevo transportista" para abrir esta herramienta.

En esta sección, vamos a crear un transportista completo, de la A a la Z, utilizando el Asistente de transportistas. Puedes crear tantos transportistas como desees.\
Si un transportista tiene diferentes servicios de envío, debes crear un transportista para cada una de tus necesidades y diferenciarlos con sus nombres:

Muchos de los detalles solicitados en los formularios de software deben ser proporcionados por sus proveedores una vez que haya configurado una cuenta o tenga un contrato con ellos directamente. Consulte con ellos para asegurarse de que todo esté configurado correctamente.

Para crear un nuevo operador, haga clic en el botón "Agregar nuevo" en la página "Transportistas". Esto abrirá el Asistente para transportistas en el primero de sus cuatro paneles.

### Panel 1: Configuración general <a href="#carriers-panel1-generalsettings" id="carriers-panel1-generalsettings"></a>

Aquí es donde se describe el transportista, dando información que el cliente necesitará para reconocer y elegir el transportista que prefiere.

![](<../../.gitbook/assets/51839920 (4) (4) (3).png>)

Examinemos toda la información que necesita ingresar:

* **Nombre del operador**. El nombre es público, por lo que deberás utilizar el nombre oficial. Si has creado un transportista por servicio de envío a partir de un único transportista, el nombre te ayudará a diferenciarlos. \
  También puedes agregar una descripción del servicio. Por ejemplo, puede completar "PrestaShipping - 500 lbs y más".
* **Tiempo de tránsito**. El tiempo estimado que le toma a este transportista entregar sus productos está escrito en un lenguaje sencillo. Esto se muestra a los clientes durante el proceso de pago. Les ayudará a seleccionar su transportista según el tiempo que estén dispuestos a esperar para recibir su envío. Los clientes a menudo pueden aceptar pagar más por un operador más rápido.\
  Debes completar este campo en todos los idiomas disponibles, especialmente el predeterminado.
* **Grado de velocidad**. Dado que el campo "Tiempo de tránsito" puede contener cualquier texto, no se puede utilizar para comparar los tiempos de tránsito de los transportistas. La configuración "Calificación de velocidad" le permite darle al transportista una calificación, desde 0 (very slow) hasta 9 (very fast). Luego, esto se utiliza para clasificar a los transportistas por su grado de velocidad y ayudar a los clientes a elegir el que prefieren.
* **Logo**. Tener un logotipo ayuda a los clientes a elegir entre diferentes operadores más fácilmente. El tamaño de su imagen cambiará automáticamente para que quepa en la página de pago.\
  El logotipo aparecerá en cada panel del Asistente de transportista, como recordatorio de qué transportista está editando/creando.
* **URL de seguimiento**. Este campo debe completarse con la URL de seguimiento proporcionada por su operador (if there exists one). Indica "@" donde aparecerá el número de seguimiento. Por ejemplo, el servicio postal francés (La Poste) ofrece esta URL: [`http://www.colissimo.fr/portail_colissimo/suivreResultat.do?parcelnumber=@`](http://www.colissimo.fr/portail\_colissimo/suivreResultat.do?parcelnumber=@). Cuando los clientes finalicen su compra, recibirán esa URL con la "@" reemplazada por el número de seguimiento proporcionado por el transportista, lo que permitirá hacer clic en ese enlace y ver dónde se encuentra el proceso de entrega.

Haga clic en "Siguiente" para llegar al segundo panel.

### Panel 2: Lugares y costos de envío <a href="#carriers-panel2-shippinglocationsandcosts" id="carriers-panel2-shippinglocationsandcosts"></a>

![](<../../.gitbook/assets/51839921 (4) (4) (3).png>)

Primero, este panel presenta algunas configuraciones:

* **Agregue costos de manejo**. Incluya o excluya los costos de envío y manipulación en el precio de este transportista, según lo establecido en la página "Preferencias" ("Handling charges").
* **Envío gratis**. Si está habilitado, no podrá indicar precios de envío.\
  Si está deshabilitado, podrá editar los rangos y los costos por país en el siguiente formulario.
* **Facturación**. Al facturar al cliente, el software PrestaShop puede aplicar uno de dos comportamientos, que debe configurar dependiendo de cómo su operador maneje la facturación (so make sure to check their documentation about this):\

  * **Según precio total**. La facturación depende del precio total del pedido.
  * **Según peso total**. La facturación depende del peso total del pedido.
* **Impuesto**. Indica si este transportista requiere un impuesto local para realizar la entrega y, de ser así, cuál. El impuesto ya debe existir en el software (which can be done in the "Taxes" page of the "International" menu).
* **Comportamiento fuera de rango**. En caso de que el transportista elegido no haya fijado ningún coste de envío para la zona o peso requerido, podrás indicar cómo debe reaccionar el software. Tienes dos opciones:
  * **Aplica el costo del rango más alto definido**. Este tomará la gama más costosa y aplicará sus condiciones.
  * **Desactivar operador**. No se sugerirá este transportista, ya que probablemente no pueda entregar este pedido.

Luego viene la parte importante: la creación de la gama del transportista. Este es un paso muy importante, ya que el software necesita esta información para presentar al cliente los transportistas que realmente pueden entregar el paquete solicitado. De hecho, dependiendo del precio total o del peso total del pedido, algunas opciones de transportista no estarán disponibles mientras que otras solo aparecerán por un valor determinado. Debes ser muy preciso al completar estos valores, y preferiblemente los sugeridos por la documentación de cada transportista.

De aquí es de donde toma su nombre todo el Carrier Wizard. Aquí, creará los rangos de precio o peso de su operador (depending on your choice for the "Billing" option above), un rango tras otro, aplicando sus precios para cada zona a lo largo del camino.

Las zonas deben haber sido definidas previamente. Para ello, vaya a la página "Ubicaciones" en el menú "Internacional".

Para cada rango, sólo necesitas un par de pasos:

1.  **Fija los límites superior e inferior del rango que estás creando**. Dependiendo de la opción "Facturación", se mostrará "Se aplicará cuando el precio sea" o "Se aplicará cuando el peso sea" para el límite inferior, y "Se aplicará cuando el precio sea" o "Se aplicará cuando el peso sea" para el límite superior.

    Tenga en cuenta que el límite inferior es (>=) inclusivo, mientras que el límite superior es (<) exclusivo. Esto significa que el límite superior de un rango puede tener el mismo valor que el valor inferior del siguiente rango, ya que ambos no se superpondrán.
2. **Rellena los precios**. Tan pronto como se completen los límites superior e inferior, se podrá editar el campo "Todos". Este es un campo especial: cualquier valor que ingreses en él se copiará en el campo para todas las zonas geográficas disponibles, sin ninguna acción por tu parte. Para editarlo, marque la casilla de verificación y luego ingrese su valor. Luego podrá editar los valores de cada campo de zona por separado.\
   Marque la casilla de verificación para cada zona a la que el transportista realiza entregas en este rango. Si este transportista no realiza entregas en una zona geográfica determinada para este rango actual, asegúrese de desmarcar su casilla de verificación.
3. **Crea el rango**. Para crear otro rango, haga clic en el botón "Agregar nuevo rango". Esto agregará una nueva columna de campos de zona. Comience de nuevo fijando los límites superior e inferior de este rango y luego complete los precios por zona.

Las unidades de peso y precio son las predeterminadas que se configuran automáticamente durante la instalación del software y las que utilizan sus productos. Puede cambiar estas unidades en la página "Localización" del menú "Internacional".

Haga clic en "Siguiente" para llegar al tercer panel.

### Panel 3: Tamaño, peso y acceso al grupo <a href="#carriers-panel3-size-weightandgroupaccess" id="carriers-panel3-size-weightandgroupaccess"></a>

![](<../../.gitbook/assets/51839922 (4) (4) (1).png>)

This panel presents two sets of options:

* **Alto/ancho/profundidad/peso máximo del paquete**. Ahora podrás indicar la altura y el peso mínimo y máximo del paquete, que son una parte esencial a la hora de elegir un transportista de paquetes. El valor es utilizar las unidades de peso y dimensión predeterminadas, tal como se establece en la página "Localización" del menú "Internacional".
* **Acceso grupal**. Es posible que desee que solo algunos grupos de usuarios puedan utilizar un operador. Esta opción sirve para este propósito.

Haga clic en "Siguiente" para llegar al cuarto y último panel.

### Panel 4: Summary <a href="#carriers-panel4-summary" id="carriers-panel4-summary"></a>

![](<../../.gitbook/assets/51839923 (4) (4) (1).png>)

Este último panel le brinda una descripción general de su configuración para este operador.

Si algunas configuraciones son incorrectas, puede volver a cualquier panel anterior usando el botón "Anterior" o haciendo clic directamente en la pestaña del panel. \
Si desea guardar este operador como borrador por ahora y volver a él más tarde, desactive el operador usando la opción "Activado" en la parte inferior de este panel final. \
De cualquier manera, haga clic en el botón "Finalizar" para guardar su trabajo y crear el transportista.

Cuando se utiliza el modo multitienda, hay otro panel disponible y el orden de los paneles cambia ligeramente:

1. Configuraciones generales
2. **MultiStore**
3. Lugares y costos de envío
4. Tamaño, peso y acceso grupal.
5. Summary

Todos los paneles son como se describe arriba. El nuevo, "MultiStore", le permite limitar este operador a una selección de sus tiendas.

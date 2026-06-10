# Reglas fiscales

Las normas fiscales establecen que los impuestos sólo se aplican a países seleccionados.

De forma predeterminada en PrestaShop, se aplica un impuesto a todos los países/estados/zonas. Para aplicar una tasa impositiva específica para un solo país o un conjunto de países (and not some others), debe crear una regla impositiva. Luego, la regla fiscal se aplica por producto, durante la creación del producto ("Pricing" tab).

No se puede aplicar directamente un impuesto a un producto; sólo puedes aplicar reglas fiscales. Por lo tanto, primero debe registrar todos los impuestos relevantes, luego crear una regla impositiva para ese impuesto a fin de especificar los países donde se aplica el impuesto y, finalmente, establecer la regla impositiva para el producto.

Ya existen algunos ejemplos de reglas fiscales, que dependen del país que haya elegido para su tienda durante la instalación de PrestaShop. Las reglas impositivas se establecen para cada impuesto: en realidad, las reglas sirven como una especie de filtro de país, limitando el uso de ese impuesto a un conjunto específico de países.

![](<../../../.gitbook/assets/51839958 (4) (4) (4).png>)

Debería editar un par de las reglas presentadas para comprender mejor cómo se pueden establecer las reglas impositivas.

## Agregar una nueva regla fiscal <a href="#taxrules-addinganewtaxrule" id="taxrules-addinganewtaxrule"></a>

Puede agregar tantas reglas fiscales como necesite a su instalación de PrestaShop. No sólo eso, sino que debes asegurarte de que todas las normas fiscales necesarias estén registradas en tu tienda.

La creación de una nueva regla fiscal se realiza en dos pasos:

1. Cree la regla fiscal:
   * Haga clic en el botón "Agregar nuevo grupo de reglas fiscales".
   * En el formulario que aparece, nombre la regla. Utilice un nombre revelador: utilice el código de país de la norma fiscal, su nombre, tal vez incluso su tasa, para volver a encontrarlo fácilmente. Si PrestaShop ya tiene normas fiscales para el país de destino, utilice su nombre como inspiración para tener cierta coherencia.\
     \
     ![](<../../../.gitbook/assets/51839959 (1) (3).png>)\
     \

   * Seleccione si la regla debe habilitarse desde el principio o no. Puede habilitarlo más tarde si es necesario.
   * Haga clic en el botón "Guardar y permanecer". La página se recarga, con un encabezado de tabla en la parte inferior y un nuevo formulario.\
     \

2. Especifique el país y los comportamientos:
   * Complete los campos de la sección "Nueva regla fiscal":\
     \


![](<../../../.gitbook/assets/51839960 (4) (4) (1).png>)

*
  *
    * **País**. El país de destino de la regla que está creando.
      * _Estado._ Algunos países tienen estados federales registrados en PrestaShop (see the "States" page, under the "Localization" menu). En ese caso, puedes hacer que el impuesto sea aún más específico o elegir que se aplique a todo el país. Puede seleccionar más de un estado presionando la tecla Ctrl al hacer clic en los nombres de los estados.
    * **Rango de código postal**. Ya sea que el país tenga estados registrados o no, puede especificar aún más la aplicación de impuestos utilizando el código postal del cliente. Este campo le permite definir códigos postales en los que se debe aplicar el impuesto: ingrese un solo código postal o defina un rango usando el guión. Por ejemplo, utilice "75000-75012" para crear un rango para todos los códigos postales entre estos dos.
    * **Comportamiento**. Es posible que algunos clientes tengan una dirección que coincida con más de una de sus normas fiscales. En ese caso, puedes elegir cómo debe comportarse esta regla fiscal:
      * _Este impuesto únicamente_. Se aplicará únicamente este impuesto, no ninguno de los demás impuestos correspondientes.
      * _Combinar._ Combinar impuestos. Por ejemplo: 100€ + (10% + 5% => 15%) => 115€.
      * _Uno tras otro._ Aplicar los impuestos uno tras otro. Por ejemplo: 100€ + 10% => 110€ + 5% => 115,5€.
    * **Impuesto.** El impuesto que se utilizará para esta regla fiscal. Ese impuesto ya debe estar registrado en PrestaShop. De lo contrario: elija "Sin impuestos", deshabilite la regla impositiva, guárdela, vaya a crear un impuesto en la página "Impuestos" y luego regrese para editar la regla impositiva.
    * **Descripción**. Puede agregar un texto breve como recordatorio de por qué existe esta norma fiscal para este país.
  * Haga clic en "Guardar y permanecer". El país se agrega a la siguiente tabla y puede comenzar a agregar otro país a este grupo de reglas impositivas haciendo clic en "Agregar una nueva regla impositiva".

Tenga en cuenta que la tarifa predeterminada aplicada a sus productos se basará en el país predeterminado de su tienda.

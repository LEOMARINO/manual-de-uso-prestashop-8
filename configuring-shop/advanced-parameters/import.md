# Import

La página de importación le permite completar fácilmente su catálogo de productos cuando tiene una gran cantidad de productos, o importar datos que exportó y convirtió desde otra herramienta de comercio electrónico.

Históricamente, las importaciones se realizaban mediante archivos .CSV en PrestaShop. Desde la versión 1.7, se admiten otros formatos de archivo, como .xls, .xlsx, .xlst, .ods y .ots.

CSV es un acrónimo de "valores separados por comas". Es un formato de texto plano popular cuando es necesario importar, exportar o simplemente almacenar datos en un formato no propietario. Casi todas las herramientas de manejo de datos admiten el formato CSV, en varias encarnaciones. Puede leer más sobre el formato CSV en Wikipedia: [http://en.wikipedia.org/wiki/Comma-separated\_values](http://en.wikipedia.org/wiki/Comma-separated\_values).

![](<../../.gitbook/assets/51840005 (3) (3).png>)

El proceso de importación requiere preparación y comienza con un formulario compuesto por configuraciones primarias:

* **¿Qué quieres importar?**. Elija en la lista desplegable qué tipo de entidad desea importar a su tienda. Los "Campos disponibles" a la derecha se actualizan cuando elige una entidad, para que sepa el tipo de datos que debe contener su archivo de importación.\
  PrestaShop le permite importar los siguientes tipos de datos:
  * Categories,
  * productos,
  * Combinations,
  * Clientes,
  * Addresses,
  * Brands,
  * Suppliers,
  * Aliases,
  * Órdenes de suministro (if Advanced Stock Management is enabled),
  * Detalles del pedido de suministro (if Advanced Stock Management is enabled).
  * Contactos de la tienda
*   **Seleccione un archivo para importar**. Puede importar más de un archivo a la vez, pero asegúrese de que todos contengan el mismo tipo de datos. Puede cargar archivos desde su computadora o elegir archivos que ya estén disponibles en su FTP o en su historial.

    Puede descargar archivos de muestra para cada tipo de datos desde la sección "Descargar archivos CSV de muestra" a la derecha. Esto le ayuda a comparar estos archivos de muestra con sus propios archivos, para que pueda asegurarse de que los archivos que está a punto de importar estén realmente listos para importarse a PrestaShop. En realidad, estos archivos se almacenan en la carpeta `/docs/csv_import` de su instalación de PrestaShop.
* **Idioma del archivo**. Los datos solo se pueden importar para un único idioma a la vez. Si sus datos existen en más de un idioma, debe dividirlos en tantos archivos como sea posible.
* **Separador de campos**. No todos los archivos CSV usan comas para separar sus valores: algunos usan tabulaciones, otros punto y coma, etc. Puedes indicar qué usan tus archivos en este campo.
* **Separador de valores múltiples**. Cuando un atributo puede admitir más de un valor, estos valores deben separarse con un separador específico. Después de revisar sus archivos, indique aquí su separador.
* **Eliminar todo \_\_\_ antes de importar**. Esta opción borrará todas las entradas previamente existentes del tipo de datos que está importando. De esta forma empezarás desde cero.
* **Utilice la referencia del producto como clave**. Importación de productos únicamente. Puede optar por que PrestaShop determine la clave del producto o, en su lugar, utilizar la referencia del producto como ID. En este caso, asegúrese de que el archivo contenga referencias de todos sus productos importados.
* **Omitir la regeneración de miniaturas**. Importación de categorías y productos únicamente. Puede optar por que PrestaShop regenere las miniaturas vinculadas desde su archivo CSV (in the "Image URL" or "Image URLs" fields).
* **Forzar todos los números de identificación**. Puede conservar los ID importados o dejar que el importador los incremente automáticamente.
* **Enviar correo electrónico de notificación**. Si está importando archivos grandes, active esta opción para recibir un correo electrónico cuando se complete la importación.

Al cambiar la entidad que desea importar, la sección de la derecha, titulada "Campos disponibles", cambia para presentar los campos de datos esperados. Aunque la herramienta de importación le ayuda a hacer coincidir los campos de su archivo con los de PrestaShop, debe esforzarse por hacer que sus datos sean más fáciles de importar siguiendo el esquema de nombres y el orden de los campos presentados. Si no, la importación será más tediosa, pero no imposible.\
Algunos campos tienen una pequeña ventana emergente de información disponible (represented by an "i" logo), que puede mostrar al pasar el cursor del mouse sobre él. En su mayoría pertenecen a las funciones multitienda o de gestión avanzada de stock de PrestaShop. Asegúrese de leerlos todos para poder crear/editar mejor sus archivos de datos.

![](<../../.gitbook/assets/45580389 (4) (4).png>)

## Data format <a href="#import-dataformat" id="import-dataformat"></a>

El archivo de datos importado debe estar en un archivo de texto, utilizando un formato basado en CSV y la extensión de archivo `.csv` que lo acompaña. Recomendamos utilizar un punto y coma ";" como separador de campos. Si sus datos textuales (product description and such) contienen punto y coma, debe eliminarlos o elegir otro separador en la opción "Separador de campo".

Puede crear un archivo CSV utilizando cualquier editor de texto (we recommend Notepad++: [http://notepad-plus-plus.org/](http://notepad-plus-plus.org/)), pero le recomendamos que utilice un programa de hoja de cálculo y luego guarde su trabajo en formato CSV. El uso de un programa de hoja de cálculo le permite tener una comprensión más fácil y visual de sus datos, en comparación con el archivo de texto sin formato. Puede utilizar el Microsoft Excel comercial ([http://office.microsoft.com/en-us/excel/](http://office.microsoft.com/en-us/excel/) o el gratuito [OpenOffice.org](http://openoffice.org) [http://www.openoffice.org/](http://www.openoffice.org/) Calc.

Aquí hay un archivo de importación de muestra, con una lista de productos:

```
"Enabled";"Name";"Categories";"Price";"Tax rule ID";"Buying price";"On sale";"Reference";"Weight";"Quantity";"Short desc.";"Long desc";"Images URL"
1;"Test";"1,2,3";130;1;75;0;"PROD-TEST";"0.500";10;"'Tis a short desc.";"This is a long description.";"http://www.myprestashop/images/product1.gif"
0;"Test 02";"1,5";110;1;65;0;"PROD-TEST2";"0.500";10;"'Tis also a short desc.";"This is a long description too.";"http://www.myprestashop/images/product2.gif"
1;"Test 03";"4,5";150;1;85;0;"PROD-TEST3";"0.500";10;"'Tis a short desc. again";"This is also a long description.";"http://www.myprestashop/images/product3.gif"
```

Tenga en cuenta que estos son sólo archivos de muestra normales creados para esta demostración; intencionalmente no está optimizado para la importación de PrestaShop. Si necesita un archivo de muestra del que pueda aprender, utilice los que puede descargar desde "Descargar archivos CSV de muestra".

La primera fila debe ser un nombre descriptivo para la columna de datos (you will be able to skip it during the import process). Debe haber el mismo número de columnas en cada fila.

Debes recordar que:

* La columna de precio utilizará la moneda predeterminada de su tienda.
* Las categorías deben especificarse utilizando sus ID existentes (so you should have imported them first) y separadas con una coma (by default).
* La URL de la imagen debe ser un enlace absoluto. En otras palabras, debe ser el enlace que se puede utilizar en un navegador web para mostrar la imagen. Por ejemplo: [http://www.myprestashop/images/productXXX.gif](http://www.myprestashop/images/productXXX.gif).
* La codificación de caracteres del archivo debe ser UTF-8. De lo contrario, utilice ISO-8859-1.
* Las fechas utilizan el formato ISO 8601, sin un designador de zona horaria (the time zone is the one for your store): `2013-06-21 15:07:27`.

## Subiendo el archivo <a href="#import-uploadingthefile" id="import-uploadingthefile"></a>

Una vez que tengas todos tus datos en formato CSV, podrás subirlos a la base de datos de tu tienda usando el formulario de esta página.

Tienes dos formas de registrar archivos para importar:

* Usando su navegador: haga clic en el botón "Cargar", busque su archivo y luego valídelo. Haga esto tantas veces como sea necesario para enumerar todos sus archivos de importación.
* Usando tu cliente FTP: sube los archivos en la carpeta `/admin-dev/import` de tu instalación de PrestaShop. Vuelva a cargar la página de importación: el botón "Elegir del historial/FTP" ahora debería indicar un número. Haga clic en el botón para mostrar la lista de archivos disponibles (including the ones you previously uploaded using the browser), luego haga clic en el botón "Usar" para el archivo que desea importar.

Una vez que todos sus archivos estén listados en la sección "Seleccione un archivo para importar", puede continuar con el resto del formulario:

1. **Confirma el tipo de datos contenidos en tu archivo**, usando la lista desplegable denominada "¿Qué deseas importar?". Una vez que haya seleccionado el tipo de datos, la lista de campos disponibles aparece a la derecha, lo que le ayudará a refinar su archivo CSV, al menos en cuanto al orden de las columnas, lo que pronto resultará útil.
2. **Seleccione el idioma del contenido importado**. Si el idioma de destino no está disponible, primero debe instalarlo en la página "Traducciones" en el menú "Internacional".
3. **Seleccione los separadores**. Le sugerimos que deje los valores predeterminados ("field separator" with a semicolon "ZXQ0QXZ", "multiple value separators" with a comma "ZXQ1QXZ"). Pero obviamente, si su archivo CSV está creado de manera diferente, debe cambiar estos valores en consecuencia.
4. Si desea eliminar todos los productos de su catálogo antes de importarlos, seleccione la opción adecuada.
5. Una vez que haya realizado todas sus elecciones, haga clic en "Siguiente paso".

Todos los archivos de importación se cargan directamente en la subcarpeta `/import` de la carpeta de administración. Si el menú desplegable de archivos se llena demasiado, puede eliminar importaciones antiguas directamente utilizando su cliente FTP.

Al hacer clic en el botón "Siguiente paso", la página se recarga con la herramienta de mapeo de datos. Esta interfaz le ayuda a asignar las columnas de datos de su archivo con las requeridas por PrestaShop.

![](<../../.gitbook/assets/45580390 (4) (4).png>)

En esta tabla se presentan las filas de su archivo, colocadas debajo de columnas arbitrarias que coinciden con las necesidades de la base de datos de PrestaShop. Depende de usted asegurarse de que todas las columnas de su archivo CSV coincidan con el encabezado de columna correcto, utilizando el selector desplegable de cada encabezado, para importar su contenido correctamente.

For instance, with our sample file:

* **Primera columna**. Lo marcamos como "Habilitado", PrestaShop presenta "ID" como encabezado. Haga clic en el menú desplegable del encabezado y seleccione "Activo (0/1)".
* **Segunda columna**. Marcado como "Nombre", el encabezado indica "Activo (0/1)". Cambiemos el encabezado por "Nombre \*".
* **Tercera columna**. Entiendes la idea...

La pantalla no puede contener más de 6 columnas, así que haga clic en los botones ">" y "<" para ver las otras columnas y asegúrese de que todas coincidan correctamente.

En nuestro ejemplo, utilizamos la primera fila para los nombres de las columnas. Como no queremos que se importen, ingrese "1" en el campo de texto "Filas para omitir".

Una vez que haya terminado de hacer coincidir sus columnas, haga clic en el botón "Importar" (bottom right-hand corner of the screen) y PrestaShop iniciará el proceso de importación. Se abrirá una ventana emergente para mostrarle el progreso de la importación.

Cuando finalice el proceso, deberá indicar "100% validado" y "100% importado". Al cerrar esta ventana emergente, se le enviará a la pantalla principal. Si ocurrió un error durante la importación, verá un aviso de todos los problemas encontrados. En este segundo caso, deberás revisar tu expediente y asegurarte de corregir todo.

### Mapping configurations <a href="#import-mappingconfigurations" id="import-mappingconfigurations"></a>

El proceso de mapeo puede ser una tarea tediosa si no puedes personalizar el orden de las columnas de tu archivo de acuerdo con el utilizado por el importador de PrestaShop, y más aún si tienes que hacerlo repetida o frecuentemente. Es por eso que PrestaShop incluye una pequeña herramienta para guardar el orden de mapeo actual que has configurado usando todos los selectores desplegables de encabezados.

![](<../../.gitbook/assets/23789871 (1) (2).png>)

La herramienta es un campo simple en la parte superior de la herramienta de coincidencia. Puedes realizar las tres acciones básicas (only one if there is no mapping configuration saved yet):

* **Ahorro**. Ingrese un nombre descriptivo en el campo y haga clic en "Guardar". La interfaz se actualiza para presentar la configuración guardada en su lista desplegable.
* **Cargando**. Seleccione una configuración de mapeo en la lista desplegable y haga clic en "Cargar".
* **Eliminando**. Seleccione una configuración de asignación en la lista desplegable y haga clic en "Eliminar".

### Importing Features using Excel <a href="#import-importingfeaturesusingexcel" id="import-importingfeaturesusingexcel"></a>

La importación de Excel es especial porque no puede configurar el campo o delimitadores de valores múltiples. Por eso, se debe prestar especial atención a los campos "irregulares" (i.e. fields which are not straightforward text fields and which have several variables). El campo/columna Características en Importación de producto es uno de estos campos irregulares.

El formato de la columna Característica se divide en 4 “partes”, cada una separada por dos puntos: **nombre de la característica:valor:posición:valor personalizado**

Para agregar varias funciones, separe los "paquetes" de funciones mediante comas, p. **nombre de característica1:valor1:posición1:valor personalizado2,nombre de característica2:valor2:posición2:valor personalizado2,nombre de característica3:valor3:posición3:valor personalizado3** etc.

Se permiten espacios en cada “parte”, pero no puede usar dos puntos (:) o comas (,), ya que son los delimitadores de parte y valor respectivamente y siempre se interpretarán como tales. Puede tener partes vacías, por ejemplo, si desea mantener vacía la parte de “valor”. Simplemente use dos puntos para omitir la parte. P.ej. Fecha de origen::1:1

La descripción de cada parte es la siguiente:

**nombre de característica:** El nombre de la característica. Si se trata de un valor (non-customized) seleccionable, debe ser exactamente como aparece en Catálogo > Características. P.ej. Ingredientes\


**valor**: el valor de la característica. Si se trata de un valor no personalizado, debe ser uno de los valores existentes en Catálogo > Características; de lo contrario, Prestashop agregará esos valores a la lista de valores.

**posición:** La posición de visualización de la característica en relación con otras características, comenzando en 1.\


**valor personalizado:** 1 (for yes) o 0 (for no). Un valor personalizado es aquel que no se puede seleccionar de una lista de valores predefinidos en la pantalla Catálogo > Funciones. Utilice 0 si ha definido una lista de valores seleccionables en el backend.

Si establece el valor personalizado en 0 e ingresa un nombre de característica o un valor que NO existe, la característica y/o el valor se agregarán por usted.

Si está importando un archivo que NO es su idioma predeterminado (i.e. a translation file), no incluya ninguna característica predefinida (i.e. customizedvalue is 0) ya que esto creará una nueva característica duplicada. Las traducciones de funciones predefinidas deben realizarse una vez en el backend a través de Catálogo > Funciones. Para idiomas no predeterminados, agregue solo funciones de valor personalizadas.

\
_También escrito con la valiosa contribución de Fadi H. Rezq_\
\

# Translations

Las traducciones oficiales de PrestaShop se obtienen de [Crowdin](https://crowdin.com/project/prestashop-official), una plataforma de gestión de localización en la que una comunidad de traductores voluntarios trabaja en nada menos que 80 proyectos de traducción.

{% hint style="success" %}
Si desea contribuir a la traducción de PrestaShop en su idioma, no dude en [unirse al proyecto](https://crowdin.com/project/prestashop-official).
{% endhint %}

En la página **Internacional > Traducciones**, podrás adaptar estas traducciones oficiales a tus necesidades. Por ejemplo, puedes cambiar la redacción elegida por los traductores por algo menos formal y personalizar el texto para que se adapte mejor a tu audiencia y hacer que tu tienda sea aún más única.

## Seleccionar el tipo de traducciones a modificar

Translations have been organized into 5 sections, depending on where strings appear on PrestaShop software.

![](<../../.gitbook/assets/Untitled (3).png>)

{% hint style="info" %}
_Una cadena es una serie de caracteres. Puede tener un carácter o contener varias palabras. Cuando se lanza una nueva versión menor o mayor de PrestaShop, todas las cadenas nuevas asociadas con esta versión se agregan a_ [_Crowdin_](https://crowdin.com/project/prestashop-official) _para ser traducidas por la comunidad._
{% endhint %}

* **Traducciones del back office:** las cadenas que son visibles para ti y tu equipo desde el panel de administración de tu tienda.
* **Traducciones de temas:** las cadenas visibles para tus clientes cuando navegan por tu tienda.
* **Traducciones de módulos instalados:** las cadenas presentes en un módulo. Sólo se enumerarán los módulos instalados.
* **Traducciones de correo electrónico:** las cadenas utilizadas en las plantillas de correo electrónico predeterminadas.
* **Otras traducciones:** las cadenas que aún no han sido identificadas como pertenecientes al tema o al back office.

Algunas categorías tienen una segunda lista desplegable para limitar la búsqueda.

Una vez realizada su selección, seleccione el idioma en el que desea modificar las traducciones y haga clic en "Modificar". Se abre una nueva página, donde puede buscar traducciones para modificar.

## Searching for a specific string

![](<../../.gitbook/assets/Untitled (4).png>)

En la parte superior izquierda de la página, hay una barra de búsqueda que le permite buscar una palabra o cadena específica.

También puedes encontrar rápidamente las cadenas sin traducir. En la parte superior derecha se muestra el número total de cadenas en la sección y el número de traducciones faltantes. Las categorías que contienen traducciones faltantes se muestran en rojo en el menú a la izquierda de la página.

## Browsing translations

![](<../../.gitbook/assets/Untitled (5).png>)

El menú a la izquierda de la página le permite explorar todas las cadenas de la categoría. Todas las cadenas están organizadas en lo que se denomina "dominios de traducción". Los dominios de traducción tienen como objetivo dar más contexto a los traductores, indicando dónde aparece la cadena en el software PrestaShop.

Para saber más sobre los dominios de traducción, consulte la página dedicada en la [Guía de estilo de contenido](https://zeroheight.com/80a6c5a61/v/latest/p/738e72-manage-translation-domains) del proyecto PrestaShop.

## Modifying translations

Para modificar una traducción existente o completar una que falta, edite o agregue texto en el campo justo debajo de la cadena y haga clic en uno de los botones "Guardar" en la parte superior o inferior de la página.

Algunas cadenas utilizan una sintaxis especial, con variables como `%s`, `%d`, `%product%`, etc.

Si una cadena contiene una variable, será reemplazada por un valor dinámico. Por ejemplo, en la cadena "El producto (ZXQ0QXZ) ya no está disponible", `%product%` se reemplazará con el nombre del producto. Por ejemplo, "El producto (Hummingbird printed t-shirt) ya no está disponible". Por lo tanto, siempre debes conservar las variables en tu traducción final.

Si una cadena contiene una variable, debes asegurarte de que el contenido de esa variable se coloque en el flujo correcto de la oración y evitar la traducción literal.

Los marcadores de posición numerados (ZXQ0QXZ, ZXQ1QXZ, etc.) permiten a los traductores reorganizar el orden de las variables en la cadena. Por ejemplo, "Este es un `%1$s` `%2$d`", donde `%1$s` significa "rojo" y `%2$d` significa "bolígrafo", podría traducirse como "C'est un `%2$s` `%1$s`" = "C'est un stylo rouge" en francés.

### Traducción de módulos&#x20;

Para traducir un módulo específico, seleccione la opción "Traducciones de módulos instalados" y el módulo deseado. Se abre una nueva página, con todas las cadenas del módulo.

Dependiendo del módulo que se seleccione, la interfaz podría ser diferente. Algunos módulos utilizan un sistema de traducción específico de la versión 1.7, mientras que otros todavía utilizan el sistema anterior de la versión 1.6. Al final, no cambia nada para ti, ya que podrás traducir tus módulos de la misma manera.

### Translating email templates

Hay dos formas de modificar la traducción de un correo electrónico:

* **Editar la versión HTML**

Con esta vista previa editable, lo que ves es lo que obtienes. Haga clic en el botón "Editar versión HTML". Podrás editar el texto y el diseño de tu correo electrónico. Cuando hayas terminado, guarda.&#x20;

* **Editar la versión de texto**

Puede editar la versión de texto de su correo electrónico directamente en el campo de texto.

{% hint style="info" %}
Asegúrese de mantener las variables (for example ZXQ0QXZ or ZXQ1QXZ) en sus traducciones. Serán reemplazados por el valor correcto cuando se envíe el correo electrónico.
{% endhint %}

![](<../../.gitbook/assets/image (49) (1).png>)

## Resetting translations

![](<../../.gitbook/assets/Untitled (6).png>)

Para reemplazar una traducción personalizada con la traducción oficial de PrestaShop, haga clic en el botón "Restablecer" al lado de la cadena. Si el campo está vacío, significa que no hay traducción oficial disponible en este momento. No dude en [contribuir al proyecto de traducción](https://crowdin.com/project/prestashop-official) si desea que su traducción esté disponible para otros comerciantes.

## Agregar o actualizar un idioma

![](<../../.gitbook/assets/Untitled (7).png>)

Para agregar o actualizar un idioma, seleccione el idioma que desee de la lista y haga clic en el botón "Agregar o actualizar un idioma". Si agregaste un nuevo idioma, puedes administrarlo en **Localización > Idiomas.**

## Exportar un idioma

![](<../../.gitbook/assets/image (47).png>)

Puedes crear tu propio paquete de idiomas usando esta herramienta, ya sea como una forma de hacer una copia de seguridad de tus traducciones o compartirlas.

Primero, seleccione el idioma en el que desea exportar las traducciones.

Luego, selecciona el tipo de traducciones que deseas:

* PrestaShop translations
* Theme translations
* Traducciones de módulos instalados

Cada categoría tiene una segunda lista desplegable o casillas de verificación para limitar su selección.

Una vez que haya terminado, haga clic en el botón "Exportar".

## Copiar traducciones de un idioma a otro

![](<../../.gitbook/assets/image (50) (1).png>)

Puede copiar el contenido de un idioma a otro. Esto es especialmente útil cuando deseas reemplazar el idioma de un tema con el mismo idioma de otro tema.

Seleccione el idioma y el tema de origen, luego el idioma y el tema de destino, haga clic en el botón "Copiar". En la mayoría de los casos, el idioma debería seguir siendo el mismo en ambas listas desplegables.

Si ya existe una carpeta de idioma para ese idioma en el tema de destino, se sobrescribirá con los archivos de idioma y tema que esté copiando. Es posible que desees crear un nuevo idioma para el tema de destino antes de copiarle el idioma de origen.

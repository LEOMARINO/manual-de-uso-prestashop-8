# La interfaz multitienda

## La página Multitienda <a href="#themultistoreinterface-managingyourstores" id="themultistoreinterface-managingyourstores"></a>

### Comprender la organización de páginas multitienda

{% hint style="info" %}
Para acceder a la página Multitienda, primero debe [habilitar la función](../#managingmultipleshops-enablingthemultistorefeature) en **Parámetros de la tienda > General**.
{% endhint %}

Luego habrá una nueva página disponible en el menú **Parámetros avanzados**: la **página Multitienda**.

Esta página está dividida en 3 secciones:

* **Árbol de tiendas múltiples:** El árbol de tiendas múltiples le brinda una descripción general de cómo están organizadas sus tiendas en diferentes grupos.&#x20;
* **Multitienda:** Esta tabla enumera todos los grupos de tiendas que ha creado, estén habilitados o no.&#x20;
* **Opciones de multitienda:** En esta sección, puedes seleccionar la tienda que deseas establecer como predeterminada. &#x20;

{% content-ref url="adding-new-store.md" %}
[agregando-nueva-tienda.md](adding-new-store.md)
{% endcontent-ref %}

{% content-ref url="adding-new-group-of-stores.md" %}
[agregando-nuevo-grupo-de-tiendas.md](adding-new-group-of-stores.md)
{% endcontent-ref %}

{% content-ref url="setting-store-url.md" %}
[configuración-tienda-url.md](setting-store-url.md)
{% endcontent-ref %}

## Trabajar en diferentes contextos <a href="#themultistoreinterface-onebackofficetorulethemall" id="themultistoreinterface-onebackofficetorulethemall"></a>

### Saber en qué contexto estás

Cuando la función multitienda está habilitada, puede aplicar cambios a **todas las tiendas**, **un grupo de tiendas** o **una tienda específica**, según el contexto seleccionado en el selector desplegable o en el encabezado.

* **Todas las tiendas**: Los cambios se aplicarán a todas tus tiendas.
* **Grupo X**: Los cambios solo se aplicarán a las tiendas del grupo X.
* **Tienda Y**: Los cambios solo se aplicarán a la tienda Y.

#### El selector desplegable (versiones anteriores y páginas no actualizadas)

El selector desplegable en la parte superior de cada página del back office indica el contexto en el que está trabajando (Todas las tiendas, grupo o tienda única).

![](<../../.gitbook/assets/57081980 (4) (4) (2).png>)

#### el encabezado

La interfaz multitienda evoluciona y el menú desplegable Editar página multitienda EN se convierte en un encabezado en la mayoría de las páginas. &#x20;

<figure><img src="../../.gitbook/assets/image (92).png" alt=""><figcaption></figcaption></figure>

{% hint style="success" %}
El color de cada tienda o grupo de tiendas se puede personalizar en la página **Parámetros avanzados > Multitienda**. Dependiendo de la tienda en la que estés trabajando, el encabezado cambiará de color, permitiéndote saber de un vistazo en qué contexto te encuentras.
{% endhint %}

<figure><img src="../../.gitbook/assets/image (36).png" alt=""><figcaption></figcaption></figure>

### Realizar cambios en un grupo de tiendas o en una tienda específica

Para aplicar cambios a un grupo de tiendas o a una tienda específica, cambie el contexto con el encabezado y seleccione el grupo o la tienda que desea personalizar.

La interfaz puede ser diferente según su versión de PrestaShop y la página en la que se encuentre:

#### El botón de alternancia y las casillas de verificación de multitienda (versiones y páginas anteriores)

En un contexto de grupo o tienda única, aparecerán nuevas opciones en la página, lo que le permitirá personalizar la configuración para el grupo o tienda específica seleccionada:

* Un botón de alternancia "Sí/No" multitienda
* Una casilla de verificación al lado de cada parámetro

Para realizar cambios:&#x20;

1. Para que todas las configuraciones de una sección sean editables, configure el botón de alternancia de varias tiendas en "Sí".  Si solo desea personalizar una configuración específica, **marque la casilla** junto a ella.
2. Una vez que un parámetro sea editable, realice los cambios y guárdelo.

{% hint style="info" %}
Configurar la opción multitienda en Sí o marcar una casilla hace que los parámetros sean editables pero no cambian su valor. Depende de usted hacer los ajustes y guardar.
{% endhint %}

#### Casillas de verificación

Las casillas de verificación se muestran cuando trabaja en un contexto de tienda única o de grupo. Le permiten modificar un parámetro para una tienda específica o un grupo de tiendas y mantener un registro de este cambio.&#x20;

Si la casilla está marcada la próxima vez que accedas a la página, significa que el parámetro está personalizado para la tienda o el grupo de tiendas en el que estás trabajando. Al desmarcar la casilla se cancelará la personalización y el parámetro tomará el mismo valor que en el contexto "Todas las tiendas" (o el contexto del grupo, si corresponde).

Por ejemplo, en la captura de pantalla siguiente, la casilla junto al parámetro de texto de mantenimiento está marcada. Esto significa que este parámetro está personalizado en la Tienda 1.

<figure><img src="../../.gitbook/assets/image (96).png" alt=""><figcaption></figcaption></figure>

### Realizar un seguimiento de los cambios realizados en una sola tienda

#### El menú desplegable de configuración específica

Gracias al menú desplegable de configuración específica, si realizas cambios en una tienda específica y luego vuelves al contexto "Todas las tiendas" o grupo, podrás saber fácilmente qué parámetros se han modificado en una tienda específica.

Entonces, si ve este menú desplegable junto a un parámetro, significa que este parámetro se ha personalizado en al menos una tienda. Implemente el menú desplegable para saber qué tiendas están interesadas.

<figure><img src="../../.gitbook/assets/image (29) (2).png" alt=""><figcaption></figcaption></figure>

**Personalizado**: El parámetro fue modificado en la tienda.

**Heredado**: El parámetro se configura de la misma forma en todas las tiendas.

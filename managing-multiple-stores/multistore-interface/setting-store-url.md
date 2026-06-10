# Configurar la URL de una tienda

## Composición de la URL de una tienda

![](<../../.gitbook/assets/httpswww.mystore.comwomen (1).png>)

## Tener dos tiendas en un nombre de dominio

Dos tiendas no pueden compartir la misma URL.&#x20;

Sin embargo, puede tener tantas tiendas como desee en un nombre de dominio utilizando subcarpetas o subdominios.

### **Usando subcarpetas**

![](<../../.gitbook/assets/httpswww.mystore.comwomen (4).png>)

En el caso de tiendas de subcarpetas, asegúrese de crear 2 URL para cada tienda: una con "www." y otra sin él.

De lo contrario, los clientes que intenten acceder a su tienda secundaria sin el "www." en la URL será redirigido a su tienda principal.

### &#x20;**Usando subdominios**

![](<../../.gitbook/assets/httpswww.mystore.comwomen (5) (2).png>)

{% hint style="success" %}
No es necesario crear subdominios o subcarpetas manualmente. PrestaShop creará la ruta en su servidor automáticamente.
{% endhint %}

### Usando un nombre de dominio diferente

En caso de que desee utilizar un nombre de dominio diferente para su tienda complementaria en lugar de un subdominio o una subcarpeta, debe configurar su dominio para que apunte a la carpeta donde se encuentra PrestaShop. La reescritura de la URL la realiza el propio PrestaShop.

Alternativamente, puedes crear un alias para tu nombre de dominio que redirija a la URL absoluta donde se encuentra tu instalación de PrestaShop. La forma de conseguirlo depende del panel de control y de las opciones que te proporcione tu empresa de hosting: "Alias" para Plesk, "Forward" para CPanel, "Aliasdomain" para ISPConfig, etc.

## Establecer una URL&#x20;

Para configurar una URL para una tienda**:**

1. **Selecciona la tienda** en el árbol Multitienda
2. Haga clic en el enlace **"Haga clic aquí para establecer una URL para esta tienda" en la columna "URL principal"** de la tabla.
3. **Rellena el formulario**&#x20;

**Opciones de URL:**

<figure><img src="../../.gitbook/assets/image (31) (2).png" alt=""><figcaption></figcaption></figure>

* **Tienda:** Seleccionó la tienda en la que desea establecer la URL.
* **URL principal:** Cambie el botón a "Sí" si desea que todas las URL de la tienda redireccionen a la URL principal.
* **Estado:** Todas las URL, excepto la principal, se pueden desactivar.

**URL de la tienda:**

<figure><img src="../../.gitbook/assets/image (20) (2).png" alt=""><figcaption></figcaption></figure>

*   **Dominio:** Introduzca el nombre de dominio de la tienda. Puede indicar un subdominio si es necesario. Solo asegúrate de que no contenga '`http://`' ni ningún '`/`'.&#x20;

    Example: [`www.example.com`](http://www.example.com/) o [`kids.example.com`](http://kids.example.com/).
* **Dominio SSL:** Si tu dominio SSL es diferente a tu dominio principal, asegúrate de indicarlo en ese campo.
* **URL física:** Ingrese la ruta física de su instalación en su servidor. Si instaló la tienda en el directorio raíz, entonces la URL física debe ser `/`. Alternativamente, si instaló su tienda en una subcarpeta, la URL física es el nombre de la subcarpeta.
*   **URL virtual:** Gracias a la reescritura de URL, puedes utilizar esta opción si quieres crear una tienda con una URL que no existe en tu servidor, sin tener que crear una subcarpeta. Por ejemplo, si desea que su tienda esté disponible con la URL `www.example.com/my-store/shoes/`, debe configurar `shoes/` en este campo, asumiendo que `my-store/` es su URL física.&#x20;

    Las URL amigables deben estar habilitadas en **Parámetros de la tienda >Tráfico y SEO**. Tenga en cuenta que esta opción solo funciona para almacenes de subcarpetas, no para almacenes de subdominios.&#x20;
* **URL final:** Aquí puede obtener una vista previa de cómo se verá la URL de la tienda, según la configuración anterior.&#x20;


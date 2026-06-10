# Security

## Protección de tokens en el back office

La protección de token ayuda a **proteger el acceso a su back office mediante el uso de tokens**.&#x20;

<details>

<summary>Más información sobre la protección de tokens del back office </summary>

Cuando esta función está habilitada, cada URL se vuelve específica de la sesión de un cliente y no se puede usar tal como está en otro navegador, protegiendo así cualquier información que puedan haber almacenado durante esa sesión.

De forma predeterminada, la protección del token del back office está **habilitada.**

</details>

### Configure la política de contraseñas y el indicador de seguridad de la contraseña

El menú **política de contraseñas** le permite configurar la política de contraseñas de su tienda eligiendo entre 5 niveles crecientes de complejidad. Esto le permitirá decidir qué tan estricto quiere ser con las contraseñas de los usuarios.&#x20;

Las contraseñas se clasifican de **0** (Extremely guessable) a **4** (Very unguessable) según su puntuación de seguridad. La longitud mínima y máxima de las contraseñas se puede configurar manualmente.

<figure><img src="../../.gitbook/assets/image (84).png" alt=""><figcaption></figcaption></figure>

Al crear una cuenta, los usuarios de la oficina principal reciben señales en tiempo real sobre la seguridad de la contraseña elegida de acuerdo con la política de contraseñas de la oficina administrativa. Una señal codificada por colores _–_ así como una información sobre herramientas _–_ les ayudarán a comprender si su contraseña es lo suficientemente segura.

_**Nota:** los temas deben actualizarse para admitir esta función. Ver_ [#themeandlogo-yourcurrenttheme](../../improving-shop/customizing-store-design/theme-and-logo.md#themeandlogo-yourcurrenttheme "mention")

| Cue color | Password length | Password strength |
| :-------: | :-------------: | :---------------: |
|     🟥    | Not long enough | Not strong enough |
|     🟧    | Not long enough |       Strong      |
|     🟩    |       Good      |       Strong      |

|      An example of a weak password (🟥,🟧)     |      An example of a strong password (🟩)      |
| :--------------------------------------------: | :--------------------------------------------: |
| ![](<../../.gitbook/assets/image (87).png>) | ![](<../../.gitbook/assets/image (58).png>) |

## Gestionar sesiones de empleados y clientes.

Estas pestañas le permiten **administrar sesiones de empleados y clientes**. Para eliminar una sesión y cerrar la sesión del usuario, haga clic en el botón Eliminar en la columna Acciones.

Para acceder al back office, el empleado o cliente deberá volver a iniciar sesión con su correo electrónico y contraseña.

<figure><img src="../../.gitbook/assets/image (76) (1).png" alt=""><figcaption><p>The <strong>Employee Sessions</strong> tab allows you to manage employee sessions.</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (81).png" alt=""><figcaption><p>The <strong>Customer Sessions</strong> tab allows you to manage customer sessions.</p></figcaption></figure>

### Clear outdated Sessions

El botón Borrar le permite eliminar manualmente sesiones obsoletas para reducir el desorden de la base de datos.

<figure><img src="../../.gitbook/assets/image (72) (1).png" alt=""><figcaption></figcaption></figure>

# Permissions

Los permisos son la parte central de los perfiles de PrestaShop. Le permiten ver con mucha precisión lo que una cuenta de empleado puede y no puede hacer en su tienda.

La página de administración "Permisos" se crea mediante pestañas:

* A la izquierda de la pantalla, tantas pestañas como perfiles disponibles.
* En el resto de la derecha de la pantalla, PrestaShop muestra los permisos del perfil seleccionado. Esta pestaña contiene dos tablas una al lado de la otra.

Cuando haces clic en cualquier perfil (except SuperAdmin), aparecen las dos tablas para darte acceso a sus criterios:

* A la izquierda, permisos relacionados con los menús: puedes decidir qué puede hacer el perfil con los menús. De hecho, podría evitar que un perfil edite el contenido de una página o incluso ocultar el menú por completo.
* A la derecha, permisos relacionados con los módulos: si bien puede permitir que algunos perfiles vean los módulos disponibles, es posible que prefiera que solo los empleados más confiables puedan configurar algunos módulos clave.&#x20;

![](<../../../.gitbook/assets/43417612 (2) (1) (4).png>)

Para cada uno de los criterios del menú, tienes 5 opciones:

* **View**. Employee can view information.
* **Add**. Employee can add new information.
* **Edit**. Employee can change information.
* **Delete**. Employee can delete information.
* **Todo**. Habilite todas las opciones anteriores para la fila actual.

Mientras tanto, los criterios del módulo tienen 3 opciones:

* **Vista**. El empleado puede ver la configuración del módulo.
* **Configurar**. El empleado puede configurar el módulo.
* **Desinstalar**. El empleado puede desinstalar el módulo.

Los permisos de SuperAdmin no se pueden cambiar: el perfil simplemente tiene todos los derechos para cada criterio.

## Setting permissions for a new profile <a href="#permissions-settingpermissionsforanewprofile" id="permissions-settingpermissionsforanewprofile"></a>

Para este ejemplo crearemos un nuevo perfil, "Preparador de pedidos". Primero cree el perfil en la página "Perfiles", completando el campo "Nombre". Una vez guardado, aparece en la lista de perfiles.

Luego necesitas asignar permisos a este nuevo perfil. Vaya a la página "Permisos" y haga clic en la pestaña del nuevo perfil: aparece la lista de criterios. De forma predeterminada, un perfil nuevo no tiene acceso a ninguna de las páginas del back office.

Hay dos formas de cumplir los criterios, dependiendo de los límites o libertad que quieras que tenga el perfil:

* Haga clic en las casillas de permiso una por una hasta que tenga suficientes derechos de acceso para realizar el trabajo.
* Marque todas las casillas de verificación, luego elimine los permisos uno por uno hasta que solo tenga los necesarios.

Tiene dos formas de marcar casillas de verificación en lotes:

* Por columna: en la parte superior de cada columna, una casilla de verificación permite marcar todas las casillas de la columna a la vez. Al desmarcarlo, se desmarcan todas las casillas actualmente marcadas.
* Por fila: si hace clic en la casilla de verificación "Todos" para una fila determinada, se marcarán todas las casillas de esta fila. Al desmarcarlo, se desmarcan todas las casillas actualmente marcadas.

Luego puede desmarcar las filas seleccionadas en lugar de perder tiempo revisando cada fila necesaria una por una.

Para evitar errores durante la configuración de tus permisos, PrestaShop guarda automáticamente tu configuración cada vez que realizas un cambio. Esto significa que no tiene que hacer clic en ningún botón "Guardar". Una vez que haya asignado sus derechos al perfil, puede regresar a la página de administración "Empleados" y comenzar a asignar ese nuevo perfil a los empleados que lo necesiten.

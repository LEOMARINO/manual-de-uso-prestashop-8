# Groups

PrestaShop le permite otorgar ciertos privilegios a sus clientes, asignándolos a grupos. Puede crear tantos grupos de clientes como necesite y asignar un usuario a tantos grupos como desee.

Todo esto se hace desde la pestaña "Grupos", en el menú "Configuración de clientes".

![](<../../../.gitbook/assets/51839979 (4) (4) (4).png>)

De forma predeterminada, hay tres grupos especiales disponibles:

* **Visitante**. Todas las personas sin una cuenta de cliente o no autenticadas.
* **Invitado**. Todas las personas que realizaron un pedido con Guest Checkout: esa opción debe estar habilitada.
* **Cliente**. Todas las personas que crearon una cuenta en su tienda y están autenticadas.

These three groups cannot be deleted.

Para crear más grupos, haga clic en el botón "Agregar nuevo grupo": obtendrá un formulario de creación.

![](<../../../.gitbook/assets/51839980 (4) (4) (4).png>)

* **Nombre**. Utilice un nombre breve y descriptivo.
* **Descuento (%)**. El descuento que puedes establecer para los miembros de este grupo se aplica a todos los productos de tu tienda.\
  Es posible que prefieras no establecer ningún valor de descuento y, en su lugar, crear reglas de carrito.
* **Método de visualización de precios**. PrestaShop se utiliza frecuentemente en el sector Business to Business (B2B). Puedes crear un grupo de clientes que podrán comprar productos sin pagar impuestos. La lista desplegable le permite elegir entre "impuestos incluidos" e "impuestos excluidos".
* **Mostrar precios**. Por defecto, todos los usuarios de tu tienda pueden ver los precios. Es posible que prefieras que algunos no tengan acceso a los precios de tus productos. Por ejemplo, podría hacer que los usuarios sólo puedan ver los precios si tienen una cuenta. En ese caso, debes editar el grupo "Visitantes" para que "Mostrar precios" esté configurado en "No".&#x20;

Una vez que estas configuraciones estén implementadas, puede guardar el grupo tal como está o agregar configuraciones por categoría y/o por módulo. En ese segundo caso, una vez guardado el grupo, ábrelo nuevamente: el formulario se cargará con dos opciones más:

* **Descuento de categoría**. Haga clic en "Agregar un descuento de categoría" para abrir una nueva ventana, que contiene una lista de todas sus categorías. Puede elegir uno y aplicar un descuento específico que se aplicará solo a ese grupo de clientes y solo a esa categoría.\
  Note that:
  * Sólo los productos que tengan esta categoría como categoría predeterminada se verán afectados por el descuento. Los productos que tengan esta categoría como categoría secundaria no se verán afectados.
  * This category discount will replace any other discount that members of this group would otherwise enjoy on this category.
  * Puede agregar tantos descuentos de categoría para este grupo de clientes como necesite, lo que le permitirá brindarle a este grupo un conjunto completo de descuentos diferentes si lo considera necesario.
* **Módulos autorizados**. Esta sección le permite bloquear a los miembros de este grupo para que accedan y utilicen algunos de los módulos de su tienda. Por ejemplo, es posible que prefiera que algunos clientes no puedan ver sus productos más vendidos o sus ofertas especiales.&#x20;

![](<../../../.gitbook/assets/51839982 (4) (4) (4).png>)

Puede agregar un cliente a un grupo de su elección editando los detalles del cliente: de la lista de clientes (in the "Customers" page under the "Customers" menu), haga clic en el botón Editar en la fila del cliente. Luego, en la tabla "Acceso al grupo", selecciona el grupo(s) al que quieres que pertenezca tu cliente. Si asignas al cliente a más de un grupo, recuerda configurar su grupo principal con la opción "Grupo de clientes predeterminado".

![](<../../../.gitbook/assets/51839981 (4) (4) (1).png>)

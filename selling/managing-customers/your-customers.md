# Tus clientes

La primera página debajo del menú "Clientes" le brinda una lista de todos los usuarios registrados en su tienda.

![](<../../.gitbook/assets/51839862 (3) (11) (2).png>)

Esto le brinda una vista panorámica de sus clientes, con algunos detalles que puede usar para ordenar y buscar cuentas:

* **ID.** El ID único adjunto al cliente.
* **Título social**. Los clientes pueden declarar su título social, que se relaciona con un género y puede ayudarlo a personalizar mejor la experiencia de sus clientes. Hay dos títulos sociales predeterminados (Señor y Señora), pero puede crear más en la página "Títulos" en la página "Configuración de clientes" en el menú "Parámetros de la tienda".
* **Nombre y Apellido**. El nombre del cliente.
* **Dirección de correo electrónico**. La dirección de correo electrónico que el cliente utilizó para registrarse en su tienda.
* **Ventas**. Cuánto ha gastado el cliente en tu tienda hasta el momento.
* **Activado**. Indica si el cliente está activo o no. Puede desactivar una cuenta haciendo clic en la marca de verificación verde.
* **Hoja informativa**. Indica si el cliente está suscrito a la newsletter de tu tienda o no. Puede darse de baja haciendo clic en la marca de verificación verde.
* **Ofertas de socios**. Indica si la cuenta ha aceptado recibir correos electrónicos de sus socios o no. Puedes darte de baja haciendo clic en la marca de verificación verde. **No suscribas a un usuario a estos correos electrónicos sin su consentimiento, ya que se considera spam**.
* La fecha de registro y la última visita siempre pueden resultar útiles a la hora de ordenar las cuentas de usuario.
* **Comportamiento**. Puedes editar la cuenta del usuario, simplemente verla completa (con sus mensajes, pedidos, direcciones, vales, etc.) o eliminarla para siempre.

Cuando se instala por primera vez con datos de muestra, PrestaShop tiene un usuario predeterminado, llamado John DOE.

Puede utilizar este usuario falso para probar algunas de las funciones de su tienda, navegar por ella y verla como lo haría un usuario normal.

Para iniciar sesión en su tienda utilizando esta cuenta pública, utilice estas credenciales:

* Dirección de correo electrónico: [pub@prestashop.com](mailto:pub@prestashop.com)
* Contraseña: 123456789

**Antes de abrir tu tienda al público, asegúrate de eliminar este usuario predeterminado, ¡o al menos cambia sus credenciales!** De lo contrario, los visitantes malintencionados podrían usarlo para realizar compras falsas y más.

Debajo de la tabla de clientes se encuentra el botón "Establecer campos obligatorios para esta sección". Abre un formulario donde puede indicar si un campo de base de datos es necesario o no marcando las casillas correspondientes: de esta manera, puede hacer que campos como "ofertas de socios" sean obligatorios cuando un visitante crea una cuenta de cliente en su tienda.

Puede exportar una lista de sus clientes haciendo clic en el botón "Exportar" en la parte superior.\
También puede importar clientes usando el botón "Importar". Necesitará que su archivo CSV siga este formato:

```
ID;Title;Last name;First Name;Email address;Age;Enabled;News.;Opt.;Registration;Last visit;
2;1;Gorred;Francis;francis@example.com;-;1;0;0;2013-07-04 15:20:02;2013-07-04 15:18:50;
1;1;DOE;John;pub@prestashop.com;43;1;1;1;2013-07-02 17:36:07;2013-07-03 16:04:15;
```

Hay más opciones de importación disponibles en la página "Importar" del menú "Parámetros avanzados".

## Crear una nueva cuenta de cliente <a href="#yourcustomers-creatinganewcustomeraccount" id="yourcustomers-creatinganewcustomeraccount"></a>

Para crear una cuenta de cliente manualmente, seleccione "Agregar nuevo cliente". Aparece un formulario.

![](<../../.gitbook/assets/51839855 (3) (3) (1).png>)

Complete la información del cliente:

* **Título social**. Elija entre los disponibles o cree otro en la página "Títulos" en la página "Configuración de clientes" en el menú "Parámetros de la tienda".
* **Nombre**, **Apellido**, **Dirección de correo electrónico**. Son esenciales: los nombres se utilizan en los correos electrónicos de confirmación que envía PrestaShop y la dirección de correo electrónico se utiliza para iniciar sesión.
* **Contraseña**. Elija una contraseña de al menos 5 caracteres.
*   **Cumpleaños**. Esta información se puede utilizar para correos electrónicos de cumpleaños y descuentos temporales.\
    \


    Si no desea solicitar la fecha de nacimiento cuando un cliente crea una cuenta, puede desactivar el campo de fecha de nacimiento en la página "Configuración del cliente". Simplemente seleccione "No" en la opción "Solicitar fecha de nacimiento".
* **Activado**. Es posible que desees crear una cuenta, pero aún no la tienes activa.
* **Ofertas de socios**. Puede ser utilizado por módulos para enviar promociones periódicas de socios a aquellos clientes que lo soliciten. **No suscribas a un usuario a estos correos electrónicos sin su consentimiento, ya que se considera spam**.
* **Acceso grupal**. Tener grupos de clientes le permite crear descuentos grupales. Muchas otras funciones de PrestaShop también pueden restringirse a grupos.&#x20;
* **Grupo de clientes predeterminado**. No importa a cuántos grupos pertenezca ese cliente, siempre debe tener un grupo principal.\
  \


Si sus clientes son en su mayoría empresas, debe habilitar el modo B2B para obtener opciones adicionales: vaya a la página "Configuración de clientes" del menú "Parámetros de la tienda" y elija "Sí" para la opción "Habilitar modo B2B".

![](<../../.gitbook/assets/23038650 (3) (1).png>)

El modo B2B añade algunos campos específicos de la empresa:

* **Compañía**. El nombre de la empresa.
* **SIRET**. Su número SIRET (sólo Francia).
* **MONO**. Su código de actividad principal (_Activité principale exercée_ - sólo Francia).
* **Sitio web**. Su sitio web.
* **Monto pendiente permitido**. La cantidad de dinero pendiente que tiene permitida la empresa.
* **Número máximo de días de pago**. El número de días que la empresa tiene permitido.
* **Calificación de riesgo**. Su calificación de riesgo de esta empresa: Bajo, Medio o Alto.

## Ver la información de un cliente <a href="#yourcustomers-viewingacustomersinformation" id="yourcustomers-viewingacustomersinformation"></a>

En el caso de que desee tener más información sobre un cliente determinado, puede hacer clic en el botón "ver", ubicado al final de la fila en la lista de clientes. Aparece una nueva página.

![](<../../.gitbook/assets/51839857 (3) (3).png>)

Las distintas secciones le proporcionan algunos datos clave sobre el usuario:

* **Información del cliente**, nombre y apellido, dirección de correo electrónico, DNI, fecha de registro, fecha de última visita, rango.
* Información sobre la suscripción al boletín de la tienda y la suscripción a anuncios de empresas asociadas, la edad, la fecha de la última actualización y si la cuenta está activa o no.
* **Notas privadas** de los empleados de la tienda (es decir, usted o su equipo).
* **Mensajes** enviados por el cliente al equipo de la tienda (a través de atención al cliente).
* Disponibles **vales** / reglas del carrito.
* **Conexiones previas** a la tienda.
* Los **grupos** a los que pertenece el cliente.
* Resumen de los **pedidos** anteriores del cliente. Monto gastado, tipo de pago, estado del pedido. Para obtener más información sobre cada pedido, haga clic en la fecha del pedido.
* **Carritos** que el cliente ha creado (pero no necesariamente validado) desde el registro. Cuando su cliente está actualmente en su tienda, puede ver lo que se agrega al carrito en tiempo real.
* Resumen de los productos que fueron adquiridos por un cliente. Entre otras cosas, esto te permite saber cuándo a un cliente le gusta mucho un producto y tal vez crear un descuento especial para la décima compra. Al hacer clic en un producto, se dirige al pedido al que está vinculado ese producto.
* Una lista del **producto visto** por el cliente. Asimismo, puede ver qué páginas de productos visitó el cliente en su sitio web. Si ningún pedido sigue a varias visitas de un producto, tal vez puedas ayudar al cliente a decidir enviándole un descuento específico.
* **Direcciones registradas**.\
  \


## Buscando un cliente <a href="#tusclientes-buscandouncliente" id="tusclientes-buscandouncliente"></a>

La búsqueda de un cliente en tu tienda PrestaShop se puede realizar de dos formas diferentes.

**El primer método** consiste en ingresar la información que tienes en la barra de búsqueda de PrestaShop, que se encuentra en la parte superior central de tu back office. Seleccionando "en todas partes", "por nombre" o "por dirección IP", podrá realizar una búsqueda basada en:

* IDENTIFICACIÓN. Los números que se asignan al cliente en la base de datos.
* Nombre o apellido. Tenga en cuenta que no puede buscar ambos: elija "john" o "doe", ya que "john doe" no funcionará.
* Dirección de correo electrónico.
* Dirección IP. Puedes buscar usando la IP de la última conexión a tu tienda.

![](<../../.gitbook/assets/51839858 (3) (3) (2).png>)

Luego se presentan los resultados, si los hay: la lista le presenta la identificación de los usuarios, el título social, el correo electrónico, la fecha de nacimiento, la fecha de registro, la cantidad de pedidos y si la cuenta del usuario está activa o no. A partir de ahí, puede ver la página completa del usuario o editar sus detalles.

![](<../../.gitbook/assets/51839860 (3) (3) (3).png>)

**El segundo método** consiste en ir a la página "Clientes" y enumerar todos tus clientes.

![](<../../.gitbook/assets/51839859 (3) (3) (1).png>)

En esta página, puede completar los campos en la parte superior de la lista para filtrarla según los siguientes criterios: ID, título social, nombre, apellido, dirección de correo electrónico, edad, estado de la cuenta (habilitada o deshabilitada), suscripción al boletín informativo, suscripción a anuncios de socios, fecha de registro y fecha de última conexión. Ingrese sus criterios y haga clic en el botón "Filtro" en la esquina superior derecha de la tabla. Luego puede ordenar la lista para algunas de las columnas.

Haga clic en el botón "Restablecer" para volver a la lista completa.

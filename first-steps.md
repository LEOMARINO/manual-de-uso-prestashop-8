# Primeros pasos con PrestaShop 8

## Primeros pasos con PrestaShop 8 <a href="#firststepswithprestashop1.7-firststepswithprestashop1.7" id="firststepswithprestashop1.7-firststepswithprestashop1.7"></a>

Debe asegurarse de que cada parte de su futura tienda en línea esté correctamente configurada, protegida, validada y lista para funcionar.

PrestaShop es una herramienta muy completa y la cantidad de posibilidades puede resultar abrumadora. Por lo tanto, este capítulo le guiará a través de algunas acciones básicas que debe realizar para configurar su tienda antes del gran lanzamiento. Se pueden y se deben hacer muchas cosas antes de lanzar su tienda, pero estos pasos son los pasos de configuración esenciales de cualquier tienda.

### Desactiva tu tienda <a href="#firststepswithprestashop1.7-deactivateyourshop" id="firststepswithprestashop1.7-deactivateyourshop"></a>

Consideraremos que todavía estás dentro de la primera hora después de la instalación de PrestaShop, en una instancia de tienda única.

Desactivar tu tienda significa asegurarte de que nadie pueda acceder a ella mientras estás ocupado haciendo cambios, creando productos, configurando precios e impuestos, instalando módulos de pago y un nuevo tema, configurando transportistas... Esto se llama "poner tu tienda en modo de mantenimiento".

![](<.gitbook/assets/51185217 (3) (3) (1).png>)

En tu back office, ve a la página "Parámetros de la tienda/General". Las opciones de mantenimiento están en la segunda pestaña y presentan tres configuraciones simples:

* **Habilitar tienda**. Simplemente configúrelo en "No" y su interfaz mostrará la página de mantenimiento a sus visitantes, que simplemente indica que su tienda pronto volverá a estar en línea.
* **IP de mantenimiento**. Aquí es donde debes ingresar tu propia dirección IP, para que aún puedas acceder a tu página principal y navegar por tu tienda como si estuviera disponible para todos. Esto es algo que debes hacer cada vez que pongas tu tienda en modo de mantenimiento, ya que siempre necesitarás navegar por tu interfaz para asegurarte de que todo esté en su lugar según lo previsto. \
  Simplemente haga clic en el botón "Agregar mi IP". Puede agregar más direcciones IP separándolas con comas.
* **Texto de mantenimiento personalizado**. Puede mostrar su propio mensaje en la página de mantenimiento, para informar a sus visitantes, por ejemplo, cuándo volverá el sitio.\
  \


Si ya ha decidido cuál es su tema y sus productos, simplemente puede poner su tienda en modo Catálogo. Esto significa que los clientes pueden navegar por su tienda, pero no se mostrará ningún precio y no podrán agregar nada a su carrito hasta que desactive el modo Catálogo.

Puedes activar el modo Catálogo yendo a la página "Parámetros de la tienda" > "Configuración de productos", donde es la primera opción.

![](<.gitbook/assets/51185218 (3) (3) (3).png>)

### Eliminar el contenido de la tienda predeterminada <a href="#firststepswithprestashop1.7-deletethecontentofthedefaultshop" id="firststepswithprestashop1.7-deletethecontentofthedefaultshop"></a>

La instalación predeterminada incluye un puñado de productos, principalmente ropa de mujer. Su único uso es ayudarle a explorar la organización de una tienda real. Una vez que haya aprendido las complejidades de los vínculos entre productos, categorías, pedidos y clientes, debe eliminar todos estos elementos para comenzar su tienda con borrón y cuenta nueva.

![](<.gitbook/assets/51185219 (3) (3).png>)

Por lo tanto, debes eliminar todos los datos predeterminados, lo que significa:

* productos y sus...
  * categorias
  * atributos
  * características
  * fabricantes
  * proveedores
  * mapeos de imágenes
  * etiquetas
* pedidos
  * ordenar mensajes
* clientes
  * carritos de compras de clientes
* transportistas
  * rangos de precios
  * rangos de peso
* contacto y tiendas (eliminar o adaptar a las necesidades de tu negocio)
* Páginas (eliminar o adaptar a las necesidades de tu negocio)

### Configura la información de tu tienda <a href="#firststepswithprestashop1.7-configureyourshopsinformation" id="firststepswithprestashop1.7-configureyourshopsinformation"></a>

Ahora que tienes una tienda limpia, puedes empezar a hacerla tuya, y eso implica configurar todo a tu gusto, empezando por tu información personal y tus preferencias.

#### La configuración básica de la tienda <a href="#firststepswithprestashop1.7-theshopsbasicsettings" id="firststepswithprestashop1.7-theshopsbasicsettings"></a>

Debe prestar atención a las siguientes configuraciones, la mayoría de las cuales son importantes porque se muestran en la oficina principal y, por lo tanto, a la vista de sus clientes.

Algunas de estas configuraciones requieren que configures un módulo en lugar de cambiar una de las preferencias de PrestaShop.

Configurar un módulo es fácil:

1. Vaya a la página "Módulos instalados" en el menú "Módulos".
2. Escriba el nombre del módulo (o parte de él) en el cuadro de búsqueda del módulo. Debería mostrar resultados a medida que escribe.
3. Cuando encuentre el módulo, haga clic en el botón "Configurar" y siga las instrucciones.

Para cada módulo presentado aquí, debe leer su documentación para obtener más información.

| Configuración | Descripción | Dónde encontrarlo |
| ---------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Nombre de la tienda | Define su marca, especialmente en los motores de búsqueda (Google, Yahoo!, Bing...).                                                                                                                                                                                                                                                     | Menú "Parámetros de la tienda", página "Contacto", pestaña "Tiendas", luego en la sección "Detalles de contacto", edite la opción "Nombre de la tienda".                                                                                                                                                                                                                                           |
| Logotipo de la tienda | <p>Define tu marca visualmente. El logotipo predeterminado dice "Clásico", que es el nombre del tema predeterminado.<br>Se muestra en la parte superior izquierda de cada página de tu tienda, así como en tus facturas y otros correos electrónicos automáticos.</p> | Menú "Diseño", página "Tema y logotipo", sección "Su tema actual", luego cambie las distintas imágenes predeterminadas a su logotipo.                                                                                                                                                                                                                                               |
| Moneda predeterminada de la tienda | La moneda en la que desea establecer el precio predeterminado para sus productos.                                                                                                                                                                                                                                                        | <p>Menú "Internacional", página "Localización", sección "Configuración".<br>Si la moneda no está disponible, primero debe importar un paquete de localización para su país: utilice la herramienta "Importar un paquete de localización" de la misma página.</p> |
| Información de la tienda | Varios bloques que presentan el número de teléfono de su tienda, su dirección de contacto y el correo electrónico de su tienda. Estos se muestran en varios lugares de las oficinas centrales.                                                                                                                                                         | <p>La información proviene del menú "Parámetros de la tienda", la página "Contacto", la pestaña "Tiendas" y luego en la sección "Detalles de contacto".</p><p>Para desactivarlo, consulte el módulo "Información de contacto".</p> |
| Control deslizante de imagen | <p>El control deslizante presenta varias imágenes, desplazándose una tras otra. Es una fuerte firma visual para su tienda y sus productos.<br>Generalmente se coloca al frente y en el centro de la página de inicio</p> | Módulo "Control deslizante de imagen".                                                                                                                                                                                                                                                                                                                                               |
| Páginas | <p>El contenido de páginas estáticas, como "Acerca de nosotros", "Entrega", "Aviso legal", "Términos y condiciones" y "Pago seguro". Algunas de ellas tienen contenido predeterminado, que debes adaptar a tu negocio; algunos otros están vacíos y debes pegar tu propio texto.<br>Se muestra en la sección "Información" del pie de página.</p> | Menú "Diseño", página "páginas", luego edite y cree páginas a voluntad.                                                                                                                                                                                                                                                                                                     |
| Redes sociales | <p>Un bloque que presenta varios íconos para seguir a su empresa en las redes sociales. No se mostrará de forma predeterminada, así que asegúrese de ingresar los enlaces de sus redes sociales en el módulo.<br>Cuando está activo, se muestra en el pie de página, en la columna derecha.</p> | Módulo "Enlaces de seguimiento de redes sociales".                                                                                                                                                                                                                                                                                                                                  |
| Compartir redes sociales | En cada página de producto, 4 botones para compartir la URL de la página en las redes sociales: Facebook, Twitter, Google + y Pinterest.                                                                                                                                                                                                               | Módulo "Botones para compartir en redes sociales".                                                                                                                                                                                                                                                                                                                                 |
| Menú superior | La parte superior del tema predeterminado utiliza un menú superior para indicar las categorías a las que el visitante puede acceder, así como enlaces a otras ubicaciones.                                                                                                                                                                                              | Módulo "Menú principal".                                                                                                                                                                                                                                                                                                                                                  |
| Tranquilidad | En la página del producto, un bloque le permite mostrar algunos detalles de tranquilidad. Úselo para brindar algunos detalles sobre su política de devoluciones ("¡Devoluciones gratuitas!"), su política de seguridad ("Pagos seguros"), etc., para que los visitantes sientan que es seguro realizar pedidos en su tienda.                                                              | Módulo "Tranquilización del cliente".                                                                                                                                                                                                                                                                                                                                       |
| Contenido de la página de inicio | El tema predeterminado contiene una gran cantidad de contenido de demostración: textos, imágenes, enlaces, etc. Si tiene la intención de utilizar ese tema para su propia tienda en lugar de comprarlo, primero debe asegurarse de eliminar todo el contenido predeterminado.                                                                                                     | <p>Módulo "Banner": cambia la imagen en la parte inferior de la página de inicio.</p><p>Módulo "Bloques de texto personalizados": muestra tus propios mensajes en la parte inferior de la página de inicio, debajo del banner.</p><p>Otros módulos disponibles en la sección "Módulos instalados" y "Módulos temáticos" te ayudarán a definir los distintos ajustes para tu front office, ¡asegúrate de revisarlos todos!</p> |
| Cumplimiento legal | Algunos países requieren que usted brinde información específica a sus clientes sobre sus diversas políticas. El módulo "Cumplimiento legal" está aquí para ayudarle.                                                                                                                                                                        | Lea la página "[Cumplimiento de la legislación europea](http://doc.prestashop.com/display/PS17/Complying+with+the+European+legislation)" para saber más sobre los cambios que debe realizar.                                                                                                                                                                     |

Estas son las configuraciones predeterminadas más visibles en su interfaz, al menos con el tema predeterminado.\
La columna "Dónde encontrarlo" le permite ver dónde puede encontrar la interfaz para cambiar estos aspectos de su tienda. Esta guía del usuario le proporcionará más detalles para cada interfaz.

#### Idiomas de la tienda <a href="#firststepswithprestashop1.7-shoplanguages" id="firststepswithprestashop1.7-shoplanguages"></a>

PrestaShop es capaz de trabajar con muchos idiomas, tanto en el front office como en el back office. Tan pronto como se habilita más de un idioma en su back office, cada campo de texto del back office va acompañado de un selector de código de idioma, que indica el idioma actual y en el que puede hacer clic para elegir otro idioma en el que escribir el contenido de ese campo.

La página del producto funciona de forma un poco diferente. No encontrarás un selector de idioma para cada campo de texto, sino un selector de idioma general en la parte superior de la página. Una vez que haya seleccionado un idioma, podrá cambiar todos los contenidos en ese idioma. ¡Asegúrate de estar editando el correcto!

De forma predeterminada, PrestaShop se instala con dos idiomas: el que se utiliza al instalar el software y el que se adjunta al país predeterminado durante la instalación (si es diferente). Para administrar los idiomas actualmente instalados, vaya a la página "Localización/Idiomas" del menú "Internacional". Le presenta una tabla de los idiomas disponibles.

![](<.gitbook/assets/51185233 (3) (3) (1).png>)

Los idiomas actualmente habilitados tienen una marca de verificación verde, mientras que los demás tienen una cruz roja. Haga clic en una marca de verificación para desactivar el idioma seleccionado; haga clic en una cruz para habilitarlo nuevamente.

Puede instalar y habilitar muchos idiomas si cree que su tienda los necesita, pero tenga en cuenta que tendrá que traducir su contenido para todos los idiomas habilitados: nombres de productos, descripciones, etiquetas, nombres y descripciones de categorías, contenido estático (páginas), configuración de módulos, etc.

Puede importar fácilmente muchos más idiomas en la página "Internacional/Traducción" ("Agregar/actualizar un idioma) y luego habilitarlos en la página "Localización/Idiomas".

#### Información de los empleados <a href="#firststepswithprestashop1.7-employeesinformation" id="firststepswithprestashop1.7-employeesinformation"></a>

Si tienes personas que te ayudan con tu tienda (ya sean tu familia, tus amigos o empleados remunerados), debes asegurarte de crear una cuenta de empleado para cada uno de ellos, aunque sólo sea para saber quién ha realizado qué acción reciente. La otra ventaja es que puedes darles perfiles específicos y derechos de acceso específicos a las páginas de administración: por ejemplo, es posible que no quieras que todos tengan acceso a tus estadísticas, tus facturas o tus configuraciones de pago.
Puedes crear tantos perfiles como necesites.

Para crear una nueva cuenta de empleado, vaya al menú "Parámetros avanzados", página "Equipo" y haga clic en el botón "Agregar nuevo empleado". Asígnele un nombre, como "Martin Doe" o "Manejador de envío", y guárdelo. \
Se puede utilizar una cuenta para tantas personas como sea necesario, pero le recomendamos que cree una para cada persona que ayude.

Ahora que tiene una cuenta adecuada para este empleado, debe otorgarle permisos específicos, adaptados a las tareas del empleado. De forma predeterminada, un perfil nuevo no puede hacer mucho. Depende de usted establecer exactamente las partes de su tienda a las que ese perfil debe tener acceso. Puede ser una tarea tediosa, pero es importante.\
Para asignar permisos a una cuenta de empleado, debe utilizar la opción "Perfil" en la página de creación de cuenta: este menú le permite elegir el perfil de la cuenta (SuperAdmin, traductor, etc.)

Puede editar estos permisos de esta manera: vaya a la pestaña "Permisos" y seleccione el perfil que desea cambiar. Aparece una larga lista de permisos: edítalos a tu antojo. Sus cambios se guardan automáticamente.

![](<.gitbook/assets/23038245 (3) (3) (3).png>)

### Configura tus métodos de pago <a href="#firststepswithprestashop1.7-configureyourpaidmethods" id="firststepswithprestashop1.7-configureyourpaidmethods"></a>

Tu tienda está destinada a ganar dinero, y esto sólo puede convertirse en realidad si utilizas al menos un módulo de pago. Varios módulos ya están disponibles en la instalación predeterminada, que puede instalar y configurar (desde la página "Módulos instalados" en el menú "Módulos", en la categoría "Pagos y pasarelas") y crear restricciones para ellos (en la página "Preferencias" en el menú "Pago"). Muchos módulos de pago requieren que primero configures una cuenta en el servicio para el que fueron creados.

El cheque y la transferencia bancaria son los dos únicos métodos de pago habilitados de forma predeterminada. Si elige conservarlos, **necesita** configurarlos con su información: orden y dirección del cheque, propietario de la cuenta y datos bancarios (IBAN, BIC, etc.).

Estos métodos de pago se configuran a través de los módulos "Pago por transferencia bancaria" y "Pagos con cheque", que podrás encontrar en la página "Módulos instalados".

### Configurar transportistas y envío <a href="#firststepswithprestashop1.7-configurecarriersandshipment" id="firststepswithprestashop1.7-configurecarriersandshipment"></a>

Los productos vendidos en su tienda deben enviarse a sus clientes, a menos que solo venda productos descargables, en cuyo caso el menú "Envío" le será de poca utilidad.

Ya sea que envíe sus productos usted mismo por correo postal normal o haya establecido un contrato con un transportista, debe configurar esta información en PrestaShop.

Consulte el capítulo "Administración de envíos" de esta guía para obtener información sobre envíos y transportistas.

**La devolución de mercancía no está habilitada de forma predeterminada**. Si desea permitir que sus clientes devuelvan productos y obtengan un reembolso o un vale, puede hacerlo en las "Opciones de devolución de mercancía (RMA)" de la página "Devoluciones de mercancía", en el menú "Servicio al cliente".
Las devoluciones de mercancías se explican en el capítulo "Gestión del Servicio de Atención al Cliente" de esta guía.

### Elige tu tema <a href="#firststepswithprestashop1.7-chooseyourtheme" id="firststepswithprestashop1.7-chooseyourtheme"></a>

Tu tienda debe tener su propia temática para tener un estilo distintivo y, por lo tanto, ser más reconocible, diferenciándola de muchas otras tiendas online.

Hay muchos temas para elegir en el mercado de complementos de PrestaShop: [http://addons.prestashop.com/en/3-templates-prestashop](http://addons.prestashop.com/en/3-templates-prestashop).

También puede optar por crear su propio tema o que un desarrollador lo cree para usted. Consulte la Guía del diseñador de PrestaShop para obtener ayuda.

Una vez instalado tu tema, debes explorarlo a fondo para saberlo de memoria y poder ayudar a los clientes a salir de una situación. Lea atentamente su documentación.

Puedes y debes personalizar algunos de los aspectos del tema, en particular su logotipo en diversas situaciones (encabezado, correo, factura, etc.). Esto se hace usando la página "Tema y logotipo", que puede encontrar en el menú "Diseño".

### Elige tus módulos <a href="#firststepswithprestashop1.7-chooseyourmodules" id="firststepswithprestashop1.7-chooseyourmodules"></a>

PrestaShop viene con más de cien módulos. Estos son muy variados: análisis, funciones de front office, pago, envío... Debes explorar los módulos disponibles en su totalidad para saber qué es posible que desees habilitar y cuáles preferirías mantener deshabilitados.

También puedes encontrar muchos otros módulos en el mercado de complementos: [http://addons.prestashop.com/en/2-modules-prestashop](http://addons.prestashop.com/en/2-modules-prestashop)

Cada vez que active y configure un módulo, asegúrese de que funcione bien dentro de los límites de su tema, en caso de que sus características afecten la interfaz de su tienda.

### Crea tus productos y categorías de productos <a href="#firststepswithprestashop1.7-createyourproductsandproductcategories" id="firststepswithprestashop1.7-createyourproductsandproductcategories"></a>

Esto se describe en detalle en los capítulos "Administración de productos" y "Administración de categorías".

### Crea tu contenido estático <a href="#firststepswithprestashop1.7-createyourstaticcontent" id="firststepswithprestashop1.7-createyourstaticcontent"></a>

Si aún no lo ha hecho, debería tomarse el tiempo para escribir el contenido de las distintas páginas estáticas que ya están disponibles en su instalación de PrestaShop o aquellas que considere necesarias.

Algunas páginas ya existen, pero su contenido debería ser revisado tres veces, ya que pueden tener un gran impacto, entre otras cosas, en el estado legal de su tienda.

Las páginas predeterminadas son "Acerca de nosotros", "Entrega", "Aviso legal", "Términos y condiciones de uso" y "Pago seguro". Algunos de ellos tienen contenido predeterminado, que debes actualizar; algunos otros están vacíos y debes pegar tu propio texto.\
Para editar estas páginas, vaya al menú "Diseño", haga clic en la página "Páginas", luego elija la página que desea editar o cree otras nuevas.

Puede crear tantas páginas como considere necesarias.

### Crea tu menú superior <a href="#firststepswithprestashop1.7-buildyourtopmenu" id="firststepswithprestashop1.7-buildyourtopmenu"></a>

Ahora que tienes categorías de productos y páginas estáticas, debes organizarlas de forma lógica y atractiva en el menú superior.

Esto se hace usando el módulo "Menú principal": vaya a la pestaña "Módulos instalados" de la página "Módulos", escriba "menú" en el formulario de búsqueda del módulo y debería encontrar el módulo. Habilítelo si está deshabilitado, luego configúrelo: elimine las páginas o categorías que considere innecesarias, agregue otras páginas y mueva el contenido, hasta que esté satisfecho con la jerarquía de su menú.

### Activa tu tienda <a href="#firststepswithprestashop1.7-activateyourshop" id="firststepswithprestashop1.7-activateyourshop"></a>

Ahora que todo está configurado y hecho, finalmente puedes abrir tu tienda al público.

Vaya a la página "Parámetros de la tienda/General" y cambie las dos opciones en la pestaña "Mantenimiento":

* **Habilitar tienda**: configúrelo nuevamente en "Sí".
* **IP de mantenimiento**: elimina tu IP de la lista. Esto es opcional: tu tienda seguirá funcionando si dejas el campo como está.

Tu tienda ahora debería estar completamente lista para recibir a sus primeros visitantes... ¡y recibir sus primeros pedidos!

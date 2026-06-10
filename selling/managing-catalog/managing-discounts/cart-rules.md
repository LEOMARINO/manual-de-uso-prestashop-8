# Reglas del carrito

La página "Reglas del carrito" le da acceso a una herramienta avanzada para crear vales muy precisos. Cuando esta guía menciona vales, en realidad estamos hablando de reglas del carrito, que, en sí mismas, son bastante diferentes a las boletas de crédito.

Diferencias entre un comprobante de crédito, un vale y una regla del carrito

Un **recibo de crédito** es ante todo una prueba escrita de que un producto ha sido devuelto. La mayoría de las veces, el usuario puede utilizarlo como bono.

Un **vale** es un código de descuento que no tiene por qué estar vinculado a una devolución de mercancía o a un reembolso, y que puede adoptar más formas que un simple recibo de crédito:

* Un descuento en un pedido (porcentaje).
* Un descuento en un pedido (monto).
* Envío gratis.

Puede aplicar un bono a todos los clientes, a un grupo de clientes o a un solo cliente; puede establecer su fecha de vencimiento.

Una **regla del carrito** es básicamente una versión avanzada de un cupón:

* Nombra el descuento.
* Permita que el cliente utilice solo una parte del descuento.
* Asigna prioridades entre las reglas del carrito.
* Establezca la compatibilidad entre las reglas del carrito.
* Haga que el descuento solo funcione con algunos operadores.
* Haz que el descuento solo funcione con una selección de productos y/o categorías y/o marcas y/o proveedores y/o atributos... ¡o todos estos al mismo tiempo si es necesario!
* Haga que el descuento sea aplicable para envío gratuito y/o un descuento en un pedido y/o un regalo gratis... ¡o todos estos al mismo tiempo si es necesario!

En esta guía del usuario, "regla del carrito" y "vale" son sinónimos e intercambiables.

La página "Reglas del carrito" enumera las reglas del carrito y los cupones existentes actualmente, que puede habilitar o deshabilitar haciendo clic en los íconos en la columna "Estado".

![](<../../../.gitbook/assets/51839295 (3) (3) (2).png>)

## Creando una nueva regla de carrito <a href="#cartrules-creatinganewcartrule" id="cartrules-creatinganewcartrule"></a>

Se puede crear un vale automáticamente después de la devolución de un producto, pero puedes crear un nuevo vale en cualquier momento manualmente y ser muy específico sobre sus propiedades. Para ello, haga clic en "Agregar nueva regla de carrito". El formulario de creación tiene tres pestañas, lo que le permite crear con precisión nuevas reglas y vales.

### Pestaña Información <a href="#cartrules-informationtab" id="cartrules-informationtab"></a>

La primera pestaña, "Información", contiene los identificadores de la regla y la configuración principal.

![](<../../../.gitbook/assets/51839296 (3) (3) (3).png>)

* **Nombre**. El nombre es público, por lo que debes mantenerlo informal.
* **Descripción**. La descripción no es pública. Ayuda a los empleados de su taller a comprender por qué se creó la regla.
* **Código**. Dale a tu regla un código único. Puedes crear una manualmente (y por lo tanto usar palabras legibles, como 1VOUCH4JOE), o hacer que PrestaShop genere una cadena única haciendo clic en el botón "Generar". Por supuesto, también puedes usar cualquier otro generador de cadenas (como [http://www.random.org/strings/](http://www.random.org/strings/)).\
  Tenga en cuenta que si no se establece ningún código, la regla se aplicará a cualquier cliente que cumpla las otras condiciones:
  * Si hay un código, los clientes deben ingresarlo durante el proceso de pedido.
  * Si no hay ningún código, la regla se aplica automáticamente para beneficiar a los clientes en el momento del pago.
* **Resaltar.** Si está habilitado, PrestaShop le informará al usuario que un vale correspondiente a los artículos del carrito está disponible y se puede agregar.
* **Uso parcial**. Si está deshabilitada, la regla/vale solo se puede usar una vez, incluso si no se usa por completo. Si está habilitado, se crea un nuevo bono cuando el actual no se utiliza por completo.
  * Solo aplica si el valor del bono es mayor que el total del carrito. Si permites un uso parcial, se creará un nuevo vale con el resto.
  * Si no permite el uso parcial, el valor del cupón se reducirá al monto total del pedido.&#x20;
* **Prioridad**. Si un cliente (o grupo de clientes) es elegible para más de un vale, o si se puede aplicar más de un vale a un pedido, PrestaShop aplica dicho vale uno por uno en el pedido alfanumérico. Puede cambiar ese orden colocando una prioridad más baja en su cupón. De forma predeterminada, todos tienen una prioridad de 1. Si lo configura en un número mayor, el vale se aplicará después de los vales con un número menor.
* **Estado**. Puede deshabilitar y habilitar una regla cuando lo considere necesario.

### Pestaña Condiciones <a href="#cartrules-conditionstab" id="cartrules-conditionstab"></a>

La segunda pestaña, "Condiciones", contiene un gran conjunto de posibilidades, lo que le permite identificar con precisión quién debería poder beneficiarse de esta regla.

![](<../../../.gitbook/assets/51839297 (3) (7) (5).png>)

* **Límite a un solo cliente**. Aquí es donde indicas que el bono que estás creando es para un solo cliente. Por ejemplo, si tuviste un retraso en la entrega y quieres hacer un gesto de buena voluntad, puedes crear un vale para este cliente al que solo él o ella podrá acceder. Para encontrar rápidamente al cliente, escriba las primeras letras de su nombre, apellido o correo electrónico en el campo de texto.\
  Si está vacío, PrestaShop entenderá que cualquier cliente puede usarlo... a menos que haya agregado un grupo de clientes como condición adicional (consulte la casilla de verificación "Selección de grupo de clientes" a continuación).
* **Validez**. La validez predeterminada es de un mes, pero puedes reducirla a una semana o incluso a un día.
* **Cantidad mínima**. El importe mínimo del pedido a partir del cual se aplica el cupón. Su bono solo será aplicable si el pedido del cliente supera el monto indicado. Puedes elegir si ese monto debe incluir impuestos y/o costos de envío.
* **Totalmente disponibles**. Establece una cantidad de vales disponibles: ya sea "1" si está destinado a un solo cliente, o cualquier número si el vale es para quien utilice uno primero.
* **Total disponible para cada usuario**. Puede establecer la cantidad de veces que se puede utilizar un cupón para cada usuario. Ese número debe ser al menos igual a la cantidad de vales disponibles arriba (campo "Total disponible").
  * Si ese número es inferior a la cantidad total de vales disponibles, entonces un solo cliente no podrá utilizarlos todos.
  * Mantenerlo en "1" garantiza que cada uno de sus clientes solo pueda usar el cupón una vez. En ese caso, asegúrese de que el cupón se aplique a un grupo y no a un cliente...

Las casillas de verificación en la parte inferior de la sección son muy importantes, ya que le ayudan a filtrar mejor qué o a quién se aplicará la regla.

![](<../../../.gitbook/assets/57081959 (3) (3).png>)

* **Selección de operador**. Puede hacer que el cliente tenga un descuento si elige un transportista específico para la entrega del paquete.
* **Selección de grupo de clientes**. Esto es muy útil. Gracias a la herramienta de creación de grupos de PrestaShop, puedes crear descuentos que se aplican a una variedad de usuarios y crear otras condiciones además de ese descuento gracias a la herramienta de creación de reglas del carrito.
* **Compatibilidad con otras reglas del carrito**. De forma predeterminada, un pedido puede beneficiarse de cualquier cantidad de reglas de carrito. Con esta opción, puede indicarle a PrestaShop que esta regla no se puede combinar con una selección de otras reglas. Esta opción solo aparece si tienes más de una regla de carrito.
* **Selección de productos**. Otra herramienta muy útil, que permite crear vales automáticos para un carrito que contiene productos específicos. La herramienta se explica con más detalle a continuación.
* **Selección de tienda**. Cuando el modo multitienda está habilitado, de forma predeterminada se aplica una regla de carrito a todas sus tiendas. Con esta opción, puedes hacer que una regla solo se aplique a una selección de tus tiendas.

La opción "Selección de productos" trae una forma completamente nueva y le permite crear no sólo vales por producto, sino también por categorías, por marcas, por proveedores e incluso por atributo. Como beneficio adicional, puedes combinar todo esto para especificar tu objetivo de cliente tanto como sea posible.

Por ejemplo, puede crear vales automáticos para su cliente en el formulario "¡Compre al menos 3 productos Apple y obtenga envío gratis!". Esta también es una herramienta dentro de la regla del carrito y su configuración es bastante específica. Puede agregar tantas selecciones de productos como necesite, siguiendo esta ruta:

1. Haga clic en el enlace "Selección de productos" para agregar una nueva sección.
2. Indica el número de productos necesarios para que se active el descuento.
3. Agrega al menos una regla, del tipo que desees: productos, atributos, categorías, marcas, proveedores. Puedes agregar tantas reglas por selección de producto como quieras, incluso una para cada tipo si es necesario.
4. Al hacer clic en el botón "Agregar", se agrega una nueva línea en la selección. Para cada tipo, debes dar detalles sobre el contenido al que se aplica la regla. Haga clic en el enlace "Elegir" y se abrirá una ventana que enumera el contenido disponible para este tipo (productos, categorías...). Mueva el contenido del panel izquierdo al derecho haciendo clic en el botón "Agregar" y cierre la ventana haciendo clic en la "X" en la parte superior derecha. Si solo se selecciona un contenido, el campo de contenido dará su nombre; en caso contrario indicará el número de contenidos seleccionados.

Puede agregar tantas reglas dentro de una selección como sea necesario. Estas reglas son acumulativas: o se aplican todas o no se concede el descuento.

Las selecciones de productos son independientes: puedes agregar tantos como necesites y no se influirán entre sí. Esto le permite crear una gama completa de productos a los que se aplicará la regla del carrito.

### Pestaña Acciones <a href="#cartrules-actionstab" id="cartrules-actionstab"></a>

La tercera y última pestaña, “Acciones”, es donde eliges en qué consiste realmente el descuento.

![](<../../../.gitbook/assets/64225545 (3) (3).png>)

* **Envío gratis**. La norma trata de beneficiar a los clientes con el envío gratuito.
* **Aplica descuento**.
  * _Porcentaje (%)._ La regla se aplica a un porcentaje del total del pedido. Por ejemplo, digamos que el pedido está valorado en $200 antes de impuestos. La regla tiene un valor del 15%. Los clientes que se beneficien de esta regla sólo tendrán que pagar $170 (antes de impuestos y costos de envío).
  * _Importe._ La regla aplica un descuento monetario sobre el total del pedido. Por ejemplo, digamos que el pedido está valorado en $200 antes de impuestos. El descuento ofrece $20 de descuento en la compra. Los clientes que se beneficien de esta regla solo pagarán $180 (antes de los costos de envío). Puedes elegir si se aplican impuestos al descuento o no.
  * _Ninguno._ La norma no ofrece ningún descuento en el pedido. Al elegir esta opción, la siguiente sección, "Aplicar un descuento a", desaparece.
* **Excluye productos con descuento**. _¡Novedad en PrestaShop 1.7!_ Por defecto, el bono se aplica a cualquier tipo de producto, ya tenga descuento o no. Al habilitar esta función, el cupón que estás creando no se aplicará a un producto o combinación si ya está en oferta.
* **Envía un regalo gratis**. Puede optar por ofrecer un regalo bajo algunas condiciones (y omitir el descuento por completo). Aparece un campo: escriba las primeras letras del producto y elija de la lista de nombres coincidentes.

Una vez que todo se haya guardado, puede enviar su código de cupón a sus clientes o dejar que el sistema maneje las reglas del carrito automáticamente, según su configuración.

Su cupón aparecerá en la página "Reglas del carrito", en el menú "Reglas de precios". Puedes eliminarlo o editarlo en cualquier momento. Si el cupón se configuró para un grupo o cliente específico, aparecerá en la oficina principal, en la sección "Cupones" de su cuenta del cliente, así como en el carrito (si así lo desea), donde podrá elegir cuál aplicar a su pedido.

![](<../../../.gitbook/assets/51839849 (1) (2).png>)

![](<../../../.gitbook/assets/51839850 (3) (3).png>)

Las reglas del carrito que están configuradas para aplicarse a todos los clientes no aparecen en la página "Mis cupones" del cliente: él o ella debe conocerlas para poder utilizarlas. Depende de usted informarles sobre estos descuentos públicos.

Para aplicar la regla del carrito, el cliente debe visitar su carrito e ingresar el cupón en el campo "¿Tiene un código de promoción?" y haga clic en "Agregar". El cliente no podrá aplicar el bono si el check-out ya está validado.

Una vez aplicado, el resumen del carrito muestra el impacto del cupón en el monto del pedido.

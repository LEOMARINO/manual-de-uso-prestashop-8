# Reglas de precios del catálogo

Las reglas de precios del catálogo le permiten asignar reducciones de precios por categoría, marca, proveedor, atributo o característica. Como su nombre lo indica, este tipo de reglas se aplican a una variedad de productos; no se puede utilizar para un solo producto. Si necesita que se aplique un descuento a un solo producto, debe crear una regla de carrito o crear un precio específico (en la pestaña "Precios" de la página de edición del producto).

Por ejemplo, puedes establecer una regla que diga que los clientes españoles que pertenezcan al grupo "Buenos clientes" obtendrán un 10% de descuento en tu categoría de electrónica y en todos los productos Sony durante la primera semana de julio.

La página "Reglas de precios del catálogo" enumera las reglas existentes actualmente, que puede editar o eliminar haciendo clic en los botones de acción. Si necesita deshabilitar una regla, simplemente cambie su fecha de finalización al día anterior.

## Creando una nueva regla de precio de catálogo <a href="#catalogpricerules-creatinganewcatalogpricerule" id="catalogpricerules-creatinganewcatalogpricerule"></a>

La página del formulario de creación tiene dos secciones que le permiten crear nuevas reglas con precisión.

### Reglas de precios de catálogo <a href="#catalogpricerules-catalogpricerules.1" id="catalogpricerules-catalogpricerules.1"></a>

La primera forma es fácil de entender.

![](<../../../.gitbook/assets/51839309 (3) (3) (3).png>)

Aquí es donde estableces quién debería beneficiarse de la regla, cuál debería ser el descuento y otros detalles.

* **Nombre**. El nombre es público, por lo que debes mantenerlo informal.
* **Comercio**. _¡Solo modo multitienda!_ La regla se aplica a los clientes que compran a través de una tienda específica. Sólo disponible si tienes al menos dos tiendas.
* **Divisa**. La regla se aplica a los clientes que configuran el pago con una moneda específica.
* **País**. La regla se aplica a clientes de un país específico.
* **Grupo**. La regla se aplica a los clientes que pertenecen a un grupo de clientes específico.
* **De cantidad.** La regla se aplica si el pedido tiene al menos una cantidad específica de productos coincidentes.
* **Precio (sin IVA).** El nuevo precio para la selección de productos. Aquí puedes establecer el precio público de los productos que coincidan con las reglas que estás implementando. Por defecto, la regla se aplica al precio fijado inicialmente.
* **Desde y hacia**. La regla se aplica en este período de tiempo.
* **Tipo de reducción.** El descuento puede ser una cantidad de dinero o un porcentaje del total del pedido.
* **Reducción con o sin impuestos.** El descuento puede incluir el impuesto o dejar el impuesto como está.
* **Reducción**. El valor de la reducción. Dependiendo del "Tipo de reducción" anterior, poner "10.0" en el campo puede significar "$10 de descuento" (dependiendo de la moneda predeterminada) o "10% de descuento".

Por supuesto, puedes combinar todas estas reglas.

### Condiciones <a href="#catalogpricerules-conditions" id="catalogpricerules-conditions"></a>

La sección "Condiciones" es donde estableces los productos a los que se aplica la regla de precio de categoría. Solo aparece si haces clic en el botón "Agregar un nuevo grupo de condiciones".

Si no se establecen condiciones, la regla de precio se aplicará a TODOS los productos de su catálogo. ¡Cuidado con no olvidar las condiciones!

![](<../../../.gitbook/assets/51839310 (3) (3) (1).png>)

Las condiciones se crean en torno a grupos de condiciones, lo que significa que los datos de la sección "Regla de precios del catálogo" anterior se pueden aplicar a muchas gamas diferentes de productos. Las condiciones se agrupan de forma inclusiva: tienen que aplicarse todas las condiciones del grupo para que se aplique el precio de catálogo. De ahí el "Y". Mientras tanto, los grupos de condiciones son exclusivos: solo tiene que aplicar un grupo para que se aplique el precio del catálogo. De ahí el "O".

El grupo de condiciones predeterminado está vacío. Puede agregarle condiciones usando los menús desplegables en la parte inferior de la sección:

* Elija una categoría o cualquier otro tipo de selección y luego haga clic en el botón "Agregar condición".
* La condición aparecerá en el grupo de condiciones. Puede poner muchas condiciones en un grupo de condiciones.
* Una vez que se completa un grupo y desea crear un nuevo grupo de condiciones, haga clic en "Agregar nuevo grupo de condiciones". Entonces aparecerá un nuevo grupo, que podrás completar de la misma forma.

De forma predeterminada, las nuevas condiciones se agregan al grupo de condiciones que se creó por última vez. Si necesita agregar condiciones a un grupo anterior, haga clic en ese grupo para resaltarlo y luego agregue sus condiciones.

Actualmente no puede eliminar un grupo de condiciones.

# States

Por "Estados", PrestaShop llama a las divisiones administrativas de primer nivel de un país. En Estados Unidos se les llama estados; en Italia es _regioni_ (singular: _regione_); en Francia, es _régions_; en el Reino Unido, es _regiones_. \
De forma predeterminada, PrestaShop le proporciona un conjunto de estados: 54 estados y territorios de EE. UU., 31 _estados_ mexicanos, 13 provincias y territorios canadienses, 34 _provinsi_ de Indonesia, 24 _provincias_ argentinas, 47 _todōfuken_ japoneses y 110 _provincias_ italianas (singular: _provincia_).

![](<../../../.gitbook/assets/23789709 (4) (4).png>)

Tener estados correctamente definidos en su base de datos ayuda a representar mejor las posibilidades de entrega de sus transportistas. Estos estados también pueden ser esenciales para el cálculo de las tasas impositivas, según el país. Por lo tanto, es importante ingresar todas las divisiones administrativas de un país determinado si son importantes para sus operadores. Puede encontrar una lista de dichas divisiones en esta página de Wikipedia: [http://en.wikipedia.org/wiki/Table\_of\_administrative\_divisions\_by\_country](http://en.wikipedia.org/wiki/Table\_of\_administrative\_divisions\_by\_country).

Actualmente, el formulario de dirección de PrestaShop solo enumera los estados que están disponibles para que el cliente elija. Por lo tanto, asegúrese de utilizar una lista sensata al agregar contenido a su lista de estados. Ésa es la razón por la que, por ejemplo, la lista contiene la _provincia_ italiana (second-level administrative divisions) en lugar de la _regioni_ (first-level administrative divisions).

## Adding a New State <a href="#states-addinganewstate" id="states-addinganewstate"></a>

Creemos un nuevo estado. Haga clic en el botón "Agregar nuevo estado" para acceder al formulario de creación.

![](<../../../.gitbook/assets/23789711 (4) (3).png>)

* **Nombre**. El nombre del estado, tal como debe aparecer en las facturas y en el paquete. Por lo tanto, debería estar en el idioma del país del estado.
* **Código ISO**. El código ISO-3166-2 del estado:
  1. Vaya a esta página de Wikipedia: [http://en.wikipedia.org/wiki/ISO\_3166-2](http://en.wikipedia.org/wiki/ISO\_3166-2),
  2. Haga clic en el código de dos letras del país del estado (in the "Entry" column of the main table of the above mentioned Wikipedia page),
  3. En esa misma página, busque el código del estado (it should be in a list on the page, or in the text for the smallest countries),
  4. Si lo hay, elimine el prefijo del país para mantener el código en menos de 4 caracteres. Por ejemplo, la norma ISO 3166-2 completa para Devon, en el Reino Unido, es "GB-DEV". Simplemente utilice "DEV" como código ISO del estado; ya está adjunto al país mediante la lista desplegable "País" de PrestaShop (see next step).
* **País**. Indique su país utilizando la lista desplegable.
* **Zona**. Indique su zona geográfica mediante la lista desplegable. Preste atención a no utilizar la zona incorrecta, ya que esto puede confundir la configuración de país y zona de PrestaShop.
* **Estado**. No se sugerirá un estado deshabilitado como opción cuando un visitante quiera registrarse y crear una nueva cuenta.

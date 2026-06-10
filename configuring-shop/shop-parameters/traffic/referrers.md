# Referrers

Un referente significa un sitio web que le brinda al menos un visitante. Este sitio web incluye un enlace a su tienda y, por lo tanto, le ayuda a crear una audiencia y, finalmente, a realizar más ventas.

![](<../../../.gitbook/assets/43089936 (4) (4) (3).png>)

Algunas referencias son más importantes para usted que otras: es posible que tenga socios que tengan enlaces a su tienda en su propio sitio web, y tanto usted como sus socios seguramente querrán saber cuántos visitantes les trajeron esos enlaces. Incluso podrías pagar a tus socios para que muestren un enlace a tu tienda, dependiendo de cuánto valoras tu tráfico.\
Esto, en efecto, se llama afiliación, y la página "Recomendadores" le ayuda a crear un programa de afiliados completo, al que incluso su socio puede conectarse para ver el número de visitas y ventas que han generado sus enlaces. Los afiliados registrados generan tráfico a su tienda, desea recompensarlos por esos visitantes y el programa de afiliados es la forma en que ambos pueden acceder a las cifras en las que se basa la recompensa.

La herramienta de referencia de PrestaShop se puede comparar con la de un panel estadístico abierto a otras personas además de los miembros de su personal. Cuando crea una campaña de afiliados para un sitio, puede otorgarle a ese sitio acceso a toda la actividad que habrá realizado para su sitio, a través de una URL protegida con contraseña: [http://example.com/modules/trackingfront/stats.php](http://example.com/modules/trackingfront/stats.php).

En la lista de referentes, los valores de clic, base y porcentaje se calculan según los clics reales, las ventas y el porcentaje de ventas del sitio de referencia.

## Adding a new referrer <a href="#referrers-addinganewreferrer" id="referrers-addinganewreferrer"></a>

El espacio de afiliados le permite crear un acceso privilegiado para sus socios. Tendrán acceso a todas las estadísticas sobre el flujo de visitantes desde su sitio a su tienda online. Para crear su espacio privilegiado, debes crear su cuenta en tu programa de afiliación y luego definir cómo pagarás en función del tráfico y las ventas generadas.

Para crear un nuevo socio afiliado, haga clic en el botón "Agregar nuevo", que lo llevará al formulario de creación de afiliados.

![](<../../../.gitbook/assets/43089930 (4) (4) (3).png>)

Each section is important:

* **Filial**. La cuenta del socio en su programa de afiliación.
  * **Nombre**. Para conectarse a su back office de afiliación, su socio necesita un nombre de inicio de sesión; Puedes usar un nombre simple o un correo electrónico, pero asegúrate de usar algo que tanto tú como tu pareja puedan recordar fácilmente.
  * **Contraseña**. La primera vez que crea la cuenta, PrestaShop guarda la contraseña junto con el nombre de inicio de sesión. Cuando necesite editar la cuenta (for instance, when needing to change the commission), la contraseña estará en blanco. Esto no significa que no haya contraseña; Si completa el campo en blanco al editar la cuenta, cambiará la contraseña.
* **Plan de comisiones**. Aquí es donde usted indica las tarifas de su afiliado, es decir, el dinero que le deberá a su socio por las acciones de los visitantes de su sitio.
  * **Tarifa por clic**. Esto define cuánto estima que vale un visitante del sitio de este socio. Cada vez que un visitante del sitio de su socio llega a su tienda haciendo clic en su enlace, el socio gana la cantidad marcada.
  * **Tarifa base**. También puede recompensar a sus socios si los visitantes de sus sitios compran uno de sus productos. Tenga en cuenta que esto sólo es válido si la compra se realiza durante la sesión de navegación que sigue al clic en el enlace del socio.
  * **Tarifa porcentual**. Además de la tarifa base, o como reemplazo, puedes recompensar a los socios con un porcentaje de las ventas realizadas durante la sesión de navegación de los visitantes de sus sitios.
* **Información técnica - Modo simple**. Esto es muy importante, ya que es lo que hará que el sistema diferencie a este socio de otros enlaces de referencia. Una vez configurado, debes realizar un par de pruebas para asegurarte de que estás rastreando al afiliado correctamente.
  * **Referente HTTP**. En el campo "Incluir", establezca el nombre de dominio del socio que desea rastrear como su dominio afiliado.
  * **Solicitar URI**. En el campo "Incluir", establezca la última parte de la cadena de consulta. El sistema rastreará las referencias que utilizan una cadena de consulta especial. Por ejemplo, puede realizar un seguimiento de las referencias que utilizan el argumento `?prestaff=` en su URL. Esto puede ayudarle a diferenciar aún más a los referentes.
* **Información técnica - Modo experto**. Mientras que el modo simple relaciona palabras usando la función "ME GUSTA" de MySQL, el modo experto le permite usar expresiones regulares de MySQL. Esto puede resultar muy poderoso pero también muy difícil de mantener. Asegúrese de dominar el tema de las expresiones regulares antes de poner algo en estos campos.

![](<../../../.gitbook/assets/43089933 (4) (4) (3).png>)

La sección "Ayuda" le ofrece valiosas indicaciones sobre cómo configurar mejor su afiliado. Léelo completo.

## Configuración <a href="#referrers-settings" id="referrers-settings"></a>

Las configuraciones de referencia son en su mayoría herramientas que lo ayudarán a aprovechar al máximo su programa de afiliados.

![](<../../../.gitbook/assets/43089934 (4) (4) (2).png>)

There are three possibilities:

* **Indexación**. Debe hacer clic una vez en el botón "Actualizar índice" cuando agregue un nuevo referente y desee analizar su tráfico anterior para este nuevo referente.
* **Cache**. PrestaShop almacena en caché los datos que recopila. Puede utilizar el botón "Actualizar caché" para actualizar periódicamente su caché de datos.
* **¿Ahorrar tráfico directo?**. El tráfico directo representa a los visitantes que llegan directamente a su tienda escribiendo su URL en su navegador. Si bien estos son importantes porque son visitantes que realmente conocen su tienda y están interesados ​​en sus productos (contrary to visitors with referrer, who might have simply stumble upon your shop by chance), ahorrar este tráfico puede afectar enormemente su base de datos. Es por eso que este tráfico no se guarda ni analiza de forma predeterminada. Habilite esta opción solo si sabe lo que está haciendo.

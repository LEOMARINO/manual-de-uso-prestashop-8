# Currencies

PrestaShop admite una gran cantidad de monedas. De forma predeterminada, solo se registra una moneda para su tienda, es decir, la moneda del país predeterminado de su tienda. Sin embargo, puede agregar y configurar nuevas monedas para satisfacer mejor las necesidades de sus clientes. De hecho, ¡los clientes apreciarán poder comprar en su propia moneda!&#x20;

![](https://lh5.googleusercontent.com/iiCDXDmk8RoXR0En6n\_bc03N-lLM3NmuJJCktD4wGN\_G0vAFoJdNmynUY0heLJxRmX2ZNB8OVTQmmZhMUv5ExaS6gFdijTpYZajM5ibWlcUN4rbUg2GLQfgIK1iAmem1KkpeX2Z6)

## **Cambiar la moneda predeterminada**&#x20;

Todos los tipos de cambio de las monedas agregadas (official or alternative) se calculan a partir de una unidad de la moneda predeterminada de su tienda. Es por eso que la moneda predeterminada debe ser aquella en la que se sienta más cómodo.

Para cambiar la moneda predeterminada de tu tienda:

1. Vaya a la página Internacional > Localización
2. Consulte la función "Moneda predeterminada" en la sección Configuración
3. Seleccione la moneda que desea establecer como predeterminada

![](<../../../.gitbook/assets/image (2) (2) (1).png>)

Si la moneda que desea establecer como predeterminada no está disponible, deberá agregarla ya sea importando el paquete de localización de un país que utiliza esta moneda o completando el formulario “Agregar una nueva moneda” (See “Adding a new currency”).&#x20;

## **Adding a new currency**

There are two ways of adding a new currency:&#x20;

### 1. Importa el paquete de localización de un país usando esta moneda.

Esto se puede hacer en la página "Localización" del menú "Internacional".&#x20;

![](https://lh3.googleusercontent.com/khKRlRUevgK7s0Vrznpy4RAt0O70EdqiilLjnssnmus\_4O8DVTqbTTomkKpDgkMtZCDvADgceWhHr\_Cv7FO7r2oQV5dPe906WQxnNSC6B2fTyc4V-QX8SGwrpAY3X4DHEjhxdqR6)

Por ejemplo, si desea agregar el dinar argelino, puede importar el paquete de localización de Argelia.

Al importar un paquete de localización, el idioma y la moneda estarán habilitados de forma predeterminada. Una vez importada, puede administrar el estado de la moneda en la página "Monedas".&#x20;

### 2. Agrega la moneda manualmente

Haga clic en el botón "Agregar una moneda". Seleccione la moneda que desea agregar de la lista. Los campos se completarán automáticamente.&#x20;

De forma predeterminada, la moneda está deshabilitada. Para activarlo en tu tienda, no olvides cambiar el botón Estado a "Sí" y guardar.

## **Creating an alternative currency**&#x20;

Es posible que necesites agregar una moneda que no esté incluida en ninguno de los paquetes de localización o que no esté disponible en la lista de monedas. Utilice esta función para agregar cualquier criptomoneda, moneda local, etc. que satisfaga las necesidades de sus clientes.

1. Haga clic en el botón "Agregar una nueva moneda"
2. Marque la casilla "Crear una moneda alternativa"&#x20;
3. Complete los campos:

![](https://lh5.googleusercontent.com/dkP6rZ9vf1\_NUob3\_0PH4xvFiYbvvcIvQdwm2kFdWzi124hGirkclA\_um9eH99CZU24LLLGjk\_C5QFn8SQAip-DCFCIlFCuWTq58r42Bx1P\_NL4zRou6SDHd8M7FIX7vgkl23Jxb)

* **Nombre de la moneda.** Ingrese el nombre de la moneda.&#x20;
* **Código ISO.** Introduzca el código ISO de moneda 4217. Consulte [Wikipedia] (https://en.wikipedia.org/wiki/ISO\_4217#Active\_codes) para obtener más información. También podrás encontrar códigos ISO no oficiales de monedas alternativas, como Bitcoin.
* **Tipo de cambio.** Este tipo de cambio se definirá según la moneda predeterminada de su tienda. Por ejemplo, si la moneda predeterminada es el euro y la moneda elegida es el dólar, escriba "1,20" (1€ = $1.20).
* **Decimales.** Número de dígitos que siguen al punto decimal para los precios de tu tienda.
* **Estado.** Cualquier moneda se puede desactivar en cualquier momento, tanto desde la página de edición como desde la lista de monedas en la página "Monedas". Cuando crea una nueva moneda utilizando el formulario "Agregar una nueva moneda", está deshabilitado de forma predeterminada.&#x20;

## **Edición de símbolos y formato**&#x20;

Puedes personalizar el formato y el símbolo de cada moneda dependiendo de los idiomas de tu tienda (both the activated and deactivated ones).

Al editar una moneda, en la parte inferior de la página, elija el idioma para el cual desea modificar el símbolo y/o formato de la moneda y haga clic en “Editar símbolo/formato”.&#x20;

Ingrese el símbolo de moneda y elija el formato:

* justo delante de la cantidad, p.e. □999.99
* delante con un espacio entre el símbolo y la cantidad, p.e. □ 999,99
* justo después de la cantidad, p.e. 999.99□
* después de la cantidad con un espacio entre ellos, p.e. 999,99 □

El cuadrado blanco será reemplazado por el símbolo de la moneda una vez que se complete el campo "Símbolo".

Please note that this feature is only available when editing a currency.&#x20;

## **Updating currency rates**

Un tipo de cambio de moneda, o tipo de conversión, es el tipo al que se cambiará una moneda por otra. Por ejemplo, un tipo de conversión EUR/USD de 1,22 significa que 1 euro equivale a 1,22 dólares.

Si un producto cuesta 15 euros, costará 18,30 dólares. (15\*1,22 = 18,3)&#x20;

Por el contrario, si un producto cuesta 15 dólares, costará 12,30 euros. (15/1,22 = 12,3)

{% hint style="info" %}
Las tarifas en PrestaShop las proporciona Fixer ([https://fixer.io/](https://fixer.io/)) y se actualizan todos los días. Sin embargo, tenga en cuenta que pueden diferir ligeramente de las actuales, ya que estas tarifas pueden fluctuar mucho en poco tiempo.
{% endhint %}

No olvides actualizar periódicamente las tarifas, siguiendo estos pasos:&#x20;

![](https://lh5.googleusercontent.com/qopylC5ZST5Xkv9RgCaVWMfCeX9ckAEqJyNolSM8iat18FGsMn7LG7KYhqrUEyTwXw-ufLYQRg9U\_YGBn-Bk8iD5JJRtdwlFzlaluNnDAeDWQtOIbx\_gdiTnm7Nn0OaWm6xMr5nF)

Al hacer clic en el botón “Actualizar” se actualizarán automáticamente los tipos de cambio de las monedas de su tienda:

1. Vaya a la sección "Tipo de cambio" de la página "Monedas"
2. Haga clic en el botón “Actualizar” &#x20;

{% hint style="warning" %}
Los tipos de cambio de las monedas personalizadas no se actualizarán automáticamente, por lo que tendrás que actualizarlos manualmente. Por ejemplo, si agregó Bitcoin y desea actualizar el tipo de cambio, haga clic en el lápiz para modificar la moneda en el listado de Monedas e ingrese el tipo de cambio en el campo correspondiente. Por lo tanto, para monedas alternativas muy volátiles, se recomienda encarecidamente utilizar un módulo que pueda actualizar automáticamente el tipo de cambio.
{% endhint %}

\
Una simple búsqueda en Internet suele ser suficiente para encontrar el tipo de cambio de moneda. Hay muchos convertidores en línea que puedes usar, como XE.com:&#x20;

[https://www.xe.com/currencyconverter/convert/?Amount=1\&From=XBT\&To=USD](https://www.xe.com/currencyconverter/convert/?Amount=1\&From=XBT\&To=USD)

Para criptomonedas, puede visitar los siguientes sitios web: [https://coinmarketcap.com/](https://coinmarketcap.com/) \

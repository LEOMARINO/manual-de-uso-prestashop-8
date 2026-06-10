# Logs

Los errores ocurren. La mayoría de las veces, no eres consciente de ellos porque PrestaShop los maneja en silencio. Pero quizás quieras conocerlos para poder corregir los más habituales y asegurar una mayor estabilidad a tu tienda.

![](<../../.gitbook/assets/43417626 (4) (2) (3).png>)

La página "Registros" es donde puedes echar un vistazo a todas las acciones realizadas en tu tienda y así encontrar los errores de PHP que podrían afectar a tu tienda. Se enumeran en la tabla central de la página y se presentan en 4 niveles:

* **1: Sólo informativo**. Avisos en tiempo de ejecución. Indique que el script encontró algo que podría indicar un error, pero que también podría ocurrir en el curso normal de la ejecución de un script.
* **2: Advertencia**. Advertencias en tiempo de ejecución (non-fatal errors). La ejecución del script no se detiene.
* **3: Error**.
* **4: ¡Problema importante (crash)!**. Errores fatales en tiempo de ejecución. Estos indican errores de los que no se puede recuperar, como un problema de asignación de memoria. La ejecución del script se detiene.

Estas explicaciones son las oficiales del manual de PHP. Leer más: [http://www.php.net/manual/en/errorfunc.constants.php](http://www.php.net/manual/en/errorfunc.constants.php).

## Logs by e-mail <a href="#logs-logsbye-mail" id="logs-logsbye-mail"></a>

Los niveles de error también sirven como valores para la función "Registros por correo electrónico".\
PrestaShop añade un último valor, 5, que indica que el administrador no quiere recibir ninguna notificación, ya sea por errores menores o mayores.

![](<../../.gitbook/assets/23789888 (4) (4) (1).png>)

La herramienta de registro de errores le permite recibir una notificación por correo electrónico cuando se produce un error. Las notificaciones se envían a la dirección de correo electrónico del propietario de la tienda, y puedes configurar el grado de importancia con el que debes empezar a recibir dichos correos electrónicos:

* "1" si quieres saberlo todo, hasta el más mínimo dato.
* "3" si solo desea conocer los problemas (errors and major issues).
* "4" si sólo desea conservar los temas principales.
* "5" es el valor predeterminado, lo que significa que no se envía ninguna notificación.

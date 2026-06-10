# Search Engines

Muchos de sus visitantes procederán de motores de búsqueda. Para saber qué estaban buscando y cómo puedes mejorar tu tienda para sus consultas de búsqueda, necesitas conocer sus consultas.

Esta página presenta una tabla de todos los motores de búsqueda que admite su instalación de PrestaShop, lo que significa que PrestaShop puede reconocerlo y extraer la consulta que el visitante de ese motor de búsqueda determinado utilizó para encontrar su tienda.

![](<../../../.gitbook/assets/23789937 (4) (4) (2).png>)

Si bien Google tiene la mayor proporción de usuarios de motores de búsqueda, existen muchos otros motores de búsqueda que las personas pueden utilizar para encontrar su sitio web. Por lo tanto, también debe poder recuperar sus solicitudes de búsqueda. Cuando un motor de búsqueda desconocido comienza a atraer visitantes regulares, ya es hora de agregarlo a su base de datos; de lo contrario, esos visitantes se marcarían en sus estadísticas como provenientes de "Otros motores de búsqueda", lo cual no ayuda en absoluto.

## Adding a Search Engine <a href="#searchengines-addingasearchengine" id="searchengines-addingasearchengine"></a>

Es muy sencillo agregar un nuevo motor de búsqueda a tu lista.

![](<../../../.gitbook/assets/23789939 (4) (4) (4).png>)

Supongamos que desea agregar DuckDuckGo, un motor de búsqueda que enfatiza su respeto por la privacidad de los datos:

1. Obtenga la URL de referencia completa para la búsqueda. Por ejemplo, [http://duckduckgo.com/?q=kids+shoes](http://duckduckgo.com/?q=kids+shoes)
2. Tome el nombre de dominio, que es específico de ese motor de búsqueda, y colóquelo en el campo "Servidor". En nuestro caso, "patopatogo".
3. Encuentre la variable de consulta:
   1. Busque la cadena de consulta. Debe ser un conjunto de letras, seguido de un signo "=", seguido de la consulta misma, cerrada por un "&" o el final de la cadena. En nuestro caso, es "q=niños+zapatos".
   2. La variable de consulta es el conjunto de letras antes del signo "=". En nuestro caso: "q". Ponlo en el campo "$\_GET variable".
4. Haga clic en el botón "Guardar" y, a partir de ahora, PrestaShop podrá reconocer a los visitantes de DuckDuckGo.

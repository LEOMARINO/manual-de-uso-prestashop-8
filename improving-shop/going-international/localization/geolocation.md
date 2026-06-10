# Geolocation

La geolocalización es "_la identificación de la ubicación geográfica real de un objeto, como un radar, un teléfono móvil o una computadora conectada a Internet_" (read more on [Wikipedia](http://en.wikipedia.org/wiki/Geolocation)). En nuestro caso, la geolocalización se utiliza para descubrir la ubicación de un visitante, utilizando la IP de su ordenador y otras herramientas. Uno de los usos de la geolocalización es bloquear visitantes de determinadas ciudades/países.

Como se indicó la primera vez que abre la página "Geolocalización", para utilizar la geolocalización, primero debe descargar un archivo especial: [http://geolite.maxmind.com/download/geoip/database/GeoLiteCity.dat.gz](http://geolite.maxmind.com/download/geoip/database/GeoLiteCity.dat.gz). Este archivo es la base de datos GeoLite City de MaxMind, una base de datos precisa de ciudades y ubicaciones. Descárgalo haciendo clic en el enlace y luego descomprímelo en el directorio `/tools/geoip/` de tu instalación de PrestaShop. Una vez que el archivo esté en su lugar, habilite la opción "Geolocalización por dirección IP" y listo.

![](<../../../.gitbook/assets/64225610 (4) (4).png>)

## Options <a href="#geolocation-options" id="geolocation-options"></a>

Puedes elegir qué países pueden acceder a tu tienda (by default, all of them) y configurar los comportamientos de PrestaShop para países restringidos y no restringidos (or "other" countries). Tú eliges entre estas tres opciones:

* Los visitantes no pueden ver su catálogo.
* Los visitantes pueden ver su catálogo pero no pueden realizar un pedido. En efecto, tu tienda está en "Modo Catálogo".
* All features are available (only for unrestricted countries).\
  \
  ![](<../../../.gitbook/assets/64225611 (4) (2) (1).png>)

Puede seleccionar o anular la selección de todos los países a la vez marcando la casilla en la parte superior de la lista (next to "Name"). Al seleccionar los países que pueden acceder a tu tienda online, asegúrate de no bloquear ningún país por error, ¡ya que perderías todas las ventas potenciales a sus habitantes!

## Whitelist of IP address <a href="#geolocation-whitelistofipaddress" id="geolocation-whitelistofipaddress"></a>

Esta sección le permite aceptar direcciones IP específicas a pesar de un bloqueo. Puede resultar útil en caso de spammers, bots o ataques. Ya está lleno de una lista de IP buenas conocidas. Agregue tantos como necesite, uno por línea, y haga clic en "Guardar".

![](<../../../.gitbook/assets/64225612 (4) (3) (3).png>)

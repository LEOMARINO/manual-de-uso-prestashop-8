# Módulos instalados

En esta página podrás instalar, desinstalar, configurar y actualizar cada uno de tus módulos. Este capítulo simplemente explica cómo puede administrar sus módulos desde la pestaña "Módulos instalados".

![](<../../../.gitbook/assets/51185201 (5) (3).png>)

## La lista de módulos <a href="#installedmodules-themoduleslist" id="installedmodules-themoduleslist"></a>

Esta lista le permite encontrar rápidamente el módulo que desea configurar o editar.

It is divided into 3 sections:

* **Módulos instalados**. Estos son todos los módulos que has añadido a tu tienda, ya sea comprándolos en PrestaShop Addons o subiéndolos directamente.
* **Módulos incorporados**. Estos módulos de PrestaShop están preinstalados cuando configura su tienda. Cubren los conceptos básicos del comercio electrónico y son gratuitos.
* **Módulos temáticos**. Cada tema que instales vendrá con su propio conjunto de módulos. Encontrarás aquí todos los módulos relacionados con tu tema activo.

Si desea encontrar rápidamente un módulo, puede buscar un módulo específico o filtrar los módulos hasta encontrar el que está buscando.

![](<../../../.gitbook/assets/51185200 (5) (2) (4).png>)

* **Campo de búsqueda**. Busca un módulo por su nombre, autor o por palabras clave.
* **Ordenar selectores**. La lista se recarga automáticamente cuando realiza una selección y muestra los módulos de acuerdo con todas las configuraciones actuales.
  * **Categorías**. A la izquierda hay una lista de todas las categorías de módulos, con el número de módulos para cada una entre paréntesis. Haga clic en una categoría para mostrar los módulos de esta categoría.
  * **Mostrar todos los módulos.** Le permite elegir entre módulos habilitados y deshabilitados. Los módulos habilitados son los únicos que se pueden configurar, de ahí la importancia de este selector.
  * **Instalado y no instalado**. La mayoría de las veces, querrás realizar una acción en un módulo instalado o instalar uno nuevo. Este filtro es el más utilizado.
  * **Último acceso.** Si usas los mismos módulos con frecuencia, esta opción hará que sea más fácil encontrar los módulos más recientes en los que has estado trabajando.
  * **Nombre**. Ordena los módulos por orden alfabético, de la A a la Z.

Los módulos pueden tener uno de 4 estados:

* Non-installed.
* Installed but disabled
* Instalado y habilitado.
* Instalado y habilitado, pero con advertencias.\
  \


Diferencia entre deshabilitar y desinstalar

Cuando ya no tenga uso para un módulo, puede desactivarlo o desinstalarlo. Los resultados de ambas acciones son aparentemente los mismos: el módulo ya no está disponible, sus opciones no aparecen en tu back office y cualquier elemento que haya agregado a tu front-end ha desaparecido.

La diferencia es que deshabilitar un módulo mantiene su configuración segura para volver a habilitarlo más tarde, mientras que al desinstalarlo se elimina toda su configuración y datos de base de datos. Se eliminarán todos los archivos del módulo.

Por lo tanto, sólo debes desinstalar un módulo si no te importan sus datos o si estás seguro de que no lo necesitarás. Es como borrarlo para siempre.

## Realizar acciones en los módulos <a href="#installedmodules-performingactionsonmodules" id="installedmodules-performingactionsonmodules"></a>

Estas son las acciones disponibles, según el estado del módulo:

* Módulos desinstalados:
  * **Instalar**. Esto activará la instalación del módulo en su instalación de PrestaShop. El módulo se habilitará automáticamente.\
    \

* Módulos instalados:
  * **Mejora**. Su instalación de PrestaShop verifica periódicamente con el servidor de complementos si hay alguna actualización para sus módulos. Si es así, el botón de acción pasa a ser "Actualizar" para los módulos afectados. Simplemente haz clic en él y PrestaShop se encargará de descargar y actualizar el módulo.
  * **Permitir**. Para módulos que han sido anteriormente deshabilitados. Una vez habilitado nuevamente, podría agregar nuevas opciones a su back office.
    * **Habilitar en dispositivos móviles**. Esto habilitará la vista de front office del módulo solo para dispositivos móviles (smartphones, etc.).
  * **Configurar**. Algunos módulos tienen una página de configuración. En ese caso, ofrecen un enlace "Configurar" para acceder a una nueva interfaz donde el usuario podrá ajustar todas sus configuraciones.
  * **Desactivar**. Cuando se instala, un módulo está habilitado de forma predeterminada. Puede desactivarlo, lo que eliminará sus opciones de su back office pero mantendrá su configuración para volver a habilitarlo más adelante.
    * **Desactivar en móvil**. Esto deshabilitará la vista de front office del módulo solo para dispositivos móviles (smartphones, etc.).
  * **Reiniciar**. Esto restaurará la configuración del módulo a sus valores predeterminados.
  * **Desinstalar**. Esto desactivará el módulo. Para eliminar también todos sus archivos y datos, debe seleccionar la opción "Eliminar carpeta del módulo después de la desinstalación".

Estas acciones se pueden realizar de forma individual en cada módulo o de forma masiva gracias al menú "Acciones masivas" de la derecha.

### Desinstalación de un módulo <a href="#installedmodules-uninstallingamodule" id="installedmodules-uninstallingamodule"></a>

**¡Nunca elimines un módulo tirando directamente a la papelera su carpeta usando tu cliente FTP!** Debes dejar que PrestaShop se haga cargo de ello.

Cuando necesite dejar de usar temporalmente un módulo, pero aún desee mantener su configuración, simplemente puede desactivarlo: simplemente haga clic en el enlace "Desactivar". Las acciones se convertirán en "Habilitar" y "Eliminar", pero aún se podrá ver el botón "Desinstalar".

Si no le importa la configuración del módulo, haga clic en el botón "Desinstalar": la carpeta de su módulo seguirá estando en la carpeta `/modules`, pero el módulo ya no tendrá ningún impacto en su tienda.\
Si desea eliminar completamente el módulo de su servidor, haga clic en el enlace "Eliminar": PrestaShop eliminará su carpeta y todos sus archivos.

Asegúrese de que la desactivación o eliminación del módulo no rompa el tema.

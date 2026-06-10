# Database Backup

Una copia de seguridad es la acción de guardar el contenido de su base de datos en archivos que almacena en un lugar seguro. El punto es que puede volver a ellos en caso de que su base de datos falle.

Debes realizar copias de seguridad periódicas de tu tienda, para que, en caso de fallo, puedas reiniciar tu tienda rápidamente y en las mejores condiciones. La base de datos contiene la mayor parte de la información de su tienda, mucha de la cual es indispensable para que PrestaShop funcione correctamente, incluidos sus productos, categorías y otros datos que agregó desde la instalación, pero no sus imágenes, por ejemplo (these are stored, along with your theme files, on your server).

Cuanto más a menudo realice una copia de seguridad, más seguro estará. Una vez por semana es una frecuencia mínima.

Para crear copias de seguridad de la base de datos de tu tienda, tienes varias soluciones. Puedes utilizar herramientas como phpMyAdmin (reserved for advanced users), o utilizar la integrada en PrestaShop: la página "Copia de seguridad de la base de datos".

La página comienza con dos grandes avisos. Debes leer ambos completamente para tener una mejor idea de lo que hace la página:

* La sección "Descargo de responsabilidad" le brinda una serie de recordatorios sobre las copias de seguridad, que debe leer cada vez que realice una copia de seguridad. La sección termina con el botón "He leído el descargo de responsabilidad. Cree una nueva copia de seguridad", en el que debe hacer clic para crear una copia de seguridad. Una vez creada, la copia de seguridad aparece en una nueva "sección de Descargas" en la parte superior de la página (click the button in order to download the backup file to your computer), y en la lista debajo de los avisos.
* La sección "Cómo restaurar" le brinda consejos sobre cómo recuperar sus datos en PrestaShop en caso de falla. Debe guardar esto en la memoria, o al menos guardar esta información en algún lugar en caso de que una falla de la base de datos le imposibilite acceder a la administración de PrestaShop (y, por lo tanto, a la página de respaldo de la base de datos) nuevamente. Por si acaso, también lo encontrarás a continuación.\
  \


How to restore a database backup in 10 easy steps

1. Establezca "Habilitar tienda" en "No" en la página "Mantenimiento" en el menú "Preferencias".
2. Descargue la copia de seguridad de la lista a continuación o desde su servidor FTP (in the folder "admin/backups").
3. Verifique la integridad de la copia de seguridad: busque errores, archivos incompletos, etc. Asegúrese de verificar todos sus datos.
4. Solicite a su proveedor de alojamiento acceso "phpMyAdmin" a su base de datos.
5. Conéctese a "phpMyAdmin" y seleccione su base de datos actual.
6. A menos que haya habilitado la opción "Eliminar tablas existentes", debe eliminar todas las tablas de su base de datos actual.
7. En la parte superior de la pantalla, seleccione la pestaña "Importar"
8. Haga clic en el botón "Examinar" y seleccione el archivo de respaldo de su disco duro.
9. Verifique el tamaño de archivo máximo permitido (e.g. Max: 16MB)
10. Haga clic en el botón "Ir" y espere pacientemente a que concluya el proceso de importación. Esto puede tardar varios minutos.

La tabla debajo de los avisos enumera todas las copias de seguridad que ya se han realizado, indicando la fecha de creación, antigüedad, nombre del archivo y tamaño.\
A la derecha de cada fila están las acciones disponibles:

* **Vista**. Le permite descargar esta copia de seguridad.
* **Borrar**. Le permite eliminar esta copia de seguridad. Ojo, no hay vuelta atrás.

![](<../../../.gitbook/assets/23789873 (3) (4).png>)

Después de cada proceso de copia de seguridad, debe descargar el archivo de copia de seguridad generado haciendo clic en el ícono "Ver" o simplemente usando el enlace en el cuadro de notificación en la parte superior. Guarde su archivo de respaldo en un lugar seguro, ya que podría necesitarlo en cualquier momento. Además, puede encontrar estas copias de seguridad directamente en su servidor, en la carpeta `/backup`, debajo de su carpeta `/admin` con nombre personalizado.

Su base de datos se guarda usando el formato SQL estándar y su extensión de archivo `.sql`, y se comprime usando el algoritmo BZip2 ((simply put, a variant of the popular Zip format. Read more: [http://en.wikipedia.org/wiki/Bzip2](http://en.wikipedia.org/wiki/Bzip2)) y su extensión de archivo `.bz2`. Eso proporciona un archivo con la extensión de archivo `.sql.bz2`.

## Backup Options <a href="#databasebackup-backupoptions" id="databasebackup-backupoptions"></a>

En la parte inferior de la pantalla, hay dos opciones disponibles:

*
  * **Ignorar tablas de estadísticas**. PrestaShop almacena las estadísticas de su sitio en un puñado de tablas de bases de datos, y éstas pueden crecer con bastante rapidez. Si bien puede ser una buena idea mantener sus estadísticas en un lugar seguro, también genera archivos enormes para descargar, mientras que probablemente esté más interesado en una copia de seguridad de sus productos, categorías, clientes, pedidos, etc.
    De forma predeterminada, PrestaShop realiza una copia de seguridad de todas las tablas, pero si tiene poco espacio en el disco de su servidor web, cambie esta opción a "Sí".
  * **Elimine las tablas existentes durante la importación**. Al importar un archivo de copia de seguridad, el sistema puede sobrescribir las tablas activas existentes con el contenido de aquellas de las que se realizó una copia de seguridad o eliminar todas las existentes para reemplazarlas con el contenido de la copia de seguridad. El primer caso puede resultar en dobles, razón por la cual esta opción está habilitada de forma predeterminada.\
    \
    ![](<../../../.gitbook/assets/45580384 (4) (4) (1).png>)

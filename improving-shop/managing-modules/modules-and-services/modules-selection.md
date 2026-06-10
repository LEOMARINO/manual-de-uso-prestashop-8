# Selección de módulos

Puedes descubrir e instalar nuevos módulos para mejorar tu tienda cuando estés iniciando o haciendo crecer tu actividad.

* [Explicando módulos y servicios](modules-selection.md#what-is-the-difference-between-a-module-and-service)
* [Cargar e instalar un módulo manualmente](modules-selection.md#modulesselection-uploadingamodulemanually)
  * [Instalación mediante el formulario de carga](modules-selection.md#ModulesSelection-Installingusingtheuploadform)
  * [Instalación usando un cliente FTP](modules-selection.md#ModulesSelection-InstallingusinganFTPclient)

### ¿Cuál es la diferencia entre un módulo y un servicio?

Por un lado, **un módulo** te permite agregar funcionalidades a tu tienda, como nuevos medios de pago, sincronización de inventario y pedidos con tu logístico, exportación a guías de compra inteligentes y muchas herramientas para ti y tus clientes. Los módulos vienen con un archivo que debe instalarse en su tienda.

Por otro lado, **un servicio** es intangible: no tienes que instalar nada en tu tienda para que el servicio funcione. En su lugar, es posible que deba firmar un contrato con el proveedor de servicios.

#### **¿Qué es un módulo integrado?**

Los módulos (or native) integrados están disponibles dentro de su tienda desde su configuración. Algunos módulos ya están preinstalados para ayudar a su tienda a ejecutar (you will find them in the "Installed modules" tab), y otros puede cargarlos e instalarlos manualmente. Puedes optar por conservarlos o no, según tus necesidades. Cubren los conceptos básicos del comercio electrónico y son gratuitos.

## Cargando e instalando un módulo manualmente <a href="#modulesselection-uploadingamodulemanually" id="modulesselection-uploadingamodulemanually"></a>

#### Instalación usando el formulario de carga <a href="#modulesselection-installingusingtheuploadform" id="modulesselection-installingusingtheuploadform"></a>

Para instalar un nuevo módulo automáticamente, haga clic en el botón "Cargar un módulo" en la parte superior de la página. Se abrirá una ventana emergente.

![](<../../../.gitbook/assets/51185188 (4) (2) (4).png>)

Este bloque le permite cargar el archivo del módulo, tal como lo descargó. Puede cargar un archivo `zip` o un `tar.gz` o un (tarball). Simplemente suelte el archivo del módulo aquí o busque el archivo que descargó haciendo clic en "seleccionar archivo". No apunte a la carpeta descomprimida del módulo ni a ninguno de sus archivos descomprimidos: ¡solo el archivo comprimido!&#x20;

Una vez que se detecta el archivo, la instalación comenzará automáticamente: el software cargará el módulo desde su computadora a su servidor, lo descomprimirá, colocará los archivos en la ubicación correcta y actualizará la página, todo esto en unos pocos segundos. Luego, el software mostrará el mensaje "¡Módulo instalado!" mensaje.

![](<../../../.gitbook/assets/51185193 (6) (9) (2).gif>)

Los módulos no se instalan de forma predeterminada: aún debe hacer clic en el botón "Instalar" del módulo y luego posiblemente configurar sus ajustes a través de la pestaña "Módulos instalados".

Una vez completada la configuración, asegúrese de probar el módulo inmediatamente para confirmar que funciona según lo planeado.

#### Installing using an FTP client <a href="#modulesselection-installingusinganftpclient" id="modulesselection-installingusinganftpclient"></a>

También puede optar por instalar un módulo usted mismo, utilizando un cliente FTP.

Para instalar un nuevo módulo manualmente:

1. Descomprima (decompress) el archivo de almacenamiento del módulo (ZXQ0QXZ or ZXQ1QXZ). Esto debería resultar en una nueva carpeta.
2. Usando su cliente FTP, conéctese al servidor web PrestaShop y coloque la carpeta del módulo descomprimido en la carpeta `/modules` de su instalación.\
   Preste atención a NO cargar esa carpeta en la carpeta de otro módulo (which can happen when drag-and-dropping items). **Sube tanto la carpeta como los archivos que contiene, no solo los archivos.**
3. Ve a tu back office, en la pestaña "Selección".
4. Localice el nuevo módulo en la lista de módulos. Quizás tengas que desplazarte hacia abajo; También puede utilizar el motor de búsqueda de la lista, que debería proporcionarle una lista actualizada dinámicamente de nombres de módulos coincidentes.
5. En la fila del nuevo módulo, haga clic en el botón "Instalar".
6. Su módulo ahora está instalado y debería activarse también. Si es necesario, haga clic en el enlace "Configurar" del módulo. Además, preste atención a cualquier mensaje de advertencia que pueda aparecer en su pantalla.

Una vez completada la configuración, asegúrese de probar el módulo inmediatamente para confirmar que funciona según lo planeado.

Los módulos pueden provenir de muchas fuentes y no todas son confiables. Esta es la razón por la que el software PrestaShop a veces muestra una ventana de advertencia para módulos "no confiables", es decir, módulos que no han sido verificados por PrestaShop. Esta ventana de pantalla le permite elegir si desea continuar con la instalación sin más notificaciones o detener el proceso de instalación.

# Configuración de imagen

La página "Configuración de imágenes" le permite configurar los distintos tamaños de imágenes que sus clientes verán en su tienda. De forma predeterminada, todas las configuraciones de imágenes ya están instaladas en su tienda. ¡No los borres, lo necesitarás!

Cuando carga una imagen en PrestaShop, PrestaShop genera automáticamente varios tamaños de esta imagen, incluidas miniaturas y otras versiones más pequeñas de su imagen. Por lo tanto, sólo tienes que cargar una versión "maestra" de tu imagen, lo suficientemente grande como para cambiar su tamaño a todos los tamaños de imagen.

Si desea asegurarse de que su imagen tenga el tamaño correcto, debe cargar una imagen que se ajuste a la proporción de tamaño de los distintos tamaños de imagen. Si la imagen cargada no tiene la misma relación ancho-alto que la configuración vigente, corre el riesgo de ver espacios en blanco en la imagen redimensionada.

![](<../../.gitbook/assets/64225495 (4) (4) (3).png>)

Puede habilitar el tamaño de imagen para tipos específicos de contenido, directamente en la lista de tamaños de imagen.

Cuando agregas un nuevo tema a tu tienda, el tema agregará los tamaños de imagen que necesita. De forma predeterminada, la página muestra los tamaños de imagen del tema Clásico predeterminado.

## Add New Images Type <a href="#imagesettings-addnewimagestype" id="imagesettings-addnewimagestype"></a>

Puede agregar fácilmente un nuevo tamaño de imagen e incluso establecer a qué tipo de contenido se aplica.

![](<../../.gitbook/assets/51839910 (4) (4).png>)

Haga clic en el botón "Agregar nuevo tipo de imagen" y luego:

1. Escriba el nombre, el ancho y el alto del tamaño.
2. Choose to which type of content it applies.
3. Save.

## Images preferences <a href="#imagesettings-imagespreferences" id="imagesettings-imagespreferences"></a>

![](<../../.gitbook/assets/38469761 (4) (3) (3).png>)

* **Formato de imagen**. Puede elegir entre dos de los principales formatos de archivo: JPEG y PNG. Ambos están bien establecidos entre los navegadores. JPEG tiene una buena relación de compresión pero puede provocar artefactos visibles. El algoritmo de compresión de PNG no es tan bueno como el de JPEG, pero hay comparativamente menos artefactos visibles; no obstante, es posible que los navegadores más antiguos no reconozcan este formato.\
  Elegir entre uno y otro muchas veces es cuestión de gustos. Dicho esto, JPEG sigue siendo la opción recomendada. Si prefiere evitar la pérdida de información debido a un cambio de formato, elija la segunda opción, "Usar PNG sólo si la imagen base está en formato PNG".
* **JPEG compression**. Do not choose anything below 80 or at worst 75, for fear of visible compression artifacts.
* **PNG compression**. Do not choose anything over 6 or at worst 7, for fear of visible compression artifacts.
* **Genere imágenes basadas en un lado de la imagen de origen**. Esta característica le permite posicionar la imagen del producto en su espacio preestablecido:
  * Elija "_Height_" para completar la altura del marco (the width is then recalculated to maintain the same height/width ratio as in the file of origin).
  * Elija "_Width_" para que la imagen ocupe el ancho del marco (the height is then recalculated to maintain the same proportion).
  * Elija "_Automático_" para que el ancho y el alto se calculen para maximizar el espacio que puede ocupar en el marco.
* **Tamaño máximo de archivo de imágenes de personalización de productos**. Sus clientes pueden cargar imágenes de productos personalizados. De forma predeterminada, PrestaShop establece este valor en la configuración máxima de PHP; esto puede significar varios megabytes: por ejemplo, 8.388.608 bytes significa 8 Mb. Puede ampliar este valor si es necesario, pero asegúrese de que su instalación de PHP pueda soportar cargas de archivos de este tamaño.
* **Ancho de la imagen del producto**. De forma predeterminada, los clientes pueden cargar imágenes con un ancho máximo de 64 píxeles.
* **Altura de la imagen del producto**. De forma predeterminada, los clientes pueden cargar imágenes con una altura máxima de 64 píxeles.
* **Genere imágenes de alta resolución**. Las pantallas más recientes con alta densidad de píxeles (Retina and similar technologies) requieren imágenes de alta resolución. Puede habilitar esta función para asegurarse de que sus imágenes se muestren correctamente en este tipo de pantallas. Generará un nuevo archivo para cada una de tus imágenes, con una resolución dos veces mayor. Esto duplicará la cantidad de archivos de imagen, así que utilícelo con prudencia si tiene espacio de almacenamiento limitado.

## Regenerate Thumbnails <a href="#imagesettings-regeneratethumbnails" id="imagesettings-regeneratethumbnails"></a>

Es posible que no esté satisfecho con el tamaño actual de las miniaturas de su tienda. Esta sección le permite regenerarlos todos, o solo aquellos para un tipo específico de contenido:

![](<../../.gitbook/assets/46170135 (4) (4) (1).png>)

1. Cambie la configuración del tamaño de la imagen en la tabla en la parte superior de la página de preferencias "Imágenes".
2. Seleccione qué imágenes del contenido deben regenerarse.
3. Indique si se deben conservar o no las miniaturas anteriores.
4. Haga clic en "Regenerar miniaturas".

Las miniaturas cargadas manualmente se borrarán y reemplazarán por miniaturas generadas automáticamente.

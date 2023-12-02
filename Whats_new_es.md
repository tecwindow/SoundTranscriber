# Novedades en Sound Transcriber?

## Versión 1.3.2:

- Ahora se pueden añadir ficheros con la opción de arrastrar y soltar.
- Arreglado un error que hacía que al extraer texto apareciera en un orden diferente al esperado al convertir ficheros.
- Arreglado un error que hacía que la opción de guardado se deshabilitara si la conversión no había finalizado.
- Varias mejoras a la traducción al árabe. Muchas gracias a Zeinab Bahaa.
- Otros cambios menores.

## Versión 1.3.1:

Algunas correcciones y mejoras.

## Versión 1.3.0:

- Añadida traducción al francés. Muchas gracias a Riad Assoum.
- Ahora se pueden abrir archivos en Sound Transcriber para transcribirlos desde el menú contextual de los tipos de archivo compatibles.
- Ahora se puede acceder rápidamente a Sound Transcriber con sólo escribir 'st' en el cuadro de diálogo de Ejecutar.
- Sound Transcriber es ahora capaz de reconocer automáticamente las traducciones de la interfaz e integrar nuevos archivos de ayuda. Para contribuir, traduzca el archivo messages.pot utilizando Poedit y guarde los archivos en el mismo orden que los archivos de idioma existentes.
- Si se desactiva la opción de conservar los archivos descargados, Sound Transcriber los conservará hasta que se cierre el programa. Esto resulta especialmente práctico si desea repetir el proceso de conversión con diferentes opciones.
- Se han corregido varios errores relacionados con la función de pegar desde el portapapeles. Como ignorar ciertas rutas, fallos al iniciar las conversiones desde el mensaje de detección, pegar enlaces en cualquier momento, y más. Muchas gracias a Dawlat Hassan por el comentario que ayudó a descubrir muchos de estos errores relacionados con esta función.
- Arreglado un error que a veces provocaba que Sound Transcriber se iniciara en otro idioma después de la última actualización.
- Ya no se pueden abrir dos instancias de Sound Transcriber simultáneamente.
- Se han introducido cambios en el método de detención de la conversión.
- Otros cambios menores.

## Versión 1.2.0:

Importante, a partir de esta versión, Sound Transcriber sólo soportará versiones de 64 bits de Windows.

- Añadida traducción al español. Muchas gracias a Georgiana Frincu.
- Ahora se puede convertir vídeos de Youtube, Facebook, Twitter (X) y otros servicios en texto, para que Sound Transcriber descargue el vídeo y luego lo convierta.
- Se puede elegir entre conservar el archivo original tras la conversión o eliminarlo desde los ajustes.
- Se ha añadido la función de pausa y reanudación al proceso de transcripción.
- Ahora se pueden pegar las rutas de los archivos a convertir.
- Se puede especificar la extensión de archivo que se envía a wit.ai para la conversión desde la configuración.
- Sound Transcriber intentará gestionar los archivos cuyos nombres contengan Emojis.
- Sound Transcriber ya no se detiene durante la conversión. Si esto ocurre, se podrá continuar con el proceso.
- Pequeñas mejoras aquí y allá.

### Notas

- Se puede pausar mientras se extrae texto, pero no mientras se dividen archivos.
- Si se detiene temporalmente un proceso y luego se quiere iniciar un nuevo proceso de conversión, se perderá todo lo relacionado con el proceso anterior; Por lo tanto, es aconsejable guardar el resultado actual antes de iniciar una nueva conversión.
- Elegir el formato wav en los ajustes de wit.ai acelera la división de archivos, pero provoca una conversión más lenta y un mayor uso de datos. Considere la posibilidad de probar .ogg y compartir sus comentarios sobre los resultados.

## Versión 1.1.2:

- Se ha corregido un error que impedía la conversión correcta de archivos .mp4.
- Se ha corregido un error que provocaba que el formato de archivo guardado conservara la extensión del archivo original con los archivos de salida y, en ocasiones, guardaba los archivos de salida con la misma extensión que el archivo original al abrir un archivo a través del portapapeles.
- Ya no es posible cambiar entre servicios y abrir la configuración de Sound Transcriber durante el proceso de conversión.
- Ahora Sound Transcriber intentará avisarle cuando realice la conversión utilizando una clave de API de wit.ai incorrecta.
- Se ha corregido un error que provocaba que el botón "Editar" apareciera dos veces después de añadir una clave de wit.ai.
- Se ha corregido un error que provocaba que los botones Actualizar y Cancelar aparecieran en inglés cuando se utilizaba Sound Transcriber en árabe.
- Otros errores corregidos.

## Versión 1.1.1:

- Corregido un error que provocaba que la posición del cursor se moviera al principio del texto constantemente con el lector de pantalla mientras se extraía texto.
- Corregido un error que provocaba que las opciones de guardado no funcionaran una vez finalizado el proceso de extracción de texto.
- Corregidos otros errores.

## Versión 1.1:

Esta versión incluye varias correcciones de errores y algunas funciones nuevas.

- Se ha añadido soporte para varios formatos de archivos de audio y vídeo.
- Los archivos de Word se guardan ahora como .docx en lugar de .doc.
- Sound Transcriber mostrará una advertencia cuando se cierre durante la conversión de archivos.
- Si el guardado automático está desactivado y el texto extraído no se guarda en ningún archivo, Sound Transcriber le preguntará qué hacer al cerrar. Si decide guardar, el archivo se guardará según las opciones especificadas en la sección Opciones de guardado de la configuración.
- Sound Transcriber ahora recuerda el idioma seleccionado para la conversión de archivos para cada servicio.
- El texto extraído se muestra ahora durante el proceso de extracción. Es decir, si el proceso de extracción se detiene por cualquier motivo, no perderá el texto extraído. El nuevo texto se añadirá a medida que continúe el proceso.
- Ahora puede comprobar el progreso de la extracción pulsando P.
- Se ha corregido un error que impedía que funcionara el botón "Examinar" de la ruta de guardado automático.
- Se ha corregido un error que impedía cambiar las claves API para idiomas distintos del idioma principal en la lista de idiomas de wit.ai.
- Se ha corregido un error que impedía convertir archivos con un idioma distinto del idioma principal mediante Wit.ai.
- Se ha corregido un error que impedía restaurar la configuración predeterminada.
- Se ha ajustado el diseño del cuadro de diálogo de configuración para mostrar los elementos correctamente.
- Mejoras a la traducción árabe
- Corrección de errores menores.

## Versión 1.0:

Versión inicial
# Guía de usuario de Sound Transcriber

El objetivo de esta guía de usuario es proporcionarle un conocimiento exhaustivo de Sound Transcriber y ayudarle a sacar el máximo partido de sus funciones.

Le recomendamos encarecidamente que lea esta guía para garantizar un uso óptimo del programa.

## Introducción a Sound Transcriber:

Sound Transcriber es un programa accesible de conversión de audio a texto diseñado para transcribir archivos de audio y vídeo, ofrece soporte para extraer archivos de subtítulos y mucho más.

Desarrollado por Mahmoud Atef, Ahmed Bakr y Qais Alrefai del equipo TecWindow.

## Características:

Sound Transcriber ofrece las siguientes características:

- Conversión de archivos de audio y vídeo a texto utilizando varios servicios de transcripción.
- Guardar los resultados de la conversión como archivos .txt y .doc o como archivos de subtítulos .SRT.
- Convierta vídeos de plataformas como YouTube, Facebook, o X descargando el archivo directamente, con una opción que permite guardar el archivo para un acceso más sencillo y  usarlo en el futuro.

## Características previstas:

Tenemos varias características previstas para el futuro, incluyendo:

- Traducción de los resultados de la conversión a varios idiomas.
- Corrección ortográfica con diccionarios.
- Conversión de resultados en audio utilizando motores de texto a voz.

## Servicios soportados:

Actualmente, el software sólo admite la conversión en línea mediante el reconocimiento de voz de Google, Whisper de OpenAi y wit.ai de Meta.

## Notas importantes:

Tenga en cuenta la siguiente información importante:

- Por defecto, el programa utiliza el servicio de Google. Para utilizar otros servicios, es necesario obtener una clave API del respectivo proveedor de servicios.
- Para obtener los mejores resultados con la transcripción en árabe, recomendamos utilizar wit.ai.
- Se ha incluido Whisper de OpenAI basándose en experiencias anteriores, pero es posible que no funcione como está previsto o que no funcione en absoluto. Agradecemos comentarios y experiencias para ayudarnos a resolver cualquier problema.
- A diferencia de OpenAI, Wit.ai proporciona claves API gratuitas.
- Al convertir un archivo, asegúrese de seleccionar el idioma adecuado antes de iniciar el proceso de conversión. Si un archivo es multilingüe, es posible que las palabras en idiomas distintos al seleccionado no se conviertan con precisión debido a las limitaciones de los servicios.
- Antes de la conversión, los archivos se dividen en segmentos de hasta 60 segundos, dependiendo de las limitaciones de cada servicio. En consecuencia, es posible que se pierdan algunas palabras durante este proceso. Para obtener resultados óptimos, recomendamos ajustar la duración del segmento en función del tiempo de silencio, la longitud del archivo y la duración del segmento permitidos por cada servicio.
- Para resultados óptimos con archivos .srt, recomendamos seleccionar una duración corta, como por ejemplo 5 segundos, para los segmentos.
- Sound Transcriber requiere [Microsoft Visual C++ 2015-2022 Redistributable X64](https://aka.ms/vs/17/release/vc_redist.x64.exe) y [Microsoft Visual C++ 2013 Redistributable X64](https://aka.ms/highdpimfc2013x64enu). Si el programa no le funciona, por favor utilice los enlaces anteriores para descargar e instalar los archivos requeridos.
- Actualmente, Sound Transcriber se encuentra en los siguientes idiomas: árabe, inglés, español, francés, ruso, turco y vietnamita.
- Sound Transcriber es compatible con sistemas que tengan Windows 8 o superior, pero solo con sistemas de 64-bits systems.

## Extensiones de archivo compatibles:

Sound Transcriber admite las siguientes extensiones de archivo para la conversión:

.mp3, .wav, .aac, .flac, .oga, .opus, .mp4, .avi, .mkv, .mov, .m4a, .ogg, .ram, .rm, .wma, .wmv, .3gp, .flv.

## Obtener claves API:

### Wit.ai:

Si incluyéramos una clave API en el propio programa, probablemente se bloquearía tras un uso generalizado por parte de múltiples usuarios.

Además, wit.ai proporciona claves API distintas para cada idioma. Esto significa que es necesario crear una aplicación en el idioma deseado y obtener su clave API correspondiente.

Lamentablemente, no nos es posible reunir claves API para todos los idiomas, ya que varían en función de las preferencias individuales.

Por lo tanto, le proporcionaremos instrucciones sobre cómo obtener su propia clave API privada.

Aunque los pasos siguientes pueden parecer extensos, son sencillos y sólo hay que completarlos una vez.

- Abra el [sitio web de wit.ai](https://wit.ai)
- Inicie sesión con una cuenta Meta pulsando "Continue With Meta".
- Siga los pasos normales de creación de cuenta o pulse "Continuar con Facebook"
- Vaya a la parte superior de la página, o pulse h o 1 para los usuarios de lectores de pantalla.
- Haga clic en "New App" y escriba cualquier nombre en inglés para la aplicación, como test o my app.
- Encontrará un cuadro de opciones para el idioma de la app, ábralo y elija el idioma apropiado. Los archivos de audio se convertirán al idioma elegido.
- Por último, haga clic en "Create".
- Busque el nombre de la aplicación creada, haga clic en él y, a continuación, desplácese hasta el botón "Management".
- Al llegar a este botón, pulse la letra b para encontrar un botón llamado "Settings". Pulse este botón.
- Muévase con el número 4 o h para los usuarios de lectores de pantalla hasta encontrar un encabezado llamado Client Access Token, desplácese hacia abajo y encontará su clave como un botón. Puede seleccionar el texto manualmente para copiarlo o pulsar el mismo botón para que se copie automáticamente.
- Vuelva a Sound Transcriber y pegue la clave API en el campo correspondiente.

Puede repetir estos pasos y crear una nueva aplicación con un nombre diferente para obtener una clave API para transcribir en otro idioma. Si quiere utilizar varios idiomas con wit.ai, sólo tiene que repetir los pasos para obtener una clave de API para cada idioma.

### Whisper:

Sound Transcriber admite la transcripción mediante el uso de claves de API Whisper de OpenAI, que no están disponibles de forma gratuita.

El precio se basa en el número de caracteres transcritos, y aquí no se mencionan planes específicos.

Para obtener información detallada sobre los límites y las opciones de suscripción, visite [esta página/.](https://platform.openai.com/account/billing/overview). Tenga en cuenta que iniciar sesión y añadir un método de pago es bajo su propia responsabilidad.

Para obtener una clave API para Sound Transcriber, vaya a la [página de la clave API](https://platform.openai.com/account/api-keys) y haga clic en "Create new secret key." Copie la clave generada y proceda a añadirla en los ajustes del programa como se demuestra más adelante.

## Interfaz de Sound Transcriber:

Al abrir el programa, encontrará un cuadro de edición que muestra el resultado transcrito. Utiliza el tabulador para navegar por el resto de opciones.

La casilla "Idioma" le permite especificar el idioma del archivo que desea transcribir. Seleccione el idioma adecuado utilizando las flechas.

Pulse el botón "Iniciar" para iniciar el proceso de conversión.

A continuación, encontrará el botón "Guardar como", que permite especificar las preferencias de guardado del archivo de salida.

Debajo hay un cuadro de edición de sólo lectura que indica la ruta o el enlace del archivo que se va a transcribir.

Utilice el botón "Examinar" para localizar y seleccionar el archivo que desea transcribir.

Además, puede utilizar atajos de teclado, que se explicarán más adelante.

Tenga en cuenta que el orden de los elementos en la pantalla puede variar al navegar con el tabulador.

## Menús

El programa incluye algunos menús a los que se puede acceder pulsando la tecla Alt.

### Archivo:

- Abrir: Utilice esta opción para navegar por el dispositivo y buscar un archivo para transcribir.
- Guardar: Permite guardar el resultado de la transcripción con la extensión especificada en los ajustes.
- Guardar como: Permite guardar el resultado con una extensión específica.
- Ajustes: Permite acceder a las opciones y personalizaciones del programa.
- Abrir Archivo De LOG: permite ver el archivo de log de Sound Transcriber.
- Salir: Sirve para salir del programa.

### Servicios:

Contiene los nombres de los servicios disponibles para la conversión, puede seleccionar cualquier servicio.

### Ayuda:

- Guía de usuario: Ver este archivo.
- Novedades: Ver el registro de cambios de Sound Transcriber.
- Buscar actualizaciones: Buscar actualizaciones del programa.
- Contacto: Mostrar menús con opciones para ponerse en contacto con los desarrolladores del programa.
- Donar: Donar a los desarrolladores de Sound Transcriber.
- Abrir el repositorio: Abre el repositorio de Sound Transcriber en GitHub, el programa no es de código abierto.
- Acerca de: Proporciona información sobre Sound Transcriber.

## Ajustes de Sound Transcriber:

De forma similar a la configuración del lector de pantalla NVDA, los ajustes de Sound Transcriber se clasifican en varias secciones, cada una de las cuales contiene varias opciones. Puede navegar entre las secciones utilizando las flechas arriba y abajo. Utilice las teclas Tab y Shift+Tab para desplazarse por las opciones dentro de la sección seleccionada.

### General:

Esta sección incluye varias opciones del programa:

- Idioma de la interfaz: Especifique el idioma del programa.
- Servicio: Definir el servicio utilizado para la transcripción de archivos.
- Archivos para transcribir simultáneamente: Esta función le permite especificar el número de archivos que se transcribirán de manera simultánea. Esta función controla la cantidad de clips del mismo archivo que se mandarán simultáneamente después de que éste se divida.
- Detectar automáticamente si hay un archivo en el portapapeles: El programa comprueba el portapapeles al iniciarse y, si encuentra un archivo compatible, selecciona automáticamente su ruta para una conversión rápida.
- Preguntar qué hacer cuando se detecta un archivo en el portapapeles: Si está activado, el programa le preguntará cómo manejar el archivo detectado.
- Sonidos: Activa sonidos de alerta cuando se inicia y finaliza la conversión.
- Acciones habladas: Activar el lector de pantalla para proporcionar información sobre el estado de la conversión.
- Buscar actualizaciones automáticamente: Buscar automáticamente actualizaciones del programa al iniciarse.
- Incluir versiones beta al buscar actualizaciones: permite recibir las actualizaciones beta para el programa. Se explican más detalles en el apartado de actualizaciones beta de esta guía.
- Permitir logs: Esta función permite que Sound Transcriber genere un archivo de registro de los pasos de la transcripción. Es particularmente útil para solucionar errores. Cuando se requiera, active esta función y mándenos el archivo generado. Si está deshabilitada, los archivos de registro antiguos serán borrados, pero los últimos detalles serán conservados. Esto asegura que el programa pueda registrar errores que puedan darse, incluso si no puede usar el programa por primera vez y activar la opción.
- Restaurar ajustes por defecto: Restablecer la configuración a sus valores por defecto.

### Opciones de guardado:

Las opciones de esta sección afectan a la funcionalidad de guardado en el menú Archivo del programa.

- Autoguardar archivos: Activa el guardado automático de los resultados de la conversión.
- Ruta de salida: Muestra la ruta actual en la que se guardan los archivos. Utilice el botón Examinar para cambiarla.
- Guardar como fichero .txt: Permite guardar automáticamente los archivos con extensión .txt.
- Guardar como fichero .docx: Guardar el archivo con la extensión .docx.
- Guardar como fichero de subtítulos: Guardar el archivo con la extensión .srt.
- Mantener archivos descargados. Los archivos descargados de Internet se conservarán después de la conversión. Si está desactivada, el archivo se descargará, se convertirá y luego se borrará.

Si la función Autoguardar está desactivada, la opción "Guardar" del menú "Archivo" realizará la misma función, guardando los archivos según las extensiones y la ruta especificadas.

### Google:

Esta sección requiere que introduzca una clave API segura en el cuadro de texto "Clave secreta". Puede hacer clic en el botón de edición para modificar la clave. Además, puede ajustar la duración del segmento especificando la duración de cada parte del archivo cuando utilice este servicio.

Tenga en cuenta que el archivo debe dividirse en varios segmentos para su conversión. La duración máxima por segmento para este servicio es de un minuto.

### OpenAI:

Similar al servicio anterior, esta sección le permite introducir una clave API. Sin embargo, la duración máxima de cada archivo cuando se utiliza OpenAI es de 30 segundos.

### Wit.ai:.

Como Wit.ai separa los idiomas en función de las claves API, esta sección permite combinar idiomas de la siguiente manera:

Encontrará una lista de los idiomas añadidos actualmente.

Cada idioma tiene un campo de edición oculto correspondiente para la clave API.

Puede editar la clave eliminando la antigua, pegando la nueva clave, y usando el botón de editar. Alternativamente, puede usar el botón Añadir para agregar la nueva clave.

Seleccione el idioma que coincida con su aplicación en Wit.ai, pegue la clave y haga clic en Añadir.

Repita estos pasos para cada idioma que vaya a utilizar. Después de obtener una clave del sitio Wit.ai, vuelva a la ventana de ajustes para añadirla.

Puede eliminar claves individuales o todas las claves guardadas asociadas a este servicio utilizando los botones proporcionados.

Elija el formato de audio: Para especificar la extensión del archivo al convertirlo, elija ogg o mp3 si su conexión a internet es mala.

Si elige wav, el archivo se dividirá rápidamente, pero será más grande.

Por último, puede especificar la duración de cada segmento de archivo, que oscila entre 4 y 20 segundos. Elija la duración que ofrezca los mejores resultados.

Pulse OK cuando haya terminado de ajustar la configuración.

## Atajos de teclado::

Sound Transcriber trae algunos atajos de teclado para poder usar el programa más rápido y de manera más sencilla.

- Ctrl+O: Abrir la ventana de examinar para seleccionar un archivo a convertir.
- Ctrl+V: Copiar un fichero del portapapeles para la conversion.
- Ctrl+1: Cambiar al servicio de Google.
- Ctrl+2: Cambiar al servicio de Wit.ai.
- Ctrl+3: Cambiar a Whisper.
- Ctrl+Enter: Iniciar el proceso de conversion.
- P: Mostrar el porcentaje actual de la conversion.
- Ctrl+S: Abrir los ajustes de guardado.
- Ctrl+Shift+S: Guardar el resultado como .srt.
- Ctrl+Shift+T: Guardar el resultado como .txt.
- Ctrl+Shift+D: Guardar el resultado como .docx.
- Ctrl+U o F3: Buscar actualizaciones.
- Alt+S o F8: Abrir los ajustes.
- F1: Abrir la guía de usuario.
- F2: Ver novedades.
- F5: Donar.
- F6: Abrir el repositorio.
- F7: Abrir Archivo De LOG.
- F9: Acerca De.
- Ctrl+W o Ctrl+F4: cerrar Sound Transcriber.

## Cómo convertir archivos:

Para convertir archivos, abra Sound Transcriber y busque el archivo haciendo clic en "Examinar" o utilice el atajo de teclado Ctrl+O. También puede copiar el archivo desde su dispositivo y pegarlo utilizando Ctrl+V.

Además puede usar la opción disponible en el menú contextual para archivos compatibles, la opción de enviar a de los menús Windows, o simplemente arrastrar y soltar.

O también puede copiar un enlace de vídeo de sitios como Facebook, Twitter (X), Youtube, SoundCloud y otros.

Elija el idioma y el servicio deseados utilizando los accesos directos proporcionados o cámbielos en los ajustes. Pulse "Inicio" o utilice el atajo Ctrl+Enter para iniciar la conversión.

Por si no lo sabía, puede abrir Sound Transcriber pulsando Windows + R para abrir el diálogo de ejecutar, y escribiendo st.

### Notas:

- Mientras el proceso de conversión está en curso, se puede pausar durante la extracción del texto, y durante la descarga, pero si se inicia un nuevo proceso, todo lo relacionado con el proceso anterior será ignorado.
- Si el proceso se detiene durante la división de los ficheros, no podrá reanudarse.

## Informar de errores:

Si encuentra algún error en Sound Transcriber, puede utilizar los métodos de comunicación disponibles en el menú "Contacto" de la sección "Ayuda". Proporcione una explicación detallada de las acciones que provocaron el fallo. Le recomendamos que comparta el archivo Sound Transcriber.log, que nos ayudará a comprender y resolver el fallo con mayor eficacia.

Vaya a Ajustes > General y active la opción de permitir logs. Ahora, repita los pasos que generaron el error. No se olvide de desactivar la opción de permitir logs después de enviar el fichero. Tenga en cuenta que mantener la opción habilitada puede resultar en un archivo de registro muy largo. Sin embargo, puede optar por mantenerla habilitada si lo desea.

Puede encontrar el archivo en la siguiente ruta:

AppData\Roaming\tecwindow\SoundTranscriber

## Actualizaciones Beta:

Sound Transcriber ofrece un sistema de actualizaciones beta, lo que le permite probar nuevas funciones y ayudarnos a identificar errores. Aunque activar esta característica es sencillo, hay algunos puntos importantes a considerar:

- Las actualizaciones beta pueden ser inestables, y no podemos garantizar la liberación inmediata de soluciones para cualquier problema que usted encuentre.
- En ciertos casos, podríamos lanzar hasta tres actualizaciones en la misma semana.
- Algunas opciones pueden no estar siempre traducidas a su idioma al usar versiones beta.
- Recomendamos probar la beta solo si se siente cómodo identificando y compartiendo errores.

Para optar a las actualizaciones beta, navegue a los ajustes > General, habilite la opción "Incluir versiones beta al buscar actualizaciones" y luego busque actualizaciones.

Si desea volver a las versiones estables, simplemente desactive la misma opción y luego descargue e instale la última versión estable.

Extendemos nuestra más sincera gratitud a todos los que contribuyen probando Sound Transcriber, encontrando errores y compartiendo sus percepciones.

## Cómo Traducir:

Aunque Sound Transcriber actualmente solo admite un número limitado de idiomas en sus opciones de interfaz y guía de usuario, puede transcribir el habla a texto en una amplia gama de idiomas.

Sin embargo, damos la bienvenida a cualquier persona interesada en traducir el programa a su idioma nativo.

### Traducción de la interfaz:

La traducción de las opciones de interfaz se basa principalmente en archivos .po, que se pueden editar usando el programa Poedit. Puede descargar Poedit desde su sitio web oficial, luego navegar al repositorio de Sound Transcriber en GitHub o localizar la carpeta del programa en su dispositivo. A continuación, localice el archivo messages.pot y ábralo en Poedit. Desde allí, puede traducir las cadenas a su idioma, guardar el archivo (lo que generará tanto un archivo .po como un .mo) y compartir estos archivos con nosotros.

## Testear la Traducción:

Sound Transcriber puede reconocer nuevas traducciones, lo que permite probar su traducción antes de enviarla. Para hacer esto, navegue a la carpeta de Idiomas, cree una carpeta con el código del idioma (las primeras dos letras del idioma), luego cree una subcarpeta llamada LC_MESSAGES y coloque los archivos .po y .mo dentro. No olvide nombrar los archivos como SoundTranscriber.po y SoundTranscriber.mo.

### Traducción de la documentación:

Si bien la traducción de las novedades y de la guía de usuario no es obligatoria, puede traducirlas a su idioma usando archivos .pot.

Usamos ficheros .md para crear ficheros .pot, que luego mandamos a los traductores. Después, convertimos los ficheros .po que los traductores nos han vuelto a mandar de vuelta a ficheros .md, y después a ficheros.html para incluir con el programa.

Esto nos permite hacer correcciones a cualquier parte del manual y las novedades, asegurando que se aplican de manera consistente a todos los idiomas. También asegura que los ficheros en distintas lenguas permanecen en el mismo formato y estructura.

Para traducir ficheros, siga estos pasos:

- Obtenga los ficheros .pot  del repositorio en GitHub o de la carpeta de documentación en el directorio de Sound Transcriber.
- Tradúzcalos usando Poedit.
- Puede ser que encuentre frases repetidas con puntos adicionales. Usamos esto para distinguir frases, asegurando que están en las posiciones correctas. Añada la misma cantidad de puntos, y nosotros los quitaremos al incorporar la traducción.
- Tenga en cuenta que puede ser que los textos no aparezcan en el orden correcto si la traducción está incompleta. Cuando la traducción ya esté correcta, reabra el fichero para verlos en el orden correcto.
- Finalmente, comparta los archivos con nosotros.

### Notas:

- Si se elige no traducir la Guía del Usuario y el archivo de novedades Sound Transcriber los mostrará en inglés.
- La traducción de software es un esfuerzo continuo, y nos pondremos en contacto con usted antes de lanzar nuevas actualizaciones para que pueda traducir cualquier contenido nuevo.

## Web de Sound Transcriber:

Aunque no hay un sitio web oficial de Sound Transcriber, se puede acceder a todos los recursos necesarios en el repositorio de Sound Transcriber en GitHub. Este repositorio contiene los archivos de traducción y la última versión del programa.

Nota: Ahora mismo Sound Transcriber no es de código abierto, y por tanto, el repositorio no tiene el código fuente del programa.

[Enlace al repositorio.](https://github.com/tecwindow/SoundTranscriber)

## Contáctenos:

Si no puede acceder a nuestros datos de contacto dentro de Sound Transcriber, puede comunicarse con nosotros por correo electrónico usando las siguientes direcciones:

- Qais Alrefai: ww258148@gmail.com
- Mahmoud Atef: mahmoud.atef.987123@gmail.com
- Ahmed Bakr: AhmedBakr593@gmail.com

## Agradecimientos:

- Muchas gracias a Riad Assoum por traducir la guía del usuario al inglés y corregir las cadenas en inglés y árabe del programa.
- Muchas gracias a Georgiana Frincu por traducir Sound Transcriber al español.
- Muchas gracias a Danil por traducir Sound Transcriber al ruso.
- Muchas gracias a Kadir öz por traducir Sound Transcriber al turco.
- Muchas gracias a Nguyen Anh Duc por la traducción de Sound Transcriber al Vietnamita.

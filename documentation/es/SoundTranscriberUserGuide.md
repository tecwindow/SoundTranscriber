# Guía de usuario de Sound Transcriber

El objetivo de esta guía de usuario es proporcionarle un conocimiento exhaustivo de Sound Transcriber y ayudarle a sacar el máximo partido de sus funciones.

Le recomendamos encarecidamente que lea esta guía para garantizar un uso óptimo del programa.

## Introducción a Sound Transcriber

Sound Transcriber es un programa accesible de conversión de audio a texto diseñado para transcribir archivos de audio y vídeo, ofrece soporte para extraer archivos de subtítulos y mucho más.

Desarrollado por Mahmoud Atef, Ahmed Bakr y Qais Alrefai del equipo TecWindow.

## Características

Sound Transcriber ofrece las siguientes características:

- Conversión de archivos de audio y vídeo a texto utilizando varios servicios de transcripción.
- Guardar los resultados de la conversión como archivos .txt y .doc o como archivos de subtítulos .SRT.

## Características previstas

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

## Whisper:

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
- Salir: Sirve para salir del programa.

### Servicios:

Contiene los nombres de los servicios disponibles para la conversión, puede seleccionar cualquier servicio.

### Ayuda:

- Guía de usuario: Ver este archivo.
- Novedades: Ver el registro de cambios de Sound Transcriber.
- Buscar actualizaciones: Buscar actualizaciones del programa.
- Contacto: Mostrar menús con opciones para ponerse en contacto con los desarrolladores del programa.
- Acerca de: Proporciona información sobre Sound Transcriber.

## Ajustes de Sound Transcriber:

De forma similar a la configuración del lector de pantalla NVDA, los ajustes de Sound Transcriber se clasifican en varias secciones, cada una de las cuales contiene varias opciones. Puede navegar entre las secciones utilizando las flechas arriba y abajo. Utilice las teclas Tab y Shift+Tab para desplazarse por las opciones dentro de la sección seleccionada.

### General:

Esta sección incluye varias opciones del programa:

- Idioma de la interfaz: Especifique el idioma del programa.
- Servicio: Definir el servicio utilizado para la transcripción de archivos.
- Detectar automáticamente si hay un archivo en el portapapeles: El programa comprueba el portapapeles al iniciarse y, si encuentra un archivo compatible, selecciona automáticamente su ruta para una conversión rápida.
- Preguntar qué hacer cuando se detecta un archivo en el portapapeles: Si está activado, el programa le preguntará cómo manejar el archivo detectado.
- Sonidos: Activa sonidos de alerta cuando se inicia y finaliza la conversión.
- Acciones habladas: Activar el lector de pantalla para proporcionar información sobre el estado de la conversión.
- Buscar actualizaciones automáticamente: Buscar automáticamente actualizaciones del programa al iniciarse.
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

### Wit.ai:

Como Wit.ai separa los idiomas en función de las claves API, esta sección permite combinar idiomas de la siguiente manera:

Encontrará una lista de los idiomas añadidos actualmente.

Cada idioma tiene un campo de edición oculto correspondiente para la clave API.

Utilice el botón editar para cambiar la clave o el botón añadir para añadir una nueva clave.

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
- Ctrl+V: Copiar un fichero del portapapeles para la conversión
- Ctrl+1: Cambiar al servicio de Google.
- Ctrl+2: Cambiar al servicio de Wit.ai.
- Ctrl+3: Cambiar a Whisper.
- Ctrl+Enter: Iniciar el proceso de conversión
- P: Mostrar el porcentaje actual de la conversión
- Ctrl+S: Abrir los ajustes de guardado
- Ctrl+Shift+S: Guardar el resultado como .srt.
- Ctrl+Shift+T: Guardar el resultado como .txt.
- Ctrl+Shift+D: Guardar el resultado como .docx.
- Ctrl+U: Buscar actualizaciones
- Alt+S: Abrir los ajustes
- Ctrl+W o Ctrl+F4: cerrar Sound Transcriber.

## Cómo convertir archivos:

Para convertir archivos, abra Sound Transcriber y busque el archivo haciendo clic en "Examinar" o utilice el atajo de teclado Ctrl+O. También puede copiar el archivo desde su dispositivo y pegarlo utilizando Ctrl+V.

O también puede copiar un enlace de vídeo de sitios como Facebook, Twitter (X), Youtube, SoundCloud y otros.

Elija el idioma y el servicio deseados utilizando los accesos directos proporcionados o cámbielos en los ajustes. Pulse "Inicio" o utilice el atajo Ctrl+Enter para iniciar la conversión.

### Notas:

- Mientras el proceso de conversión está en curso, se puede pausar durante la extracción del texto, y durante la descarga, pero si se inicia un nuevo proceso, todo lo relacionado con el proceso anterior será ignorado.
- Si el proceso se detiene durante la división de los ficheros, no podrá reanudarse.

## Informar de errores:

Si encuentra algún error en Sound Transcriber, puede utilizar los métodos de comunicación disponibles en el menú "Contacto" de la sección "Ayuda". Proporcione una explicación detallada de las acciones que provocaron el fallo. Le recomendamos que comparta el archivo Sound Transcriber.log, que nos ayudará a comprender y resolver el fallo con mayor eficacia.

Puede encontrar el archivo en la siguiente ruta:

AppData\Roaming\tecwindow\SoundTranscriber

## Agradecimientos

- Muchas gracias a Riad Assoum por traducir la guía del usuario al inglés y corregir las cadenas en inglés y árabe del programa.
- Muchas gracias a Georgiana Frincu por traducir Sound Transcriber al español.

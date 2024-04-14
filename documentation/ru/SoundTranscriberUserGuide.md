# Руководство пользователя Sound Transcriber.

Это руководство пользователя призвано дать вам полное представление о программе Sound Transcriber и помочь вам использовать её возможности на полную катушку.

Мы настоятельно рекомендуем прочитать это руководство, чтобы обеспечить оптимальное использование программы.

## Введение в Sound Transcriber

Sound Transcriber - это доступная программа для преобразования звука в текст, предназначенная для расшифровки аудио- и видеофайлов, поддерживающая извлечение файлов субтитров и многое другое.

Разработана Махмудом Атефом, Ахмедом Бакром и Каисом Алрефаем из команды TecWindow.

## Особенности

Sound Transcriber предлагает следующие возможности:

- Преобразование аудио- и видеофайлов в текст с помощью различных сервисов расшифровки.
- Сохранение результатов конвертации в файлы .txt и .doc или в файлы субтитров .SRT.

## Планируемые возможности:

В разработке находится несколько запланированных функций, в том числе:

- Перевод результатов расшифровки на несколько языков.
- Проверка орфографии с помощью словарей.
- Преобразование результатов в аудио с помощью механизмов преобразования текста в речь.

## Поддерживаемые сервисы:

В настоящее время программа поддерживает только онлайн-конвертацию с помощью распознавания речи Google, Whisper от OpenAi и wit.ai от Meta.

## Важные замечания:

Пожалуйста, примите к сведению следующую важную информацию:

- По умолчанию программа использует сервис Google. Чтобы использовать другие сервисы, необходимо получить API-ключ у соответствующего поставщика услуг.
- Для достижения наилучших результатов при расшифровке арабского языка мы рекомендуем использовать wit.ai.
- Whisper от OpenAI был добавлен на основе предыдущего опыта, но он может работать не так, как задумано, или не работать вообще. Мы ценим ваши отзывы и опыт, которые помогут нам решить любые проблемы.
- В отличие от OpenAI, Wit.ai предоставляет бесплатные API-ключи.
- При расшифровке файла убедитесь, что вы выбрали нужный язык, прежде чем начать процесс конвертации. Если файл многоязычный, слова на языках, отличных от выбранного, могут быть преобразованы неточно из-за ограничений сервиса.
- Перед конвертированием файлы разбиваются на сегменты длительностью до 60 секунд, в зависимости от ограничений каждого сервиса. Следовательно, некоторые слова могут быть потеряны во время этого процесса. Для достижения оптимальных результатов мы рекомендуем регулировать длительность сегмента в зависимости от времени молчания, длины файла и длительности сегмента, допустимых каждым сервисом.
- Для достижения оптимальных результатов при работе с файлами .srt рекомендуется выбирать для сегментов небольшую продолжительность, например 5 секунд.
- Для работы Sound Transcriber требуется [Microsoft Visual C++ 2015-2022 Redistributable X64](https://aka.ms/vs/17/release/vc_redist.x64.exe) и [Microsoft Visual C++ 2013 Redistributable X64.](https://aka.ms/highdpimfc2013x64enu) Если программа не работает, пожалуйста, воспользуйтесь вышеупомянутыми ссылками для загрузки и установки необходимых файлов.
- В настоящее время Sound Transcriber поддерживает следующие языки: Арабский, Английский, Испанский, Французский и Русский.
- Sound Transcriber совместим с Windows 8 и выше, но только в 64-битных системах.

## Поддерживаемые расширения файлов:

Sound Transcriber поддерживает следующие расширения файлов для конвертирования:

.mp3, .wav, .aac, .flac, .oga, .opus, .mp4, .avi, .mkv, .mov, .m4a, .ogg, .ram, .rm, .wma, .wmv, .3gp, .flv.

## Получение ключей API:

### Wit.ai:

Если бы мы включили API-ключ в саму программу, он, скорее всего, был бы заблокирован после широкого использования несколькими пользователями.
Более того, wit.ai предоставляет отдельные API-ключи для каждого языка. Это означает, что вам необходимо создать приложение на нужном языке и получить соответствующий API-ключ.
К сожалению, мы не можем собрать API-ключи для всех языков, поскольку они зависят от индивидуальных предпочтений.
Поэтому мы предоставим вам инструкции по получению вашего собственного частного ключа API.
Хотя следующие шаги могут показаться сложными, они просты и их нужно выполнить только один раз.

- Откройте сайт [wit.ai](https://wit.ai).
- Войдите в свою учётную запись Meta, нажав "Продолжить с Meta".
- Выполните обычные шаги по созданию учётной записи или нажмите "Продолжить с Facebook".
- Перейдите в верхнюю часть страницы, нажмите h или 1 для пользователей программ чтения с экрана.
- Нажмите "Новое приложение" и дайте приложению любое английское название, например test или my app.
- Вы найдёте поле для выбора языка приложения, откройте его и выберите подходящий язык. Аудиофайлы будут преобразованы на выбранном вами языке.
- Наконец, нажмите "Создать".
- Найдите название созданного вами приложения, нажмите на него, а затем перейдите к кнопке "Управление".
- Когда вы доберётесь до этой кнопки, нажмите на букву b, чтобы найти кнопку "Настройки". Нажмите на эту кнопку.
- Двигайтесь с помощью цифры 4 или h для пользователей программы чтения с экрана, пока не найдёте заголовок под названием Client Access Token (Токен доступа клиента), прокрутите вниз, и вы найдёте свой ключ в виде кнопки. Вы можете выделить текст вручную, чтобы скопировать его, или нажать ту же кнопку, чтобы он скопировался автоматически.
- Вернитесь в Sound Transcriber и вставьте свой API-ключ в соответствующее поле.

Вы можете повторить эти шаги и создать новое приложение с другим именем, чтобы получить API-ключ для расшифровки на другом языке. Если вы хотите использовать несколько языков с wit.ai, просто повторите эти шаги, чтобы получить API-ключ для каждого языка.

## Whisper:

Sound Transcriber поддерживает транскрибацию с помощью ключей API Whisper от OpenAI, которые не предоставляются бесплатно.

Цена зависит от количества расшифрованных символов, и конкретные тарифные планы здесь не упоминаются.

Чтобы получить подробную информацию об ограничениях и вариантах подписки, посетите [эту страницу.](https://platform.openai.com/account/billing/overview) Помните, что вход в систему и добавление способа оплаты осуществляются на ваш страх и риск.

Чтобы получить API-ключ для Sound Transcriber, перейдите на страницу [API-ключи] (https://platform.openai.com/account/api-keys) и нажмите на кнопку "Создать новый секретный ключ". Скопируйте сгенерированный ключ и добавьте его в настройки программы, как показано далее.

## Интерфейс Sound Transcriber:

После открытия программы вы увидите поле редактирования, в котором отображается результат расшифровки. Используйте клавишу табуляции для перемещения по другим опциям.

В поле "Язык" можно указать язык файла, который вы хотите расшифровать. Выберите нужный язык с помощью клавиш-стрелок.

Нажмите кнопку "Начать", чтобы запустить процесс преобразования.

Далее находится кнопка "Сохранить как", которая позволяет указать параметры сохранения выходного файла.

Под ней находится поле для редактирования, доступное только для чтения, в котором указывается путь или ссылка на файл, подлежащий расшифровке.

Используйте кнопку "Обзор", чтобы найти и выбрать файл, который вы хотите расшифровать.

Кроме того, вы можете использовать сочетания клавиш, которые будут описаны ниже.

Обратите внимание, что порядок элементов на экране может отличаться при навигации с помощью клавиши Tab.

## Меню

Программа содержит несколько меню, доступных при нажатии клавиши Alt.

### Файл:

- Открыть: Используйте эту опцию для просмотра устройства и поиска файла для расшифровки.
- Сохранить: Сохранить результат транскрипции с указанным в настройках расширением.
- Сохранить как: Сохранить результат с определённым расширением.
- Настройки: Доступ к опциям и настройкам программы.
- Открыть файл журнала: позволяет просмотреть файл журнала программы Sound Transcriber.
- Выход: Выход из программы.

### Сервисы:

Содержит названия сервисов, доступных для конвертирования, вы можете выбрать любой сервис.

### Справка:

- Руководство пользователя: Просмотр текущего файла.
- Что нового: Просмотр журнала изменений Sound Transcriber.
- Проверка обновлений: Поиск обновлений программы.
- Связаться с нами: Отображение меню с опциями для связи с разработчиками программы.
- О программе: Предоставляет информацию о программе Sound Transcriber.

## Настройки Sound Transcriber:

Подобно настройкам программы чтения с экрана NVDA, настройки Sound Transcriber разделены на несколько категорий, каждый из которых содержит различные параметры. Перемещаться между разделами можно с помощью стрелок вверх и вниз. Используйте клавиши Tab и Shift+Tab для перемещения по параметрам в выбранном разделе.

### Общие:

В этом разделе содержатся различные параметры программы:

- Язык интерфейса: Укажите язык программы.
- Сервис: Определите сервис, используемый для транскрипции файлов.
- Файлы для одновременной транскрипции: Эта функция позволяет указать количество файлов, которые будут транскрибироваться одновременно.
- Автоопределение наличия файла в буфере обмена: Программа проверяет буфер обмена при запуске и, если находит поддерживаемый файл, автоматически выбирает путь к нему для быстрой конвертации.
- Спрашивать, что делать при обнаружении файла в буфере обмена: Если эта функция включена, программа спросит вас, как поступить с обнаруженным файлом.
- Звуки: Активируйте звуковые сигналы о начале и окончании преобразования.
- Произносить действия: Включите функцию чтения с экрана для предоставления информации о состоянии преобразования.
- Автоматически проверять обновления: Автоматический поиск обновлений программы при запуске.
- Включать бета-версии при проверке обновлений: позволяет получать бета-версии обновлений для программы. Более подробную информацию можно найти в разделе "Бета-версии" данного руководства.
- Включить ведение журнала: Эта функция позволяет Sound Transcriber записывать в журнал шаги процесса транскрипции. Это особенно полезно для устранения ошибок. При необходимости активируйте ведение журнала и отправьте нам созданный файл. Если запись журнала отключена, старые журналы будут удалены, но детали последнего шага будут сохранены. Это гарантирует, что программа сможет регистрировать ошибки, которые могут возникнуть, даже если вы не сможете запустить программу в первый раз и активировать запись журнала.
- Восстановить настройки по умолчанию: Восстановление настроек до значений по умолчанию.

### Параметры сохранения:

Опции этого раздела влияют на функцию сохранения в меню Файл программы.

- Автосохранение файлов: Включить автоматическое сохранение результатов конвертации.
- Путь сохранения: Отображает текущий путь для сохранения файлов. Для его изменения используйте кнопку Обзор.
- Сохранить как .txt: Включить автоматическое сохранение файлов с расширением .txt.
- Сохранить как .docx: Сохранить файл с расширением .docx.
- Сохранить как файл субтитров: сохранение файла с расширением .srt.
- Сохранять загруженные файлы. Файлы, загруженные из Интернета, будут сохранены после преобразования. Если эта функция отключена, файл будет загружен, преобразован, а затем удален.

Если функция автосохранения отключена, пункт "Сохранить" в меню "Файл" будет выполнять ту же функцию, сохраняя файлы в соответствии с указанными расширениями и путем.

### Google:

В этом разделе необходимо ввести безопасный ключ API в текстовое поле под названием "Секретный ключ". Вы можете нажать кнопку редактирования, чтобы изменить ключ. Кроме того, при использовании этой службы можно настроить длительность сегмента, указав длительность каждой части файла.

Обратите внимание, что для преобразования файл необходимо разделить на несколько сегментов. Максимальная продолжительность одного сегмента для этого сервиса составляет одну минуту.

### OpenAI:

Как и предыдущий сервис, этот раздел позволяет ввести ключ API. Однако максимальная продолжительность каждого файла при использовании OpenAI составляет 30 секунд.

### Wit.ai:

Поскольку Wit.ai разделяет языки на основе API-ключей, этот раздел позволяет комбинировать языки следующим образом:

Вы найдёте список добавленных в данный момент языков.

Каждый язык имеет соответствующее скрытое поле для редактирования API-ключа.

Вы можете отредактировать ключ, удалив старый, вставив новый, а затем воспользовавшись кнопкой Редактировать. Также можно воспользоваться кнопкой Добавить, чтобы добавить новый ключ.

Выберите язык, соответствующий вашему приложению в Wit.ai, вставьте ключ и нажмите кнопку Добавить.

Повторите эти шаги для каждого языка, который вы собираетесь использовать. Получив ключ на сайте Wit.ai, вернитесь в окно настроек, чтобы добавить его.

Вы можете удалить отдельные ключи или все сохранённые ключи, связанные с этим сервисом, используя соответствующие кнопки.

Выберите формат аудио: Чтобы указать расширение файла при конвертации, выберите ogg или mp3. Если у вас плохое интернет-соединение.

Выбор wav позволит быстро разделить файл, но он будет больше по размеру.

Наконец, вы можете указать продолжительность каждого сегмента файла - от 4 до 20 секунд. Выберите длительность, которая даёт наилучшие результаты.

Нажмите OK, когда закончите настраивать параметры.

## Сочетания клавиш::

В Sound Transcriber предусмотрено несколько сочетаний клавиш для повышения скорости и удобства использования.

- Ctrl+O: Открыть окно просмотра файлов, чтобы выбрать файл для преобразования.
- Ctrl+V: Вставить файл из буфера обмена для преобразования.
- Ctrl+1: переключение на сервис Google.
- Ctrl+2: Переключиться на сервис Wit.ai.
- Ctrl + 3: переключиться на шепот.
- Ctrl+Enter: Начать процесс конвертации.
- P: Отображение текущего процента выполнения конверсии.
- Ctrl+S: Открыть опции сохранения.
- Ctrl+Shift+S: сохранить результат в формате .srt.
- Ctrl+Shift+T: сохранить результат в формате .txt.
- Ctrl+Shift+D: сохранить результат в формате .docx.
- Ctrl+U или F3: Проверить наличие обновлений.
- Alt+S или F8: открыть настройки.
- F1: Открыть руководство пользователя.
- F2: Просмотр обновлений.
- F5: Пожертвовать.
- F6: Открыть репозиторий.
- F7: Открыть файл журнала.
- F9: О программе.
- Ctrl+W или Ctrl+F4: Закрыть звуковой транскриптор.

## Как конвертировать файлы:

Чтобы конвертировать файлы, откройте Sound Transcriber и найдите файл, нажав кнопку "Обзор" или воспользовавшись сочетанием клавиш Ctrl+O. Кроме того, вы можете скопировать файл с устройства и вставить его с помощью Ctrl+V.

Вы также можете воспользоваться опцией, доступной в контекстном меню для поддерживаемых файлов, меню "Отправить в" в Windows или просто перетащить файл.

Кроме того, можно скопировать ссылку на видео с таких сайтов, как Facebook, Twitter (X), Youtube, SoundCloud и других.

Выберите нужный язык и сервис с помощью предлагаемых ярлыков или настройте их в настройках. Нажмите "Пуск" или воспользуйтесь сочетанием клавиш Ctrl+Enter, чтобы начать конвертацию.

Знаете ли вы, что открыть Sound Transcriber можно, нажав Windows + R, чтобы открыть диалог "Выполнить", а затем набрав st.

### Примечания:

- В процессе конвертирования вы можете приостановить его, будь то извлечение текста или загрузка файла. Однако важно отметить, что начало нового процесса приведет к удалению всего, что связано с предыдущим процессом.
- Если процесс будет остановлен во время разделения файлов, его нельзя будет возобновить.

## Сообщайте об ошибке:

Если вы столкнулись с какой-либо ошибкой в работе Sound Transcriber, вы можете воспользоваться способами связи, доступными в меню "Связаться с нами" в разделе "Помощь". Предоставьте подробное объяснение действий, которые привели к ошибке. Мы рекомендуем предоставить файл Sound Transcriber.log, который поможет нам лучше понять и устранить ошибку.

Перейдите в раздел "Настройки" > "Общие" и включите ведение журнала. Затем повторите действия, которые привели к возникновению ошибки. Не забудьте отключить ведение журнала после отправки файла. Обратите внимание, что включение этой опции может привести к созданию большого файла .log. Однако при желании вы можете оставить журнал включенным.
 
Файл можно найти по следующему пути:

AppData\Roaming\tecwindow\SoundTranscriber

## Бета-обновления:

Sound Transcriber предлагает систему бета-обновлений, позволяющую вам тестировать новые функции и помогать нам в выявлении ошибок. Хотя активировать эту функцию несложно, есть несколько важных моментов, которые следует учитывать:

- Бета-версии могут быть нестабильными, и мы не можем гарантировать немедленный выпуск исправлений для любых проблем, с которыми вы столкнетесь.
- В некоторых случаях мы можем выпустить до трех обновлений в течение одной недели.
- При использовании бета-версий некоторые опции могут быть не всегда переведены на выбранный вами язык.
- Мы рекомендуем проводить бета-тестирование только в том случае, если вам удобно выявлять ошибки и делиться ими.

Чтобы перейти к бета-версиям, перейдите в "Настройки" > "Общие", включите опцию "Включать бета-версии при проверке обновлений", а затем выполните поиск обновлений.

Если вы хотите вернуться к стабильным версиям, просто отключите ту же опцию, а затем загрузите и установите последнюю стабильную версию.

Мы выражаем искреннюю благодарность всем, кто участвует в тестировании Sound Transcriber, находит ошибки и делится своими соображениями.

## Как переводить:

Хотя в настоящее время Sound Transcriber поддерживает лишь ограниченное число языков в опциях интерфейса и руководстве пользователя, он может транскрибировать речь в текст на широком спектре языков.

Тем не менее, мы приветствуем всех, кто заинтересован в переводе программы на свой родной язык.

Перевод опций интерфейса в основном опирается на файлы .po, которые можно редактировать с помощью программы Poedit. Вы можете скачать Poedit с ее официального сайта, затем перейти в репозиторий Sound Transcriber на GitHub или найти папку с программой на вашем устройстве. Далее найдите файл messages.pot и откройте его в Poedit. После этого вы можете перевести строки на нужный вам язык, сохранить файл (при этом будут созданы файлы .po и .mo) и поделиться этими файлами с нами.

Sound Transcriber может распознавать и адаптировать новые переводы, позволяя вам протестировать свой перевод перед отправкой нам. Для этого перейдите в папку Languages, создайте папку с кодом вашего языка (первые две буквы языка), затем создайте подпапку с именем LC_MESSAGES и поместите в нее файлы .po и .mo. Не забудьте назвать файлы SoundTranscriber.po и SoundTranscriber.mo.

Хотя перевод руководства пользователя и обновлений Sound Transcriber не является обязательным, у вас есть возможность перевести Markdown-файлы, доступные на GitHub в репозитории Sound Transcriber, а затем поделиться ими с нами.

Если вы решите не переводить руководство пользователя и файл обновлений, Sound Transcriber будет отображать их на английском языке.

Перевод программного обеспечения - это постоянная работа, и мы будем связываться с вами перед выпуском новых обновлений, чтобы вы могли перевести все новое содержимое.

## Веб-сайт Sound Transcriber:

Хотя официального сайта Sound Transcriber не существует, вы можете получить доступ ко всем необходимым ресурсам в репозитории Sound Transcriber на gitHub. В этом репозитории содержатся файлы перевода и последняя версия программы.

Примечание: Sound Transcriber на данный момент не является программой с открытым исходным кодом, и репозиторий не содержит исходного кода программы.

[Ссылка на репозиторий.](https://github.com/tecwindow/SoundTranscriber)

## Свяжитесь с нами:

Если вы не можете получить доступ к нашему списку контактов в Sound Transcriber, вы можете связаться с нами по электронной почте, используя следующие адреса:

- Каис Алрефай: ww258148@gmail.com
- Махмуд Атеф: mahmoud.atef.987123@gmail.com
- Ахмед Бакр: AhmedBakr593@gmail.com

## особая благодарность:

- Большое спасибо Риаду Ассуму за перевод Sound Transcriber на французский язык, перевод руководства пользователя на английский язык и вычитку английской и арабской строк программы.
- Большое спасибо Георгиане Фринку за перевод Sound Transcriber на испанский язык.
- Большое спасибо Данилу за перевод Sound Transcriber на русский язык.

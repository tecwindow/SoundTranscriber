# دليل استخدام Sound Transcriber.

سيرشدك هذا الدليل للحصول على أقصى استفادة من برنامج Sound Transcriber.

ينصح بقراءته لتحصل على أقصى استفادة من البرنامج.

## ما هو Sound Transcriber?

برنامج Sound Transcriber هو برنامج متوافق مع قارئات الشاشة لتحويل الصوت لنص مع دعم استخراج ملفات الترجمات والمزيد.

Sound Transcriber من تطوير: محمود عاطف, أحمد بكر, قيس الرفاعي, من فريق نافذة التقنية TecWindow.

## الميزات:

- تحويل ملفات الصوت والفيديو إلى نص بالاعتماد على عدة خدمات.
- حفظ نتائج التحويل بامتدادات .txt و.doc أو بامتداد ملفات التسميات التوضيحية subtitles .SRT.

## الميزات المخطط لها:

- ترجمة نتائج التحويل إلى لغات متعددة.
- إضافة قواميس لتصحيح النتائج.
- تحويل النتائج إلى صوت باستخدام محركات تحويل النص إلى صوت text to speech.

## الخدمات المدعومة:

يدعم البرنامج حاليا التحويل عبر الإنترنت فقط عن طريق التعرف على الكلام من Google و Whisper من OpenAi و wit.ai من Meta.

## ملاحظات هامة:

- يعمل البرنامج افتراضيًا مع خدمة Google; لاستخدام خدمات أخرى, عليك الحصول على مفتاح API من تلك الخدمات.
- نوصي باستخدام wit.ai مع اللغة العربية لكونها تعطي أفضل النتائج.
- خدمة Whisper من OpenAI تمت إضافتها بناءً على تجربة سابقة, قد لا تعمل بالشكل المطلوب, وقد لا تعمل كليًا, فيرجى مشاركة تجربتك معنا للعمل على حلها.
- توفر لك wit.ai مفاتيح API مجانية على عكس OpenAI.
- لتحويل ملف, ينبغي اختيار اللغة قبل عملية التحويل. وفي حال كان الملف متعدد اللغات, قد لا يتم تحويل الكلمات باللغات غير اللغة المختارة بسبب الخدمات نفسها ولا يمكننا القيام بأي شيء حيال ذلك في الوقت الراهن.
- قبل التحويل، يتم تقسيم الملفات إلى أجزاء  تصل مدة الواحد منها بحده الأقصى إلى 60 ثانية حسب الوقت المسموح به لكل خدمة. ونتيجة لذلك, قد يتم فقدان بعض الكلمات. للحصول على أفضل نتيجة, نوصي بتغيير مدة التقسيم بحسب مدة السكتات وطول الملف الذي تقوم بتحويله والمدة التي تتيحها كل خدمة.

## الامتدادات المدعومة:

لتحويل ملف, ينبغي أن يحمل أحد الامتدادات التالية:

.mp3, .wav, .aac, .flac, .oga, .opus, .mp4, .avi, .mkv, .mov, .m4a, .ogg, .ram, .rm, .wma, .wmv, .3gp, .flv.

## الحصول على مفاتيح API:

### Wit.ai:

إذا قمنا بتوفير مفتاح API في البرنامج, فسيتم حظره بعد استخدام البرنامج من قبل العديد من الأشخاص.

كما أن wit.ai توفر مفاتيح منفصلة لكل لغة, أي إنك بحاجة لإنشاء تطبيق (App) باللغة التي تريد التحويل بها ثم الحصول على مفتاح خاص به.

ولا يمكننا جمع كل اللغات المستخدمة لإنشاء مفاتيح لها.

نتيجة لكل ما سبق, نرشدكم إلى طريقة الحصول على مفتاح خاص بكم.

قد تبدو الخطوات كثيرة, لكنها سهلة وستحتاج لتنفيذها مرة واحدة فقط.

-  افتح [موقع wit.ai](https://wit.ai)
- اضغط على "Continue With Meta" ثم قم بتسجيل الدخول باستخدام حسابك في Meta.
- تابع خطوات إنشاء الحساب الاعتيادية, أو اضغط على "Continue with Facebook".
- انتقل ؟إلى العنوان الأول في الصفحة, اضغط h أو 1 لمستخدمي قارئات الشاشة.
-  اضغط على "New App" ثم قم بتسمية التطبيق بأي اسم إنجليزي, على سبيل المثال, test أو my app.
- من لغة التطبيق, ستجد صندوق خيارات قم بفتحه واختر اللغة المناسبة, سيتم تحويل الملفات الصوتية باللغة التي اخترتها.
- أخيرا, اضغط على "Create".
- بعد ذلك, تحرك في الصفحة لتجد اسم التطبيق الذي قمت بإنشائه, اضغط عليه, ثم اضغط حرف h أو رقم 3, أو انتقل بالعنوان الثالث لمستخدمي قارئ الشاشة. ويكمن هدفك هنا في إيجاد زر باسم Management.
- بعد الوصول إلى هذا الزر, تحرك بحرف b لتجد زرًّا باسم Settings.اضغط على هذا الزر.
- ثم تحرك بالرقم 2 أو h لمستخدمي قارئ الشاشة, حتى تجد عنوانًا باسم Client Access Token, انزل وستجد مفتاحك عبارة عن زر. يمكنك تحديد النص يدويًا أو الضغط على المفتاح نفسه لنسخه.
- عد إلى Sound Transcriber وقم بلصق مفتاحك في الحقل المخصص له كما سيرد لاحقا.

هذا كل شيء, فقط ستحتاج لتكرار الخطوات وإنشاء تطبيق جديد باسم مختلف والحصول على الرمز في حال كنت تريد أن يقوم Sound Transcriber بالتحويل باستخدام لغة أخرى.

باختصار, ينبغي عليك تحديد لغة كل ملف تحوله. وإذا كنت تريد أن يدعم البرنامج أكثر من لغة مع wit.ai فما عليك سوى تكرار الخطوات لتحصل على مفتاح يتبع اللغة التي تريد استخدامها.

### Whisper:

يدعم Sound Transcriber التحويل باستخدام مفاتيح API المقدمة من OpenAI لخدمة Whisper, وهي غير مجانية.

يمكنك الدفع مقابل عدد الحروف, ولسنا هاهنا بصدد ذكر الخطط.

راجع الحدود والاشتراكات من [هذه الصفحة/.](https://platform.openai.com/account/billing/overview)

ثم سجل الدخول وأضف طريقة دفع على مسؤوليتك.

افتح [صفحة مفاتيح API](https://platform.openai.com/account/api-keys) واضغط على "Create new secret key" وقم بنسخ المفتاح.

ثم قم بإضافته في إعدادات البرنامج كما سيرد لاحقًا.

## واجهة Sound Transcriber:

عند فتح البرنامج, ستجد مربع تحرير للنتيجة, تنقل بمفتاح tab لتصفح بقية الخيارات.

صندوق اللغة لتحديد لغة الملف المراد تحويله, تحرك بالأسهم وحدد لغتك المناسبة.

ثم زر "بدء Start" لبدء التحويل.

يليه زر "حفظ بصيغة Save As" لتحديد طريقة حفظ الناتج.

ثم مربع تحرير للقراءة فقط يحتوي على اسم أو رابط  الملف المراد تحويله.

ثم زر "تصفح Browse" لتحديد مسار الملف المراد تحويله.

وكذلك يمكنك استخدام اختصارات لوحة المفاتيح كما هو مبين لاحقًا.

ملاحظة, يختلف ترتيب العناصر على الشاشة عن ترتيبها أثناء التنقل بمفتاح Tab.

## القوائم:

في البرنامج بعض القوائم التي يمكنك الوصول إليها عن طريق ضغط مفتاح Alt.

### ملف File:

- فتح Open لاستعراض جهازك والبحث عن ملف لتحويله.
- حفظ Save لحفظ نتيجة التحويل بامتدادات يتم تحديدها في الإعدادات.
- حفظ بصيغة Save As لحفظ النتيجة بامتداد معين.
- الإعدادات Settings تحتوي على خيارات البرنامج وتخصيصاته.
- إغلاق Exit للخروج من البرنامج.

### الخدمات:

تحتوي على أسماء الخدمات المتاحة للتحويل, يمكنك اختيار أي خدمة.

### مساعدة Help:

- دليل المستخدم User Guide لعرض الملف الذي تقرؤه حاليا.
- ما الجديد What's new لعرض مستجدات Sound Transcriber.
- التحقق من وجود تحديثات Check for Updates للبحث عن تحديثات البرنامج.
- اتصل بنا Contact us لعرض قوائم تحتوي على خيارات للتواصل مع مطوري البرنامج.
- حول About لعرض معلومات عن Sound Transcriber.

## إعدادات Sound Transcriber:

تنقسم إعدادات Sound Transcriber على نحو مشابه لإعدادات قارئ الشاشة NVDA إلى عدة تصنيفات, كلٌّ منها يحتوي على بعض الخيارات، ويمكنك الانتقال بالسهمين الأعلى والأسفل بين أقسام الإعدادات ثم استخدام مفتاح التنقل Tab و Shift+Tab لتصفح خيارات القسم المحدد.

### عام General:

يحتوي هذا القسم على عدة خيارات تخص البرنامج بأكمله, وهي على النحو الآتي:

- لغة الواجهة Interface Language لتحديد لغة البرنامج وخياراته.
- الخدمة Service لتحديد الخدمة التي يتم استخدامها في تحويل الملفات.
- الكشف التلقائي عن وجود ملف في الحافظة Auto detect if there is a file in the clipboard لجعل البرنامج يتحقق من حافظة جهازك عند فتحه في كل مرة؛ فإذا وجد ملفًا مدعومًا قام بتحديد مساره لبدء التحويل بسرعة.
- السؤال عما ينبغي فعله عند اكتشاف ملف في الحافظة Ask what to do when a file is detected in the clipboard هذا الخيار مرتبط بالخيار السابق؛ فإذا تم تحديده سألك البرنامج عما ينبغي فعله بالملف المكتشف.
- الأصوات Sounds لتفعيل أصوات التنبيهات عند بدء التحويل وانتهائه.
- نطق الإجراءات Speak Actions لجعل قارئ الشاشة يعلمك عن حالة التحويل.
- التحقق التلقائي من التحديثات Check for Updates Automatically للبحث عن تحديثات البرنامج بشكل آلي عند فتحه.
- استعادة الإعدادات الافتراضية Restore Default Settings لإرجاع الإعدادات إلى وضعها الافتراضي.

### خيارات الحفظ Save options:

تؤثر خيارات هذا القسم على خيار الحفظ الموجود في قائمة "ملف" في البرنامج.

- حفظ الملفات تلقائيا Auto Save files لجعل البرنامج يحفظ نتائج التحويل في ملفات بشكل آلي.
- مسار الحفظ Save Path لمعرفة المسار المحدد لحفظ الملفات، ثم زر تصفح Browse لتغييره.
- حفظ بصيغة .txt, Save as Text File لتفعيل حفظ الملف تلقائيا بهذا الامتداد.
- حفظ بصيغة .docx, Save as .Docx File لحفظ الملف بهذا الامتداد.
- حفظ بصيغة ملف ترجمات Save as Subtitle File لحفظ الملف بامتداد .srt.
- الاحتفاظ بالملفات التي تم تنزيلها, سيتم الحتفاظ بالملفات التي تم تنزيلها من الإنترنت لتحويلها, في حال تم تعطيله, سيتم تنزيل الملف وتحويله ثم حذفه.

في حال قمت بتعطيل ميزة الحفظ التلقائي, فسيؤدي خيار "حفظ" في قائمة "ملف" الوظيفة نفسها, بمعنى أنه سيحفظ الملفات وفقا للامتدادات المحددة وفي المسار المحدد هنا.

### Google:

ليس ثمة الكثير مما لذكره هنا, فلديك مربع كتابة آمن باسم Secret Key يحتوي على مفتاح API يمكنك الضغط على زر تعديل edit وتغييره, أو Segment duration by seconds لتغيير مدة كل جزء من أجزاء الملف عند استخدام هذه الخدمة.

فكما ذكرنا, ينبغي تقسيم الملف على عدة أجزاء حتى يتم تحويله.

الحد الأقصى لهذه الخدمة هو دقيقة واحدة لكل ملف.

### OpenAI:

تنطبق الخيارات المذكورة في الخدمة السابقة نفسها هنا, باستثناء أن الحد الأقصى لكل ملف هو 30 ثانية.

### Wit.ai:

نظرا لأن هذه الخدمة تفصل اللغات بحسب مفاتيح API فقد تم تصميم هذا القسم من الإعدادات ليجمع اللغات على النحو الآتي:

ستجد قائمة تحتوي على اللغات المضافة حاليًا, يليها حقل تحرير مخفي يحتوي على مفتاح API خاص بهذه اللغة، ثم زر لتعديله وزر لإضافة مفتاح جديد.

عند الضغط على زر "إضافة", قم بتحديد اللغة لتتطابق مع اللغة التي حددتها لتطبيقك في موقع wit.ai ثم قم بلصق المفتاح واضغط إضافة Add.

كرر الخطوات مع اللغات التي تستخدمها. وبعبارة أخرى: بعد الحصول على مفتاح من الموقع، عد إلى نافذة الإعدادات هنا وقم بإضافته.

ستجد أزرارًا لحذف المفتاح المحدد, أو كل المفاتيح المحفوظة المرتبطة بهذه الخدمة.

اختر صيغة الصوت, Choose audio format: لتحديد امتداد الملف عند تحويله, اختر ogg أو mp3. في حال كان اتصال الإنترنت لديك سيئ.

سيؤدي اختيار wav إلى تقسيم الملف بسرعة, لكنه سيكون بحجم أكبر.

أخيرا, ستجد مدة كل ملف عند التقسيم, وهي بين 4 و20 ثانية.


اختر ما يناسبك للحصول على أفضل نتيجة.

ثم اضغط ok عند الانتهاء من ضبط الإعدادات.

## اختصارات لوحة المفاتيح:

يقدم لك Sound Transcriber العديد من اختصارات لوحة المفاتيح التي تجعل استخدامه أسرع وأسهل.

- Ctrl+O: فتح نافذة تصفح جهازك لتحديد ملف لتحويله.
- Ctrl+V: لصق ملف من حافظتك لتحويله.
- Ctrl+1: التبديل إلى خدمة Google.
- Ctrl+2: التبديل إلى خدمة wit.ai.
- Ctrl+3: التبديل إلى خدمة Whisper.
- Ctrl+Enter: بدء عملية التحويل.
- P: معرفة نسبة تقدم عملية التحويل.
- Ctrl+s: فتح خيارات الحفظ.
- Ctrl+Shift+s: حفظ النتيجة بامتداد .srt.
- Ctrl+shift+t حفظ النتيجة بامتداد .txt.
- Ctrl+Shift+d: حفظ النتيجة بامتداد .docx.
- Ctrl+U: البحث عن التحديثات.
- Alt+s: فتح الإعدادات.
- Ctrl+w أو Ctrl+F4: إغلاق Sound Transcriber.

## كيفية تحويل الملفات:

افتح Sound Transcriber, اضغط على تصفح أو الاختصار ctrl+o وحدد الملف المراد تحويله، أو انسخ الملف من جهازك والصقه عن طريق Ctrl+V.

أو قم بنسخ رابط فيديو من مواقع مثل facebook, Twitter (X), Youtube, SoundCloud وغيرهم.

حدد اللغة وغيِّر الخدمة عن طريق الاختصارات أو من الإعدادات لتحويل الملف بالخدمة المفضلة واللغة المناسبة، ثم اضغط على بدء Start أو الاختصار Ctrl+Enter للتحويل.

### ملاحظات:

- أثناء تقدم عملية التحويل, يمكنك إيقافها مؤقتا أثناء استخراج النص, وأثناء التنزيل لكن في حال بدأت عملية جديدة سيتم تجاهل كل ما يخص العملية السابقة.
- في حال أوقفت العملية أثناء التقسيم, لا يمكن استأنافها.

## الإبلاغ عن الأخطاء:

في حال واجهت أي خطأ مع Sound Transcriber, يمكنك استخدام أي من وسائل التواصل المتاحة في قائمة "اتصل بنا" داخل قائمة "مساعدة"، ثمّ اشرح ما فعلته وتسبب في حدوث الخطأ. يُفَضَّل أن تشارك معنا ملف Sound Transcriber.log الذي سيساعدنا على فهم الخطأ وحله بشكل أكبر.

يمكنك العثور على الملف في المسار التالي:

AppData\Roaming\tecwindow\SoundTranscriber

## شكر خاص:

- جزيل الشكر لرياض أسوم علىترجمة  Sound Transcriber إلى الفرنسية, ترجمة دليل المستخدم إلى الإنجليزية وتدقيق نصوص البرنامج العربية والإنجليزية.
- جزيل الشكر لـ Georgiana Frincu على ترجمة Sound Transcriber إلى الإسبانية.
- جزيل الشكر ل Danil على ترجمة Sound Transcriber إلى الروسية.
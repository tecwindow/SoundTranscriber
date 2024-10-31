# Sound Transcriber Kullan  ı  c  ı   K  ı  lavuzu

Bu kullan  ı  c  ı   k  ı  lavuzu, Sound Transcriber'  ı   kapsaml  ı   bir   ş  ekilde anlaman  ı  z  ı   ve özelliklerinden en iyi şekilde yararlanmanızı sağlamayı amaçlamaktadır.

Programın optimal kullanımı için bu kılavuzu okumanızı şiddetle tavsiye ederiz.

## Sound Transcriber'a Giriş:

Sound Transcriber, ses ve video dosyalarını metne dönüştürmek için tasarlanmış erişilebilir bir ses-metin dönüştürme programıdır. Altyazı dosyalarını çıkarma ve daha fazlasını destekler.

Mahmoud Atef, Ahmed Bakr ve Qais Alrefai tarafından TecWindow ekibinde geliştirilmiştir.

## Özellikler:

Sound Transcriber aşağıdaki özellikleri sunar:

- Çeşitli transkripsiyon hizmetleri kullanarak ses ve video dosyalarının metne dönüştürülmesi.
- Dönüşüm sonuçlarını .txt, .doc dosyaları veya .SRT altyazı dosyaları olarak kaydetme.
- YouTube, Facebook ve X gibi platformlardan videoları doğrudan dosyayı indirerek dönüştürün; dosyayı kolay erişim ve gelecekteki kullanım için kaydetme seçeneğiyle birlikte.

## Planlanan Özellikler:

Geliştirme aşamasında olan birkaç özellik:

- Dönüşüm sonuçlarının birden fazla dile çevrilmesi.
- Sözlüklerle yazım denetimi fonksiyonu.
- Sonuçların metin-okuma motorları kullanılarak sese dönüştürülmesi.

## Desteklenen Hizmetler:

Yazılım şu anda yalnızca Google'ın konuşma tanıma, OpenAI'nin Whisper ve Meta'nın wit.ai hizmetleriyle çevrimiçi dönüşümü desteklemektedir.

## Önemli Notlar:

Lütfen aşağıdaki önemli bilgileri dikkate alın:

- Varsayılan olarak program Google hizmetini kullanır. Diğer hizmetleri kullanmak için ilgili hizmet sağlayıcısından bir API anahtarı almanız gerekir.
- Arapça dil transkripsiyonu için en iyi sonuçlar için wit.ai kullanmanızı öneririz.
- OpenAI'Whisper, önceki deneyimlere dayanarak eklenmiştir, ancak beklenildiği gibi çalışmayabilir veya hiç çalışmayabilir. Herhangi bir sorunu çözmemize yardımcı olmak için geri bildiriminizi ve deneyimlerinizi minnetle bekliyoruz .
- OpenAI'nin aksine, Wit.ai ücretsiz API anahtarları sağlar.
- Bir dosyayı dönüştürürken, dönüşüm sürecini başlatmadan önce uygun dili seçtiğinizden emin olun. Eğer bir dosya çok dilliyse, seçilen dil dışındaki dillerdeki kelimeler hizmetlerin sınırlamaları nedeniyle doğru şekilde dönüştürülemeyebilir.
- Dönüştürmeden önce dosyalar, her hizmetin sınırlamalarına bağlı olarak 60 saniyeye kadar olan parçalara bölünür. Bu nedenle, bazı kelimeler bu işlem sırasında kaybolabilir. Optimal sonuçlar elde etmek için, hizmetlerin izin verdiği sessizlik süresi, dosya uzunluğu ve parça süresi baz alınarak parça süresini ayarlamanızı öneririz.
- .srt dosyaları ile optimal sonuçlar için, parçalar için kısa bir süre, örneğin 5 saniye, seçmenizi öneririz.
- Sound Transcriber, [Microsoft Visual C++ 2015-2022 Redistributable X64](https://aka.ms/vs/17/release/vc_redist.x64.exe) ve [Microsoft Visual C++ 2013 Redistributable X64](https://aka.ms/highdpimfc2013x64enu) gerektirir. Program sizde çalışmıyorsa, lütfen gerekli dosyaları indirmek ve yüklemek için önceki bağlantıları kullanın.
- Şu anda, Sound Transcriber aşağıdaki dilleri desteklemektedir: Arapça, İngilizce, İspanyolca, Fransızca, Rusça, Türkçe ve Vietnamca.
- Sound Transcriber, yalnızca 64 bit sistemlerde Windows 8 ve üzeri ile uyumludur.

## Desteklenen Dosya Uzantıları:

Sound Transcriber aşağıdaki dosya uzantılarını dönüşüm için destekler:

.mp3, .wav, .aac, .flac, .oga, .opus, .mp4, .avi, .mkv, .mov, .m4a, .ogg, .ram, .rm, .wma, .wmv, .3gp, .flv.

## API Anahtarlarının Alınması:

### Wit.ai:

Program içinde bir API anahtarı eklemiş olsak, muhtemelen çok sayıda kullanıcı tarafından yaygın kullanım sonrası engellenirdi.

Ayrıca, wit.ai her dil için ayrı API anahtarları sağlar. Bu, istenilen dilde bir uygulama oluşturmanız ve ilgili API anahtarını almanız gerektiği anlamına gelir.

Ne yazık ki, bireysel tercihlere göre değişiklik gösterdikleri için tüm diller için API anahtarlarını toplamak mümkün değildir.

Bu nedenle, size kendi özel API anahtarınızı nasıl alacağınız konusunda talimatlar vereceğiz.

Aşağıdaki adımlar geniş görünebilir, ancak basittir ve yalnızca bir kez tamamlanmaları gerekmektedir.

- [wit.ai web sitesini](https://wit.ai) açın.
- "Meta ile Devam Et" seçeneğine tıklayarak Meta hesabınızla giriş yapın.
- Normal hesap oluşturma adımlarını izleyin veya "Facebook ile Devam Et" seçeneğine basın.
- Sayfanın üst kısmına gidin, ekran okuyucu kullanıcıları için h veya 1 tuşuna basın.
- "Yeni Uygulama"ya tıklayın ve uygulamaya test veya benim uygulamam gibi herhangi bir İngilizce isim verin.
- Uygulamanın dili için bir seçenek kutusu bulacaksınız, açın ve uygun dili seçin. Ses dosyaları seçtiğiniz dile dönüştürülecektir.
- Son olarak "Oluştur" düğmesine tıklayın.
- Oluşturduğunuz uygulamanın adını bulun, üzerine tıklayın ve ardından "Yönetim" düğmesine gidin.
- Bu düğmeye ulaştığınızda, ayarlar düğmesini bulmak için b tuşuna basın. Bu düğmeye basın.
- Müşteri Erişim Simgesi adlı bir başlık bulana kadar ekran okuyucu kullanıcıları için numara 4 veya h tuşlarıyla hareket edin, aşağı kaydırın ve anahtarınızı bir düğme olarak bulacaksınız. Metni manuel olarak seçip kopyalayabilir veya aynı düğmeye basarak otomatik olarak kopyalayabilirsiniz.
- Sound Transcriber'a geri dönün ve API anahtarınızı sağlanan alana yapıştırın.
- Sound Transcriber'a geri dönün ve API anahtarınızı sağlanan alana yapıştırın.

Bu adımları tekrarlayarak farklı bir adla yeni bir uygulama oluşturup başka bir dilde transkripsiyon yapmak için bir API anahtarı alabilirsiniz. wit.ai ile birden fazla dil kullanmak istiyorsanız, her dil için bir API anahtarı almak üzere adımları tekrarlayın.

### Whisper:

Sound Transcriber, OpenAI'nin Whisper API anahtarları kullanılarak transkripsiyonu destekler, ancak bu anahtarlar ücretsiz değildir.

Fiyatlandırma transkripsiyon yapılan karakter sayısına dayanmaktadır ve burada belirli planlar belirtilmemiştir.

Sınırlamalar ve abonelik seçenekleri hakkında ayrıntılı bilgi almak için lütfen [bu sayfayı](https://platform.openai.com/account/billing/overview) ziyaret edin. Giriş yapmanın ve ödeme yöntemi eklemenin kendi sorumluluğunuzda olduğunu unutmayın.

Sound Transcriber için bir API anahtarı almak üzere, [API anahtarları sayfasına](https://platform.openai.com/account/api-keys) gidin ve "Yeni gizli anahtar oluştur" seçeneğine tıklayın. Oluşturulan anahtarı kopyalayın ve daha sonra program ayarlarına ekleyin.

## Sound Transcriber Arayüzü:

Programı açtığınızda, dönüştürülen sonucu gösteren bir düzenleme kutusu bulacaksınız. Diğer seçenekler arasında gezinmek için sekme tuşunu kullanın.

"Dil" kutusu, dönüştürmek istediğiniz dosyanın dilini belirtmenize olanak tanır. Uygun dili seçmek için ok tuşlarını kullanın.

Dönüşüm sürecini başlatmak için "Başlat" düğmesine tıklayın.

Bir sonraki adımda, çıktı kaydetme tercihlerinizi belirlemenize olanak tanıyan "Farklı Kaydet" düğmesini bulacaksınız.

Bunun altında, dönüştürülecek dosyanın yolu veya bağlantısını gösteren salt okunur bir düzenleme kutusu bulunur.

Dönüştürmek istediğiniz dosyayı bulup seçmek için "Gözat" düğmesini kullanın.

Ayrıca, daha sonra açıklanacak olan klavye kısayollarını da kullanabilirsiniz.

Unutmayın, sekme tuşuyla gezinirken ekrandaki öğelerin sırası farklı olabilir.

## Menüler

Program, Alt tuşuna basarak erişilebilen birkaç menü içerir.

### Dosya:

- Aç: Cihazınızda bir dosya aramak ve seçmek için bu seçeneği kullanın.
- Kaydet: Dönüştürme sonucunu ayarlarda belirtilen uzantıyla kaydedin.
- Farklı Kaydet: Sonucu belirli bir uzantıyla kaydedin.
- Ayarlar: Program seçeneklerine ve özelleştirmelere erişin.
- Günlük Dosyasını Aç: Sound Transcriber günlük dosyasını görüntülemenizi sağlar.
- Çıkış: Programdan çıkın.

### Servisler:

Çevrim için mevcut hizmetlerin adlarını içerir, herhangi bir hizmeti seçebilirsiniz.

### Yardım:

- Kullanım Kılavuzu: Şu anda erişilen dosyayı görüntüleyin.
- Ne yeni: Sound Transcriber değişiklik günlüğünü görüntüleyin.
- Güncelleme Kontrolü: Program güncellemelerini arayın.
- Bizimle iletişime geç: Program geliştiricileriyle iletişim kurma seçeneklerini içeren menüyü görüntüleyin.
- Bağış Yap: Sound Transcriber geliştiricilerine bağış yapın.
- Açık Depo: Sound Transcriber deposunu GitHub'da açar, program açık kaynak değildir.
- Hakkında: Sound Transcriber hakkında bilgi sağlar.

## Sound Transcriber Ayarları:

NVDA ekran okuyucu ayarlarına benzer şekilde, Sound Transcriber ayarları çeşitli bölümlere ayrılmıştır ve her biri çeşitli seçenekler içerir. Bölümler arasında yukarı ve aşağı ok tuşlarını kullanarak gezinebilirsiniz. Seçili bölümdeki seçenekler arasında gezinmek için Sekme ve Shift+Sekme tuşlarını kullanın.

### Genel:

Bu bölüm, program genelinde geçerli olan çeşitli seçenekleri içerir:

- Arayüz Dili: Programın dilini belirtin.
- Servis: Dosya dönüştürme için kullanılan hizmeti tanımlayın.
- Aynı anda dönüştürülecek dosyalar: Bu özellik, aynı anda kaç dosyanın dönüştürüleceğini belirlemenize olanak tanır. Bu özellik, aynı anda transkribe edilecek dosya sayısını belirtmenizi sağlar.
- Pano'da dosya olup olmadığını otomatik algıla: Program başlatıldığında panonuzu kontrol eder ve desteklenen bir dosya bulursa, hızlı dönüşüm için yolunu otomatik olarak seçer.
- Pano'da bir dosya algılandığında ne yapılacağını sor: Etkinleştirilirse, program algılanan dosyayla nasıl başa çıkılacağını size sorar.
- Sesler: Dönüşüm başladığında ve bittiğinde uyarı seslerini etkinleştirin.
- Eylemleri Sesli Olarak Söyle: Ekran okuyucunun dönüşüm durumu bilgilerini sağlamasına izin verir.
- Güncellemeleri Otomatik Olarak Kontrol Et: Program başlatıldığında otomatik olarak güncellemeleri arar.
- Güncellemeleri kontrol ederken beta sürümlerini kapsa: Program için beta güncellemelerini almanızı sağlar. Bu kılavuzun beta güncellemeleri bölümünde daha fazla bilgi bulabilirsiniz.
- Günlük tutmayıü Etkinleştir: Bu özellik, Sound Transcriber'ın dönüştürme süreci adımlarının bir günlüğünü yazmasına izin verir. Özellikle hataları gidermek için kullanışlıdır. Gerektiğinde, günlüğü etkinleştirin ve bize oluşturulan dosyayı gönderin. Günlük devre dışı bırakıldığında, eski günlükler silinir, ancak son adımın ayrıntıları saklanır. Bu, programı ilk kez çalıştırıp günlüğü etkinleştiremeseniz bile hataları kaydedebilmesini sağlar.
- Varsayılan Ayarlara Geridön : Ayarları varsayılan değerlere sıfırlayın.

### Kaydetme Seçenekleri:

Bu bölümdeki seçenekler, programın Dosya menüsündeki kaydetme işlevini etkiler.

- Dosyaları Otomatik Kaydet: Dönüştürme sonuçlarının otomatik olarak kaydedilmesini etkinleştirir.
- Kaydetme Yolu: Dosyaların kaydedileceği geçerli yolu gösterir. Değiştirmek için Gözat düğmesini kullanın.
- .txt Olarak Kaydet: Dosyanın .txt uzantısıyla otomatik olarak kaydedilmesini sağlar.
- .docx Olarak Kaydet: Dosyayı .docx uzantısıyla kaydeder.
- Altyazı Dosyası Olarak Kaydet: Dosyayı .srt uzantısıyla kaydeder.
- İndirilen dosyaları sakla: İnternetten indirilen dosyalar dönüşümden sonra saklanacaktır. Devre dışı bırakılırsa, dosya indirilecek, dönüştürülecek ve ardından silinecektir.

Otomatik Kaydetme özelliği devre dışı bırakıldığında, "Dosya" menüsündeki "Kaydet" seçeneği aynı işlevi yerine getirir, dosyaları belirtilen uzantılara ve yola göre kaydeder.

### Google:

Bu bölümde, sağlanan "Gizli Anahtar" adlı metin kutusuna güvenli bir API anahtarı girmeniz gerekmektedir. Anahtarı değiştirmek için düzenle düğmesine tıklayabilirsiniz. Ayrıca, bu hizmeti kullanırken dosyanın her bir kısmının süresini belirterek segment süresini ayarlayabilirsiniz.

Bu hizmet için maksimum segment süresi bir dakikadır.

### OpenAI:

Bu bölüm, önceki hizmete benzer şekilde bir API anahtarı girmenize olanak tanır. Ancak, OpenAI kullanıldığında her dosyanın maksimum uzunluğu 30 saniyedir.

### Wit.ai:.

Wit.ai dilleri API anahtarlarına göre ayırdığı için, bu bölümde dilleri birleştirme olanağı sağlar:

Eklenen dillerin bir listesini bulacaksınız.

Her dilin API anahtarı için karşılık gelen gizli bir düzenleme alanı vardır.

Anahtarı düzenleyebilir, eski anahtarı kaldırıp yeni anahtarı yapıştırabilir ve ardından Düzenle düğmesini kullanabilirsiniz. Alternatif olarak, yeni bir anahtar eklemek için Ekle düğmesini kullanabilirsiniz.

Wit.ai uygulamanızla eşleşen dili seçin, anahtarı yapıştırın ve Ekle düğmesine tıklayın.

Kullanmayı düşündüğünüz her dil için bu adımları tekrarlayın. Wit.ai sitesinden bir anahtar aldıktan sonra, geri dönüp ayarlar penceresine ekleyin.

Bu hizmetle ilişkili kaydedilmiş anahtarları tek tek veya toplu olarak silmek için sağlanan düğmeleri kullanabilirsiniz.

Ses formatını seçin: Dönüştürme sırasında kullanılacak dosya uzantısını belirtmek için ogg veya mp3 seçin. İnternet bağlantınız kötüyse wav'ı seçin.

Son olarak, her dosya parçasının süresini 4 ila 20 saniye arasında belirtebilirsiniz. En iyi sonuçları veren süreyi seçin.

Ayarları yaptıktan sonra Tamam'a basın.

Ayarları yaptıktan sonra Tamam'a basın.

## Klavye Kısayolları:

Sound Transcriber, hız ve kullanım kolaylığını artırmak için birkaç klavye kısayolu sağlar.

- Ctrl+O: Dönüştürmek için bir dosya seçmek için dosya gözatma penceresini açar.
- Ctrl+V: Pano'dan dönüştürmek için bir dosya yapıştırır.
- Ctrl+1: Google hizmetine geçer.
- Ctrl+2: Wit.ai hizmetine geçer.
- Ctrl+3: Whisper'a geçer.
- Ctrl+Enter: Dönüştürme sürecini başlatır.
- P: Dönüştürme ilerlemesinin mevcut yüzdesini görüntüler.
- Ctrl+S: Kaydetme seçeneklerini açar.
- Ctrl+Shift+S: Sonucu .srt olarak kaydeder.
- Ctrl+Shift+T: Sonucu .txt olarak kaydeder.
- Ctrl+Shift+D: Sonucu .docx olarak kaydeder.
- Ctrl+U veya F3: Güncellemeleri kontrol eder.
- Alt+S veya F8: Ayarları açar.
- F1: Kullanıcı kılavuzunu açar.
- F2: Güncellemeleri görüntüler.
- F5: Bağış yap.
- F6: Depoyu açar.
- F7: Günlük dosyasını açar.
- F9: Hakkında.
- Ctrl+W veya Ctrl+F4: Sound Transcriber'ı kapatır.

## Dosyalar Nasıl Dönüştürülür:

Dosyaları dönüştürmek için Sound Transcriber'ı açın ve "Gözat" düğmesine tıklayarak dosyayı seçin veya Ctrl+O kısayolunu kullanın. Alternatif olarak, cihazınızdan dosyayı kopyalayıp Ctrl+V kısayolunu kullanarak yapıştırabilirsiniz.

Desteklenen dosyalar için bağlam menüsünde bulunan seçeneği, Windows'taki Gönder menüsünü kullanabilir veya sürükle ve bırak işlemi yapabilirsiniz.

Ayrıca Facebook, Twitter (X), Youtube, SoundCloud gibi sitelerden video bağlantısını kopyalayabilirsiniz.

Sağlanan kısayolları kullanarak veya ayarlarda ayarlayarak istenilen dili ve hizmeti seçin. Dönüşümü başlatmak için "Başlat" düğmesine basın veya Ctrl+Enter kısayolunu kullanın.

Windows + R tuşlarına basarak Çalıştır iletişim kutusunu açıp st yazarak Sound Transcriber'ı açabileceğinizi biliyor muydunuz.

### Notlar:

- Dönüşüm sırasında, metin çıkarma veya bir dosya indirme sırasında olsa da duraklatma seçeneğiniz vardır. Ancak, yeni bir işlem başlatıldığında, önceki işle ile ilgili her şey göz ardı edilir.
- Dosyaları bölme işlemi sırasında süreç durdurulursa, devam ettirilemez.

## Hataları Bildirin:

Sound Transcriber ile ilgili bir hata ile karşılaşırsanız, "Yardım" bölümündeki "Bize Ulaşın" menüsünde bulunan iletişim yöntemlerini kullanarak bildirebilirsiniz. Hataya neden olan eylemleri ayrıntılı olarak açıklayın. Sound Transcriber.log dosyasını paylaşmanızı öneririz, bu bize hatayı daha etkili bir şekilde anlamamıza ve çözmemize yardımcı olacaktır.

Ayarlar > Genel bölümüne gidin ve günlüğü etkinleştirin. Ardından hatayı karşılaşmanıza neden olan adımları tekrarlayın. Dosyayı gönderdikten sonra günlüğü devre dışı bırakmayı unutmayın. Bu seçeneği etkin bırakmak büyük bir .log dosyasına neden olabilir. Ancak, günlüğü etkin bırakmayı seçebilirsiniz.

Dosyayı şu yolda bulabilirsiniz:

AppData\\Roaming\\tecwindow\\SoundTranscriber

## Beta Güncellemeleri:

Sound Transcriber, yeni özellikleri test etmenizi ve hataları belirlememize yardımcı olmanızı sağlayan bir beta güncelleme sistemi sunar. Bu özelliği etkinleştirmek kolay olsa da, dikkate almanız gereken bazı önemli noktalar vardır:

- Beta güncellemeleri kararsız olabilir ve karşılaştığınız sorunlar için hemen düzeltmeler yayınlanacağını garanti edemeyiz.
- Bazı durumlarda, aynı hafta içinde üç güncellemeye kadar yayınlayabiliriz.
- Beta sürümlerinde tüm seçenekler her zaman tercih ettiğiniz dile çevrilmeyebilir.
- Beta testlerini, hataları belirlemekte ve paylaşmakta rahat olan kişilere öneririz.

Beta güncellemelerine katılmak için Ayarlar > Genel bölümüne gidin, "Güncellemeleri kontrol ederken beta sürümlerini kapsa " seçeneğini etkinleştirin ve ardından güncellemeleri arayın.

Kararlı sürümlere geri dönmek isterseniz, aynı seçeneği devre dışı bırakın ve ardından en son kararlı sürümü indirin ve yükleyin.

Sound Transcriber'ı test eden, hataları bulan ve görüşlerini paylaşan herkese içtenlikle teşekkür ederiz.

## Nasıl Çevirilir:

Sound Transcriber şu anda yalnızca arayüz seçeneklerinde ve kullanıcı kılavuzunda sınırlı sayıda dili desteklemektedir, ancak çok geniş bir dil yelpazesinde konuşmayı metne dönüştürebilir.

Bununla birlikte, programı ana dilinize çevirmek isteyen herkesi memnuniyetle karşılıyoruz.

### Arayüz çevirisi:

Arayüz seçeneklerinin çevirisi öncelikle .po dosyalarına dayanır ve Poedit programı kullanılarak düzenlenebilir. Poedit'i resmi web sitesinden indirip, Sound Transcriber deposuna GitHub'da veya cihazınızdaki program klasörüne gidin. Daha sonra messages.pot dosyasını bulun ve Poedit'te açın. Buradan, dizeleri tercih ettiğiniz dile çevirebilir, dosyayı kaydedebilir (bu, hem .po hem de .mo dosyaları oluşturur) ve bu dosyaları bizimle paylaşabilirsiniz.

### Test çevirisi:## Nasıl Çevirilir:

Sound Transcriber, yeni çevirileri tanıyabilir ve siz çevirinizi göndermeden önce test etmenize olanak tanır. Bunu yapmak için, Languages klasörüne gidin, dilinizin koduyla (dilin ilk iki harfi) bir klasör oluşturun, ardından LC\_MESSAGES adlı bir alt klasör oluşturun ve .po ve .mo dosyalarını içine yerleştirin. Dosyaları SoundTranscriber.po ve SoundTranscriber.mo olarak adlandırmayı unutmayın.

### Dokümantasyon çevirisi:## Nasıl Çevirilir:

Güncelleme günlüğü ve kullanıcı kılavuzunun çevirisi zorunlu olmamakla birlikte, bunları .pot dosyalarını kullanarak kendi dilinize çevirebilirsiniz.

.md dosyalarını .pot dosyalarını oluşturmak için kullanıyoruz, ardından bunları çevirmenlere gönderiyoruz. Daha sonra, çevirmenlerden aldığımız .po dosyalarını tekrar .md dosyalarına ve ardından programla birlikte eklemek için .html dosyalarına dönüştürüyoruz.

Bu, el kitabının ve değişiklik günlüğünün herhangi bir bölümünde düzeltmeler yapmamıza olanak tanır ve bu düzeltmelerin tüm desteklenen dillerde tutarlı bir şekilde uygulanmasını sağlar. Ayrıca, farklı dillerdeki dosyaların tam olarak aynı format ve yapıda kalmasını garanti eder.

Dosyaları çevirmek için bu adımları izleyin:

- .pot dosyalarını GitHub'daki depodan veya Sound Transcriber dizinindeki Dokümantasyon klasöründen alın.
- Poedit kullanarak çevirin.
- Bazı ifadelerin ek noktalarla tekrarlandığını görebilirsiniz. Bu, ifadeleri ayırt etmek ve doğru pozisyonlarda kalmalarını sağlamak için kullanılır. Aynı sayıda nokta ekleyin, biz çeviriyi entegre ederken bunları kaldıracağız.
- Metinlerin doğru sırada görünmeyebileceğini unutmayın eğer çeviri eksikse. Doğru bir şekilde çevrildikten sonra, dosyayı yeniden açarak metinleri doğru sırada görebilirsiniz.
- Son olarak, dosyalarınızı bizimle paylaşın.

### Notlar:

- Kullanıcı Kılavuzu ve Güncellemeler dosyasını çevirmemeyi seçerseniz, Sound Transcriber onları İngilizce olarak gösterecektir.
- Yazılım çevirisi devam eden bir çalışmadır ve yeni içerikleri çevirebilmeniz için güncellemeler yayınlamadan önce sizinle iletişime geçeceğiz.

## Sound Transcriber web sitesi:

Sound Transcriber'ın resmi bir web sitesi olmamasına rağmen, tüm gerekli kaynaklara GitHub'daki Sound Transcriber deposundan erişebilirsiniz. Bu depo, çeviri dosyalarını ve programın en son sürümünü içerir.

Not: Sound Transcriber şu anda açık kaynak değildir ve depo programın kaynak kodunu içermez.

[Depo bağlantısı.](https://github.com/tecwindow/SoundTranscriber)

## Bize Ulaşın:

Sound Transcriber içinde iletişim listemize erişemiyorsanız, aşağıdaki e-posta adreslerini kullanarak bize ulaşabilirsiniz:

- Qais Alrefai: ww258148@gmail.com
- Mahmoud Atef: mahmoud.atef.987123@gmail.com
- Ahmed Bakr: AhmedBakr593@gmail.com

## Özel Teşekkürler:

- Sound Transcriber'ı Fransızcaya çeviren, kullanıcı kılavuzunu İngilizceye çeviren ve programın İngilizce ve Arapça dizelerini düzelten Riad Assoum'a teşekkür ederiz.
- Sound Transcriber'ı İspanyolcaya çeviren Georgiana Frincu'ya teşekkür ederiz.
- Sound Transcriber'ı Rusçaya çeviren Danil'e teşekkür ederiz.
- Sound Transcriber'ı Türkçeye çeviren Kadir öz'e teşekkür ederiz.
- Sound Transcriber'ı Vietnamca'ya çevirdiği için Nguyen Anh Duc'a çok teşekkürler.

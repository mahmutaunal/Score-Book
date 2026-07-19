# Skor Defteri Gizlilik Politikası

Son güncelleme: 19 Temmuz 2026

Skor Defteri çevrimdışı çalışan bir skor takip uygulamasıdır ve kullanıcı hesabı oluşturmaz. Profil, arkadaş, fotoğraf, oyun, not ve skor verileri yalnızca kullanıcının cihazında saklanır ve geliştiriciye gönderilmez.

Ücretsiz sürüm Google AdMob tarafından sağlanan sınırlı reklamları gösterebilir. Kullanıcının bölgesine ve izin tercihlerine bağlı olarak Google; reklam kimliklerini, IP adresini, cihaz ve uygulama bilgilerini, IP adresinden türetilen yaklaşık konumu, reklam gösterim ve etkileşimlerini ve izin sinyallerini işleyebilir. Uygulama reklam istemeden önce geçerli reklam iznini belirlemek ve almak için Google User Messaging Platform (UMP) kullanır. Tek seferlik reklamsız satın alım gelecekteki reklam isteklerini durdurur.

İsteğe bağlı `Reklamları Kalıcı Olarak Kaldır` satın alımı Apple App Store veya Google Play tarafından işlenir. AlpWare Studio ödeme kartı bilgilerini almaz. Uygulama satın alımı tamamlamak veya geri yüklemek için gereken ürün kimliğini, işlem ve makbuz verisini, satın alma durumunu ve mağaza hesabı hak sahipliği bilgisini işler. Yerel hak sahipliği önbelleği çevrimdışıyken reklamların kapalı kalmasını sağlar. Mağaza sağlayıcıları satın alımları kendi koşulları ve gizlilik politikaları kapsamında işler.

Analiz ve çökme raporlama isteğe bağlıdır ve varsayılan olarak kapalıdır. Kullanıcı Ayarlar'dan **Analiz ve çökme raporları** seçeneğini etkinleştirirse Google Firebase, AlpWare Studio adına sınırlı teknik verileri işler:

- Firebase Analytics; uygulama etkileşimlerini, ekran adlarını, uygulama/cihaz bilgilerini ve genel teknik verileri alır.
- Firebase Crashlytics; çökme yığın izlerini, ilgili uygulama durumunu, cihaz ve işletim sistemi bilgilerini ve çökmeleri gruplamak ve teşhis etmek için gereken kurulum kimliklerini alır.

Skor Defteri analiz olaylarına veya çökme raporlarına profil bilgilerini, oyuncu ya da arkadaş adlarını, notları, fotoğrafları veya skorları eklemez. Firebase Analytics için reklam kimliği toplama ve reklam kişiselleştirme sinyalleri kapalıdır; AdMob tarafından kullanılan reklam izni ve kimlikler UMP ve kullanıcının tercihleri üzerinden ayrıca yönetilir. Kullanıcı isteğe bağlı tanılamayı Ayarlar'dan istediği zaman durdurabilir. Google bu verileri geçerli koşulları ve gizlilik belgeleri kapsamında küresel altyapısında işleyebilir.

Fotoğraf arşivine erişim yalnızca kullanıcı profil veya arkadaş fotoğrafı seçtiğinde gerçekleşir. Yedekleme ve paylaşım işlemleri kullanıcı tarafından başlatılır ve işletim sisteminin paylaşım paneli üzerinden kullanıcının seçtiği hedefe aktarılır.

Kullanıcılar Ayarlar > Veriler ve gizlilik > Tüm verileri sil seçeneğiyle yerel oyun ve profil verilerini kalıcı olarak silebilir. Uygulamanın kaldırılması da yerel uygulama verilerini cihazdan kaldırır. Mağaza tarafından yönetilen satın alma geçmişi ve hak sahipliği bu işlemle silinmez; Apple App Store veya Google Play üzerinden yönetilir. Daha önce Firebase'e iletilen veriler Google'ın geçerli saklama politikalarına göre saklanır ve silinir.

Gizlilik soruları için mağaza listelemesindeki geliştirici destek iletişimini kullanın.

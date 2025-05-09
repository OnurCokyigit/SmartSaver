🇹🇷 SmartSaver – Mobil Finans Yönetimi Uygulaması 💸📊
SmartSaver, Android platformu için geliştirilmiş, kapsamlı bir kişisel finans yönetim uygulamasıdır. Uygulama, kullanıcıların hem günlük para transfer işlemlerini hem de hisse senedi yatırımlarını kolaylıkla takip edebilmelerine olanak sağlar. Bu proje, CENG427 dersi kapsamında geliştirilmiştir ve hem frontend (Android) hem de backend (Node.js + SQLite) bileşenlerini içeren tam teşekküllü bir yapıya sahiptir.

🔍 Uygulama Ne İşe Yarar?
Kullanıcılar uygulama üzerinden kayıt olabilir, giriş yapabilir ve bakiye yönetimi gerçekleştirebilir.

Kullanıcılar, favori kişilerine para transferi yapabilir veya onlardan para alabilir.

Hisse senetleri API üzerinden çekilir ve kullanıcılar bu hisseleri satın alabilir veya satabilir.

Kullanıcıların işlemleri detaylı olarak kaydedilir ve geçmiş transfer/hisse hareketleri görüntülenebilir.

Yatırımlar ve getiriler grafiklerle analiz edilebilir.

🖼️ Uygulama Arayüzü ve Kullanım
1. 🟦 Splash Screen
Uygulama açıldığında özel bir splash screen sizi karşılar.

2. 👤 Giriş / Kayıt Ekranı
Kullanıcılar e-posta, şifre ve isim bilgileriyle kayıt olabilir.

Kayıtlı kullanıcılar sisteme giriş yapar.

3. 🏠 Dashboard
Kullanıcının adı ve mevcut bakiyesi gösterilir.

Transfer, yatırım planı, hisse listesi ve istatistik ekranlarına geçiş yapılabilir.

4. 💸 Para Transferi
E-posta ile alıcı belirlenir, tutar girilir.

Transfer başarılı olursa hem alıcı hem gönderici bakiyeleri güncellenir.

📥 Gelen transferler "Received" olarak gösterilir.

5. 📈 Hisse Detay Ekranı
Seçilen hissenin 1 hafta / 1 ay / 1 yıl fiyat hareketleri çizgi grafiği ile gösterilir.

Kullanıcı sahip olduğu miktarı görebilir, yeni hisse alabilir ya da elindekileri satabilir.

Tüm veriler AlphaVantage API üzerinden canlı çekilir.

6. 📊 İstatistik Ekranı (MyStats)
Kullanıcının toplam yatırımı, kâr/zarar durumu ve sahip olduğu hisselerin getirisi gösterilir.

Geçmiş para transferleri bir liste halinde küçük bir pencere (AlertDialog) ile görüntülenebilir.

⚙️ Kullanılan Teknolojiler
Katman	Teknoloji	Açıklama
📱 Mobil	Java (Android SDK)	Tüm frontend mimarisi
🔁 API	Volley / JSON	API veri çekimi ve POST işlemleri
📈 Grafik	MPAndroidChart	Hisse grafik çizimleri
🧠 Yerel DB	SQLite / Room	Hisse geçmişi ve offline veri
🌐 Backend	Node.js + Express.js	Sunucu tarafı işlemler
🗃️ Database	SQLite3	Veritabanı işlemleri (kullanıcı, transfer, portföy)

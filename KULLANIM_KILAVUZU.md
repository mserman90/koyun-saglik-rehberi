# 🐑 Koyun Sağlık Rehberi - Kullanım Kılavuzu

**Koyun Sağlık Rehberi**, internet bağlantısı ve sunucu kurulumu gerektirmeyen, doğrudan telefon ve bilgisayar tarayıcısında çalışan Progressive Web App (PWA) mimarili çevrimdışı (%100 offline) bir küçükbaş sürü sağlığı, aşı, koç katımı ve kuzu takip asistanıdır.

---

## 🚀 1. Hızlı Başlangıç & Kurulum

### Telefonunuza Yükleme (Android / iOS):
1. İnternetiniz varken **[https://mserman90.github.io/koyun-saglik-rehberi/](https://mserman90.github.io/koyun-saglik-rehberi/)** adresini açın.
2. Tarayıcı menüsünden (üç nokta veya paylaş butonu) **"Ana Ekrana Ekle"** veya **"Uygulamayı Yükle"** seçeneğine dokunun.
3. Telefonunuzun ana ekranına uygulama simgesi eklenir. Artık merada, yaylada, internetin hiç çekmediği taş ağıllarda dahi tam ekran çalışır.

### Bilgisayarda Açma:
- Doğrudan web adresini açabilir veya depodaki [`index.html`](./index.html) dosyasına çift tıklayarak çalıştırabilirsiniz.

---

## 🧭 2. Menü & Buton Hiyerarşisi (Ağıl & Mera Odaklı)

Ağıl ve mera şartlarında eldivenle ve tek elle kullanıma uygun olarak butonlar klinik aciliyete göre sıralanmıştır:
- **Alt Menü (Bottom Navigation):** `📊 Ağıl Özeti` $\rightarrow$ `🆘 İlk Yardım` $\rightarrow$ `🩺 Muayene` $\rightarrow$ `💊 İlaç & Süt` $\rightarrow$ `🥛 Sağımcı` $\rightarrow$ `🍼 Kuzu Bakımı` $\rightarrow$ `🌾 Yem & Geviş` $\rightarrow$ `⚖️ Kilo Ölç` $\rightarrow$ `🩸 Koç Katımı` $\rightarrow$ `📅 Aşı Takvimi` $\rightarrow$ `💰 Zarar Defteri`.
- **Hızlı İşlemler Paneli:** Hayat kurtaran `🆘 Acil İlk Yardım & Hayat Kurtarma` en üstte çift genişlikli buton olarak konumlandırılmıştır.
- **Eldiven Uyumu:** Tüm butonlar en az 48px dokunma yüksekliğine sahip olup koyun kırkımı, kuzu doğumu veya çamurlu saha koşullarında kolayca basılabilir.

---

## 📱 3. Temel Modüllerin Kullanımı

### 0. 📷 Kamerayla Küpe Okuma (Barkod / QR)
- Hayvan arama, muayene, ilaç yapma, koç katımı, tartım ve sağım ekranlarında yer alan sarı **"📷 Oku"** butonuna basın.
- Kamerayı koyunun sarı kulak küpesindeki barkod veya karekoda doğrultun.
- Küpe numarası otomatik dolar ve hayvanın geçmişi anında ekrana gelir.

---

### 1. 📊 Ağıl Özeti & Hayvan Kaydı
- **Yeni Hayvan Ekleme:** Ekrandaki **"+ Yeni Ekle"** butonuna basarak küpe numarası, cinsiyeti (Koyun/Öveç veya Koç/Toklu), yaşı ve kondisyonunu girin.
- **Kondisyon Skoru (Bel Omuru):** Sırt ve bel omuruna el basarak `1.5` (Jilet gibi zayıf), `3.0` (İdeal et-yağ dengeli) veya `4.5` (Aşırı yağlı) kondisyonunu seçin.
- **Pazardan Yeni Alınanlar:** *"Pazardan yeni alındı, ayrı bölmede bekleyecek (Karantina)"* kutucuğunu işaretleyin.

---

### 2. 🆘 Küçükbaş Acil İlk Yardım & Hayat Kurtarma
Veteriner hekim ağıla ulaşana kadar uygulanacak kritik protokoller:
- **🧠 Gebelik Zehirlenmesi (İkiz Koması / Ketozis):** Doğuma 2-3 hafta kala yerde yatan, kör gibi yürüyen gebe koyunlara ağızdan propilen glikol veya pekmez içirme, damardan glikoz serumu desteği.
- **⚡ Çelerme / Yem Çarpması (Enterotoksemi):** Ani tane yem/taze ot sonrası çırpınan hayvanda yemi derhal kesme, ağızdan karbonatlı su ve Clostridium antitoksin serumu.
- **❄️ Yeni Doğan Kuzu Donması & Üşüme (Hipotermi):** Ağzı buz gibi kuzuya süt zorlamama; ısıtma lambası/kutusuyla vücut ısındıktan sonra kolostrum verme.
- **💧 Sidik Zoru & İdrar Yolu Tıkanması:** Besi tokluları ve koçlarda penis ucu uzantısındaki tuz kristallerinin temizlenmesi.
- **🐺 Kurt / Köpek Isırması & Kanama:** Basınçlı tampon, yara temizliği, tetanoz aşısı ve antibiyotik kalkanı.
- **🌿 Bakır / Zehirli Ot Zehirlenmesi:** Zehirli otu kesme, aktif kömür ve sıvı yağ ile bağırsak koruması.
- **💉 Aşı Şoku (Adrenalin Dozu) & İşkembe Gaz Şişmesi:** Hızlı adrenalin enjeksiyonu ve sol böğür gazında sıvı yağ / trokar tekniği.

---

### 3. 🩺 Hasta Muayene Et (Küçükbaş Saha Triyajı)
Bir koyunun veya kuzunun hastalandığından şüphelendiğinizde bu ekrana girin:
1. **Makat Ateşi (°C):** Dereceyle ölçülen ateşi girin (Normal: 38.5–40.0 °C. 40.2 °C ve üzeri yüksek ateştir).
2. **Nabız & Nefes:** 1 dakikadaki kalp atımı (Normal: 70–90, kuzuda 100-120) ve nefes sayısını yazın.
3. **Klinik Skorlama:** Keyifsizlik, iştah durumu ve hırıltılı nefesi puanlayın.
4. Sistem anında hastalığın ağırlığını ve ne yapmanız gerektiğini listeler.

---

### 4. 💊 İlaç Kaydı & Sütü/Eti Tanka Yasaklama (İKAS)
Küçükbaşta ilaç kalıntılarının süte ve ete geçmesini önler:
1. İlaç yapılan koyunu ve ilacı seçin.
2. Vurulan dozu ve saati kaydedin.
3. **Koyun İçin Özel Kurallar:**
   - **Tilmikosin Uyarısı:** Kesinlikle damara vurulmaz, yalnızca deri altı uygulanır! Süt cezası 15 gün (360 sa), et 42 gündür.
   - **Albendazol Uyarısı:** Koç katımında ve ilk 45 günde yavru attıracağı için gebelere verilmez.
   - Oksitetrasiklin LA, Meloksikam ve Penisilin arınma süreleri otomatik sayılır.

---

### 5. 🥛 Sağımcı Ekranı (Büyük Puntolu Hızlı Kontrol)
Sağımhane personeli için tek bakışta:
- Küpe numarasını yazın veya kamerayla okutun.
- Antibiyotikli koyunlarda **🔴 BU KOYUNU TANKA SAĞMA** kırmızı alarmı verir.
- İlaçsız koyunlarda **🟢 SAĞIMA UYGUN** yeşil onayı çıkar.

---

### 6. 🍼 Kuzu Hayatta Tutma & İlk Ağız Sütü (Kolostrum)
1. **İlk 2 Saat Kuralı:** Yeni doğan kuzuya ilk 2 saatte en az **300–400 mL (2 çay bardağı dolusu)** koyu ağız sütü içirilmelidir.
2. **Brix Ölçer:** Refraktometre ile ağız sütünün kalitesini ölçün.
3. **Kuzu İshali Sıvı Hesabı:** Kuzu ağırlığı (ortalama 4 kg) ve göz çökme durumuna göre 24 saatte verilmesi gereken serum ve can suyu (0.4 – 0.6 Litre) hesaplanır.

---

### 7. 🌾 Yemlik, İşkembe Ekşimesi & Geviş Sayacı
1. **Geviş Getirme Sayacı:** Yem döküldükten 2 saat sonra ağıldaki yerde yatan koyunları ve geviş getirenleri sayıp yazın. Hedef en az %58-60'tır.
2. **Koyun Fındığı / Zibin Kıvamı (1-5):**
   - *Skor 1:* Fışkıran ishal (🚨 Çelerme veya ağır ekşime alarmı).
   - *Skor 2:* Birbirine yapışmış cıvık fındıklar (Arpa fazla / saman az).
   - *Skor 3:* İdeal nemli ve parlak koyun zibini.
3. **Karbonat Dozu:** Sağılan koyun sayısına göre günde **15–30 gram/koyun** yem karbonatı miktarını hesaplayın.

---

### 8. ⚖️ Şerit Metreyle Koyun Canlı Ağırlık Ölçer
Kantarın olmadığı ağıl ve mera şartlarında terzi mezurasıyla kilo hesaplar:
1. **Göğüs Çevresi (cm):** Ön ayakların hemen arkasından mezurayla sarın (Koyunda genelde 75–95 cm arasıdır).
2. **Vücut Uzunluğu (cm):** Omuz başı ile kalça yumrusu arası mesafe.
3. Küçükbaş *Schaeffer Formülü* ile canlı ağırlık hesaplanır ve hayvana vurulacak iğne dozları listelenir.

---

### 9. 🩸 Koç Katımı & Doğum Çarkı (150 Gün Gebelik)
1. Koç aşım tarihini ve koçun küpe numarasını kaydedin.
2. Otomatik takvim başlar:
   - **17. Gün:** Koç aşım / kızgınlık dönüş kontrolü (Tutmadıysa koç ister).
   - **35. Gün:** Ultrason ile gebelik kontrolü ve tekiz/ikiz tespiti.
   - **120. Gün:** Doğuma 1 ay kala Çelerme / Enterotoksemi pekiştirme aşısı (Ağız sütüyle kuzuya antikor geçmesi için).
   - **150. Gün:** Beklenen kuzulama günü.

---

### 10. 📅 Akıllı Aşı Takvimi & Hatırlatıcı
- Çelerme (Enterotoksemi), Çiçek, Veba (PPR), Şap ve Brucella aşıları için takvim ve rapel sürelerini takip edin.
- Aşı yapıldığında bir sonraki tekrar tarihi otomatik oluşturulur.

---

### 11. 💰 Hastalık Masrafı & Dökülen Süt Zarar Defteri
1. Koyun sütü litre satış fiyatınızı (Örn: 38 TL/Litre) yazın.
2. Tedavi gören koyunu, hastalığı (Gök Meme, Çelerme, Piyeten vb.), veteriner ve ilaç masrafını girin.
3. İlaç yüzünden dökülen sütü yazın; toplam zararınızı kuruşu kuruşuna görün.

---

## 💾 4. Veri Yedekleme & Telefona Aktarma
- Sağımcı ekranının en altında yer alan **"📥 Yedeği İndir (JSON)"** butonuna basarak tüm koyun, kuzu ve aşı kayıtlarınızı tek bir yedek dosyası olarak indirebilirsiniz.
- Başka bir telefona geçtiğinizde **"📤 Yedeği Yükle"** diyerek saniyeler içinde tüm ağıl verilerinizi geri yükleyebilirsiniz.

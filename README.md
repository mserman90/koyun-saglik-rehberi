# Koyun Sağlık Rehberi (Offline-First & PWA)

🌐 **Canlı Yayın (Web & Mobil):** [https://mserman90.github.io/koyun-saglik-rehberi/](https://mserman90.github.io/koyun-saglik-rehberi/)  
📦 **GitHub Deposu:** [https://github.com/mserman90/koyun-saglik-rehberi](https://github.com/mserman90/koyun-saglik-rehberi)  
📖 **Detaylı Kullanım Kılavuzu:** [KULLANIM_KILAVUZU.md](./KULLANIM_KILAVUZU.md)

Bu uygulama, **koyun ve keçi yetiştiricileri, çobanlar ve küçükbaş çiftlikleri** için en eski ve en basit akıllı telefonlardan masaüstü/dizüstü bilgisayarlara kadar her cihazda **hiçbir internet bağlantısı veya sunucu kurulumu gerektirmeden** çalışan Progressive Web App (PWA) mimarili bir sürü sağlığı asistanıdır.

---

## 🚀 Nasıl Çalıştırılır?

1. **Cep Telefonunda (Android / iOS):**
   - [https://mserman90.github.io/koyun-saglik-rehberi/](https://mserman90.github.io/koyun-saglik-rehberi/) adresini açın.
   - Tarayıcı menüsünden *"Ana Ekrana Ekle"* (Add to Home Screen) veya *"Uygulamayı Yükle"* seçeneğine dokunun.
   - Uygulama telefonun hafızasına yüklenir. İnternetsiz dağda, yaylada ve taş ağıllarda bağımsız çalışır.

2. **Bilgisayarda:**
   - [`index.html`](./index.html) dosyasına çift tıklayarak tarayıcınızda doğrudan çalıştırabilirsiniz.

---

## 🧭 Saha Öncelikli Buton ve Menü Hiyerarşisi

Ağıl ve mera koşullarındaki **klinik aciliyet** ve eldivenli kullanıma göre optimize edilmiştir:
- **Alt Menü (Bottom Navigation):** `📊 Ağıl Özeti` $\rightarrow$ `🆘 İlk Yardım` $\rightarrow$ `🩺 Muayene` $\rightarrow$ `💊 İlaç & Süt` $\rightarrow$ `🥛 Sağımcı` $\rightarrow$ `🍼 Kuzu Bakımı` $\rightarrow$ `🌾 Yem & Geviş` $\rightarrow$ `⚖️ Kilo Ölç` $\rightarrow$ `🩸 Koç Katımı` $\rightarrow$ `📅 Aşı Takvimi` $\rightarrow$ `💰 Zarar Defteri`.
- **Hızlı İşlemler Paneli:** Hayat kurtaran `🆘 Acil İlk Yardım & Hayat Kurtarma` en üstte çift genişlikli buton olarak konumlandırılmıştır.
- **Eldiven & Saha Uyumu:** Min. 48px dokunma alanları, koyu mod desteği ve yüksek kontrastlı renkler.

---

## 📱 Barındırdığı Temel Küçükbaş Saha Modülleri

0. **📷 Kamerayla Küpe Okuma (Barkod & QR):**
   - Hayvan arama, muayene, ilaç/İKAS girişi, sağımcı kontrolü ve yeni hayvan ekleme ekranlarında yerel kamera kütüphanesiyle küpeleri otomatik okur (%100 offline).

1. **📊 Ağıl Gösterge Paneli (Dashboard):**
   - Toplam sürü sayısı, karantindeki hayvanlar, aktif kalıntılı süt engelleri (İKAS) ve yaklaşan aşılar.
   - Kırmızı alarm: İlaçlı koyunların küpe listesi.

2. **🆘 Küçükbaş Acil İlk Yardım & Hayat Kurtarma:**
   - **Gebelik Zehirlenmesi (İkiz Koması / Ketozis):** Ağızdan propilen glikol/pekmez ve damardan serum desteği.
   - **Çelerme / Yem Çarpması (Enterotoksemi):** Yemi kesme, karbonatlı su ve Clostridium antitoksin serumu.
   - **Yeni Doğan Kuzu Donması (Hipotermi):** Isıtma lambası/kutusu ve ısındıktan sonra kolostrum protokolü.
   - **Sidik Zoru & İdrar Yolu Tıkanması:** Koçlarda penis ucu taş uzantısı müdahalesi.
   - **Kurt/Köpek Isırması & Kanama:** Basınçlı tampon, yara temizliği ve tetanoz önlemi.
   - **Timpani & Şişme:** Sıvı yağ içirme, trokar ve aşı şokunda adrenalin dozu hesabı.

3. **🩺 Saha Triyajı & Klinik Muayene:**
   - Makat ateşi (38.5–40.0 °C koyun referansı, >40.2 °C ateş alarmı).
   - Nabız (70–90 atım), solunum (15–30 nefes), işkembe dalgası ve klinik solunum skorlama motoru.

4. **💊 Küçükbaş İKAS & İlaç Rehberi:**
   - Oksitetrasiklin LA, Meloksikam, Fluniksin, Tilmikosin (yalnızca SC uyarısı), Tulatromisin, Penisilin, Amoksisilin, İvermektin (burun kurdu & uyuz), Albendazol (gebelik uyarısı).
   - Koyun sütü ve eti için kalıntı arınma süreleri (İKAS) ve canlı saat/dakika geri sayımı.

5. **🥛 Sağımcı Ekranı (Büyük Puntolu Hızlı Kontrol):**
   - Sağımhane için büyük puntolu, renkli ve titreşimli "🟢 SAĞIMA UYGUN" veya "🔴 BU KOYUNU TANKA SAĞMA" onayı.

6. **🍼 Kuzu Hayatta Tutma & İlk Ağız Sütü (Kolostrum):**
   - İlk 2 saatte en az 300–400 mL koyu ağız sütü içirme kuralı, Brix optik refraktometre kalite ölçümü ve kuzu ishalinde sıvı/can suyu hesabı.

7. **🌾 Yemlik, İşkembe Ekşimesi & Geviş Sayacı:**
   - Geviş getirme oranı kontrolü ($\ge \%58$ kuralı), koyun fındığı/zibin kıvamı (1-5) ve koyun başı 15-30 gram karbonat hesabı.

8. **⚖️ Şerit Metre ile Koyun Canlı Ağırlık Ölçer:**
   - Kantar yokken mezurayla göğüs çevresi ve vücut uzunluğundan canlı ağırlık tahmini ve otomatik ilaç dozajı.

9. **🩸 Koç Katımı, Tohumlama & Doğum Çarkı:**
   - 17 gün aşım döngüsü, 35 gün ultrason, 120 gün doğuma hazırlık/çelerme pekiştirme aşısı ve 150 gün doğum (kuzulama) geri sayımı.

10. **📅 Akıllı Aşı Takvimi & Hatırlatıcı:**
    - Çelerme, Çiçek, Veba (PPR), Şap ve Brucella aşıları için takvim ve rapel süreleri.

11. **💰 Hastalık Masrafı & Dökülen Süt Zarar Defteri:**
    - Koyun sütü litre fiyatı referansı ile dökülen sütün, veteriner ve ilaç masraflarının maliyet analizi.

---

## 💾 Çevrimdışı Veri Güvenliği
- Tüm kayıtlar telefonun veya bilgisayarın dahili hafızasında (`localStorage`) saklanır.
- Sağımcı ekranından tek tıkla JSON formatında yedek alabilir, başka bir telefona verilerinizi kayıpsız aktarabilirsiniz.

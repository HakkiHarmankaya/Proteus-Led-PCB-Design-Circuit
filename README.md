# 💡 Proteus LED PCB Devre Tasarımı (Proteus #14)

Devre tasarım sürecinin ardından, bu çalışmada devre elemanlarının baskı devre kartı (PCB) üzerine yerleştirilerek son halinin oluşturulması anlatılmaktadır. Proteus programı ile hazırlanan LED devresi, kart düzeni ile birlikte optimize edilmiştir. Bu tür uygulamalar, gerçek hayatta üretime uygun devrelerin ön tasarımı açısından büyük önem taşır.

🔗 [Web Siteme Bakmak İçin Tıkla](https://www.hakkiharmankaya.com/)

---

## 🛠 Tasarım Süreci

### 1️⃣ Devre Şeması Oluşturma
- İlk adımda Proteus ortamında klasik LED devresi şematik olarak kuruldu.
- Gerekli bileşenler: LED, direnç, güç kaynağı.
- Devre mantığı: Direnç üzerinden geçen akım ile LED’in yanması.

### 2️⃣ PCB Moduna Geçiş
- Tasarım tamamlandıktan sonra **"PCB Layout"** ekranına geçildi.
- Tüm bileşenler otomatik olarak board üzerine yerleştirildi.

### 3️⃣ Bileşenlerin Yerleşimi
- LED ve dirençler düzgün akışa göre hizalandı.
- Gereksiz kablo geçişlerini önlemek için optimize konumlandırma yapıldı.

### 4️⃣ İzlerin Çizilmesi (Routing)
- "Auto Route" özelliği yardımıyla bağlantı yolları otomatik oluşturuldu.
- Gerekirse manuel müdahale ile hatlar sadeleştirildi.

### 5️⃣ Son Kontroller ve Simülasyon
- Devre çalışması test edildi.
- Giriş-çıkış değerleri doğrulandı.
- GND ve VCC hatları netleştirildi.

---

## 📌 Proje Detayları

- **Yazılım:** Proteus 8.x veya üzeri
- **Devre Tipi:** Basit LED kontrol devresi
- **PCB Katman Sayısı:** Tek katman
- **Kullanılan Elemanlar:** LED, direnç (330Ω), güç konektörü

---

## 🎯 Neden PCB Tasarımı?
- Gerçek hayattaki üretim süreci için temel oluşturur.
- Fiziksel yerleşim, sinyal bütünlüğü ve devre dayanıklılığı için önemlidir.
- Proteus gibi yazılımlarla sanal prototipleme yapılabilir.

---

Bu proje ile birlikte PCB tasarımı konusunda temel bir adım atmış olacaksınız. LED gibi basit bir elemanla başlayan bu yolculuk, daha karmaşık devrelere geçiş için sağlam bir temel oluşturur.

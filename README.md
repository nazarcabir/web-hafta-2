# BEUShareBox - Sınıf Projesi

BEUShareBox, öğrencilerin kampüs içinde veya sınıf ortamında ürünlerini, fikirlerini ve kaynaklarını paylaşabileceği modern, hızlı ve estetik bir "Paylaşım Kutusu" uygulamasıdır. Bu proje, saf (vanilla) teknolojiler kullanılarak yüksek performans ve temiz kod prensipleriyle geliştirilmiştir.

## 🚀 Teknoloji Yığını (Stack)

Bu proje, modern web standartlarına uygun olarak aşağıdaki teknolojilerle inşa edilmiştir:

- **TypeScript:** Tip güvenliği ve daha sağlam bir kod yapısı için ana programlama dili olarak kullanıldı.
- **HTML5 & CSS3:** Semantik yapı ve modern tasarım trendlerine uygun (Glassmorphism, Responsive Design) arayüz geliştirildi.
- **Vite:** Hızlı geliştirme ortamı ve optimize edilmiş derleme (build) süreçleri için tercih edildi.
- **LocalStorage:** Verilerin tarayıcıda kalıcı olarak saklanması (Persistence) sağlandı.
- **Lucide Icons / Emoji:** Arayüzdeki görsel anlatımı güçlendirmek için kullanıldı.

## 🏗️ Kod Yapısı ve Mimari

Proje, sürdürülebilir ve genişletilebilir bir yapı sunar:

- **`src/app.ts`:** Uygulamanın tüm iş mantığını (Business Logic) içeren ana sınıftır (`ShareBoxApp`).
  - **Veri Yönetimi:** `LocalStorage` entegrasyonu ile CRUD işlemleri yönetilir.
  - **Olay Delegasyonu (Event Delegation):** Performans optimizasyonu için tüm kart etkileşimleri tek bir merkezden yönetilir.
  - **Filtreleme & Sıralama:** `Array.filter` ve `Array.sort` metodları ile dinamik içerik yönetimi sağlanır.
- **`src/style.css`:** Tasarımın kalbidir.
  - **CSS Değişkenleri (Variables):** Tema desteği (Aydınlık/Karanlık mod) ve kolay renk yönetimi için kullanıldı.
  - **Modern Layout:** Flexbox ve Grid sistemleri ile her ekrana uyumlu (Responsive) bir yapı kuruldu.
- **`index.html`:** Uygulamanın iskeletini oluşturan semantik HTML yapısı.

## ✨ Öne Çıkan Özellikler

- **Dinamik Ürün Ekleme:** Görsel (Dosya/Base64), başlık, açıklama ve fiyat ile ürün paylaşımı.
- **Gelişmiş Filtreleme:** Kategori bazlı sekmeler ve anlık arama motoru.
- **Etkileşim:** Beğeni sistemi ve her ürüne özel yorum alanı.
- **Veri Güvenliği:** XSS saldırılarına karşı metin temizleme (Sanitization) mekanizması.
- **Dışa Aktarma:** Tüm verileri tek tıkla JSON formatında indirme özelliği.

---

**Geliştiren:** Nazar Cabir Cabır

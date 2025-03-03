# 🌟 Flex Panel Gallery

Bu proje, **CSS Flexbox** kullanarak oluşturulmuş etkileşimli bir galeri uygulamasıdır. Kullanıcı, panellere tıklayarak büyütüp küçültebilir ve metin efektlerini görebilir. **HTML, CSS ve JavaScript** kullanılarak geliştirilmiştir.


## 🚀 Özellikler

- 🖼 **Etkileşimli paneller**: Tıklanınca genişler ve içerdiği metin ortaya çıkar.
- 🎨 **Şık animasyonlar**: Geçişler yumuşak ve akıcıdır.
- 🖱 **Tıklanarak kontrol edilebilir**: Kullanıcı etkileşimi ile paneller büyütülüp küçültülebilir.


## 🛠 Kullanılan Teknolojiler

- **HTML**: Sayfa yapısını oluşturmak için.
- **CSS**: Flexbox düzenini ve animasyonları belirlemek için.
- **JavaScript**: Tıklama olaylarını ve animasyonları yönetmek için.


## 🔧 Nasıl Çalışır?

- 📌 Panel Etkileşimi (Click Event)

   Kullanıcı bir panele tıkladığında, **JavaScript** bu panelin genişlemesini sağlar.
   Daha önce genişlemiş olan panel varsa, eski haline döner.

- 🎬 Animasyonlar

   **CSS `transition`** ile **panellerin genişlemesi ve yazının belirginleşmesi** sağlanır.
   **Özel cubic-bezier eğrileri** ile daha akıcı geçişler uygulanır.

- 🎭 Animasyonu Sıfırlama

   **`transitionend` olayı**, **CSS geçişi tamamlandığında** gerekli sınıfları kaldırarak animasyonu eski haline getirir.

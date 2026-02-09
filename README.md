# 👨‍💻 Musa Zerdali - Interactive About Me Page

Bu proje, kişisel bilgilerimi içeren ve kullanıcıların arayüzü kendi zevklerine göre özelleştirebildiği interaktif bir web sayfasıdır. HTML, CSS ve JavaScript kullanılarak geliştirilmiştir.

## 🌟 Proje Hakkında

Bu web sayfası sadece statik bir portfolyo değildir. Ziyaretçiler, JavaScript fonksiyonları sayesinde sayfanın temasını, yazı tiplerini ve kenar yumuşaklıklarını değiştirebilirler.

👉 [**Canlı Önizleme İçin Tıklayın**](https://musa637.github.io/about-me-/)

## 🚀 Özellikler

* **Dinamik Tema Motoru:** JavaScript ile CSS değişkenlerini (`var(--...)`) manipüle ederek anlık tema değişimi.
* **Renk Paletleri:** `favouriteFruit` fonksiyonu ile farklı renk modları (Watermelon, Tomato, Banana, Dark Mode vb.).
* **Yazı Tipi Değiştirici:** `favouriteMovieGenre` fonksiyonu ile film türlerine göre (Space, Scary, Western vb.) değişen Google Fonts entegrasyonu.
* **Kenar Stili:** Görseller ve butonlar için `sharp` (keskin), `soft` (yumuşak) veya `round` (yuvarlak) görünüm seçenekleri.

## 🛠 Kullanılan Teknolojiler

* **HTML5:** Sayfa iskeleti.
* **CSS3:** CSS Variables (Değişkenler) ve Flexbox yapısı.
* **JavaScript (ES6):** DOM manipülasyonu ve stil mantığı.

## 💻 Kurulum ve Kullanım

Projeyi bilgisayarınızda çalıştırmak için:

1. Bu repoyu klonlayın:
    ```bash
    git clone [https://github.com/Musa637/about-me-.git](https://github.com/Musa637/about-me-.git)
    ```
2. Klasörün içine girin ve `index.html` dosyasını tarayıcınızda açın.

### Özelleştirme Nasıl Çalışır?
`index.js` dosyasındaki parametreleri değiştirerek sayfanın varsayılan görünümünü ayarlayabilirsiniz:

```javascript
// Örnek Kullanım:
favouriteMovieGenre("scary") // Yazı tipini korku temalı yapar
favouriteFruit("watermelon") // Renkleri karpuz temasına çeker
favouriteMode("dark")        // Karanlık modu açar

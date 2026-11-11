# 🎲 3D Interactive Web Dice (Üç Boyutlu Çift Zar)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Three.js](https://img.shields.io/badge/Three.js-black?style=for-the-badge&logo=three.js&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)

Mobil ve masaüstü cihazlarla tam uyumlu, WebGL ve **Three.js** kullanılarak geliştirilmiş 3D zar atma uygulaması. Ekran dikey olarak 2 bölmeye ayrılmıştır; her dokunuşta zarlar rastgele döner ve tam yüzey açısıyla (2D hissiyatında net okunabilir) durur.

---

## 📸 Ekran Görüntüsü

<div align="center">
  <img src="https://via.placeholder.com/400x700.png?text=App+Preview" alt="Mobil 3D Zar Ekran Görüntüsü" width="320"/>
</div>

---

## ✨ Özellikler

- 📱 **Mobil Öncelikli (Responsive) Tasarım:** Ekran boyutuna tam adapte olan esnek 3D Viewport.
- 🎲 **Fiziksel Dönüş & 2D Durma:** Zarlar havada rastgele açılarla döner, durduğunda ise yüzey tam olarak kameraya bakacak şekilde kilitlenir.
- 🎨 **Dinamik Yüzey Çizimi (Zero-Asset):** Harici resim dosyasına gerek duymadan HTML5 Canvas üzerinde zar yüzeylerini anlık olarak üretir.
- 🌙 **Modern Renk Paleti:** Canlı mavi üst zemin ve mat koyu alt zemin ile yüksek kontrastlı modern UI.
- ⚡ **Yüksek Performans:** 60 FPS akıcı animasyonlar için optimize edilmiş yumuşak gölgeler (Soft Shadows) ve `requestAnimationFrame` döngüsü.

---

## 🚀 Canlı Önizleme & Kullanım

Proje tek bir HTML dosyası üzerinde çalışacak şekilde yapılandırılmıştır. Herhangi bir derleme işlemi (build step) veya bağımlılık yüklemesi gerektirmez.

1. **GitHub Pages üzerinden çalıştırma:**
   - Reponuzun **Settings > Pages** sekmesinden projenizi tek tıkla yayınlayabilirsiniz.

2. **Yerel olarak çalıştırma:**
   - Repoyu klonlayın:
     ```bash
     git clone [https://github.com/kullanici-adiniz/proje-adiniz.git](https://github.com/kullanici-adiniz/proje-adiniz.git)
     ```
   - `index.html` dosyasını tarayıcınızda açın veya **Live Server** eklentisini kullanın.

---

## 🛠️ Teknolojiler

- **[Three.js (r128)](https://threejs.org/):** 3D Sahne, Kamera, Işıklandırma ve Render yönetimi.
- **HTML5 Canvas:** Zar yüzey dokularının (textures) kod ile dinamik çizilmesi.
- **CSS3 Flexbox & Gradients:** İki bölmeli modern arka plan ve duyarlı yerleşim.

---

## 📂 Dosya Yapısı

```bash
.
├── index.html        # Tüm HTML, CSS ve JavaScript (Three.js) mantığını barındıran ana dosya
└── README.md         # Proje dokümantasyonu

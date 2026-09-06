<h1 align="center">Uludağ Üniversitesi — Kampüs Turu</h1>

<p align="center">
  Görükle Kampüsü'nde tek dosyalık bir yürüyüş.<br>
  Çamlarla çevrili geniş yol, fakülte, merkez kütüphane, banklar, lambalar,<br>
  hareketli kampüs servisi ve ufukta karlı Uludağ silueti.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/kaynak%20dosya-1%20HTML-FF4D4F?style=flat-square" alt="1 HTML dosyası">
  <img src="https://img.shields.io/badge/kurulum-yok-FF4D4F?style=flat-square" alt="kurulum yok">
  <img src="https://img.shields.io/badge/Three.js-0.169.0-FF4D4F?style=flat-square" alt="Three.js 0.169.0">
</p>

---

## 30 saniyede ne oluyor?

```bash
git clone https://github.com/umutseve4/uludag-campus-tour && cd uludag-campus-tour
python3 -m http.server 8000
```

http://localhost:8000 adresini aç ve yürümeye başla. Derleme adımı veya yerel
bağımlılık yok; Three.js `0.169.0` CDN üzerinden yükleniyor.

| Kontrol | Ne yapar |
| --- | --- |
| `W` `A` `S` `D` veya ok tuşları | Yürü |
| Fareyle tıkla-sürükle | Etrafa bak |

## Sınırlar

- **Stilize bir sanatsal yorumdur; birebir kampüs haritası değildir.** Bina konumları, ölçekler ve yol düzeni gerçek yerleşkeyi temsil etmez.
- İnternet bağlantısı gerekir — Three.js CDN'den yükleniyor, tamamen çevrimdışı çalışmaz.
- Otomatik test veya CI yok; tarayıcı davranışı elle kontrol edilir.
- **Bu deponun devamı ayrı bir depoda sürüyor:** [`umutseve4/uludag-campus-tour-webgl`](https://github.com/umutseve4/uludag-campus-tour-webgl) — testli, CI'lı ve daha geniş kapsamlı sürüm orada. Bu depo ilk denemenin kaydı olarak duruyor.

Bu sahnenin ilk sürümü GPT 5.6 ile üretildi.

---

MIT

# Arc · USDC Testnet Dashboard

Tek dosyalık, statik bir cüzdan/panel arayüzü konsepti. [arcworld.netlify.app](https://arcworld.netlify.app) sayfasından ilham alınarak sıfırdan tasarlandı: USDC bakiyesi, işlem geçmişi, ağ durumu ve hızlı işlemler için bir gösterge paneli.

## Önizleme

Sade koyu bir zemin üzerine elektrik mavisi ve nane yeşili vurgular, veriler için mono yazı tipi (`IBM Plex Mono`), başlıklar için `Space Grotesk`. Bakiye kartında "Arc" temasına gönderme yapan animasyonlu bir yay (arc) göstergesi var.

## Kullanım

Herhangi bir kurulum gerektirmez — saf HTML/CSS/JS.

```bash
# Yerelde açmak için
open index.html      # macOS
xdg-open index.html  # Linux
start index.html      # Windows
```

Veya bir statik hosting servisine (GitHub Pages, Netlify, Vercel) doğrudan deploy edebilirsiniz.

### GitHub Pages ile yayınlama

1. Bu depoyu GitHub'a push edin.
2. **Settings → Pages** kısmından `main` dalını ve kök dizini (`/`) kaynak olarak seçin.
3. Birkaç dakika içinde `https://<kullanici-adi>.github.io/<repo-adi>/` adresinde yayında olur.

## Yapı

```
.
├── index.html   # Tüm sayfa: HTML + CSS + JS tek dosyada
└── README.md
```

## Notlar

- Tüm veriler (bakiye, işlemler, TPS) örnek/statik verilerdir; gerçek bir zincire veya indeksleyiciye bağlı değildir.
- "Cüzdanı Bağla" butonu yalnızca arayüz amaçlı sahte bir bağlanma animasyonu gösterir.
- `prefers-reduced-motion` ayarına saygı gösterir, klavye odaklanması görünürdür, mobilde responsive'dir.

## Lisans

MIT

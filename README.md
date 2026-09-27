# Mask of Destiny

![Mask of Destiny](assets/images/logo_wide.png)

**Mask of Destiny**, ETÜ Jam kapsamında geliştirilen tarayıcı tabanlı bir karar verme ve hayatta kalma oyunudur.

Oyunda Dünya'ya zorunlu iniş yapan bir uzaylıyı yönetirsiniz. İnsanların arasına karışırken kimliğinizi gizlemeli, kaynaklarınızı dengede tutmalı ve eve dönebilmek için sinyal gücünüzü artırmalısınız.

## Oynanış

Oyuncu karşısına çıkan kartlarda **sağa veya sola kaydırarak** karar verir.

Her karar;

- enerji,
- şüphe,
- sinyal,
- kimlik

gibi temel kaynakları etkiler. Amaç bu değerler arasında denge kurarak mümkün olduğunca uzun süre hayatta kalmak ve eve dönüş yolunu açmaktır.

## Özellikler

- Kart tabanlı karar verme sistemi
- Swipe / sağ-sol seçim mekaniği
- Birden fazla kaynak ve denge sistemi
- Hikâye ve olay tabanlı soru havuzu
- Ses, video ve görsel içerikler
- Tutorial ve ayarlar ekranı
- Tarayıcı üzerinden doğrudan çalıştırılabilir yapı

## Teknolojiler

- HTML
- CSS
- JavaScript

Herhangi bir framework kullanılmadan, saf web teknolojileriyle geliştirilmiştir.

## Proje Yapısı

```text
.
├── index.html
├── styles.css
├── game.js
├── ui.js
├── swipe.js
├── cards.js
├── questionPool.js
├── maskDistribution.js
├── assets/
├── backgrounds/
├── arkaplan_fotolari/
├── kart_fotolari/
├── editli_videolar/
└── ses_dosyalari/
```

## Çalıştırma

Projeyi klonlayın:

```bash
git clone https://github.com/harunr21/yarisma_mask.git
```

Ardından `index.html` dosyasını tarayıcıda açın.

Bazı tarayıcı özellikleri ve medya dosyaları için projeyi yerel bir HTTP sunucusu üzerinden çalıştırmak daha sağlıklı olabilir.

Örneğin:

```bash
python -m http.server 8000
```

Sonrasında tarayıcıdan:

```text
http://localhost:8000
```

adresine gidin.

## Game Jam

Bu proje **ETÜ Jam** kapsamında ekip olarak geliştirilmiştir.

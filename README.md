# Omfardo Draw

**Omfardo Draw** — çizerler için tarayıcı tabanlı dijital resim uygulaması.  
Kurulum gerektirmez. Tek HTML dosyası. Çevrimdışı çalışır.

---

## Özellikler

### Çizim Araçları
| Araç | Kısayol | Açıklama |
|------|---------|----------|
| Kalem | `P` | Hassas, düz çizgi |
| Fırça | `B` | Yumuşak kenarlı fırça |
| Eskiz Kalemi | `S` | Şeffaf, dokulu eskiz hissi |
| Marker | `M` | Geniş, yarı şeffaf düz kalem |
| Silgi | `E` | Piksel bazlı silgi |
| Dolgu | `G` | Alan doldurma (flood fill) |
| Renk Al | `I` | Tuvaldeki renkten örnekleme |
| Metin | `T` | Yazı ekleme (font, boyut, kalın, italik) |
| El / Pan | `H` | Tuvali kaydır |

### Boyama Teknikleri
| Teknik | Kısayol | Simülasyon |
|--------|---------|------------|
| Yağlı Boya | `Y` | Çok katmanlı fırça darbesi, organik leke |
| Suluboya | `W` | Şeffaf yıkama, ıslak kenar efekti |
| Akrilik | `K` | Opak, palette knife vurgu ve gölge |

### Şekil Araçları
`L` Çizgi · `R` Dikdörtgen · `O` Elips

### Katman Sistemi
- Sınırsız katman ekleme / silme / kopyalama
- Katman sırası değiştirme (↑ ↓)
- Katman birleştirme ve tümünü düzleştirme
- Her katmana ayrı opaklık ve karıştırma modu
- Katman görünürlük toggle
- Çift tıkla katman yeniden adlandırma

### Zoom & Pan
- `Ctrl + Scroll` veya zoom butonları ile yakınlaştırma
- `H` tuşu veya `Space` basılı tut → tuvali kaydır
- "Sığdır" butonu ile ekrana otomatik ölçekle

### Export
| Format | Özellik |
|--------|---------|
| PNG | Kayıpsız, şeffaflık destekli |
| JPG | Ayarlanabilir kalite (10–100%) |
| WebP | Modern format, küçük dosya boyutu |

Tuval boyutları: 800×600 · HD · FHD · A4 300dpi · 1080×1080 · 4K UHD

### Geri Bildirim Sistemi
Sağ alttaki 💬 butonundan kullanıcılar puan ve yorum gönderebilir.  
Admin paneli için URL'ye `?admin` ekle.

---

## Kullanım

### Yöntem 1 — Doğrudan Aç
```
omfardo-draw.html dosyasını tarayıcıda aç
```
Chrome, Firefox, Safari, Edge ile çalışır.  
İnternet bağlantısı yalnızca Google Fonts için gereklidir.

### Yöntem 2 — Web Sunucusu (Vercel / Netlify)
```bash
# Vercel ile deploy
vercel --prod

# veya Netlify Drop
# netlify.com/drop → dosyayı sürükle bırak
```

---

## Klavye Kısayolları

| Kısayol | Eylem |
|---------|-------|
| `Ctrl + Z` | Geri al |
| `Ctrl + Y` / `Ctrl + Shift + Z` | Yeniden yap |
| `[` / `]` | Fırça boyutunu küçült / büyüt |
| `Space` (basılı tut) | Geçici pan modu |
| `Ctrl + Scroll` | Zoom |

---

## Teknik Detaylar

- **Saf HTML5 + CSS3 + Vanilla JS** — sıfır bağımlılık
- **Canvas API** tabanlı çizim motoru
- **Çoklu katman** — her katman ayrı `<canvas>` elementi
- **Geri bildirim** — `localStorage` ile istemci taraflı depolama
- **Dosya boyutu** — ~62KB (minify edilmemiş)

---

## Sürüm

**v2.0.0** — Katmanlar, metin aracı, zoom/pan, boyama teknikleri, export formatları  
**v1.0.0** — Temel çizim araçları

---

## Lisans

MIT © Omfardo  
Detaylar için `LICENSE` dosyasına bak.

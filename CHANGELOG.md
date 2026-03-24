# Changelog

Tüm önemli değişiklikler bu dosyada belgelenmiştir.  
Format: [Semantic Versioning](https://semver.org/lang/tr/)

---

## [2.0.0] — 2026-03-25

### Eklendi
- **Katman sistemi** — sınırsız katman, opaklık, karıştırma modu, görünürlük
- **Katman işlemleri** — ekle, sil, kopyala, yukarı/aşağı taşı, birleştir, düzleştir
- **Katman küçük resimleri** — gerçek zamanlı önizleme
- **Metin aracı** — font seçimi, boyut, kalın, italik, Ctrl+Enter ile uygula
- **Zoom & Pan** — fare scroll ile zoom, el aracı ve Space ile pan
- **"Sığdır" butonu** — tuvali ekrana otomatik yerleştir
- **Yağlı Boya tekniği** — organik çok katmanlı fırça simülasyonu
- **Suluboya tekniği** — ıslak yıkama, şeffaf kenar efekti
- **Akrilik teknik** — opak palette knife vurgu ve gölge efekti
- **Export formatları** — PNG (kayıpsız), JPG (ayarlanabilir kalite), WebP
- **Tuval boyutları** — HD, FHD, A4 300dpi, 1080×1080, 4K UHD
- **Geri bildirim sistemi** — kullanıcı içi yorum ve puanlama
- **Admin paneli** — `?admin` URL parametresi ile tüm geri bildirimleri görüntüle
- **Karıştırma modları** — 12 mod (Multiply, Screen, Overlay, Difference vb.)
- **Panel accordion** — tüm panel bölümleri açılıp kapanabilir

### Değiştirildi
- Toolbar yeniden düzenlendi — teknikler ayrı grup olarak ayrıldı
- Renk paleti 40 renge genişletildi
- Geri al/yeniden yap geçmişi 18 adıma çıkarıldı
- Fırça önizlemesi tool tipine göre şekil değiştiriyor (marker → kare)

---

## [1.0.0] — 2026-03-24

### Eklendi
- **Temel çizim araçları** — Kalem, Fırça, Eskiz Kalemi, Marker
- **Silgi** — piksel bazlı
- **Dolgu aracı** — flood fill
- **Renk damlalığı** — tuvaldeki renkten örnekleme
- **Şekil araçları** — Çizgi, Dikdörtgen, Elips
- **Renk paleti** — 40 renk + özel renk seçici
- **Fırça ayarları** — boyut (1–80px), opaklık, yumuşaklık
- **Tuval** — 800×600 varsayılan, 5 hazır boyut
- **Geri al / Yeniden yap** — 40 adım geçmiş
- **PNG export**
- **Klavye kısayolları** — araç seçimi, boyut değiştirme, undo/redo

---

## Yakında Planlanan

- [ ] Seçim ve taşıma aracı (lasso / rectangular select)
- [ ] Katman maskeleme
- [ ] Özel fırça oluşturma
- [ ] Izgara ve cetvel overlay
- [ ] SVG export
- [ ] Bulut kayıt (Supabase entegrasyonu)
- [ ] Geri bildirim tabanlı öncelikli geliştirmeler

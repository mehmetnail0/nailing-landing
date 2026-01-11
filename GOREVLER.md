# nailingai.co - Yapilacaklar

## Kullanici Gorevleri

### Sosyal Kanit
- [ ] Beta kullanicilarindan testimonial topla (en az 3-5 kisi)
- [ ] Somut sonuc metrikleri topla ("X saat tasarruf", "Y icerik uretildi")
- [ ] Kullanici basari hikayeleri dokumante et

### Marketplace / Sablonlar
- [ ] Hook temalari ekle (niche bazli)
- [ ] Daha fazla ucretsiz sablon ekle
- [ ] Premium sablon kategorisi dusun

### Pazarlama
- [ ] Demo/tanitim videosu cek
- [ ] Newsletter/bulten sistemi ekle (erken erisim, guncellemeler)
- [ ] Blog/icerik pazarlamasi baslat

### Teknik
- [ ] Railway deployment kontrol et
- [ ] Analytics ekle (Plausible, Umami vb.)

---

## Sablon Fikirleri

### Niche Bazli Hook Sablonlari (100 Hook Serisi)
- [x] Personal Trainer / Fitness - 100 Hook Onerisi (MOCK EKLENDI)
- [ ] E-ticaret / Dropshipping - 100 Hook
- [ ] Saglik & Wellness - 100 Hook
- [ ] Finans / Yatirim - 100 Hook
- [ ] Teknoloji / SaaS - 100 Hook
- [ ] Yemek / Restoran - 100 Hook
- [ ] Seyahat / Turizm - 100 Hook
- [ ] Egitim / Kurs Satisi - 100 Hook
- [ ] Gayrimenkul - 100 Hook
- [ ] Guzellik / Kozmetik - 100 Hook

### Icerik Tipleri
- [ ] Instagram Reels Script Sablonu
- [ ] TikTok Trend Analizi
- [ ] YouTube Shorts Hook'lari
- [ ] Carousel Post Yapisi
- [ ] Story Serisi Planlayici

---

## App Marketplace Yapisi (Referans)

**Veritabani:** Supabase `templates` tablosu

**Template Alanlari:**
- id, name, description
- category: 'genel' | 'analiz' | 'icerik' | 'trend' | 'hook'
- tags: string[]
- nodes: JSONB (canvas node'lari)
- edges: JSONB (baglantilar)
- is_public, is_featured
- use_count

**Mevcut Kategoriler:**
- Genel
- Rakip Analizi
- Icerik Plani
- Trend Analizi
- Hook Formulleri

**Yeni Sablon Ekleme:**
1. Admin panel: /admin/templates
2. API: POST /api/templates (admin only)
3. Kod: /src/data/templates.ts

---

## Tamamlanan

- [x] Hero badge "Kapali Beta" guncelleme
- [x] AI Model logolari ekleme
- [x] Sablonlar/Marketplace bolumu ekleme
- [x] Fiyatlandirma guncelleme
- [x] Trust badges ekleme
- [x] Testimonial bolumu ekleme

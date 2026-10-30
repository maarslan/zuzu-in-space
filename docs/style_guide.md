# Görsel Stil Kural Sayfası

Seçilen stil: **Stil 2 – Kil / plastilin**. Referans görsel: `docs/style_tests/stil2_chatgpt.png` (2026-10-30, Mehmet ve oğlu seçti).
Referanstaki karakter ve araç geçerli DEĞİLDİR: Zuzu oğlunun çiziminden tasarlanacak, araç tasarımı ayrıca belirlenecek. Referans sadece malzeme, ışık ve renk dili içindir.

## Malzeme ve form
- Her şey elle yoğrulmuş kil gibi: kalın, tombul, yuvarlatılmış formlar; sivri köşe yok.
- Yüzeyler mat; hafif parmak izi / el yapımı doku (abartısız, uzaktan pürüzsüz görünür).
- Parçalar birbirinden net ayrılır: ek yerleri hafif içe gömük çizgi, bazen kil "perçin" topları.
- Metal görünmesi gereken yerler (motor ağzı, bacak) de kil gibi; parlaklık düşük, sadece hafif ışık yansıması.
- Karakterlerde büyük kafa/gövde, büyük göz; gözler parlak ve ıslak görünür (yüzeydeki tek parlak malzeme).

## Işık
- Ana ışık sıcak ve alçak açılı (gün batımına yakın), yumuşak gölge.
- Dolgu ışığı gökyüzü renginden gelir; gölgeler siyah değil, gezegen renginin koyu tonu.
- Karakterin arkasında hafif kenar ışığı (rim light) ile arka plandan ayrılma.
- Konsept görsellerde alan derinliği (bulanık arka plan) serbest; **oyunda kapalı** (okunaklılık ve performans).

## Okunaklılık (oyun içi)
- Oyun alanı (karakterin yürüdüğü/uçtuğu şerit) sade: referans görseldeki kadar çok taş YOK.
- Etkileşimli nesneler (yakıt, yıldız, iniş pisti, kurtarılacak uzaylı): sarı veya camgöbeği, kalın kontur, hafif parlama.
- Tehlikeler: turuncu-kırmızı, yavaş titreşim. Her gezegende aynı dil.
- Arka plan katmanları daha az doygun ve hafif sisli; ön plan doygun.

## Renk kodları (referanstan, Mars)
| Kullanım | Renk | Kod |
| --- | --- | --- |
| Mars gökyüzü (gündüz) | Somon-pembe | #F2A08F |
| Mars zemin | Pas turuncusu | #C8562E |
| Mars zemin gölge | Kızıl kahve | #7A2E1A |
| Kutup buzu / kar | Sıcak beyaz | #F4EEE8 |
| Güneş | Soluk sarı | #F6D77A |
| Vurgu (etkileşim) | Sarı | #F5B82E |
| Vurgu (etkileşim) | Camgöbeği | #3FC8D8 |
| Tehlike | Turuncu-kırmızı | #F0552B |
| Arayüz paneli | Lacivert | #1B2350 |

Zuzu ve araç renkleri, karakter ve araç tasarımı kesinleşince eklenecek.

## Görsel üretim komutlarına eklenecek stil cümlesi
Her yeni konsept görselinin komutunun sonuna bu cümle eklenir:

```
Style: clay-like 3D render, as if handmade from soft modeling clay: rounded chunky forms, subtle fingerprint texture, matte surfaces, warm low-angle sunlight with soft shadows, gentle rim light, cozy handcrafted feel, child-friendly. No text, no logos, no watermark, no humans.
```

Karakter/nesne kartları (3D model üretimine girdi olacak görseller) için ek:

```
Single object, centered, full body visible, plain light grey background, neutral soft studio lighting, no shadows on the ground, no depth of field, three-quarter side view.
```

## Blender üretim notu
Kil görünümü Blender'da: mat malzeme + ince gürültü dokusu ile yüzey bozulması + yuvarlatılmış kenarlar. Oyuna giden modelde doku haritaya pişirilir (mobil uyumlu). İlk deneme Gün 3'te.

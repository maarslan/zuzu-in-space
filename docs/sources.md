# Bilimsel Kaynaklar

Oyundaki her gezegen değeri burada kaynağıyla listelenir. Kontrol tarihi: 2026-10-31.
Oyunda kullanılan değerler `data/planets/*.json` dosyalarındadır.

## Kaynaklar
- [N1] NASA NSSDCA Planetary Fact Sheet (metrik tablo): https://nssdc.gsfc.nasa.gov/planetary/factsheet/index.html
- [N2] NASA NSSDCA Planetary Fact Sheet – oranlar (Dünya = 1): https://nssdc.gsfc.nasa.gov/planetary/factsheet//planet_table_ratio.html
- [N3] NASA NSSDCA Moon Fact Sheet: https://nssdc.gsfc.nasa.gov/planetary/factsheet/moonfact.html
- [N4] NASA NSSDCA Mars Fact Sheet: https://nssdc.gsfc.nasa.gov/planetary/factsheet/marsfact.html
- [N5] NASA APOD 2020-08-02, Curiosity'nin Mars'ta mavi gün batımı (2015, Gale krateri): https://science.nasa.gov/image-article/apod-2020-august-2-two-worlds-one-sun/
- [N6] NASA APOD 2023-04-04, Olympus Mons: https://science.nasa.gov/image-article/apod-2023-april-4-olympus-mons-largest-volcano-in-the-solar-system/
- [N7] NASA StarChild, Apollo 11: https://starchild.gsfc.nasa.gov/docs/StarChild/space_level1/apollo11.html

## Değerler
| Gezegen | Değer | Kaynaktaki değer | Oyundaki kullanım | Kaynak |
| --- | --- | --- | --- | --- |
| Dünya | Yerçekimi | 9,8 m/s² (Dünya = 1) | gravity 1.0 | N1 |
| Dünya | Ortalama sıcaklık | 15 °C | Ilıman, özellik etkisi yok | N1 |
| Dünya | Uydu sayısı | 1 (Ay) | Kart bilgisi | N1 |
| Dünya | Yüzey basıncı | 1 bar | Hava var: sesler normal, dengeleyici tam etkili | N1 |
| Ay | Yerçekimi | 1,62 m/s²; Dünya'nın 0,166 katı | gravity 0.166 | N2, N3 |
| Ay | Sıcaklık (ekvator) | yaklaşık 95 K – 390 K (≈ −178 °C ile +117 °C) | Güneşte sıcak, gölgede soğuk bölgeler | N3 |
| Ay | Uydu sayısı | 0 | Kart bilgisi | N1 |
| Ay | Atmosfer | Neredeyse yok (basınç ≈ 0) | Ses kısılır; dengeleyici havada değil, jetle çalışır (oyun basitleştirmesi) | N1, N3 |
| Ay | Gün uzunluğu | 708,7 saat (≈ 29,5 Dünya günü) | Kart bilgisi: iki hafta gündüz, iki hafta gece | N1 |
| Ay | Ayak izleri | Rüzgar olmadığı için milyonlarca yıl kalır | Kart bilgisi + Apollo parkuru | N7 |
| Ay | Apollo 11 | 16 Temmuz 1969 fırlatma, 4 gün sonra iniş | Apollo parkuru şakası | N7 |
| Mars | Yerçekimi | 3,73 m/s²; Dünya'nın 0,377 katı | gravity 0.377 | N2, N4 |
| Mars | Ortalama sıcaklık | −59 °C [N4] / −65 °C [N1]; Viking 1 iniş yerinde günlük −89 °C ile −31 °C | "Çok soğuk"; kalın tüy avantajlı | N1, N4 |
| Mars | Uydu sayısı | 2: Phobos ve Deimos | Kart bilgisi | N4 |
| Mars | Yüzey basıncı | ≈ 6 mbar; Dünya'nın 0,01 katı | İnce atmosfer: paraşüt ve dengeleyici az işe yarar | N2, N4 |
| Mars | Gün uzunluğu | 24,66 saat (≈ 24 saat 40 dk) | Kart bilgisi | N4 |
| Mars | Rüzgar | Viking: normalde 2–10 m/s, toz fırtınasında 17–30 m/s | Toz fırtınasında rüzgar 3–4 kat artar | N4 |
| Mars | Olympus Mons | Everest'in yaklaşık üç katı yükseklikte, Güneş Sistemi'nin en büyük yanardağı | Olympus Mons parkuru | N6 |
| Mars | Gün batımı | Mavi; tozun ışığı saçmasıyla ilgili olduğu düşünülüyor (tam anlaşılmış değil) | Gün batımı görsel sürprizi | N5 |

## Notlar
- Plandaki yaklaşık değerler (Ay ~0,17, Mars ~0,38) doğrulandı; oyunda 0,166 ve 0,377 kullanılır.
- Ay'da hava olmadığı için gerçekte kanatçık/dengeleyici aerodinamik çalışmaz. Oyunda dengeleyici "jet dengeleme modülü" olarak düşünülür; kart metinlerinde bu konuda yanlış bilgi verilmez.

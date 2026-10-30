# Kararlar

| Tarih | Konu | Karar |
| --- | --- | --- |
| 2026-10-29 | Oyunun adı | Her dilde **Zuzu in Space** (kısaltma: ZiS). Türkçe sürümde de ad değişmez. |
| 2026-10-29 | Uzaylı türünün adı | **Zuzu** (çoğulu: Zuzular). Her nesil bir Zuzu. |
| 2026-10-29 | Test cihazı | Samsung Galaxy A15 (Android 16, One UI 8.5), telefon |
| 2026-10-29 | Motor sürümü | Godot 4.7.2 stable, standart sürüm, GDScript |
| 2026-10-29 | Ekran yönü | Yatay (yandan oynanış), temel çözünürlük 1280×720, farklı ekranlara genişler |
| 2026-10-29 | Görüntü işleyici | Godot "Mobile" işleyicisi (orta seviye Android için) |
| 2026-10-30 | Görsel stil | Stil 2 – kil/plastilin (referans: `style_tests/stil2_chatgpt.png`). Kurallar: `style_guide.md` |
| 2026-10-30 | Zuzu tasarımı | Oğlunun çiziminden: ayrı kafa ve gövde, 4 kol, normal bacaklar, komik ve sevimli |
| 2026-10-30 | Araç | Roket yerine **Zuzu uzay gemisi** (roket dünyalı teknolojisi). Fizik aynı: iticiler, enerji/yakıt, yerçekimi. Atölye → hangar |
| 2026-10-31 | Zuzu konsepti | `concepts/zuzu_a.png` seçildi (ayrı kafa-gövde, 4 kol) |
| 2026-10-31 | Gemi konsepti | Uçan daire (`concepts/gemi_a.png`) temel alındı; istekler: turkuaz-yeşil, Zuzu ailesi sığacak büyüklük, anten yerine su hortumu, kısa bacaklar, bacak altında jet iticiler (uçuşta açık ve yanar, inişte kısalıp kapanır) |
| 2026-10-31 | Gemi konsepti | `concepts/gemi_a2.png` (turkuaz-yeşil, aile kubbesi, su hortumu, bacak jetleri, uçuş/iniş modu) |
| 2026-10-31 | Parça yuvaları | **İtici yuvası = bacak jetleri.** Küçük/büyük itici ayaklardaki jetleri değiştirir. İniş bacağı yuvası = ayak tabanı/amortisör. 5 yuva, 8 parça korunur |
| 2026-10-31 | Özellik varyasyonları | `concepts/zuzu_ozellikler.png` (tüy, uzun bacak, yapışkan ayak, büyük göz, ağır gövde). Modelde: yapışkan ayak tabanı turkuaz, büyük gözlere ekstra parlaklık |
| 2026-10-31 | Robot asistan | Çaydanlık robot (`concepts/robot_konsept_v1.png`, sağdaki). Düzeltme: turkuaz eldiven eller, daha uzun çaydanlık silueti |
| 2026-10-31 | Robot asistan final | `concepts/robot_final.png` onaylandı (turkuaz eldiven eller, armut çaydanlık gövde, sap, fırlayan kapak) |
| 2026-10-31 | Parça değerleri ve kalkış kuralı | `parts_and_stats.md` + `data/parts/ship_parts.json` onaylandı (taslak, Gün 13'te ayar). Kalkış: itki > ağırlık × yerçekimi; itki çubuğunda gereken seviye çizgisi |
| 2026-10-31 | Parça görselleri | `concepts/parcalar.png` onaylandı. Montaj: bacaklar kabuğun parçası (açılır/katlanır); itici modülü ayak ucuna takılır; yumuşak taban jet ağzının çevresine halka yastık olarak takılır |
| 2026-10-31 | Hangar yerleşimi | `concepts/hangar_taslak.png`: çubuklar sol üst, gemi ortada, robot solda, parça şeridi altta, fırlat sağ alt, duraklat sağ üst. Gerçek ekranda arka plan daha sade ve koyu; şeritte sadece 8 parça (kubbe ve hortum parça değil) |

## Açık kararlar

- Android paket kimliği (Gün 6; Play'de yayınlandıktan sonra değiştirilemez)

## MVP sonrası fikirler

- Su hortumu mekaniği: Venüs'te ısınan gemiyi soğutma, Mars tozunu yıkama (şimdilik sadece görsel şaka)

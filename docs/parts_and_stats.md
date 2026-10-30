# Gemi Parçaları ve İstatistik Mantığı (Gün 4 – onay için taslak)

Veri dosyası: `data/parts/ship_parts.json`. Değerler taslak; Gün 13'te oyunda denenip ayarlanacak.

## 5 yuva, 8 parça
| Yuva | Parça | Açıldığı yer | Ağırlık | Ana değer |
| --- | --- | --- | --- | --- |
| Kabuk | Hafif kabuk | Başlangıç | 2 | Dayanıklılık 1 |
| Kabuk | Sağlam kabuk | Ay 1 | 5 | Dayanıklılık 3 |
| İtici (bacak jetleri) | Küçük bacak jetleri | Başlangıç | 1 | İtki 6, tüketim 1/sn |
| İtici (bacak jetleri) | Büyük bacak jetleri | Ay 3 | 2 | İtki 12, tüketim 2,5/sn, denge −1 |
| Enerji deposu | Küçük enerji kapsülü | Başlangıç | 1 | Enerji 30 |
| Enerji deposu | Büyük enerji kapsülü | Mars 1 | 3 | Enerji 70 |
| Dengeleyici | Dengeleyici | Dünya | 0,5 | Denge +3 |
| İniş bacağı | Yumuşak ayak tabanı | Ay 2 | 0,5 | Denge +1, yumuşak iniş |

## Hangardaki 4 çubuk (rakam yok, sadece çubuk + ikon)
| Çubuk | İkon | Hesap |
| --- | --- | --- |
| Ağırlık | Tüy ↔ örs (hafifken tüy, ağırken örs) | Takılı parçaların ağırlığı toplamı |
| İtki | Alev | Jetlerin itkisi |
| Enerji | Parlayan kapsül | Depo kapasitesi ÷ jet tüketimi = uçuş süresi |
| Denge | Topaç | 1 + parçaların denge katkısı |

Ek kural: İtki çubuğunun ucunda bir **çizgi** gösterilir: "bu gezegende kalkmak için gereken itki" (= ağırlık × yerçekimi). İtki çizgiyi geçmiyorsa gemi kalkamaz. Çocuk rakam okumadan "çubuk çizgiyi geçti mi?" diye bakar. Gezegen değişince çizgi kayar: Ay'da çizgi aşağı iner, bu da düşük yerçekimini gösterir.

## Kontrol: örnek gemiler (kalkış oranı = itki ÷ (ağırlık × yerçekimi), 1'in üstü kalkar)
| Gemi | Ağırlık | Dünya (1) | Ay (0,17) | Mars (0,38) | Ne olur |
| --- | --- | --- | --- | --- | --- |
| Başlangıç: hafif + küçük jet + küçük kapsül + dengeleyici | 4,5 | 1,33 | 7,8 | 3,5 | Dünya'da rahat kalkar, Ay'da fırlar |
| Sağlam + küçük jet + küçük kapsül + dengeleyici + taban | 8 | 0,75 ❌ | 4,4 | 2,0 | Dünya'da "ıhhh", kalkamaz; Ay ve Mars'ta kalkar |
| Hafif + büyük jet + küçük kapsül + dengeleyici | 5,5 | 2,2 | 12,8 | 5,7 | Çok güçlü, tavana yapışır, inişi zor |
| Sağlam + büyük jet + büyük kapsül + dengeleyici + taban | 11 | 1,09 | 6,4 | 2,9 | Dünya'da zar zor kalkar, uzun menzil |

Uçuş süresi örnekleri: küçük kapsül + küçük jet ≈ 30 sn; küçük kapsül + büyük jet ≈ 12 sn; büyük kapsül + büyük jet ≈ 28 sn.

Her parkurun en az iki çözümü olacak şekilde parkurlar bu tabloya göre tasarlanır (Gün 13'te denenir).

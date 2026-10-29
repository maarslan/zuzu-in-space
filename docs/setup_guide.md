# Kurulum Rehberi

## Kurulu olanlar

| Araç | Durum |
| --- | --- |
| Godot | v4.7.2 stable (standart sürüm) |
| GitHub Desktop | Kurulu |
| Depo | `C:\Users\arsla\Documents\GitHub\zuzu-in-space` (özel) |
| Test cihazı | Samsung Galaxy A15, Android 16, One UI 8.5 |

## Projeyi Godot'da ilk kez açmak

1. Godot'u aç. Proje yöneticisi penceresi gelir.
2. Üstteki **Import** (İçe Aktar) butonuna tıkla.
3. Açılan pencerede `C:\Users\arsla\Documents\GitHub\zuzu-in-space` klasörüne git ve `project.godot` dosyasını seç.
4. **Import** (veya **Import & Edit**) butonuna tıkla. Godot projeyi açar ve ilk açılışta dosyaları tarar (birkaç saniye).
5. Sağ üstteki **▶ (Run Project)** butonuna bas veya klavyede **F5**'e bas.
6. Lacivert arka planda sarı "Zuzu in Space" yazan bir pencere açılmalı. Pencereyi kapat.

İlk açılışta Godot proje klasöründe `.godot` adında bir klasör oluşturur. Bu Godot'un önbelleğidir, depoya gönderilmez (`.gitignore` bunu engeller).

## Her oturum sonunda GitHub'a kayıt

1. GitHub Desktop'u aç; sol üstte `zuzu-in-space` seçili olsun.
2. Sol panelde değişen dosyalar listelenir. Hepsinin yanındaki kutu işaretli olsun.
3. Sol alttaki **Summary** kutusuna o günün commit mesajını yaz (her oturum sonunda verilir).
4. **Commit to main** butonuna tıkla.
5. Üstteki **Push origin** butonuna tıkla (ilk seferde **Publish branch** yazabilir; ona tıkla).

## Sonraki adımlar

- Gün 6: Android dışa aktarımı ve telefona yükleme. Bu adımda Android araçlarının kurulumu ve telefonda geliştirici modunun açılması ayrıca anlatılacak.

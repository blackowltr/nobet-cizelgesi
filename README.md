# Nöbet Çizelgesi

Kurumunuz için personel nöbet rotasyonu yönetimi. Tek dosya, sıfır kurulum.

## Özellikler

- Personel ekleme, düzenleme, silme
- 3 grup halinde personel atama (grup başına sınırsız kişi, varsayılan 3 slot)
- Bir personel yalnızca tek bir gruba atanabilir
- Grup Amiri belirleme (en fazla 3, grup başına 1) ve sıralama
- 9 günlük sabit rotasyon döngüsü (Gündüz/Gece/İstirahat)
- Grup vardiyalarını serbestçe değiştirme (seçilen vardiya başka gruptaysa otomatik takas)
- Tarih filtresi: Son 7 gün veya özel tarih aralığı (en fazla 31 gün)
- Grup filtresi ile tek grubun çizelgesini görüntüleme/yazdırma
- Tam ekran önizleme
- A4 yatay PDF çıktısı (renkli/siyah-beyaz, sicil göster/gizle)
- Kişisel vardiya istatistikleri
- Yedek alma (JSON) ve yedekten geri yükleme
- Koyu tema
- Tüm veriler localStorage'da saklanır, kaybolmaz

## Kullanım

1. `index.html` dosyasını tarayıcıda aç (veya [canlı sürüm](https://blackowltr.github.io/nobet-cizelgesi/))
2. Personel Yönetimi sayfasından personelleri ekle
3. Nöbet Çizelgesi sayfasında gruplara personel ata
4. Her grubun bugünkü vardiyasını belirle
5. Çizelge otomatik oluşur — PDF çıktısı alabilirsin

Verilerini yedeklemek için Personel Yönetimi sayfasındaki **Yedek Al** butonunu kullan; başka bir cihaza taşımak veya geri yüklemek için **Yedekten Getir** ile JSON dosyasını seç.

Tek HTML dosyası, ekstra kütüphane gerekmez.

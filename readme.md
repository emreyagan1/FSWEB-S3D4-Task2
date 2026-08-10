# Görev 2: Gallery Responsive Challenge

## Proje Tanımı

Dünkü yarışmalar çok ilgi gördü. Bugün de bir yarışma düzenlendi.

Bu yarışmada çözülmesi gereken 2 challenge var:

1. Var olan bir web sayfasını sadece css kodları ile nasıl responsive yaparız? (header ve gallery-section),
2. normal tasarımda gallery-seciton'daki resimler 2 satır x 5 sütun iken, mobilde 2 satır x 2 sütun nasıl yaparız? (sadece ilk 4 resim görünür olacak, diğer 6 resim gizlenecek)

Hedeflenen [mobil tasarım görseli](https://materials.cdn.workintech.com.tr/projects/fullstack/gallery-responsive/tasarim_mobil.jpg) paylaşıldı.

- İpucu: `align-items: stretch` özelliğine bakabilirsin.
- İpucu: `:nth-child()` seçicisinin farklı kullanımlarını araştırabilirsin. Örn: `a:nth-child(2n+1)`, `a:nth-child(even)`
- `display: none`, `visibility: hidden` arasındaki farka bakabilirsin.

**Not:** Geniş ekranlarda veya yüksek çözünürlüklerde mobil tasarım görünmeyebilir. Mobil görünümü test etmek için tarayıcı penceresini daraltabilir ya da geliştirici araçlarını (F12) kullanabilirsin.

## Önemli Notlar

- Proje dizinindeki `user.json` dosyasını bulun ve `user_id` alanını NextGen proje ekranında görünen kendi `user_id` değeriniz ile güncelleyin.
- Geliştirme sırasında testleri izlemek için `npm test` komutunu kullanın.
- Testleri çalıştırıp skoru NextGen'e kaydetmek için `npm run sendresults` komutunu kullanın.

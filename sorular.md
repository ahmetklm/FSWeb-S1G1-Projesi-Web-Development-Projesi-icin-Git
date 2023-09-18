# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
   Git, yazılım geliştirme süreçlerinde kullanılan bir versiyon kontrol sistemidir.
2. Git ile GitHub arasında ne fark var?
   Git bir versiyon kontrol sistemidir. GitHub ise bu versiyon kontrol sistemi ile kullandığımız projeleri depolayabildiğimiz bir portaldır.
3. Neden bir branch oluşturuyoruz?
   Branch oluşturmak ana kodumuzun farklı versiyonlarına erişmemizi sağlar ve eğer bir hata yaparsak bu hata ana kodumuzu etkilemez.
4. Pull Request'in amacı nedir?
   Açık kaynaklı bir kod yaratmak ve buda katkıda bulunmak isteyen diğer insanlara inceleme imkanı sunmak.
5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
   git checkout main komutunu kullanabilirim.
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
   git fetch: uzaktaki bir deponun dosyalarını, anlık görüntülerini ve referanslarını yerel depomuza indiren bir komuttur.
   git merge: Farklı bir branch'deki değişiklikleri üzerinde çalıştığımız kendi brachimize entegre etme işlemi
   git pull: Proje ana dosyasında yaptığımız değişiklikleri bilgisayarımızdaki versiyona çekmemizi sağlar.
7. Merge conflict nedir?
   İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır.
8. Merge conflict'i nasıl çözeriz?
   Çakışma yaşadığımız kişi ile konuşup bu durumu çözebiliriz, ikimiz kodun farklı bölümlerini paylaşıp o alanlarda değişiklik yaparak çakışmanın önüne geçebiliriz.

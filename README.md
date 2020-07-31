# acikhack2-MERGEN
Bu çalışma, TEKNOFEST Türkçe Doğal Dil İşleme Projesi kapsamında sosyal medya platformlarında (Twitter vb.) anahtar kelime (Korona/Corona vb.) yardımıyla metin analizi Python dilinde yazılım çalışmasıdır.

KOD Girişi Öncesinde Bilgilendirme

Komut İstemi aracılığıyla Python kütüphanelerinin kurulumunu gerçekleştirmek üzere; Başlat / Arama / "cmd" adımları takip edilir.
"Python3 -m pip install textblob tweepy matplotlib" ile python 3 için textblob kütüphanesi kurulur.
Ardından apps.twitter sayfasına girilir ve twitter hesabına giriş yapılır.
Consumer key ve consumer secret anahtarları burada bulunmaktadır. Bu numaralar programın hangi adres üzerinden veri alıp işleyeceğini belirlemektedir. 
Daha sonra Python programı içerisine kod yazısındaki veriler yazılmaktadır. 

KOD Girişi Sonrasında Bilgilendirme

Kod girişinden sonra python dosyası çalıştırıldığında önce aranacak kelime istenmektedir.
Bir sonraki adımda kaç tweet taramasının yapılacağı sayı girilmektedir.
Kelime ve rakam girişi yapılınca program verileri Twitter üzerinden almakta ve dairesel bir görsel ile bize sunmaktadır. 
Tarama sonucunda  üç başlık halinde yüzde dilim pasta grafiği ile sağ üst köşesinde verilmektedir. 

NOT: Bu çalışmanın temel mantığında uluslararası veya ulusal çapta toplum üzerinde etkili olan kriz durumlarında talep edilen anahtar kelimenin ilişkili 
olduğu değişkenler çerçevesinde metin analizi gerçekleştirmesi ve sonuçlarının istenen oranlara göre listelenmesine olanak sağlamasıdır.

Bu çalışma temel nitelikte metin analiz sonuçlarını üç başlık halinde toplanmak üzerine hazırlanmıştır. Örnek kod yazım mantığıyla başlık sayısı talep edilen sayıda arttırılabilmektedir.
Kodlar küresel çapta toplum yönlendirmeleri üzerinde etkisi bulunan sosyal medya platformlarından "Twitter" paylaşımlarına göre yapılandırılmıştır.

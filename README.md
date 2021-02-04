# SQL Server Reporting Services
SSRS'de rapor tasarımı. Raporlarda Nortwith veri seti kullanılmıştır.


### 1) En Çok Satan Ürün 
Raporda parametre bulunmamaktadır. Şuana kadar en çok satılan 5 ürün ekranda grafikte okunmaktadır. Raporda parametre yoktur.


![en_cok_satilan_urun](https://user-images.githubusercontent.com/69402551/106933812-6bcfcd00-672a-11eb-835d-2c363f51d4cf.png)

Dataset1:


![en_cok_satan_dataset1](https://user-images.githubusercontent.com/69402551/106936965-42b13b80-672e-11eb-81ef-354a632d9e11.png)


### 2)Satış Ayrıntı Raporu
Sipariş numarası girilerek('siparisno' parametresi ile) siparişe ait bütün bilgiler ekranda görülür. iki adar Dataset bulunmaktadır. Bunlardan biri siparişe ait 
toplam satış miktarını getirirken, diğer dataset ise geriye kalan bilgileri rapora getirmektedir. Satış ayrıntı raporu resmi belge olarakte kullanılabilir.
10710 numaralı siparişin ayrıntıları resimde görülmektedir.


![satis_ayrinti_raporu](https://user-images.githubusercontent.com/69402551/106934244-f1ec1380-672a-11eb-8665-a29da2bd50d8.png)

Dataset1:


![satis_ayrinti_raporu_dateset1](https://user-images.githubusercontent.com/69402551/106934751-8ce4ed80-672b-11eb-8814-85486365919e.png)

Dataset2:


![satis_ayrinti_raporu_dateset2](https://user-images.githubusercontent.com/69402551/106934827-a7b76200-672b-11eb-9706-2ece020df13c.png)

### 3) Ürün Satış Tutarları
Üç adet parametre vardır. Parametrelere ay, yıl ve ürün kodu girilmektedir. Ay parametresi Specify Values olarak tanımlanmıştır ve 12 adet ay el ile girilmiştir. Yıl parametresi ise integer olup el ile girilmektedir. 
  'productid' parametresi ise dataset den beslenen parametredir ve liste şeklinde seçilmektedir. 'productid' listede ürün isimlerini gözükürken arka planda ürün kodunu döndürmektedir. Bu parametde dataset2'den beslenmektedir. Diğer parametre ise girilen tarihler arasındaki sipariş detaylarını rapora getirmektedir.


![urunlerin_satis_tutarlari](https://user-images.githubusercontent.com/69402551/106935548-89059b00-672c-11eb-8397-ec174cc3dd95.png)

Dataset1:


![urun_satis_tutarları_dataset1](https://user-images.githubusercontent.com/69402551/106936402-92dbce00-672d-11eb-874d-f2d48b8a28e1.png)

Dataset2:


![urunlerin_satis_tutarlari_dataset2](https://user-images.githubusercontent.com/69402551/106936436-9d966300-672d-11eb-9300-1c7cf188a09f.png)

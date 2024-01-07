# çizge renklendirme ile ders programı
 Mysql Database ile ders programı
 Dinamik takvimimizi HTML dilini kullanarak Visual Studio Code editöründe geliştirdik. Takvimimize özgü stil ayarlarını yaptık. 
![image](https://github.com/buseyener/-cizge-renklendirme-ile-ders-programi-/assets/119698903/c55ce450-e935-4ba1-a2d6-2db171c348a9)

Üst tarafta bulunan yön tuşlarıyla gün olarak ileri - geri gidebiliyorken, alt tarafta bulunan yön tuşlarıyla yıl olarak ileri – geri gidebiliyoruz. Saatli Hafta – Saatli Gün kısmından takvim görünüşlerini ayarlayabiliyoruz. Takvim üstünde gözüken etkinlikleri Visual Studio Code üzerinden ders programına paralel olarak ekledik.


![image](https://github.com/buseyener/-cizge-renklendirme-ile-ders-programi-/assets/119698903/dd6227ce-0925-4030-8e20-474ff9251c39)



Kod satırlarında sırasıyla derslerimizin adları, saatleri ve sınıf kodları yer alıyor. Ders programına özgü bilgileri MySQL Workbench üzerinden veritabanına işledik. Proje isimli yeni bir şema oluşturup bu şemaya 3 ana tablo ekledik. Hoca, ders, sinif isimli tablolarımıza ders programımıza göre bilgileri girdik.

![image](https://github.com/buseyener/-cizge-renklendirme-ile-ders-programi-/assets/119698903/fd255054-05e8-4460-b9ea-f08d2a2941aa)


Sonrasında oluşturduğumuz bu 3 tabloyu ER diyagramı ile bağladık.

Oluşturduğumuz dinamik takvimimizi Visual Studio Installer editöründe ASP.Net ile takvim.html uzantılı dosya oluşturup sunucuya bağladık. Böylece sunucu bağlantımızı gerçekleştirmiş olduk.

![image](https://github.com/buseyener/-cizge-renklendirme-ile-ders-programi-/assets/119698903/410569d8-8015-492a-8dfe-5ced40a5a9a1)



AppServer ile PhpMyAdmin kurulumunu gerçekleştirdik. Sonrasında MySQL de oluşturduğumuz proje şemasına phpMyAdmin sayfasından bağlandık.

PhpMyAdmin sayfasında tablolarımızı tek tek kontrol ettik. Veri düzenlemeleri yaptık.

![image](https://github.com/buseyener/-cizge-renklendirme-ile-ders-programi-/assets/119698903/4cb6ff8a-5e50-47a4-bed1-39d375783dba)



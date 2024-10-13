# DNN mobil cihaz kullanıcı davranışı tahmin etme
### Veri Seti Hakkında
### Bu veri seti, mobil cihaz kullanım kalıpları ve kullanıcı davranışı sınıflandırmasının kapsamlı bir analizini sunar. Uygulama kullanım süresi, ekran açık süresi, pil tüketimi ve veri tüketimi gibi ölçümler de dahil olmak üzere 700 kullanıcı verisi örneği içerir. Her giriş, hafif kullanımdan aşırı kullanıma kadar değişen beş kullanıcı davranışı sınıfından birine kategorize edilir ve bu da içgörülü analiz ve modellemeye olanak tanır.

### Temel Özellikler:

#### Kullanıcı Kimliği: Her kullanıcı için benzersiz tanımlayıcı.
#### Cihaz Modeli: Kullanıcının akıllı telefonunun modeli.
#### İşletim Sistemi: Cihazın işletim sistemi (iOS veya Android).
#### Uygulama Kullanım Süresi: Mobil uygulamalarda harcanan günlük süre, dakikalarla ölçülmektedir.
#### Ekran Açık Süresi: Ekranın günde ortalama kaç saat aktif olduğu.
#### Pil Tüketimi: Günlük pil tüketimi (mAh).
#### Yüklenen Uygulama Sayısı: Cihazda mevcut toplam uygulama sayısı.
#### Veri Kullanımı: Günlük mobil veri tüketimi (megabayt cinsinden).
#### Yaş: Kullanıcının yaşı.
#### Cinsiyet: Kullanıcının cinsiyeti (Erkek veya Kadın).
#### Kullanıcı Davranışı Sınıfı: Kullanım kalıplarına (1 ila 5) dayalı kullanıcı davranışının sınıflandırılması.
### veri manipülasyonu yapılmıştır.kategorik değişkenler için onehotencoder,sayısal değişkenler için scadartscaler kullanılmıştır.
### DNN modelinde Dropout ve EarlyStopping kullanılmıştır. 

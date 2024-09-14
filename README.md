# Aygaz-Machine-Learning-Bootcamp

# Aygaz Makine Öğrenmesi Bootcamp: Yeni Nesil Proje Kampı 
Bu proje, Kaggle'dan Online Payments Fraud Detection Dataset'ini kullanarak hem gözetimli öğrenme (supervised learning) hem de gözetimsiz öğrenme (unsupervised learning) algoritmalarını uygulamaktadır. Bu dosyada, her iki öğrenme türünün performans değerlendirmeleri ve neden belirli bir algoritmanın diğerine göre daha uygun olduğunu açıklayan bilgiler bulunmaktadır.

# Veri Seti

 Bu proje, Online Payments Fraud Detection Dataset adlı veri setini kullanmaktadır. Veri seti, çevrimiçi ödeme dolandırıcılığını tespit etmek amacıyla büyük bir veri kümesi sunar ve test ile uygulama amaçları için tasarlanmıştır ve 10 sütundan oluşmaktadır.

step: Zaman birimini temsil eder; 1 adım 1 saate eşittir.
type: Çevrimiçi işlemin türü (örneğin, alışveriş, para transferi).
amount: İşlemin tutarı.
nameOrig: İşlemi başlatan müşteri.
oldbalanceOrg: İşlem öncesi müşteri hesabındaki bakiye.
newbalanceOrig: İşlem sonrası müşteri hesabındaki yeni bakiye.
nameDest: İşlemin alıcısı.
oldbalanceDest: Alıcının işlem öncesi bakiyesi.
newbalanceDest: Alıcının işlem sonrası yeni bakiyesi.
isFraud: İşlemin dolandırıcılık olup olmadığını belirten etiket (1 = dolandırıcılık, 0 = dolandırıcılık değil).


# Proje Kapsamı

Bu projede iki farklı makine öğrenimi algoritması kullanılmıştır:

Lojistik Regresyon (Gözetimli Öğrenme)

K-Means Kümeleme (Gözetimsiz Öğrenme)

# 1. Lojistik Regresyon (Gözetimli Öğrenme)
Lojistik regresyon, sınıflandırma problemlerini çözmek için kullanılan bir gözetimli öğrenme algoritmasıdır. Modelin eğitimi, x_train ve y_train veri setleri kullanılarak gerçekleştirilmiştir. Test aşamasında, modelin doğruluğu ve karışıklık matrisi gibi performans metrikleri hesaplanmıştır.

Sonuçlar:

Doğruluk: [Doğruluk Skoru]

Karışıklık Matrisi: (Aşağıda görselleştirilmiştir)

Sınıflandırma Raporu: [Sınıflandırma raporu burada yer alacak]


# 2. K-Means Kümeleme (Gözetimsiz Öğrenme)
K-Means, verileri kümelere ayıran bir gözetimsiz öğrenme algoritmasıdır. Bu algoritma, x_train veri seti kullanılarak eğitilmiştir ve test verisi üzerinde kümeleri tahmin etmek için kullanılmıştır.

Sonuçlar:

Küme Merkezleri: [Küme merkezlerinin koordinatları]

Görselleştirme: (Aşağıda görselleştirilmiştir)

# Performans Karşılaştırması

Her iki algoritmanın performansı değerlendirildiğinde:

Lojistik Regresyon: [Yüksek doğruluk ve iyi performans gibi sonuçlar burada belirtilebilir]

K-Means Kümeleme: [Kümeleme sonuçlarının ne kadar etkili olduğu burada açıklanabilir]

# Algoritma Seçimi:

Lojistik Regresyon: Verilerin etiketli olduğu ve sınıflandırma probleminin ön planda olduğu durumlarda uygundur.

K-Means Kümeleme: Etiketli verinin mevcut olmadığı ve veri kümesinin doğal gruplara ayrılması gerektiği durumlarda daha uygundur.

# Kaggle Notebook Linki
Proje ile ilgili detaylı çalışmaya Kaggle Notebook bağlantısı üzerinden ulaşabilirsiniz.

# Aygaz-Machine-Learning-Bootcamp

# Aygaz Makine Öğrenmesi Bootcamp: Yeni Nesil Proje Kampı 
Bu proje, Kaggle'dan Online Payments Fraud Detection Dataset'ini kullanarak hem gözetimli öğrenme (supervised learning) hem de gözetimsiz öğrenme (unsupervised learning) algoritmalarını uygulamaktadır. Bu dosyada, her iki öğrenme türünün performans değerlendirmeleri ve neden belirli bir algoritmanın diğerine göre daha uygun olduğunu açıklayan bilgiler bulunmaktadır.

# Veri Seti

 Bu proje, Online Payments Fraud Detection Dataset adlı veri setini kullanmaktadır. Veri seti, çevrimiçi ödeme dolandırıcılığını tespit etmek amacıyla büyük bir veri kümesi sunar ve test ile uygulama amaçları için tasarlanmıştır ve aşağıdaki sütunlardan oluşmaktadır.

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

Lojistik Regresyon Doğruluk Skoru: 0.999170153175893
Karışıklık Matrisi:
 [[1270849      55]
 [   1001     619]]
Sınıflandırma Raporu:
               precision    recall  f1-score   support

           0       1.00      1.00      1.00   1270904
           1       0.92      0.38      0.54      1620

    accuracy                           1.00   1272524
   macro avg       0.96      0.69      0.77   1272524
weighted avg       1.00      1.00      1.00   1272524


# 2. K-Means Kümeleme (Gözetimsiz Öğrenme)
K-Means, verileri kümelere ayıran bir gözetimsiz öğrenme algoritmasıdır. Bu algoritma, x_train veri seti kullanılarak eğitilmiştir ve test verisi üzerinde kümeleri tahmin etmek için kullanılmıştır.

Sonuçlar:
Küme Merkezleri:
 [[18.78479102 -0.0374662  -0.24394651  3.83505486  7.60135743]
 [-0.0319747   3.80411004  3.80496697  0.15026511  0.06624262]
 [ 3.84485879  0.16567777  0.16960071 27.40540253 26.14982309]
 [-0.05853534 -0.19433222 -0.19420824 -0.15665436 -0.15293734]
 [ 0.58931655 -0.07467598 -0.07223552  2.57634258  2.48748354]]


Görselleştirme: (Aşağıda görselleştirilmiştir)

# Performans Karşılaştırması

Her iki algoritmanın performansı değerlendirildiğinde:

Lojistik Regresyon: [Yüksek doğruluk ve iyi performans gibi sonuçlar burada belirtilebilir]

K-Means Kümeleme: [Kümeleme sonuçlarının ne kadar etkili olduğu burada açıklanabilir]

# Algoritma Seçimi:

Lojistik Regresyon: Verilerin etiketli olduğu ve sınıflandırma probleminin ön planda olduğu durumlarda uygundur.

K-Means Kümeleme: Etiketli verinin mevcut olmadığı ve veri kümesinin doğal gruplara ayrılması gerektiği durumlarda daha uygundur.

# Kaggle Notebook Linki
Proje ile ilgili detaylı çalışmaya https://www.kaggle.com/code/aygulse/aygaz-machine-learning-bootcamp/edit  üzerinden ulaşabilirsiniz.

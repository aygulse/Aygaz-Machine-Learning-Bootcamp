# Aygaz-Machine-Learning-Bootcamp

# Aygaz Makine Öğrenmesi Bootcamp: Yeni Nesil Proje Kampı 
Bu proje, Kaggle'dan alınan Online Payments Fraud Detection Dataset'ini kullanarak hem gözetimli öğrenme (supervised learning) hem de gözetimsiz öğrenme (unsupervised learning) algoritmalarını uygulamaktadır. Bu dosyada, her iki öğrenme türünün performans değerlendirmeleri ve neden belirli bir algoritmanın diğerine göre daha uygun olduğunu açıklayan bilgiler bulunmaktadır.

# Veri Seti

 Bu proje, Online Payments Fraud Detection Dataset adlı veri setini kullanmaktadır. Veri seti, çevrimiçi ödeme dolandırıcılığını tespit etmek amacıyla büyük bir veri kümesi sunar , test ile uygulama amaçları için tasarlanmıştır ve aşağıdaki sütunlardan oluşmaktadır.

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

Lojistik Regresyon Doğruluk Skoru: 0.999170153175893

Karışıklık Matrisi: 

|          | Predicted 0 | Predicted 1 |
|----------|-------------|-------------|
| Actual 0 | 1,270,849   | 55          |
| Actual 1 | 1,001       | 619         |

 
Sınıflandırma Raporu:

| Class        | Precision | Recall | F1-Score | Support   |
|--------------|-----------|--------|----------|-----------|
| 0            | 1.00      | 1.00   | 1.00     | 1,270,904 |
| 1            | 0.92      | 0.38   | 0.54     | 1,620     |
| **Accuracy** |           |        | 1.00     | 1,272,524 |
| **Macro Avg**| 0.96      | 0.69   | 0.77     | 1,272,524 |
| **Weighted Avg** | 1.00  | 1.00   | 1.00     | 1,272,524 |


# 2. K-Means Kümeleme (Gözetimsiz Öğrenme)

K-Means, verileri kümelere ayıran bir gözetimsiz öğrenme algoritmasıdır. Bu algoritma, x_train veri seti kullanılarak eğitilmiştir ve test verisi üzerinde kümeleri tahmin etmek için kullanılmıştır.

Küme Merkezleri: 

| Cluster | Feature 1 | Feature 2 | Feature 3 | Feature 4 | Feature 5 |
|---------|-----------|-----------|-----------|-----------|-----------|
| 1       | 18.78     | -0.04     | -0.24     | 3.84      | 7.60      |
| 2       | -0.03     | 3.80      | 3.80      | 0.15      | 0.07      |
| 3       | 3.84      | 0.17      | 0.17      | 27.41     | 26.15     |
| 4       | -0.06     | -0.19     | -0.19     | -0.16     | -0.15     |
| 5       | 0.59      | -0.08     | -0.07     | 2.58      | 2.49      |




![image](https://github.com/user-attachments/assets/a949d65a-ee37-4e4c-8e88-ed93d9a871aa)




# Performans Karşılaştırması

Her iki algoritmanın performansı değerlendirildiğinde:

Lojistik Regresyon:  Logistic Regression modeli dolandırıcılık tespitinde daha başarılı olmuştur. Bunun nedeni, etiketli verilerle çalışılması ve dolandırıcılık gibi ikili sınıflandırma problemleri için Logistic Regression'ın daha uygun bir model olmasıdır.

K-Means Kümeleme: K-Means Clustering ise veriyi kümelere ayırmada etkili olmuştur ancak sınıflandırma görevinde doğrudan kullanılmamıştır.


# Kaggle Notebook Linki
Proje ile ilgili detaylı çalışmaya https://www.kaggle.com/code/aygulse/aygaz-makine-renmesi-bootcamp-proje-kamp  üzerinden ulaşabilirsiniz.

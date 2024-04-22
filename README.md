<h1 align="center"><b>Yapay Sinir Ağları ile Müşter Kaybı Tahmini</b> </h1> 

<h1 align="left"><b>Genel Bakış</b> </h1>

* <b>Bu depo, Churn_Modelling veri kümesini kullanarak müşteri kaybını tahmin etmek için yapay sinir ağı oluşturmayla ilgili kod içerir. <br>
* <b>Veri kümesi, müşteri yaşını, ülkeyi ve hesap bakiyesini içeren çeşitli özellikleri içermektedir.</b>

<br>
<br>
<br>
<b>Kodu çalıştırmak için aşağıdaki adımları izleyin:</b>
<br>

## 1) Depoyu Klonlayın: 

``
git clone https://github.com/kullanıcı-adınız/depoyunuz.git
cd depoyunuz
``
<br>
<br>

## 2) Gerekli Bağımlılıkları Yükleyin:

   ``
   pip install numpy matplotlib pandas scikit-learn keras
   ``
<br>
<br>

## 3) Kodu çalıştırın:
   
```
python kodunuz.py
kullanıcı-adınız ve deponuzu kendi GitHub kullanıcı adınız ve depo adınızla değiştirdiğinizden emin olun.
```
<br>

## !! Dosya Yapısı !!
- Churn_Modelling.csv: Eğitim ve test için kullanılan veri kümesi. <br>
- kodunuz.py: Yapay sinir ağı uygulamasını içeren Python betiği. <br>
- README.md: Projeye dair dokümantasyon. <br>
<br>

## !! Bağımlılıklar !!
- numpy <br>
- pandas <br>
- scikit-learn <br>
- keras <br>
<br>

## Yapay Sinir Ağı Mimarisi
* Yapay sinir ağı, 11 özellik içeren bir giriş katmanı, her biri 6 nöron içeren iki gizli katman ve ikili sınıflandırma için sigmoid aktivasyon fonksiyonuna sahip bir çıkış katmanından oluşmaktadır.
<br>

## Sonuçlar
* Modelin performansı, test seti üzerindeki karışıklık matrisi kullanılarak değerlendirilir.

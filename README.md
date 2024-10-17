# ANN_for_Image_Classification

## Fashion MNIST Model Training
Bu proje, Fashion MNIST veriseti ile bir yapay sinir ağı modeli eğitmek amacıyla TensorFlow kullanarak yazılmıştır.  (T-shirt, pantolon, ayakkabı, vb.) tahmin etmek için bir sinir ağı mimarisi kullanır.

Neural Network Architecture Pipeline (Sinir Ağı Mimarisi)
* Build the NN
* Compile (Derleme)
* Train (Eğitim)
* Evulation ( Performans Değerlendirmesi)

### Projeyi çalıştırabilmek için aşağıdaki kütüphanelere ihtiyaç vardır:
* TensorFlow 2.x
* NumPy
* Pandas
* Matplotlib


Gerekli kütüphaneleri yüklemek için şu komutu kullanabilirsiniz:

```pip install tensorflow numpy pandas matplotlib ```

## Veri Seti
Bu projede Fashion MNIST verisetini kullanıyoruz. Verisetinde 28x28 piksel boyutunda, 10 farklı sınıfa ait 60,000 eğitim örneği ve 10,000 test örneği bulunmaktadır. Bu örnekler aşağıdaki kategorilere aittir:

* 0: T-shirt/top
* 1: Trouser
* 2: Pullover
* 3: Dress
* 4: Coat
* 5: Sandal
* 6: Shirt
* 7: Sneaker
* 8: Bag
* 9: Ankle boot

## Eğitim 

Optimizer: Adam

Loss Function: Sparse Categorical Crossentropy

Metrics: Sparse Categorical Accuracy

Eğitim 10 epoch (dönem) boyunca gerçekleştirilmiştir. Eğitim sırasında modelin kaybı ve doğruluk oranı her epoch'ta raporlanmıştır.

## Eğitim Sonuçları
Eğitim sonunda model, test verisi ile değerlendirildi ve test kaybı (loss) ile doğruluk (accuracy) oranı raporlandı.

Test Sonuçları

Test Loss: 0.3381

Test Accuracy: 88.05%

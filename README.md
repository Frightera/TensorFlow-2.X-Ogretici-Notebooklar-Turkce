## TensorFlow 2.X Öğretici Notebooklar Serisi

### --- Özel olarak istediğiniz bir konu varsa `Issues` kısmından belirtebilirsiniz. ---
### Planan notebook: *TensorFlow ile Linear Algebra İşlemleri (yüklenecek).*
### Planan notebook: *@tf.function Detaylı Anlatım (yüklenecek).*
### Planan Anlatım: *C++ ile TensorFlow için Harici Operasyonlar Yazma*

### 0 - TensorFlow'a Giriş
1) **TensorFlow Nedir? TensorFlow ve GPU**
2) **Tensörlere Giriş**
    * Tensör nedir? 
    * Arraylerle arasındaki fark nedir?
3) **Tensörlerin Bilgilerine Erişmek**
    * `Shape`, `rank` ve `size` nedir?
4) **Tensör Operasyonları**
    * Matematiksel işlemler
    * Matris çarpımı
      * `tf.transpose()` ve `tf.reshape()` 
    * Tensör veri tipini değiştirmek
    * İstatistiksel işlemler
    * `assign` ve `add_assign` fonksiyonları
5) **Tensörleri Birleştirmek**
     * `tf.concat()` ve `tf.stack()`
6) **Diğer Tensör Operasyonları**
     * `tf.eye()`, `tf.reverse()`, `tf.roll()` ve `tf.unique_with_counts()`.
7) **Tensörler ve Numpy**
     * Tensörleri NumPy arraylerine dönüştürmek
8) **@tf.function ve AutoGraph**
      * TF1.X graf objesi ve TF2.X yenilikleri

### 1 - TensorFlow - Keras ile Lineer Regresyon ve Patlayan Gradyanlar
1) **Normal Lineer Regresyon**
2) **Gradyan Patlaması Sorunu**
   * Gradient Clipping ve Adaptive Optimizer
3) **AdaGrad, RMSProp ve Adam Optimizerları Nedir?**
   * Matematiksel gösterimleriyle arasındaki ilişki
4) **Modele Dense Layer Eklemek**

### 2 - Lineer Olmayan Regresyon, Aktivasyonlar ve Layer Subclassing
1) **Normal Lineer Regresyon**
2) **Aktivasyon Fonksiyonları**
   * Sigmoid, Tanh, Softmax, ReLU, Leaky ReLU ve Swish aktivasyonları
3) **Aktivasyonları kullanarak aynı modeli yazmak**
   * Aktivasyonların plot edilip performansının karşılaştırılması
4) **Custom Layer Yazmak - Layer Subclassing**

### 3 - TF-Keras ile CNN - Bir Input İki Model Yaklaşımı
1) **Fashion MNIST Verisini Yükleme**
2) **Basit CNN Modeli Yazmak**
   * 2 tane Conv2D Layerı ve 2 tane Dense Layer
3) **Flatten ve GlobalMaxPooling Arasındaki Fark**
   * Arka planda nasıl hesaplanıyorlar?
4) **Functional API ile Bir Inputu İki Farklı Şekilde Kullanmak**
   * Modeli plot ederek daha iyi görmek
5) **Confusion Matrix ve Classification Report Yazdırmak**

### 4 - DenseNet121 ve Çoklu Optimizer Yaklaşımı
1) **Kütüphaneler**
2) **Veriyi Yükleme ve Normalize Etme**
3) **Preprocessing Layerları**
4) **Transfer Learning Nedir?**
   * Önceden Eğitilmiş Modeli Doğrudan Kullanmak
   * Önceden Eğitilmiş Modelleri Özellik Çıkarıcı (Feature Extractor) Olarak Kullanmak
   * Önceden Eğitilmiş Modelin Son Katmanlarını -Fine Tune- Etmek
   * Başlangıç Noktası Olarak Önceden Eğitilmiş Bir Model Kullanmak
5) **Optimizerlar**
   * RAdam
   * Lookahead
   * LazyAdam
6) **Multi-Optimizer Wrapper - TensorFlow Addons**
7) **Modelin Test Setindeki Başarısı**

### X - tf.data, tf.image, tfa.image, MiniDenseNet, RAdam Part 1-2
1) **Veri Yükleme**
   * `tf.data.Dataset.list_files()` Kullanımı
2) **tf.data Pipeline**
   * tf.data pipeline'ı oluşturup, tf.image ve tfa.image kullanarak farklı dönüşümler uygulamak.
3) **Modeli Oluşturmak**
   * Mini DenseNet ve Layer Subclassing kullanmak
   * Modeli custom training loop kullanarak eğitmek
4) **Loss ve Accuracy**
   * Training loop kullanarak toplanan loss ve accuracy değerlerini plot edip görmek
5) Model Performansı
   * Modelin performansını görmek için confusion matrix ve classification report kullanmak

### X.1 - Notebook X + GradCAM
#### Notebook X'i tamamen kapsayıp ek olarak Grad-CAM anlatımı mevcuttur.
6) Grad-CAM
   * Neden GradCAM'e ihtiyaç duyarız?
   * GradCAM Nedir?
   * GradCAM'i test setinde denemek
   * ![image](https://user-images.githubusercontent.com/46622558/143658932-3d820882-7e40-436f-acfa-d70750accffe.png)


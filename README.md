## TensorFlow 2.X Öğretici Notebooklar Serisi

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

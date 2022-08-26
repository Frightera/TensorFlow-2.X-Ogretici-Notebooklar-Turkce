# TensorFlow 2.X Öğretici Notebooklar Serisi

## Genel Bakış
|  **#**  |                          **Konu**                          |                                                                                                                                   **Colab Linki**                                                                                                                                   |
|:-------:|:----------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| **0**   |                     TensorFlow'a Giriş                     | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Frightera/TensorFlow-2.X-Ogretici-Notebooklar-Turkce/blob/main/0%20-%20TensorFlow'a_Giri%C5%9F%20(G%C3%BCncellendi).ipynb)                                   |
| **1**   |    TF-Keras ile Lineer Regresyon ve Patlayan Gradyanlar    | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Frightera/TensorFlow-2.X-Ogretici-Notebooklar-Turkce/blob/main/1%20-%20Lineer%20Regresyon%20ve%20Patlayan%20Gradyanlar.ipynb )                               |
| **2**   |     Non-Lineer Regresyon, Aktivasyonlar ve Subclassing     | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Frightera/TensorFlow-2.X-Ogretici-Notebooklar-Turkce/blob/main/2%20-%20Lineer%20Olmayan%20Regresyon%2C%20Aktivasyonlar%20ve%20Layer%20Subclassing.ipynb )    |
| **2.1** |                   Regresyon Alıştırmaları                  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Frightera/TensorFlow-2.X-Ogretici-Notebooklar-Turkce/blob/main/2.1%20-%20Regresyon%20Alıştırmaları.ipynb)                                                    |
| **3**   |      TF-Keras ile CNN - Bir Input İki Model Yaklaşımı      | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Frightera/TensorFlow-2.X-Ogretici-Notebooklar-Turkce/blob/main/3%20-%20TF-Keras%20ile%20CNN%20-%20Bir%20Input%20İki%20Model%20Yaklaşımı.ipynb)               |
| **4**   |          DenseNet121 ve Çoklu Optimizer Yaklaşımı          | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Frightera/TensorFlow-2.X-Ogretici-Notebooklar-Turkce/blob/main/4%20-%20Transfer%20Learning%20DenseNet121-%20MultiOptimizer.ipynb)                            |
| **5**   |       Detaylı Transformer Anlatımı - CNN ile Ensemble      | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Frightera/TensorFlow-2.X-Ogretici-Notebooklar-Turkce/blob/main/5%20-%20Detaylı%20Transformer%20Anlatımı%20-%20CNN%20ile%20Ensemble.ipynb)                    |
| **6**   | tf.data, tf.image, tfa.image, MiniDenseNet, RAdam Part 1-2 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Frightera/TensorFlow-2.X-Ogretici-Notebooklar-Turkce/blob/main/6%20-%20tf.data%2C%20tf.image%2C%20tfa.image%2C%20MiniDenseNet%2C%20RAdam%20Part%201-2.ipynb) |
| **6.1** |                    Notebook 6 + GradCAM                    | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Frightera/TensorFlow-2.X-Ogretici-Notebooklar-Turkce/blob/main/6.1%20-%20Notebook%20X%20%2B%20GradCAM.ipynb)                                                 |
| **7**   |          Softmax Çıktıları ve -Adversarial Attack-         | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Frightera/TensorFlow-2.X-Ogretici-Notebooklar-Turkce/blob/main/7%20-%20Softmax%20Çıktıları%20ve%20-Adversarial%20Attack-%20.ipynb)                           |
| **8**   |            Sıfırdan Küçük ResNet ve Subclassing            | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Frightera/TensorFlow-2.X-Ogretici-Notebooklar-Turkce/blob/main/8%20-%20Sıfırdan%20Küçük%20ResNet%20ve%20Subclassing.ipynb)                                   |
| **9**   |                   Multi-Output All-In-One                  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Frightera/TensorFlow-2.X-Ogretici-Notebooklar-Turkce/blob/main/9%20-%20Multi-Output%20All-In-One.ipynb)                                                      |

## Detaylı Açıklamalar

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

### 5 - Detaylı Transformer Anlatımı - CNN ile Ensemble
#### Kütüphaneler
* **TensorFlow - Keras**
* **TFDS**: `wikipedia_toxicity_subtypes` verisetinin yüklenmesi.
* **TensorFlow Addons**
* **Plotly**
* **Sklearn**
* **Matplotlib - Seaborn**

#### Verisetinin İşlenmesi
Kullanılan fonksiyonlar:
* `tf.strings.regex_replace`
* `tf.strings.lower`
* `tf.one_hot`
* Cümleler için Max Uzunluk Seçilmesi
* `TextVectorization` Layerının Kullanılması

#### Attention, Multihead Attention Nedir?
* RNN Yapılarının Yüzeysel Üstünden Geçilmesi
  * Vektör - Dizi Modelleri (Vector-to-Sequence)
  * Dizi - Vektör Modelleri (Sequence-to-Vector)
  * Dizi - Dizi Modelleri (Sequence-to-Sequence)
* RNN'lerdeki Sorun ve Transformer ile Karşılaştırma
* Word Embedding
* Positional Encoding
  * Transformer Neden Buna İhtiyaç Duyuyor?
  * Cümle Uzunluğuna Göre Vektörler Tanımlamak
  * Normalize Vektörler Kullanmak
  * Attention Is All You Need --> Önerilen Çözüm
    * 3D Plotlar ile Çözümün Açıklanması
* Transformer Mimarisine Giriş
  * Kısaca Attention Nedir?
  * Self-Attention Nedir?
  * Transformerdaki MultiHeadAttention Nedir?
    * Key, Value, Query Kavramları
    * Adım Adım Matris İşlemleri
    * Attention Filter
    * Multihead ve Attention Head Açıklaması

#### Transformer Modelinin Yazılması
* Transformer Encoder Kısmının `tf.keras.layers.Layer` Olarak Yazılması
* Word + Positional Embeddinglerinin `tf.keras.layers.Layer` Olarak Yazılması

#### Ana Modelin Functional API ile Yazılması
* Transformer Mimarisinin Eklenmesi
* 1D CNN Yapılarının Eklenmesi
* Çıktıların Birleştirilmesi


### 6 - tf.data, tf.image, tfa.image, MiniDenseNet, RAdam Part 1-2
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

### 6.1 - Notebook X + GradCAM
#### Notebook 6'yı tamamen kapsayıp ek olarak Grad-CAM anlatımı mevcuttur.
6) Grad-CAM
   * Neden GradCAM'e ihtiyaç duyarız?
   * GradCAM Nedir?
   * GradCAM'i test setinde denemek
   * ![image](https://user-images.githubusercontent.com/46622558/143658932-3d820882-7e40-436f-acfa-d70750accffe.png)

### 7 - Softmax Çıktıları ve -Adversarial Attack- 
1) **fashion_mnist Verisetini Yükleyip Hazırlamak**
   * tf.one_hot()
   * tf.cast()
   * prefetch()
2) **Basit Bir CNN Yazmak**
   * Conv2D()
   * MaxPooling2D()
3) **Resimlere Basit Noise Ekleyip Tahmin Almak**
   * Noise ve Etkilenen Softmax Çıktıları
4) **InceptionResNetV2'de Aynı Noise Yaklaşımını Test Etmek**
   * 55M Parametresi Olan InceptionResNetV2
   * Noise ve InceptionResNetV2
5) **tf.GradientTape**
   * tape.watch()
   * optimizer.apply_gradients()
6) **InceptionResNetV2'ye Adversarial Attack**
   * Özel Bir Noise Vektörü Oluşturmak
   * Sonucu Görselleştirmek
   * ![kapakresmi](https://user-images.githubusercontent.com/46622558/150686075-ceee48f2-c15d-41d0-b7c5-a0506dd19f91.png)



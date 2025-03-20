# Kitap Türü Sınıflandırma Projesi

Bu proje, kitap açıklamaları kullanarak kitap türlerini tahmin eden bir metin sınıflandırma modelini geliştirmeyi amaçlamaktadır. Modelde, LSTM ve MLP gibi derin öğrenme algoritmalarını kullanarak, çeşitli vektörleştirme yöntemleriyle (BoW, TF-IDF, Word2Vec, BERT) metin verilerini işleyip sınıflandırmalar yapılmıştır.

## Proje Adımları

1. **Veri Ön İşleme**: Kitap açıklamaları metin verisinden anlamlı özellikler çıkartmak için veri temizleme ve vektörleştirme yöntemleri kullanılmıştır.
2. **Model Geliştirme**: LSTM ve MLP modelleri ile metin verileri üzerinde eğitim yapılmış ve sınıflandırma sonuçları değerlendirilmiştir.
3. **Model İyileştirme**: Dropout, L2 regularization, learning rate ayarları ve batch size değişiklikleri ile modelin doğruluğu artırılmaya çalışılmıştır.
4. **Sonuçlar ve Değerlendirme**: Her model ve vektörleştirme yöntemi için performans karşılaştırmaları yapılmıştır.

## Gereksinimler

Bu projeyi çalıştırmak için aşağıdaki kütüphaneleri yüklemeniz gerekmektedir:

### Python ve Kütüphaneler:

- Python 3.x
- TensorFlow
- Scikit-learn
- Numpy
- Pandas
- Matplotlib
- Seaborn
- NLTK (veya başka bir metin işleme kütüphanesi)

## Kurulum

Projeyi çalıştırmak için gerekli kütüphaneleri yüklemek için `requirements.txt` dosyasını kullanabilirsiniz.

### Adımlar:

1. Python ortamınızı oluşturun (örneğin, `venv` veya `conda`).
2. `requirements.txt` dosyasını kullanarak tüm bağımlılıkları yükleyin:

   ```bash
   pip install -r requirements.txt
   ```

# CNN ile Görüntü Sınıflandırma Projesi
Bu repo, Akbank Derin Öğrenme Bootcamp kapsamında gerçekleştirdiğim derin öğrenme projesini içermektedir. Projede, CNN (Convolutional Neural Network) mimarisi kullanılarak bir görüntü sınıflandırma modeli geliştirilmiştir.

# Giriş 
Bu projede seçilen veri seti kullanılarak görüntüler sınıflandırılmıştır.
Projenin temel adımları şunlardır:
Veri önişleme ve görselleştirme
Data Augmentation yöntemleri ile veri çoğaltma
CNN tabanlı modelin tasarlanması ve eğitilmesi
Modelin değerlendirilmesi (Accuracy, Loss, Confusion Matrix vb.)
Grad-CAM ile modelin karar bölgelerinin görselleştirilmesi
Hiperparametre optimizasyonu
Projenin tüm teknik anlatımı notebook dosyaları içerisinde markdown hücrelerinde detaylı olarak verilmiştir.

# Metrikler
Model eğitimi sonucunda elde edilen başarı metrikleri:

Eğitim ve doğrulama accuracy / loss grafikleri

Confusion Matrix ile sınıflandırma performansı

Classification Report (precision, recall, f1-score)

Grad-CAM görselleştirmeleri ile modelin odaklandığı bölgeler

Bu metrikler üzerinden modelin overfitting ve underfitting durumları yorumlanmıştır. Ayrıca, dropout ve regularization gibi yöntemlerle modelin genelleme kabiliyeti artırılmıştır.


# Sonuç ve Gelecek Çalışmalar
Bu proje, temel bir CNN mimarisi ile başarılı bir görüntü sınıflandırma modeli geliştirmeyi amaçlamıştır.
Gelecekte şu adımlar planlanmaktadır:

Daha büyük ve kompleks veri setleri ile modelin geliştirilmesi

Transfer Learning yöntemleri (VGG16, ResNet, EfficientNet vb.) ile performans artırılması

Daha gelişmiş hiperparametre optimizasyon yöntemlerinin uygulanması (Bayesian Optimization, Keras Tuner)

Gerçek zamanlı kullanım için mobil / web tabanlı deploy süreçlerinin eklenmesi


# Linkler
Kaggle linklerine aşağıdan ulaşabilirsiniz

Kaggle proje linki: https://www.kaggle.com/code/muhammet3425/cnn-model-e-itimi
Kaggle dataset linki: https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset


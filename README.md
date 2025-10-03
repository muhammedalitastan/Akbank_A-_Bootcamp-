# CNN ile Görüntü Sınıflandırma Projesi
Bu proje, manyetik rezonans görüntüleri (MRI) kullanarak beyindeki tümörleri tespit etmeye yönelik bir derin öğrenme modeli geliştirmeyi amaçlamaktadır. Projede Convolutional Neural Network (CNN) mimarisi kullanılmıştır ve modelin eğitiminde veri ön işleme, veri artırma (data augmentation) ve hiperparametre optimizasyonu teknikleri uygulanmıştır.

# Giriş 
Bu proje kapsamında, beyin tümörlerinin tespiti amacıyla MRI (Manyetik Rezonans Görüntüleme) verileri kullanılmıştır. Beyin tümörleri, erken teşhis edilmediğinde ciddi sağlık sorunlarına yol açabilen ve hayati risk taşıyan rahatsızlıklardır. Bu nedenle, tümörleri hızlı ve doğru bir şekilde tespit edebilen otomatik bir sistem geliştirmek büyük önem taşımaktadır.

Projede, görüntü sınıflandırma problemleri için oldukça etkili bir yöntem olan Convolutional Neural Network (CNN) mimarisi kullanılmıştır. CNN modeli, MRI görüntülerindeki tümörlü ve tümörsüz bölgeleri ayırt edebilmek için eğitilmiş ve doğrulama verileri üzerinden performansı değerlendirilmiştir. Ayrıca, veri ön işleme ve veri artırma (data augmentation) teknikleri uygulanarak modelin genelleme yeteneği artırılmış ve overfitting riski azaltılmıştır.
Projenin tüm teknik anlatımı notebook dosyaları içerisinde markdown hücrelerinde detaylı olarak verilmiştir.

# Metrikler
Model eğitimi sonucunda elde edilen performans değerlendirme metrikleri şunlardır:
Eğitim ve doğrulama doğruluk (accuracy) ile kayıp (loss) grafikleri, modelin öğrenme sürecini ve genel performansını görselleştirmek için kullanılmıştır.
Confusion Matrix, sınıflandırma doğruluğunu sınıf bazında analiz etmek için uygulanmıştır.
Classification Report (precision, recall, F1-score) ile modelin sınıflar üzerindeki detaylı performansı değerlendirilmiştir.
Grad-CAM görselleştirmeleri, modelin kararlarını verirken görüntülerde hangi bölgelere odaklandığını göstermek amacıyla kullanılmıştır.

Bu metrikler üzerinden modelin overfitting veya underfitting durumu analiz edilmiş ve gerektiğinde dropout ile regularization gibi yöntemlerle modelin genelleme yeteneği artırılmıştır.


# Sonuç ve Gelecek Çalışmalar
Bu proje, temel bir CNN mimarisi ile başarılı bir görüntü sınıflandırma modeli geliştirmeyi amaçlamıştır.
Gelecekte şu adımlar planlanmaktadır:

Daha büyük ve kompleks veri setleri ile modelin geliştirilmesi
Transfer Learning yöntemleri (VGG16, ResNet, EfficientNet vb.) ile performans artırılması
Daha gelişmiş hiperparametre optimizasyon yöntemlerinin uygulanması (Bayesian Optimization, Keras Tuner)
Gerçek zamanlı kullanım için mobil / web tabanlı deploy süreçlerinin eklenmesi

<img width="510" height="337" alt="image" src="https://github.com/user-attachments/assets/cbfc4a2f-84cc-4cc3-964d-33e20e7a3ea6" />
<img width="645" height="659" alt="Ekran görüntüsü 2025-10-03 232823" src="https://github.com/user-attachments/assets/2e573202-7de2-46ec-9c6e-ed94259dfe09" />
<img width="721" height="323" alt="image" src="https://github.com/user-attachments/assets/779697e7-217e-41e4-b752-a82818b3eef8" />
<img width="833" height="479" alt="Ekran görüntüsü 2025-10-03 233720" src="https://github.com/user-attachments/assets/43fe9be0-dfea-4104-a2d8-2210175320f8" />
<img width="433" height="586" alt="Ekran görüntüsü 2025-10-03 234254" src="https://github.com/user-attachments/assets/777dc73f-4954-4317-8f1a-d74afc6ec2b6" />




# Linkler
Kaggle linklerine aşağıdan ulaşabilirsiniz

Kaggle proje linki: https://www.kaggle.com/code/muhammet3425/cnn-model-e-itimi
Kagggle notebook linki: https://www.kaggle.com/code/muhammet3425/cnn-model-e-itimi

Kaggle dataset linki: https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset


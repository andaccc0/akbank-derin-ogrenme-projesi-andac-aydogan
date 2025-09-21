# Akbank Derin Öğrenme Bootcamp Projesi

Bu proje, Akbank'ın **"Yeni Nesil Proje Kampı"** kapsamında, **Convolutional Neural Network (CNN)** mimarisi kullanılarak geliştirilmiş bir görüntü sınıflandırma (image classification) projesidir. Proje, derin öğrenme alanında pratik deneyim kazanmayı ve karmaşık görüntü verilerini işleyebilen bir model oluşturmayı amaçlamaktadır.

### Projenin Amacı
Projenin temel amacı, **Intel Image Classification** veri setindeki 6 farklı doğal ve yapay ortamı (Binalar, Orman, Buzul, Dağ, Deniz, Sokak) yüksek doğrulukla sınıflandırabilen bir derin öğrenme modeli oluşturmaktır. Bu amaçla, sıfırdan bir CNN mimarisi oluşturulmuş ve ardından bu modelin performansı, **Transfer Öğrenme** yöntemiyle geliştirilmiştir.

### Kullanılan Yöntemler
Proje kapsamında modelin performansını ve genelleme yeteneğini artırmak için çeşitli derin öğrenme teknikleri uygulanmıştır:

* **Veri Ön İşleme ve Çoğaltma (`Data Augmentation`):** Modelin aşırı öğrenme durumunu engellemek için görüntü verileri üzerinde rotasyon, yakınlaştırma ve yatay çevirme gibi dönüşümler uygulanmıştır.
* **Temel CNN Mimarisi:** Evrişim (`Conv2D`), havuzlama (`MaxPooling2D`), dropout ve yoğun (`Dense`) katmanlarından oluşan özel bir CNN modeli tasarlanmıştır.
* **Transfer Öğrenme (`Transfer Learning`):** Önceden eğitilmiş güçlü bir model olan **VGG16**'nın evrişim tabanları kullanılarak, daha yüksek bir doğruluk oranına ulaşılmıştır.
* **Optimizasyon Teknikleri:** Model eğitimi sırasında **Adam, RMSprop** ve **SGD** optimizasyon algoritmaları karşılaştırılarak en iyi performans gösteren belirlenmiştir.
* **Model Değerlendirme:** Modelin başarısı, eğitim/doğrulama grafikleri, karmaşıklık matrisi (`confusion matrix`) ve sınıflandırma raporu (`classification report`) gibi standart metriklerle kapsamlı bir şekilde analiz edilmiştir.

### Elde Edilen Sonuçlar ve Değerlendirme
Proje sonunda, uygulanan yöntemlerin etkisi net bir şekilde görülmüştür.

* **Temel CNN Model Doğruluğu:** %77.93
* **Transfer Öğrenme Model Doğruluğu:** %85.77
* **En İyi Optimizasyon Algoritması:** Adam

Elde edilen sonuçlar, Transfer Öğrenme yönteminin bu tür görüntü sınıflandırma görevleri için çok daha güçlü bir çözüm sunduğunu göstermektedir. Proje, belirlenen hedeflere ulaşmış ve geliştirilen modellerin başarıyla çalıştığını kanıtlamıştır.

### Proje Dosyaları
Projenin tüm kodları ve ayrıntılı teknik açıklamaları [Proje_Kaggle_Notebook.ipynb](link-buraya) dosyasında bulunmaktadır.

Kaggle Not Defteri: https://www.kaggle.com/code/andaaydoan/gemini-deneme-son

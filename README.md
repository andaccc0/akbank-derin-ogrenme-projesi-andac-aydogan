Akbank Derin Öğrenme Bootcamp Projesi
Bu proje, Akbank'ın "Yeni Nesil Proje Kampı" kapsamında, Convolutional Neural Network (CNN) mimarisi kullanılarak geliştirilmiş bir görüntü sınıflandırma (image classification) projesidir. Proje, katılımcılara derin öğrenme alanında pratik deneyim kazandırmayı amaçlamaktadır.

Projenin Amacı

Projenin temel amacı, Intel Image Classification veri setindeki 6 farklı doğal ve yapay ortamı (Binalar, Orman, Buzul, Dağ, Deniz, Sokak) doğru bir şekilde sınıflandırabilen bir derin öğrenme modeli oluşturmaktır.

Veri Seti

Projeye özel olarak Kaggle'dan seçilen Intel Image Classification veri seti kullanılmıştır. Veri seti, yaklaşık 25.000 eğitim ve 14.000 test görüntüsü içermektedir.

Kullanılan Yöntemler

Veri Ön İşleme ve Çoğaltma (Data Augmentation): Modelin aşırı öğrenme (overfitting) durumunu engellemek ve daha iyi genelleme yapmasını sağlamak için ImageDataGenerator ile görüntüler üzerinde rotasyon, yakınlaştırma ve yatay çevirme gibi dönüşümler uygulanmıştır.

Model Mimarisi: Model, evrişim (Conv2D), havuzlama (MaxPooling2D), dropout ve yoğun (Dense) katmanlarından oluşan CNN mimarisi ile oluşturulmuştur.

Model Değerlendirme: Modelin performansı, eğitim ve doğrulama doğruluğu/kayıp grafikleri, karmaşıklık matrisi (confusion matrix) ve sınıflandırma raporu (classification report) gibi metriklerle kapsamlı bir şekilde analiz edilmiştir.

Elde Edilen Sonuçlar

Eğitilen model, test verisi üzerinde %77.93 gibi yüksek bir doğruluk oranına ulaşmıştır. Sınıflandırma raporu, modelin 'forest' (orman) sınıfında %97'lik bir recall değeriyle en başarılı tahmini yaptığını göstermektedir. Diğer sınıflarda da başarılı sonuçlar elde edilmiştir.

Proje Dosyaları

Projenin tüm kodları ve ayrıntılı teknik açıklamaları aşağıda paylaşılan Kaggle not defterinde bulunmaktadır.

Kaggle Not Defteri: https://www.kaggle.com/code/andaaydoan/notebookceab5725c1

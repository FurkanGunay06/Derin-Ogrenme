Akbank Derin Öğrenme Projesi
Proje Amacı
Bu proje, Kaggle üzerinde yer alan Large Scale Fish Dataset ile bir sınıflandırma modeli geliştirmeyi amaçlamaktadır. Yapay Sinir Ağı (ANN) kullanılarak balık türlerini sınıflandırmak ve model performansını değerlendirmek hedeflenmiştir.

Proje Adımları

1.Veri Önişleme
-.png formatındaki görseller işlenip Pandas DataFrame'e dönüştürüldü.
-Görseller üzerinde görselleştirmeler yapıldı ve veri eğitim/test olarak bölündü.

2.Modelin Eğitilmesi
-ANN mimarisi kullanıldı.
-Katmanlar, aktivasyon fonksiyonları ve dropout ile model yapılandırıldı.
-Eğitim süreci sırasında doğruluk ve kayıp fonksiyonları izlendi.

3.Model Değerlendirme
-Doğruluk (accuracy) ve kayıp grafikleri oluşturuldu.
-Confusion Matrix ve Classification Report ile sonuçlar analiz edildi.

4.Hiperparametre Optimizasyonu
-Katman sayısı, öğrenme oranı, dropout ve optimizer değişkenleri optimize edildi.
-Modelin overfitting yapmaması için erken durdurma uygulandı.


KAGGLE NOTEBOOK:https://www.kaggle.com/code/furkangunay/akbank-derin-ogrenme

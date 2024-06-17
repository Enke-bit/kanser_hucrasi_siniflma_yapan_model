# Destek Vektör Makineleri ile Meme Kanseri Hücrelerinin Sınıflandırılması ve Veri Görselleştirme

Bu proje, meme kanseri hücrelerini sınıflandırmak için Destek Vektör Makineleri (SVM) kullanır ve veri setini çeşitli grafiklerle görselleştirir. Çalışma, Python programlama dili ve scikit-learn, pandas, matplotlib ve seaborn gibi popüler veri bilimi kütüphaneleri kullanılarak gerçekleştirilmiştir.

## İçindekiler
- [Kurulum](#kurulum)
- [Veri Seti Hakkında](#veri-seti-hakkında)
- [Kod Açıklaması](#kod-açıklaması)
- [Sonuçlar](#sonuçlar)
- [Katkıda Bulunma](#katkıda-bulunma)

## Kurulum

Gerekli kütüphaneleri kurmak için aşağıdaki komutları kullanabilirsiniz:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn

## Veri Seti Hakkında
Meme kanseri veri seti, Wisconsin Meme Kanseri Veri Seti olarak bilinir ve iki farklı kanser türünü sınıflandırmak için kullanılır: malign (kötü huylu) ve benign (iyi huylu). Veri setinde 30 özellik ve 569 örnek bulunur.

## Kod Açıklaması
Proje dört ana bölümden oluşmaktadır:

Veri Yükleme ve Ön İşleme: Meme kanseri veri seti yüklenir ve eğitim/test olarak bölünür.
Veri Görselleştirme: Verinin bazı özellikleri ve sınıflandırma hedefi görselleştirilir.
Model Eğitimi: SVM kullanılarak model eğitilir.
Model Değerlendirme: Modelin doğruluğu ve performansı değerlendirilir.

## Sonuçlar
Bu çalışma, SVM modelinin meme kanseri hücrelerinin sınıflandırılmasında yüksek doğruluk sağladığını göstermektedir. Modelin doğruluğu, karmaşıklık matrisi ve sınıflandırma raporu ile detaylandırılmıştır.

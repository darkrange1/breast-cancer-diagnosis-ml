# 🎗️ Meme Kanseri Teşhisi (Breast Cancer Prediction)

Bu proje, **Wisconsin Breast Cancer (Diagnostic)** veri setini kullanarak, hücre özelliklerine dayalı olarak meme kanseri tümörlerini **İyi Huylu (Benign)** veya **Kötü Huylu (Malignant)** olarak sınıflandırmayı amaçlayan bir Makine Öğrenmesi uygulamasıdır.

## 📂 Veri Seti
Projede kullanılan veri seti [Kaggle]([https://www.kaggle.com/uciml/breast-cancer-wisconsin-data](https://www.kaggle.com/datasets/erdemtaha/cancer-data)) platformundan temin edilmiştir.
- **Örnek Sayısı:** 569
- **Özellik Sayısı:** 33 (Yarıçap, Doku, Çevre, Alan vb.)
- **Hedef:** M (Malignant - Kötü) / B (Benign - İyi)

## 🛠️ Kullanılan Teknolojiler ve Kütüphaneler
Proje **Python** dili ile geliştirilmiştir.
- **Veri Analizi:** Pandas, NumPy
- **Görselleştirme:** Matplotlib, Seaborn
- **Makine Öğrenmesi:** Scikit-learn (Logistic Regression, Random Forest)

## 📊 Proje Adımları
1. **Veri Keşfi (EDA):** Eksik veri kontrolü, aykırı değer analizi (Boxplot) ve korelasyon haritası incelenmesi.
2. **Ön İşleme:** Gereksiz sütunların temizlenmesi, Label Encoding ve StandardScaler ile ölçeklendirme.
3. **Modelleme:** Verisetinin %80 Eğitim - %20 Test olarak ayrılması ve modellerin eğitilmesi.
4. **Değerlendirme:** Accuracy, Confusion Matrix ve ROC-AUC skorları ile modellerin kıyaslanması.

## 🏆 Sonuçlar
İki farklı algoritma kullanılmış ve aşağıdaki başarı oranları elde edilmiştir:

| Model | Accuracy (Doğruluk) | ROC-AUC Skoru |
| :--- | :--- | :--- |
| **Logistic Regression** | %96.49 | 0.9960 |
| **Random Forest** | **%97.37** | **0.9929** |

*Sonuç olarak, Random Forest modeli en yüksek doğruluğu sağlamıştır.*

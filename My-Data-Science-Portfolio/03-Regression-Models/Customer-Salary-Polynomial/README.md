# 💰 Customer Satisfaction & Salary Prediction (Polynomial Regression)

Bu proje, veriler arasındaki ilişkinin doğrusal olmadığı durumlarda **Polinom Regresyon (Polynomial Regression)** yönteminin nasıl kullanıldığını gösteren bir çalışmadır.

## 🔍 Problem Tanımı
Veri setinde, müşteri seviyesi/memnuniyeti ile maaş/prim arasında doğrusal olmayan (non-linear) bir artış gözlemlenmiştir. Basit lineer regresyon bu veriyi modellemede yetersiz kaldığı için polinom dereceleri denenmiştir.

## ⚙️ Metodoloji
1.  **Linear Regression vs Polynomial Regression:** İlk olarak doğrusal model denenmiş, ancak veriye "underfit" (yetersiz uyum) olduğu görülmüştür.
2.  **Degree Selection (Derece Seçimi):** `PolynomialFeatures` kullanılarak 1'den 10'a kadar farklı dereceler (`degree`) test edilmiştir.
3.  **Hata Analizi:** Her derece için RMSE değerleri karşılaştırılarak en uygun model (overfitting olmadan) seçilmiştir.

## 📈 Sonuçlar
* Düşük dereceli modellerde yüksek hata (Bias) gözlemlendi.
* Yüksek dereceli modellerde aşırı öğrenme (Overfitting) riski analiz edildi.
* Optimum derece ile gerçeğe en yakın tahmin eğrisi çizildi.

## 🛠️ Teknolojiler
* **Python, Scikit-learn** (PolynomialFeatures, Pipeline)
* **Matplotlib** (Polinom eğrilerinin görselleştirilmesi)

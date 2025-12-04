# 🔥 Forest Fire Prediction (Ridge, Lasso, ElasticNet)

Bu proje, meteorolojik verilere dayanarak orman yangını riskini veya etkilenen alanı tahmin etmek için **Düzenlileştirilmiş Regresyon (Regularized Regression)** tekniklerinin karşılaştırıldığı bir çalışmadır.

## 🧪 Uygulanan Yöntemler
Standart Lineer Regresyon modelinin aşırı öğrenme (Overfitting) riskine karşı üç farklı teknik uygulanmış ve karşılaştırılmıştır:
1.  **Ridge Regression (L2):** Katsayıları sıfıra yaklaştırarak varyansı azaltma.
2.  **Lasso Regression (L1):** Önemsiz özellikleri sıfırlayarak özellik seçimi (Feature Selection) yapma.
3.  **ElasticNet:** Ridge ve Lasso'nun dengeli kombinasyonu.

## ⚙️ Model Tuning
* **ElasticNetCV** kullanılarak en uygun `alpha` değeri (ceza katsayısı) otomatik olarak belirlenmiştir.
* Modellerin başarısı **RMSE** ve **R² Score** ile kıyaslanmıştır.

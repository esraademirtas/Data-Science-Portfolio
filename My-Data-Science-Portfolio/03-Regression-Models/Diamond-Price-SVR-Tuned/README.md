# 💎 Diamond Price Prediction (SVR + GridSearchCV)

Bu proje, pırlantaların fiziksel özelliklerini (karat, derinlik, tablo vb.) kullanarak fiyat tahminlemesi yapan gelişmiş bir **Support Vector Regression (SVR)** modelidir.

## 🧪 Metodoloji
SVR algoritması aykırı değerlere ve veri ölçeğine duyarlı olduğu için aşağıdaki adımlar izlenmiştir:
1.  **Scaling:** Tüm veriler `StandardScaler` ile ölçeklenmiştir.
2.  **Hyperparameter Tuning:** `GridSearchCV` kullanılarak en uygun `C` (Ceza parametresi), `gamma` ve `kernel` (rbf, poly, linear) değerleri tespit edilmiştir.

## 📊 Sonuçlar
Optimize edilen modelin başarısı **R² Score** ve **Mean Absolute Error (MAE)** ile test edilmiştir.

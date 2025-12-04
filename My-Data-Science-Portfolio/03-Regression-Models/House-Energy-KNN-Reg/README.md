# 🏥 & 🏠 KNN Dual Analysis: Health Risk & Energy Prediction

Bu proje, **K-Nearest Neighbors (KNN)** algoritmasının hem Sınıflandırma hem de Regresyon problemlerinde nasıl uygulandığını gösteren iki aşamalı bir çalışmadır.

## 📂 Proje İçeriği

### 1. Health Risk Classification (Sınıflandırma)
* **Amaç:** Hastaların sağlık verilerine dayanarak risk seviyelerini sınıflandırmak.
* **Yöntem:** `KNeighborsClassifier`
* **Önemli Adım:** Mesafe temelli bir algoritma olduğu için veriler **StandardScaler** ile ölçeklenerek modelin performansı artırılmıştır.

### 2. House Energy Regression (Tahminleme)
* **Amaç:** Evlerin özelliklerine göre enerji tüketim değerlerini tahmin etmek.
* **Yöntem:** `KNeighborsRegressor`
* **Model Tuning:** Farklı 'K' (komşu sayısı) değerleri denenerek hata oranı (MSE/RMSE) en düşük model hedeflenmiştir.

## 🛠️ Teknik Detaylar
* **Feature Scaling:** KNN'in hassas olduğu ölçekleme problemi çözüldü.
* **Model Evaluation:** Sınıflandırma için Accuracy/F1-Score, Regresyon için R² Score ve MAE metrikleri kullanıldı.

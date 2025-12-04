# 💵 Income Level Prediction (Random Forest Tuned)

Bu proje, bireylerin demografik özelliklerine (yaş, eğitim, meslek vb.) dayanarak yıllık gelirlerinin 50.000$ üzerinde olup olmadığını tahmin eden optimize edilmiş bir **Random Forest** modelidir.

## 🚀 Proje Detayları
* **Algoritma:** Random Forest Classifier
* **Optimization:** Modelin başarımını artırmak için `RandomizedSearchCV` kullanılarak en iyi hiperparametreler (Hyperparameter Tuning) tespit edilmiştir.
* **Veri:** 14 farklı özellik içeren nüfus sayımı verileri.

## 📊 Sonuçlar
* Optimize edilen model ile **Accuracy: %86+** seviyesine ulaşılmıştır.
* **Confusion Matrix** ile modelin "False Positive" ve "False Negative" oranları analiz edilmiştir.

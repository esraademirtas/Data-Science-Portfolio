# 💳 Credit Card Fraud Detection (Advanced Analysis)

Bu proje, dengesiz veri setlerinde (Imbalanced Datasets) model başarısını doğru ölçmek için ileri seviye metriklerin kullanıldığı bir **Dolandırıcılık Tespiti (Fraud Detection)** çalışmasıdır.

## ⚠️ Zorluk: Dengesiz Veri (Imbalanced Data)
Dolandırıcılık işlemleri, normal işlemlere göre çok az sayıdadır. Bu durumda modelin sadece "Doğruluk" (Accuracy) oranına bakmak yanıltıcı olur. Bu projede **Hassasiyet (Precision)** ve **Duyarlılık (Recall)** dengesi gözetilmiştir.

## 🔬 Gelişmiş Teknikler
* **ROC & AUC Curve:** Modelin ayırt etme gücünün görselleştirilmesi.
* **Precision-Recall Curve:** Dengesiz veriler için en kritik başarım eğrisi.
* **Threshold Tuning:** Sınıflandırma eşik değerinin (default 0.5) optimize edilerek Recall değerinin artırılması amaçlanmıştır.

## 📊 Sonuç
Model, yasal işlemleri yanlışlıkla engellemeden (False Positive), potansiyel dolandırıcılıkları (True Positive) yakalamak üzere optimize edilmiştir.

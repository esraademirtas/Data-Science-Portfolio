# 🛡️ Cyber Attack Detection (Multi-Class Classification)

Bu proje, ağ trafiği verilerini kullanarak farklı siber saldırı türlerini tespit etmeyi amaçlayan bir **Çok Sınıflı Sınıflandırma (Multi-Class Classification)** çalışmasıdır.

## 🔍 Problem Tanımı
Geleneksel ikili sınıflandırmanın aksine, bu projede hedef değişken 2'den fazla sınıf içermektedir (Örn: Normal Trafik, DDoS, Phishing vb.). Bu nedenle model, her bir sınıfı diğerlerinden ayırt edecek şekilde eğitilmiştir.

## ⚙️ Teknik Yaklaşım
* **Veri Seti:** Kaynak ve hedef paket oranları (`src_packet_rate`, `dst_packet_rate`) gibi ağ trafiği özelliklerini içerir.
* **Yöntem:** Logistic Regression (Multi-class modu).
* **Metrikler:** Her bir saldırı tipi için ayrı ayrı Precision, Recall ve F1-Score değerleri incelenmiştir.

## 📈 Performans
Confusion Matrix üzerinde modelin hangi saldırı türlerini kartırdığı (False Positives/Negatives) analiz edilmiştir.

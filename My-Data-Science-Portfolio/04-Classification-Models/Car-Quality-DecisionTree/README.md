# 🚗 Car Quality Classification (Decision Tree Analysis)

Bu proje, araçların teknik ve maliyet özelliklerini analiz ederek "Satın Alınabilirlik/Kalite" durumunu sınıflandıran bir **Karar Ağacı (Decision Tree Classifier)** modelidir.

## 🎯 Amaç
Araçların fiyatı, bakım maliyeti, kapı sayısı, kişi kapasitesi, bagaj hacmi ve güvenlik seviyesi gibi özelliklerine dayanarak; aracın kabul edilebilir olup olmadığını (Unacceptable, Acceptable, Good, Very Good) tahmin etmektir.

## ⚙️ Veri Ön İşleme (Feature Engineering)
* **Ordinal Encoding:** Veri setindeki kategorik değişkenler (örn: 'Low', 'Med', 'High'), modelin anlayabileceği hiyerarşik sayısal değerlere dönüştürülmüştür.
* **Data Splitting:** Veri seti Eğitim (%60) ve Test (%40) olarak ayrılmıştır.

## 🌳 Model ve Görselleştirme
* **Algoritma:** Scikit-Learn `DecisionTreeClassifier` (Gini Impurity kriteri ile).
* **Tree Visualization:** Modelin karar verme mekanizması `plot_tree` kullanılarak görselleştirilmiş, hangi özelliğin (Feature) kararda en etkili olduğu (Root Node) analiz edilmiştir.

## 📊 Sonuçlar
* **Accuracy Score:** Modelin test verisi üzerindeki doğruluk oranı hesaplanmıştır.
* **Confusion Matrix:** Sınıf bazlı hata oranları incelenmiştir.

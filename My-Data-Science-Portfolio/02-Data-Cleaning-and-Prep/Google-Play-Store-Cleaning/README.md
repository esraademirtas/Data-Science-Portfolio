# 📱 Google Play Store Data Cleaning Project

Gerçek dünya verileri nadiren temizdir. Bu proje, **Google Play Store** veri setindeki "kirli" (kullanıma hazır olmayan) verileri analiz edilebilir bir formata dönüştürmek için geliştirdiğim kapsamlı bir veri temizleme çalışmasıdır.

## 🧹 Yapılan İşlemler (Data Cleaning Steps)
Proje kapsamında aşağıdaki veri ön işleme adımları uygulanmıştır:

1.  **String Manipülasyonu:** * `Size` sütunundaki 'M' (Megabyte) ve 'k' (Kilobyte) ifadeleri temizlenip sayısal değere çevrildi.
    * `Installs` ve `Price` sütunlarındaki '+' ve '$' gibi özel karakterler (`special characters`) kaldırıldı.
2.  **Veri Tipi Dönüşümü (Type Casting):** * Object (String) tipindeki sayısal veriler `float/int` formatına dönüştürüldü.
3.  **Eksik Veri Yönetimi (Missing Values):** * `Rating` ve diğer sütunlardaki NaN değerler analiz edilerek uygun stratejilerle yönetildi.
4.  **Tarih İşleme:** * `Last Updated` sütunu datetime objesine çevrildi, gün/ay/yıl olarak ayrıştırıldı.

## 🛠️ Kullanılan Kütüphaneler
* **Pandas:** Veri manipülasyonu ve temizliği.
* **NumPy:** Sayısal işlemler.
* **Seaborn & Matplotlib:** Temizlenen verinin dağılımını kontrol etmek için görselleştirme.

## 📈 Sonuç
Bu çalışma sonucunda, ham veri seti üzerinde istatistiksel analiz ve makine öğrenmesi modelleri uygulanabilir hale getirilmiştir.

---
*Veri Bilimi yolculuğumda "Data Wrangling" yetkinliğimi geliştirmek için hazırlanmıştır.*

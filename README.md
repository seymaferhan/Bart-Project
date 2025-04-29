# Bart-Project

# Veri seti Kaggle'dan alınmıştır:  
[BART Ridership Dataset (2016-2017) - Kaggle](https://www.kaggle.com/datasets/mrgeislinger/bart-ridership)


# San Francisco BART Data Analysis Project

Bu projede San Francisco’daki BART (Bay Area Rapid Transit) sisteminin yolcu taşıma verileri analiz edilmiştir. Amaç, hem veri analitiği hem de veri bilimi yaklaşımlarıyla yolcu davranışlarını anlamak, tahminler geliştirmek ve şehir planlamasına katkı sağlayacak içgörüler sunmaktır.

---

## 📊 Veri Analitiği Soruları

Aşağıdaki sorulara veri analizi yöntemleriyle cevaplar aranmıştır:

- **En yoğun BART istasyonu hangisidir?**
- **En az tercih edilen BART hattı nedir?**
- **Berkeley'den San Francisco’ya koltuk bulma ihtimalinin en yüksek olduğu saat aralığı nedir?**
- **Haftanın en yoğun günü hangisidir?**
- **Gece geç saatlerde kaç kişi BART kullanıyor?**

---

## 🧠 Veri Bilimi Soruları

Aşağıdaki sorular daha ileri düzey veri bilimi perspektifiyle ele alınmıştır:

- **Soru A**: Her istasyon çifti arasındaki düz çizgi (kuş uçuşu) mesafe nasıl hesaplanır?
- **Soru B**: Herhangi iki istasyon arasında işe giden yolcu sayısını tahmin eden bir model nasıl oluşturulur?

Ayrıca aşağıdaki detaylar düşünülmüştür:

- Bu problem nasıl ele alınır?
- Hangi ek verilere ihtiyaç duyulur?
- Bu modelden şehir veya BART yöneticileri nasıl faydalanabilir?

---

## 🧹 Veri Hazırlama Süreci

- **2016 ve 2017 yıllarına ait BART yolculuk verileri birleştirilmiştir.**
- **İstasyon bilgilerini içeren ayrı veri dosyası, yolculuk verisiyle birleştirilmiştir.**
- **Eksik veri analizi, veri temizliği ve ön işleme adımları uygulanmıştır.**

---

## 📁 Kullanılan Teknolojiler

- Python (Jupyter Notebook)
- Pandas, NumPy
- Matplotlib / Seaborn (görselleştirme)
- Haversine (coğrafi mesafe hesaplama)

---

## 🎯 Projenin Amacı

Bu proje, şehir planlamacılarının, ulaşım uzmanlarının ve veri bilimcilerinin BART sistemini daha iyi anlaması ve geliştirmesi amacıyla hazırlanmıştır. Ulaşım akışlarını modellemek, yoğun saatleri belirlemek ve veri destekli karar mekanizmaları geliştirmek için önemli bir örnektir.

---

## 📌 Kaynaklar

- BART Resmi Yolcu Verileri (2016 & 2017)
- İstasyon Koordinat Verileri

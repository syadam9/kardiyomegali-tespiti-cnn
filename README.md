# 🫀 Kardiyomegali Tespiti - CNN ile Derin Öğrenme Projesi

## 📋 Proje Amacı
Kardiyomegali (kalp büyümesi) rahatsızlığının erken teşhisi için derin öğrenme tabanlı bir tanı sistemi geliştirmek. Geçirdiğim kalp rahatsızlığı sonrasında kardiyoloji ve yapay zeka kesişimine olan ilgim, bu proje konusunu seçmemde motive edici oldu.

## 📊 Veri Seti Hakkında Bilgi
**Kaynak:** [NIH Chest X-ray Dataset](https://www.kaggle.com/datasets/rahimanshu/cardiomegaly-disease-prediction-using-cnn)

- **Görsel Sayısı:** 4,438 adet (2,219 eğitim / 2,219 test)
- **Sınıflar:** Sağlıklı vs Kardiyomegali
- **Çözünürlük:** 128×128 piksel, gri tonlamalı
- **İşlem:** CLAHE ile ön işleme uygulanmış

**Veri Seti Özelliği:** Kardiyomegali tespiti için CTR (Cardiothoracic Ratio) hesaplama metodolojisi kullanılarak hazırlanmıştır.

## 🛠️ Kullanılan Yöntemler
- **Veri Ön İşleme:** Normalizasyon, boyut standartizasyonu
- **Data Augmentation:** Döndürme, çevirme, yakınlaştırma teknikleri
- **CNN Mimarileri:** 
  - Basit CNN modeli
  - Geliştirilmiş CNN (BatchNorm, Dropout, L2)
  - Transfer Learning (VGG16)
- **Hiperparametre Optimizasyonu:** 8 farklı parametre testi
- **Görselleştirme:** Grad-CAM ile model interpretability
- **Değerlendirme:** Accuracy, Loss, Confusion Matrix analizleri

## 📈 Elde Edilen Sonuçlar
- **En Yüksek Doğruluk:** Transfer Learning (VGG16) - **%66.90 accuracy**
- **Hiperparametre Optimize Model:** %60.83 accuracy
- **Grad-CAM Başarısı:** Modelin karar mekanizması başarıyla görselleştirildi
- **Overfitting Kontrolü:** Model dengeli çalıştığı doğrulandı

## 🔗 Kaggle Notebook
https://www.kaggle.com/code/seymensezgin/seymen-sezgin-kardiyomegali

## 👨‍💻 Proje Hakkında
Akbank Derin Öğrenme Bootcamp kapsamında geliştirilmiştir. Kalp sağlığı ve yapay zeka kesişiminde anlamlı bir proje olması hedeflenmiştir.
- https://www.kaggle.com/code/seymensezgin/seymen-sezgin-kardiyomegali



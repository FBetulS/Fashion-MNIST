# 👗 Fashion MNIST Sınıflandırma Projesi

Bu proje, giyim ürünlerini sınıflandırmak için derin öğrenme tekniklerini kullanmaktadır. Model, Fashion MNIST veri seti kullanılarak geliştirilmiştir.

⚠️ Not
3D grafiklerim ve görselleştirmelerim maalesef gözükmüyor. Bu durum, bazı tarayıcı veya platform uyumsuzluklarından kaynaklanabilir.

## 🔗 Kaggle Veri Seti
[Fashion MNIST](https://www.kaggle.com/competitions/fashion-mnist)

## 📌 Sonuç
- **Test Doğruluğu**: %90.00
- **F1-Score (Macro Avg)**: 0.90
- **En Başarılı Sınıf**: Çanta (%99 precision/recall)
- **En Zayıf Sınıf**: Gömlek (%71 F1-score)

## 🎯 Model Özellikleri
- 3 Katmanlı CNN
- MaxPooling ve Dropout
- Adam optimizer (lr=0.001)

## 🔍 Analiz
### ✅ Güçlü Yönler:
- %90 doğruluk ile başarılı sınıflandırma.
- Çanta ve Bilekte Bot sınıflarında yüksek performans.
- Dengeli eğitim ve doğrulama eğrileri.

### ⚠️ Zayıf Yönler:
- Gömlek sınıfında düşük performans.
- Spor Ayakkabı ve Ceket arasında karışıklıklar.

## 🚀 İyileştirme ve Gelecek Çalışmalar
- Batch Normalization ve Learning Rate Scheduler eklenmesi.
- ResNet gibi pre-trained modellerin kullanımı.
- Grad-CAM ile model açıklanabilirliği.
- CutMix, MixUp veri artırma teknikleri.

Bu çalışma, CNN tabanlı modellerin giyim sınıflandırmasındaki potansiyelini gösterirken, iyileştirilmesi gereken alanları da ortaya koymuştur.

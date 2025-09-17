# Akbank-Derin-renme-Bootcamp-al-mas-
# Proje Başlığı: Intel Image Classification - CNN Denemesi

## Projenin Amacı
Bu proje ile Kaggle üzerinde bulunan "Intel Image Classification" veri seti kullanılarak CNN tabanlı görüntü sınıflandırma modeli geliştirilmiştir. Amaç: sahne tiplerini (Buildings, Forest, Glacier, Mountain, Sea, Street) doğru sınıflandırabilen bir model kurmak ve modelin karar verdiği görsel bölgeyi Grad-CAM ile yorumlamaktır.

## Veri Seti
- Kaynak: Kaggle - Intel Image Classification
- Sınıf sayısı: 6
- Toplam görüntü: yakl. 25.000 (train) / 14.000 (test)

## Yöntemler
- Veri önişleme: yeniden boyutlandırma, normalizasyon, train/val/test ayrımı
- Data augmentation: rotation, horizontal flip, zoom, color jitter
- Model: Basit CNN (Conv -> Pool -> Dropout -> Dense). Ayrıca transfer learning (ResNet50) denendi.
- Eğitim: Cross-entropy loss, Adam optimizer, erken durdurma (EarlyStopping), ModelCheckpoint

## Elde Edilen Sonuçlar
- En iyi doğruluk (validation): %XX (buraya sen koyacaksın)
- Confusion Matrix ve sınıf başına precision/recall raporu eklendi.
- Grad-CAM görselleştirmeleri ile modelin karar verdiği bölgelere bakıldı.

## Kullanım
Kaggle notebook linki: <KAGGLE NOTEBOOK LINKİNİ BURAYA EKLE>


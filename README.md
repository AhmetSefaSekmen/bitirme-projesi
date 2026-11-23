# bitirme-projesi
Yapay Zekâ ve Görüntü İşleme Tabanlı Bel Fıtığı Tespit ve Segmentasyon Sistemi
# Yapay Zekâ ve Görüntü İşleme Tabanlı Bel Fıtığı Tespit ve Segmentasyon Sistemi

## Proje Hakkında

Bu proje, lomber disk herniasyonlarının (bel fıtığı) Manyetik Rezonans (MR) görüntüleri üzerinden yapay zekâ ve görüntü işleme teknikleri kullanılarak tespit edilmesini amaçlamaktadır.

Proje kapsamında derin öğrenme algoritmaları kullanılarak omurga yapılarının, intervertebral disklerin ve fıtık bölgelerinin belirlenmesi hedeflenmektedir.

Görüntü segmentasyonu ve nesne tespiti yöntemleriyle sağlıklı ve patolojik disk yapılarının değerlendirilmesi amaçlanmaktadır.

## Projenin Amaçları

- MR görüntülerinin dijital görüntü işleme yöntemleriyle analiz edilmesi.
- Omurga ve disk bölgelerinin belirlenmesi.
- Bel fıtığına ait bölgelerin yapay zekâ algoritmalarıyla tespit edilmesi.
- Disk ve fıtık bölgelerinin piksel düzeyinde segmentasyonunun gerçekleştirilmesi.
- Derin öğrenme modellerinin performanslarının karşılaştırılması.

## Kullanılan Teknolojiler

- Python
- PyTorch
- OpenCV
- NumPy
- Pandas
- Mask R-CNN
- YOLO
- U-Net
- Google Colab
- Labelme

## Sistem Mimarisi

Sistemin temel çalışma aşamaları:

1. MR görüntülerinin alınması
2. Görüntü ön işleme
3. Veri etiketleme
4. Segmentasyon maskelerinin oluşturulması
5. Eğitim ve test veri setlerinin hazırlanması
6. Derin öğrenme modellerinin eğitilmesi
7. Fıtık bölgelerinin tespit ve segmentasyonu
8. Performans değerlendirmesi

## Performans Değerlendirme

- Accuracy
- Precision
- Recall
- F1-Score
- Dice Coefficient
- IoU

## Proje Çıktısı

MR görüntülerinde bel fıtığına ilişkin bölgelerin otomatik olarak tespit edilmesi ve segmentasyon maskeleriyle görsel olarak işaretlenmesi hedeflenmektedir.

Bu çalışma akademik bir bitirme projesi kapsamında geliştirilen araştırma ve prototip sistemidir. Tek başına klinik tanı amacıyla kullanılmamaktadır.

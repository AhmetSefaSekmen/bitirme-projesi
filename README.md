# bitirme-projesi
Yapay Zekâ ve Görüntü İşleme Tabanlı Bel Fıtığı Tespit ve Segmentasyon Sistemi
Yapay Zekâ ve Görüntü İşleme Tabanlı Bel Fıtığı Tespit ve Segmentasyon Sistemi

Proje Hakkında

Bu proje, lomber disk herniasyonlarının (bel fıtığı) Manyetik Rezonans (MR) görüntüleri üzerinden yapay zekâ ve görüntü işleme teknikleri kullanılarak tespit edilmesini amaçlamaktadır.

Proje kapsamında, bel bölgesine ait MR görüntüleri derin öğrenme algoritmalarıyla analiz edilerek omurga yapılarının, intervertebral disklerin ve fıtık bölgelerinin belirlenmesi hedeflenmektedir.

Görüntü segmentasyonu ve nesne tespiti yöntemleri kullanılarak sağlıklı ve patolojik disk yapılarının değerlendirilmesi amaçlanmaktadır.

Geliştirilecek sistemin, tıbbi görüntülerin bilgisayar destekli analizini kolaylaştıran bir karar destek prototipi olması hedeflenmektedir.

Projenin Amaçları

MR görüntülerinin dijital görüntü işleme yöntemleriyle analiz edilmesi.

Omurga ve intervertebral disk bölgelerinin belirlenmesi.

Bel fıtığı bulunan alanların yapay zekâ algoritmalarıyla tespit edilmesi.

Disk ve fıtık bölgelerinin piksel düzeyinde segmentasyonunun gerçekleştirilmesi.

Sağlıklı ve patolojik disk yapılarının karşılaştırılması.

Derin öğrenme modellerinin performanslarının karşılaştırılması.

Güvenilir ve ölçülebilir bir görüntü analizi sistemi geliştirilmesi.

Kullanılan Teknolojiler

Python

PyTorch

OpenCV

NumPy

Pandas

Mask R-CNN

YOLO

U-Net

Google Colab

Labelme

Sistem Mimarisi

MR görüntülerinin veri setinden alınması

Görüntü ön işleme ve normalizasyon

Görüntülerin etiketlenmesi

Segmentasyon maskelerinin oluşturulması

Eğitim ve test veri setlerinin hazırlanması (hasta bazlı)

Derin öğrenme modellerinin eğitilmesi

Fıtık bölgelerinin tespit ve segmentasyonu

Model performansının değerlendirilmesi

Kullanılacak Derin Öğrenme Modelleri

Mask R-CNN: Disk ve fıtık bölgelerinin nesne tespiti ve piksel düzeyinde segmentasyonu için.

YOLO: MR görüntülerinde ilgili anatomik yapıların ve fıtık bölgelerinin tespit edilmesi için.

U-Net: Görüntüler üzerinde piksel düzeyinde segmentasyon gerçekleştirmek için.

Performans Değerlendirme

Modellerin başarısı aşağıdaki metriklerle değerlendirilecektir:

Accuracy (Doğruluk)

Precision (Kesinlik)

Recall (Duyarlılık)

F1-Score

IoU (Intersection over Union)

Dice Coefficient

Proje Çıktısı

Proje sonucunda MR görüntülerinde bel fıtığına ilişkin bölgelerin otomatik olarak tespit edilmesi ve segmentasyon maskeleriyle görsel olarak işaretlenmesi hedeflenmektedir.

Geliştirilecek sistemin, uzmanların değerlendirme süreçlerine yardımcı olabilecek yapay zekâ tabanlı bir karar destek prototipi olması amaçlanmaktadır.

Akademik Not

Bu çalışma akademik bir bitirme projesi kapsamında geliştirilen araştırma ve prototip sistemidir. Tek başına klinik tanı koymak amacıyla kullanılmamaktadır.

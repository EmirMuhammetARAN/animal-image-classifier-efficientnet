# Animal Image Classifier (EfficientNet)

Bu proje, EfficientNetB0 transfer learning ile hayvan görsellerini sınıflandırır. Model ağırlıkları ve sınıf isimleri kaydedilir, test fonksiyonu ile görselden tahmin yapılabilir.

## Dosyalar
- Untitled-1.ipynb: Model eğitimi, kaydı ve test fonksiyonları
- animal_classifier_model.h5: Eğitilmiş model ağırlıkları
- class_names.json: Sınıf isimleri
- raw-img/: Görsel veri klasörü (her sınıf için alt klasör)
- ornek.jpg: Test görseli (isteğe bağlı)

## Kullanım
1. Notebook’u açıp çalıştırın.
2. Model eğitimi ve kaydı yapılır.
3. predict_file fonksiyonu ile görselden sınıf tahmini alınabilir.

## Gereksinimler
- tensorflow
- scikit-learn
- numpy

## Lisans
MIT
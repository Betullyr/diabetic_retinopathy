# diabetic_retinopathy
DataSet : https://www.kaggle.com/datasets/mariaherrerot/aptos2019

TR:
## Veri Seti ve Veri Ön İşleme

- Diabetik Göz veri seti, farklı boyutlardaki görsellerden oluşur. Bu nedenle, veri seti üzerinde bazı ön işleme adımları uygulanmıştır.
- Görseller boyutlandırılmış, ölçeklendirilmiştir.
- Veri setindeki gürültüyü azaltmak için görüntülerde augmentasyon teknikleri kullanılmıştır.

## Transfer Learning

- Önceden eğitilmiş bir derin öğrenme modeli  EfficientNet ile  transfer learning kullanılmıştır.
- Transfer learning işlemi, göz veri seti üzerindeki özellikleri öğrenmek için önceden eğitilmiş modelin ağırlıklarının ayarlanmasını içerir.
ingilizcesini de verirmiisn

EN:
## Dataset and Data Preprocessing

This project utilizes a dataset consisting of images of varying sizes for eye recognition. Consequently, several preprocessing steps have been applied to the dataset:

- **Resizing:** The images have been resized to ensure uniformity for feeding into the model.
- **Scaling:** The pixel values of the images have been scaled to a specific range.
- **Augmentation:** To reduce noise in the dataset, augmentation techniques have been applied to the images.

## Transfer Learning

- Transfer learning has been employed in this project using a pre-trained deep learning model, EfficientNet.
- The transfer learning process involves fine-tuning the weights of the pre-trained model to learn features specific to the eye dataset.

# Coursework Practice – Cats vs Dogs Classification (Transfer Learning)

This is a **coursework practice project** for binary image classification (cats vs dogs).  
It demonstrates the use of **transfer learning** with a pretrained CNN (e.g., VGG16/ResNet50 from Keras).

## What I practiced
- Using **ImageDataGenerator** for preprocessing & augmentation
- Applying **transfer learning**: loading a pretrained CNN, freezing layers, and adding a custom classifier
- Training and evaluating with **binary crossentropy** + accuracy
- Visualizing **training/validation accuracy and loss curves**
- Making predictions on new images

## Dataset
- Cats vs Dogs dataset (Keras-provided or downloaded from Kaggle)
- Split into **train/validation/test**

## Notes
- This project trains only the top classifier layers; the base CNN is pretrained on ImageNet.
- Purpose: **coursework practice and understanding of transfer learning workflows**

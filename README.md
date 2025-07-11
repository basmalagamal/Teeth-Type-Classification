# 🦷 Teeth Image Classification using CNN

This project uses deep learning (TensorFlow) to classify teeth conditions into 7 classes using RGB images.

## 🗂️ Dataset
Teeth images labeled into 7 categories: CaS, CoS, Gum, MC, OC, OLP, OT.

## 🧪 Preprocessing
- Resized to 224×224
- Gaussian Blur
- Sharpening
- Normalizatoin
- Augmentation: Flip, Rotate, Zoom

## 🧠 Model Architecture
4 Conv blocks with batch norm, dropout, and global average pooling. Trained with `sparse_categorical_crossentropy`.

## ▶️ Run the Notebook
Run the notebook on [Kaggle]() or locally with Python ≥3.8 and TensorFlow ≥2.11





   

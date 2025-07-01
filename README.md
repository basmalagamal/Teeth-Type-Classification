# 🦷 Teeth Image Classification using CNN

This project uses deep learning (TensorFlow) to classify teeth conditions into 7 classes using RGB images.

## 🗂️ Dataset
Teeth images labeled into 7 categories: CaS, CoS, Gum, MC, OC, OLP, OT.

## 🧪 Preprocessing
- Resized to 128×128
- Gaussian Blur
- Sharpening
- CLAHE (optional)
- Augmentation: Flip, Rotate, Zoom

## 🧠 Model Architecture
4 Conv blocks with batch norm, dropout, and global average pooling. Trained with `sparse_categorical_crossentropy`.

## 📊 Sample Result

![Sample Predictions](images/sample_predictions.png)

## ▶️ Run the Notebook
Run the notebook on [Kaggle]() or locally with Python ≥3.8 and TensorFlow ≥2.11

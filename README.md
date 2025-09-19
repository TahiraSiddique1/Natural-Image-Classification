# 🌍 Natural Scene Image Classification with CNN  

This project builds and trains a **Convolutional Neural Network (CNN)** to classify natural scene images into **6 categories**:  

- 🏙️ Buildings  
- 🌲 Forest  
- 🧊 Glacier  
- ⛰️ Mountain  
- 🌊 Sea  
- 🛣️ Street  

Using **Keras + TensorFlow**, the model learns to identify features in images and achieves strong classification performance.  

---

## ✨ Features  

✅ **Data Augmentation** with `ImageDataGenerator`  
✅ **CNN Architecture** with Conv2D, MaxPooling, BatchNormalization & Dropout layers  
✅ **6-Class Classification** using `softmax`  
✅ **Overfitting Prevention** with Dropout & Batch Normalization  
✅ **Training & Validation** on separate datasets  
✅ **Predictions** with label mapping to human-readable classes  

---

## 🛠️ Tech Stack  

- **Python** 🐍  
- **TensorFlow / Keras**  
- **NumPy**  
- **Pandas**  
- **Matplotlib** (optional for visualization)  

---

## 📂 Dataset  

- **Training set**: `seg_train/seg_train` (14,034 images, 6 classes)  
- **Validation set**: `seg_test/seg_test` (3,000 images, 6 classes)  
- **Prediction set**: `seg_pred/seg_pred` (unseen images for testing)  

---

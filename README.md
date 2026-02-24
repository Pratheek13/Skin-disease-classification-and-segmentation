# Skin-disease-classification-and-segmentation

# AI for Tele-Dermatology  
### Applied Computer Vision – Case Study  

## 📌 Project Overview

This project was developed as part of the **Applied Computer Vision** course (B.Tech III Year).  
The objective of this case study is to design and critically evaluate deep learning models for:

- Skin disease classification
- Lesion segmentation
- Robustness analysis under brightness and skin-tone variations

Tele-dermatology enables remote diagnosis of skin diseases using images captured through mobile devices. However, real-world conditions introduce challenges such as:

- Illumination variation  
- Skin-tone diversity  
- Noise and device artifacts  

This project focuses on addressing these challenges using deep learning techniques.

---

## 📂 Dataset Used

**HAM10000 – Human Against Machine with 10000 Training Images**

Dataset Link:  
https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000

The dataset contains dermatoscopic images of multiple skin disease categories including:

- Melanoma  
- Melanocytic nevi  
- Basal cell carcinoma  
- Actinic keratoses  
- Benign keratosis-like lesions  
- Dermatofibroma  
- Vascular lesions  

It is a multi-class classification dataset widely used for medical image research.

---

## 🧠 Week 1 – Skin Disease Classification

### 🔹 Model Implementation
- CNN-based architecture (ResNet / VGG / MobileNet depending on experiment)
- Baseline training without augmentation
- Evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - Confusion Matrix

### 🔹 Analysis Performed
- Misclassification analysis
- Class imbalance study
- Impact of brightness variation
- Performance variation across skin tones

---

## 🧬 Week 2 – Lesion Segmentation

### 🔹 Model Implementation
- U-Net architecture for pixel-level lesion segmentation
- Dice Loss & Binary Cross-Entropy
- Evaluation using:
  - Dice Score
  - IoU (Intersection over Union)
  - Precision & Recall

### 🔹 Error Analysis
- Over-segmentation
- Boundary leakage
- Missed lesion regions
- Brightness augmentation impact

---

## 📊 Integrated Analysis

This project critically answers:

> How do brightness variation and skin-tone diversity affect both classification accuracy and segmentation quality in tele-dermatology images?  
> Which task is more sensitive and why?

Experimental results were used to compare robustness between classification and segmentation models.

---

## 🛠️ Technologies Used

- Python  
- PyTorch / TensorFlow  
- Google Colab  
- NumPy  
- Matplotlib  
- scikit-learn  

---

## 🎯 Learning Outcomes

- Medical image classification & segmentation
- Robustness analysis in healthcare AI
- Bias and fairness considerations in medical imaging
- Error interpretation in deep learning systems

---

## 👨‍💻 Author

Pratheek Chowdary  
B.Tech CSE  
Applied Computer Vision Case Study

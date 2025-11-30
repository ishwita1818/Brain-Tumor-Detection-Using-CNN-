# 🧠 Brain Tumor Detection with Explainable AI  
### Deep Learning • CNN • Grad-CAM • LIME • SHAP • Medical Imaging  

This project is a complete Deep Learning system for detecting brain tumors from MRI scans using both custom-built and pre-trained neural network architectures.  
The system not only predicts whether a tumor is present — it also **explains** its decision using powerful Explainable AI techniques.

---

## 🚀 Features

- **Custom CNN architecture** designed from scratch for MRI images  
- **Model comparison** with ResNet50 & EfficientNet-B0  
- **Explainable AI (XAI)** integrated throughout:
  - 🔥 **Grad-CAM** (heatmaps showing model focus)
  - 🍃 **LIME** (region-based explanations)
  - 🌈 **SHAP** (pixel-level contributions)
- **MRI upload interface** for real-time prediction + heatmap generation  
- **Full evaluation metrics** (Accuracy, Precision, Recall, F1-score, Confusion Matrix)  
- **Clean, modular notebook structure** for training, evaluation, and visualization  

---

## 🧠 Custom CNN Architecture

The proposed CNN consists of:

- 4 Convolution Blocks (32 → 64 → 128 → 256 filters)  
- MaxPooling layers for downsampling  
- Dense layers (128, 64)  
- Dropout for regularization  
- Sigmoid output for binary classification  

This architecture was optimized specifically for MRI patterns and achieved strong performance with high interpretability.

---

## 📊 Model Benchmarking

To ensure fairness and reliability, the custom CNN was compared with:

- **ResNet50**
- **EfficientNet-B0**
- **VGG16** (optional training)
  
Each model was evaluated using:

- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  

---

## 👁 Explainable AI (XAI)

Medical AI must be transparent.  
This project uses multiple interpretability techniques:

- **Grad-CAM** → Highlights tumor regions  
- **LIME** → Shows which parts of the image influenced the prediction  
- **SHAP** → Pixel-level feature contribution (game theory–based)  

These visualizations make predictions more trustworthy for clinical use.

---

## ⚡ MRI Upload & Prediction Pipeline

A simple interface lets you:

1. Upload an MRI image  
2. Run it through the trained model  
3. Get prediction (Tumor / No Tumor)  
4. Visualize Grad-CAM heatmap  

---

## 📁 Dataset

The dataset used:

- (https://www.kaggle.com/datasets/ahmedhamada0/brain-tumor-detection).
- Preprocessed: resizing, normalization, data augmentation  

---

## 🏗 Directory Structure


# 🧬 RCC Histopathology Classification

This project focuses on classifying **Renal Cell Carcinoma (RCC)** using histopathology images and deep learning techniques.

The work was carried out during my **research internship at NITK**. The dataset was collected from **KMC Hospital, Mangalore** and was provided strictly for academic research. Since this is **private medical data**, the dataset is **not included** in this repository.

Instead of using an off-the-shelf model, I designed a **custom CNN architecture** tailored for histopathology images. The task involves **5-class RCC classification**, and the model achieves a **best validation accuracy of 93%**.

---

## ✨ Project Highlights
- Custom CNN model built from scratch  
- Designed for 5-class RCC histopathology classification  
- Uses attention and multi-scale feature extraction  
- Achieved **93% validation accuracy**  
- Developed as part of an academic research internship  

---

## 🧠 Model Overview
The proposed model combines multiple feature enhancement techniques, including:

- **SE blocks** for channel attention  
- **RFB blocks** for capturing multi-scale features  
- **MKRC blocks** for richer residual representations  
- **RPAB and RCAB blocks** for feature refinement  

These blocks help the network focus on important tissue patterns and improve classification performance.

---

## 📊 Results
- **Validation Accuracy:** 93%  
- Performance evaluated using:
  - Confusion matrix  
  - Precision, recall, and F1-score  

The training process was stable, and the model showed good generalization on validation data.

---

## 📈 Comparison with Existing Work
The model was compared with **RCCGNet**, which reports an accuracy of **92.16%** for RCC classification.  
The custom model developed in this project achieves a slightly higher validation accuracy of **93%**.

---

## 🔒 Dataset Information
- **Source:** KMC Hospital, Mangalore  
- **Provided via:** NITK  
- **Type:** Private medical dataset  

Due to privacy, ethical guidelines, and institutional policies, the dataset cannot be shared publicly.  
The provided code can be used with any compatible RCC histopathology dataset.

---

## 🛠️ Tools & Libraries
- Python  
- PyTorch / TensorFlow  
- OpenCV  
- NumPy  
- Matplotlib  
- scikit-learn  

---

## 📌 Note
This project was developed for **academic and research purposes only** as part of an internship.

# 🧬 Breast Cancer Cells Detection in Histopathology Images  

This project focuses on **binary classification of breast cancer histopathology images** into **normal tissue** and **cancer tissue**. It leverages deep learning techniques to assist in early detection and diagnosis of breast cancer, enabling better medical support and decision-making.  

---

## 📌 Problem Statement  
Breast cancer is one of the leading causes of death among women worldwide. Early detection through histopathology can significantly improve survival rates, but manual diagnosis is **time-consuming, subjective, and error-prone**.  

The goal of this project is to build an **automated classification system** to distinguish between **normal tissue** and **cancerous tissue** in histopathology images.  

---

## ⚙️ Proposed Solution  
- **Data Preprocessing**  
  - Loaded histopathology images (PCam dataset).  
  - Applied resizing, normalization, and augmentation techniques.  

- **Model Development, Training & Evaluation**  
  - Implemented a **Transfer Learning based CNN architecture** for feature extraction and classification.    
  - Trained models using cross-entropy loss and Adam optimizer.  

---


## 📊 Results  
- Achieved high classification performance with **Accuracy**: 98%    
- Performance Credit: Transfer Learning

<img width="835" height="374" alt="image" src="https://github.com/user-attachments/assets/9a748b13-a650-47b7-8007-9076d9c4ba22" />
  

---

## 🚀 Future Scope  
- Extend to **multi-class classification** (different cancer subtypes).  
- Use **transformer-based architectures** (ViT, Swin Transformer) for improved accuracy. Utilizing **GAN** for handling data imbalance by generating realistic data. 
- Apply **explainability methods** (Grad-CAM, SHAP) to highlight decision regions.  
- Deploy as a **web app** for pathologists to use in real-time diagnosis.  

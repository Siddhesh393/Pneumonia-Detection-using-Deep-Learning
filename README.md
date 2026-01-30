# Pneumonia Detection Using VGG16 CNN

## 📌 Project Overview
This project focuses on **detecting pneumonia from chest X-ray images** using a **VGG16-based Convolutional Neural Network (CNN)**. The model analyzes lung X-ray images to identify abnormal fluid accumulation and patterns associated with pneumonia, helping in early and accurate diagnosis.

---

## 📊 Dataset
**Dataset Used:** *Chest X-Ray Images (Pneumonia)*

The dataset consists of labeled chest X-ray images categorized as:
- **Normal:** Clear lungs with no abnormal opacification.
- **Bacterial Pneumonia:** Shows focal lobar consolidation (commonly visible in one lung region).
- **Viral Pneumonia:** Exhibits a diffuse interstitial pattern across both lungs.

These variations help the model learn different pneumonia patterns effectively.

---

## 🧠 Model Architecture
- **Base Model:** VGG16 (pretrained on ImageNet)
- **Approach:** Transfer Learning
- **Classifier:** Custom fully connected layers added on top of VGG16
- **Input:** Chest X-ray images
- **Output:** Pneumonia detection (Normal vs Pneumonia)

VGG16 was chosen for its strong feature extraction capabilities in medical image analysis.

---

## 🛠️ Technologies & Libraries Used
- **TensorFlow / Keras** – Model building and training  
- **OpenCV (cv2)** – Image preprocessing and resizing  
- **NumPy** – Numerical operations and data handling  

---

## ⚙️ Workflow
1. Load and preprocess chest X-ray images  
2. Resize and normalize images using OpenCV  
3. Use VGG16 as a feature extractor  
4. Train CNN on labeled dataset  
5. Evaluate model performance on validation data  

---

## 🚀 Features
- Automated pneumonia detection from X-ray images  
- Transfer learning using VGG16 for improved accuracy  
- Efficient preprocessing pipeline  
- Scalable and extensible architecture  

---

## 📈 Future Improvements
- Separate classification of bacterial and viral pneumonia  
- Improve accuracy using data augmentation  
- Add Grad-CAM for model interpretability  
- Deploy as a web application using Flask or Streamlit  


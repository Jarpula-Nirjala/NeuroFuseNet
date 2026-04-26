# 🧠 Brain MRI Disease Classifier

A deep learning-based system for classifying brain MRI scans into:

- Alzheimer’s Disease  
- Parkinson’s Disease  
- Healthy Control  

🚀 Achieved **97.84% test accuracy** using advanced deep learning techniques.

---

## 🔍 Overview

This project uses a hybrid deep learning approach combining modern architectures to accurately classify neurological conditions from MRI scans. It also includes explainability using Grad-CAM to visualize important brain regions.

---

## 🚀 Features

- Hybrid Deep Learning Model (EfficientNetV2 + Swin Transformer)
- Cross-Attention based feature fusion
- Grad-CAM++ for explainability
- Test-Time Augmentation (TTA)
- High-performance classification with strong generalization

---

## 📊 Model Performance

- ✅ **Test Accuracy (TTA):** 97.84%  
- ✅ **Macro AUC-ROC:** 0.9981  
- ✅ **F1 Score:** High across all classes  

---

## 📸 Results

### 🔹 Confusion Matrix
![Confusion Matrix](outputs/confusion_matrix.png)

### 🔹 Accuracy Plot
![Accuracy](outputs/training_curves.png)

### 🔹 ROC Curve
![ROC Curve](outputs/roc_curves.png)

---

## 🛠 Tech Stack

- Python  
- PyTorch  
- OpenCV  
- NumPy  
- Matplotlib  
- Scikit-learn  
- timm  

---

## 📂 Project Structure


alzheimer-parkinson-classifier/
│
├── notebooks/
│ └── NIRJALA_13.ipynb
│
├── outputs/
│ ├── confusion_matrix.png
│ ├── training_curves.png
│ ├── roc_curves.png
│
├── model/
│ └── (model available via Google Drive)
│
├── README.md
├── requirements.txt


---

## ▶️ How to Run

### 1. Clone the repository
```bash
git clone https://github.com/Jarpula-Nirjala/alzheimer-parkinson-classifier.git
cd alzheimer-parkinson-classifier
2. Install dependencies
pip install -r requirements.txt
3. Run the notebook

Open:

notebooks/NIRJALA_13.ipynb

⚠️ Dataset
Due to size limitations, the dataset is not included.

👉 Download dataset:
https://drive.google.com/file/d/1AnHbNwv5rBtxYwCBDUwXS_dIGAs2FX1F/view?usp=sharing

📥 Model Download
Due to GitHub file size limitations (~195MB), the trained model is hosted on Google Drive:

👉 Download model:
https://drive.google.com/file/d/1rDF-vTOgMSIrpE3rV1OXukyhXiVNxxRq/view?usp=sharing

📌 Future Improvements
Deploy as a web application (Streamlit/Flask)
Add real-time MRI prediction interface
Expand dataset for better generalization
Optimize model for faster inference

✨ Author
Jarpula Nirjala
📧 nirjala8462@gmail.com
🔗 https://www.linkedin.com/in/nirjala-jarpula-749346321/

⭐ If you like this project
Give it a ⭐ on GitHub!

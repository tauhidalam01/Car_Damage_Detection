# 🚗 Car Damage Detection System

A deep learning-powered Streamlit web application that classifies car damage severity from uploaded images using a PyTorch ResNet50 model.

---

## 🔗 Live Demo

🌐 **Streamlit App:**  
https://cardamagedetection-lbpnyqtaxaxtl2radnz4qp.streamlit.app/

---

## 📌 Project Overview

This project is an end-to-end **computer vision application** that detects and classifies car damage types from images.  
Users can upload a car image, and the trained deep learning model predicts the damage category in real time.

The system is fully deployed using **Streamlit Community Cloud**.

---

## 🧠 Tech Stack

- **Frontend & UI:** Streamlit  
- **Machine Learning:** PyTorch  
- **Model Architecture:** ResNet50  
- **Deployment:** Streamlit Community Cloud  
- **Language:** Python  

---

## ⚙️ Architecture
```
Streamlit UI → PyTorch Model → Prediction Output
```
---

## 📂 Features
```
✅ Upload car damage images  
✅ Real-time prediction  
✅ Deep learning inference  
✅ Clean and interactive UI  
✅ Cloud deployment
```

---

## 🎯 Damage Classes
```
The model predicts the following categories:
- Front_Breakage  
- Front_Crushed  
- Front_Normal  
- Rear_Breakage  
- Rear_Crushed  
- Rear_Normal
```

---

---

## 🚀 How to Run Locally
```
### 1️⃣ Clone Repository

```bash
git clone https://github.com/tauhidalam01/Car_Damage_Detection.git
cd Car_Damage_Detection/streamlit-app
```

---

## Create Virtual Environment
```
python -m venv venv
venv\Scripts\activate
```

---

## Install Dependencies
```
pip install -r requirements.txt
```

---

## Run Streamlit App
```
streamlit run app.py
```

---

## Project Structure 
```
Car_Damage_Detection/
│
├── streamlit-app/
│   ├── app.py
│   ├── model_helper.py
│   ├── requirements.txt
│   └── model/
│       └── saved_model.pth
│
└── README.md
```

---

## 🧪 Model Details
```
-- Base Model: ResNet50

-- Framework: PyTorch

-- Input Size: 224 × 224

-- Output: Damage Classification
```

---
## 👨‍💻 Author
```
Tauhid Alam
Machine Learning | Deep Learning | Generative AI
```




# 🚀 Vidzai Digital eKYC Project

«AI-powered eKYC system for digital identity verification using Machine Learning, Backend, and Frontend»

---

## 🌐 Live Demo

🔗 https://vidz-ai-git-frontend-daves-projects-f7f915af.vercel.app/

---

## 📂 Repository Structure

This project is separated into branches for clean organization:

- main → Core machine learning notebooks and documentation  
- backend → FastAPI backend, APIs, deployment, Docker  
- Frontend → UI built with HTML, CSS, JavaScript  

---

## 📁 Project Structure

```
Vidzai-Digital/
│
├── 🐍 main.py                      # FastAPI backend entry point
├── 🐍 classify.py                 # Classification logic
├── 🐍 document_detector.py        # Document detection (YOLOv8)
├── 🐍 image_utils.py              # Image processing utilities
├── 🐍 ocr_service.py              # OCR text extraction
├── 🐍 text_classifier.py          # Text classification
│
├── 📦 model_config.json           # Model configuration
├── 📦 model_metadata.json         # Model metadata
├── 🤖 face_verification_model.joblib  # Face verification model
├── 🧠 yolov8n.pt                  # YOLOv8 model weights
│
├── 📓 Address_Detection.ipynb     
├── 📓 document_detection.ipynb    
├── 📓 tampering dataset (2).ipynb 
├── 📓 tampmodeltraining.ipynb     
│
├── 🌐 index.html                  # Frontend entry page
├── 🌐 dashboard.html              
├── 🌐 verification_flow.html      
├── 🌐 analytics.html              
├── 🌐 alerts.html                 
├── 🌐 settings.html               
│
├── ⚡ script.js                   # Frontend logic
├── 🎨 styles.css                  # Frontend styling
│
├── 📜 requirements.txt            # Python dependencies
├── 🔐 .env                        # Environment variables
├── ⚙️ .dockerignore               
├── 🐳 Dockerfile                  # Docker configuration
│
├── 🚀 deploy.sh                   
├── 🚀 deploy-vidzai.sh            
├── 🪟 deploy-vidzai.ps1           
├── ☁️ cloudbuild.yaml             
├── 🗄️ init_db.sql                 
│
├── 📘 DEPLOYMENT_GUIDE.md         
├── 📘 DEPLOY_NOW.md               
├── 📘 QUICK_DEPLOY.txt            
│
├── 📖 README.md                   
└── 📜 LICENSE
```

---

## 🧩 System Overview

### 🔹 Frontend
- Built using **HTML, CSS, JavaScript**
- Files:
  - index.html  
  - dashboard.html  
  - verification_flow.html  
  - analytics.html  
  - alerts.html  
  - settings.html  
  - script.js  
  - styles.css  

### 🔹 Backend
- Built using **Python + FastAPI**
- Files:
  - main.py  
  - classify.py  
  - document_detector.py  
  - ocr_service.py  
  - text_classifier.py  
  - image_utils.py  

### 🔹 Machine Learning Models
- YOLOv8 for document detection  
- OCR for text extraction  
- Face verification model  

---

## ⚙️ How to Access the Project

### 🔹 Clone Backend
```bash
git clone -b backend https://github.com/gksiddineni/Vidzai-Digital.git
```

### 🔹 Clone Frontend
```bash
git clone -b Frontend https://github.com/gksiddineni/Vidzai-Digital.git
```

---

## 🛠️ Tech Stack

- Python 🐍  
- FastAPI ⚡  
- HTML / CSS / JavaScript 🌐  
- Machine Learning 🤖  

---

## 🚀 Features

- ✅ Digital eKYC verification  
- ✅ Backend APIs using FastAPI  
- ✅ Frontend UI for user interaction  
- ✅ ML models for identity validation  
- ✅ Secure and scalable architecture  

---

## 👨‍💻 Author

Gopala Krishna Siddineni  
🔗 https://github.com/gksiddineni  

---

## ⭐ Notes

- Switch branches to access different modules  
- Install dependencies before running backend  
- Recommended: use virtual environment  

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!

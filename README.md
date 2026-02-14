# Multi-AI-Agent-Medical-Diagnosis-System

## Overview
The **Multi-Agent AI Medical Diagnosis System** is designed to assist in medical imaging diagnosis using deep learning and computer vision.  
This project integrates multiple AI agents to analyze, classify, and provide insights into medical images while maintaining a modular backend and interactive frontend.

---

## Features
- Multi-agent system for medical diagnosis  
- Deep Learning (CNN-based models for image classification)  
- Flask backend for API and model inference  
- Streamlit frontend for user interaction  
- Deployment-ready setup for Hugging Face Spaces & Vercel  

---

## Project Structure
```bash
├── app.py                  # Streamlit frontend
├── flask_app.py            # Flask backend API
├── models/                 # Pre-trained and fine-tuned models
├── static/                 # Static files (CSS, JS, images)
├── templates/              # HTML templates for Flask
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
```

---



Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate   # For Linux/Mac
venv\Scripts\activate    # For Windows
```

Install dependencies:
```bash
pip install -r requirements.txt
```

---

## Usage

### 1. Start Flask Backend
```bash
python flask_app.py
```

### 2. Run Streamlit Frontend
```bash
streamlit run app.py
```

---

## Example Workflow
1. Upload a medical image through the Streamlit interface  
2. Image is sent to the Flask backend for preprocessing and inference  
3. AI agents (CNN models, diagnostic rules) analyze the image  
4. Results are displayed with prediction probabilities  

---


## Credits
- **Frontend (Streamlit):** Developed by Ankit Vishwakarma  
- **Backend (Flask):** Developed by Ankit Vishwakarma  

---



```bash
Copyright (c) 2025 Ankit Vishwakarma
```
## Author
### Ankit Vishwakarma
### B.Tech - Computer Science and Engineering (Artificial Intelligence and Machine Learning)

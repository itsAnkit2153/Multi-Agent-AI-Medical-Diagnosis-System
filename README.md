# 🧠 Multi-Agent AI Medical Diagnosis System

<p align="center">
  <b>Deep Learning • Computer Vision • Multi-Agent Architecture • Streamlit Deployment</b>
</p>

---

## 🚀 Live Demo

🔗 **Try the App Here:**  
👉 https://multi-agent-ai-medical-diagnosis-system-2153.streamlit.app/

---

## 📌 Overview

The **Multi-Agent AI Medical Diagnosis System** is an AI-powered application designed to assist in medical image diagnosis using Deep Learning and Computer Vision.

The system integrates multiple AI agents to analyze uploaded medical images, perform classification, and provide prediction probabilities through an interactive frontend interface.

This project demonstrates:

- Multi-agent system design  
- CNN-based image classification  
- Modular backend architecture  
- End-to-end deployment  

---

## ✨ Features

- 🧠 Multi-agent AI architecture  
- 🖼 Medical image classification (CNN models)  
- ⚙️ Flask backend for API & inference  
- 🎨 Streamlit frontend for user interaction  
- 📊 Prediction probability visualization  
- ☁️ Deployed on Streamlit Cloud  

---

## 🏗 System Architecture

```
User (Streamlit UI)
        ↓
Flask Backend API
        ↓
AI Agents (CNN Models)
        ↓
Prediction Output
```

---

## 📂 Project Structure

```bash
├── app.py                  # Streamlit frontend
├── flask_app.py            # Flask backend API
├── models/                 # Pre-trained / fine-tuned models
├── static/                 # Static assets (CSS, images)
├── templates/              # HTML templates
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
```

---

# ⚙️ Installation & Local Setup (Windows - VS Code)

## 1️⃣ Clone Repository

```bash
git clone https://github.com/itsAnkit2153/Multi-Agent-AI-Medical-Diagnosis-System.git
cd Multi-Agent-AI-Medical-Diagnosis-System
```

---

## 2️⃣ Create Virtual Environment

```bash
python -m venv venv
```

---

## 3️⃣ Activate Virtual Environment

```bash
venv\Scripts\activate
```

You should now see:

```
(venv)
```

in your terminal.

---

## 4️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Run the Application

## Option A – Run Streamlit (Frontend)

```bash
streamlit run app.py
```

Open in browser:

```
http://localhost:8501
```

---

## Option B – Run Flask Backend + Streamlit

Start Flask backend:

```bash
python flask_app.py
```

Then in a new terminal:

```bash
streamlit run app.py
```

---

# 🔄 Example Workflow

1. Upload a medical image via Streamlit UI  
2. Image is sent to Flask backend  
3. CNN-based AI agents analyze the image  
4. Model generates prediction probabilities  
5. Results displayed interactively  

---

# 🛠 Tech Stack

- Python  
- Streamlit  
- Flask  
- Deep Learning (CNN)  
- Computer Vision  
- Pandas  
- Plotly  

---

# 📈 Future Improvements

- Integrate advanced architectures (ResNet / EfficientNet)  
- Add explainability (Grad-CAM)  
- Separate backend deployment  
- Add model monitoring  

---

# 👨‍💻 Author

**Ankit Vishwakarma**  
B.Tech – Computer Science & Engineering (AI & ML)

GitHub: https://github.com/itsAnkit2153  

---

# 📜 License

```
Copyright (c) 2025 Ankit Vishwakarma
```

---

⭐ If you found this project useful, consider giving it a star!

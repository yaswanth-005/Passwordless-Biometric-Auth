# 🔐 Passwordless Authentication System Using Voice Biometrics

## 📌 Project Overview
This project implements a **Passwordless Authentication System** using **voice biometrics** instead of traditional passwords.  
Users are authenticated based on unique voice characteristics, improving security and user convenience.

The system uses a **Flask backend** to process voice input and a **web-based frontend** for user interaction.

---

## 🎯 Objectives
- Eliminate password-based authentication
- Improve security using biometric verification
- Provide a simple and user-friendly authentication mechanism
- Demonstrate voice biometric authentication using Python

---

## 🧠 Features
- Voice-based login authentication
- Passwordless secure access
- Lightweight Flask backend
- Simple web-based frontend
- MFCC-based voice feature extraction

---

## 🏗️ System Architecture
Frontend (HTML/CSS/JS)
↓
Flask Backend (Python)
↓
Voice Recording & Processing
↓
Feature Extraction (MFCC)
↓
Authentication Decision

yaml
Copy code

---

## 🧪 Technology Stack
### Frontend
- HTML
- CSS
- JavaScript

### Backend
- Python
- Flask

### Libraries & Tools
- Librosa
- NumPy
- SoundDevice
- Git & GitHub
- VS Code

---

## 📂 Project Structure
Passwordless-Biometric-Auth/
│
├── backend/
│ ├── app.py
│ ├── requirements.txt
│ └── voice/
│ ├── init.py
│ └── voice_login.py
│
├── frontend/
│ ├── index.html
│ ├── script.js
│ └── style.css
│
├── data/
│ └── voice_features/
│ └── .gitkeep
│
├── Project_Documentation.pdf
├── README.md
└── .gitignore

yaml
Copy code

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yaswanth-005/Passwordless-Biometric-Auth.git
cd Passwordless-Biometric-Auth
2️⃣ Install Backend Dependencies
bash
Copy code
pip install -r backend/requirements.txt
3️⃣ Run the Backend Server
bash
Copy code
cd backend
python app.py
The server will start at:

cpp
Copy code
http://127.0.0.1:5000
4️⃣ Open the Frontend
Navigate to frontend/

Open index.html in a browser

Click Login with Voice

Allow microphone access

📊 Output
Backend processes voice input

Voice features are extracted

Authentication result is returned as:

✅ Login Success

❌ Login Failed

✅ Advantages
No password storage

Enhanced security

Easy to use

Contactless authentication

⚠️ Limitations
Sensitive to background noise

Voice may vary due to illness

Requires microphone access

🚀 Future Enhancements
Voice registration module

Multi-factor authentication

Face and fingerprint integration

Deep learning-based voice recognition

📄 Documentation
Detailed project documentation is available here:
📘 Project_Documentation.pdf

🔗 GitHub Repository
👉 https://github.com/yaswanth-005/Passwordless-Biometric-Auth

👤 Author
Yaswanth
Final Year Project
Passwordless Authentication System

📜 License
This project is created for educational purposes.

yaml
Copy code

---

## ✅ HOW TO ADD THIS TO GITHUB

1. Open your repository folder in VS Code  
2. Open `README.md`
3. Paste the above content
4. Save (`Ctrl + S`)
5. Run:
   ```bash
   git add README.md
   git commit -m "Updated README"
   git push

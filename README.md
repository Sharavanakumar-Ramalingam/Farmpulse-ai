# 🌱 FarmPulse AI

FarmPulse AI is a Smart India Hackathon (SIH) project offering an AI-powered platform that enables **farmers** and **veterinarians** to detect and manage **crop and animal diseases** using **text** and **image** symptom inputs. It combines **Natural Language Processing (NLP)**, **Computer Vision (CV)**, and veterinarian expertise to deliver fast, actionable advice. Designed with a **kiosk-friendly interface** for rural accessibility.

---

## 🚀 Features

### 👨‍🌾 Farmer Dashboard
- Role-based login and signup
- Report symptoms via text input or image upload
- Receive AI-generated disease diagnosis and recommended remedies
- Option to escalate complex cases to veterinarians

### 🩺 Vet Dashboard
- Secure veterinarian login
- View and manage farmer-reported cases
- Validate or override AI-generated diagnoses
- Maintain case history and treatment records

### 🤖 AI Integration
- **NLP Model** for analyzing textual symptoms
- **Computer Vision Model** for analyzing images of infected crops or animals
- Automated disease prediction and treatment suggestion

---

## 🛠 Tech Stack

| Component | Technology |
|----------|------------|
| Frontend | HTML, CSS, JavaScript |
| Backend  | Django (Python) |
| Database | SQLite / PostgreSQL |
| AI/ML    | TensorFlow / PyTorch / Transformers |

---

## 📂 Project Structure

```
Farmpulse-ai/
├── backend/                # Django backend
│   ├── authenticate/      # Login and registration logic
│   ├── farmer/            # Farmer-side functionality
│   ├── vet/               # Vet-side functionality
│   ├── settings.py        # Django settings
│   └── urls.py            # URL routing
├── frontend/              # Static frontend files
│   ├── index.html         # Entry point for users
│   └── static/            # CSS and JavaScript assets
├── models/                # Trained ML models (.pkl, .h5, .pt)
├── requirements.txt       # Python dependencies
└── README.md              # Project overview
```

---

## ⚙️ Getting Started

Follow these steps to set up and run the project locally:

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Sharavanakumar-Ramalingam/Farmpulse-ai.git
cd Farmpulse-ai
```

### 2️⃣ Create and Activate a Virtual Environment
```bash
python3 -m venv venv
source venv/bin/activate     # macOS/Linux
venv\Scripts\activate        # Windows
```

### 3️⃣ Install Python Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Run Migrations and Start Server
```bash
cd backend
python manage.py migrate
python manage.py runserver
```

### 5️⃣ Access Application
- Backend: `http://localhost:8000/`
- Frontend: Open `frontend/index.html` in a browser

---

> **“Bringing smart diagnostics and expert interventions to the fingertips of India’s farmers.”**

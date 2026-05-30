# VoiceSewa 🎙️

> Multilingual Voice-Assisted Job Connection Platform for Blue-Collar Services

---

## 📌 Overview

VoiceSewa is a multilingual, voice-first job connection platform designed to bridge the gap between blue-collar workers and individuals seeking reliable services.

The platform enables users to connect with plumbers, electricians, carpenters, painters, and other skilled workers using simple voice interactions in their native language.

VoiceSewa focuses on accessibility, inclusivity, and trust by combining multilingual voice assistance, cloud-based architecture, AI-powered worker matching, and secure verification systems.

---

## ❗ Problem Statement

Millions of blue-collar workers across India still rely heavily on word-of-mouth networks to find work opportunities. Existing platforms are often:

- English-centric
- Internet dependent
- Difficult for low-literacy users
- Designed for digitally skilled users only

At the same time, customers struggle to quickly find verified and trustworthy workers nearby.

VoiceSewa solves this by providing:

- Voice-based interaction
- Local language support
- Low-bandwidth optimization
- Simplified workflows
- Secure worker-client communication

---

## 🚀 Features

### 👤 Client App
- Post service requests using voice or text
- Browse verified worker profiles
- Compare quotations
- Book services instantly
- Track job history and ratings

### 👷 Worker App
- Receive localized job notifications
- Respond using voice or one-tap actions
- Accept or reject jobs quickly
- Manage work history and availability

### 🎙️ Multilingual Voice Assistant
- Supports Hindi, Marathi, and English
- Speech-to-Text (STT)
- Text-to-Speech (TTS)
- Intent recognition and conversational flow

### 🔒 Trust & Security
- OTP-based verification
- Masked calling support
- Verified profiles
- Ratings and reviews

### ☁️ Cloud-Based & Low-Bandwidth Support
- Cloud-synced architecture using Firebase
- Optimized for low-bandwidth environments
- Lightweight UI for low-end devices
- Smart synchronization for unstable networks

### 🤖 AI Features
- AI-powered worker matching
- Skill + proximity-based suggestions
- Automatic language translation

---

## 💡 Workflow

1. Client speaks a service request in their language  
2. App converts speech into text  
3. Request is synced securely through the cloud  
4. Nearby verified workers receive notifications  
5. Workers respond using voice or one-tap actions  
6. AI suggests the best worker based on skill and proximity  
7. Booking is confirmed through OTP verification  
8. Service is completed and reviewed  

---

## 🛠️ Technology Stack

### 📱 Frontend
- Flutter

### ⚙️ Backend
- Firebase
- FastAPI

### 🗄️ Database & Cloud Infrastructure
- Firebase Firestore
- Firebase Cloud Services

### 🧠 AI & Voice Processing
- OpenAI Whisper STT
- Vosk / Mozilla DeepSpeech
- Coqui TTS / eSpeak NG
- BERT
- LLaMA
- Scikit-learn

### 🔐 Security
- Firebase Authentication
- OTP Verification
- Twilio API
- Number Masking

### 🧰 Tools
- Git & GitHub
- VS Code
- Figma

---

## 📂 Project Structure

```bash
VoiceSewa/
│
├── client_app/
├── worker_app/
├── backend/
├── ai_models/
├── cloud_services/
├── assets/
│   ├── images/
│   └── audio/
├── docs/
│   ├── architecture/
│   └── diagrams/
├── README.md
└── requirements.txt
```

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/aryan-madhavi/VoiceSewa.git
cd VoiceSewa
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
```

### 3️⃣ Activate Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Mac/Linux

```bash
source venv/bin/activate
```

### 4️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 5️⃣ Run the Application

```bash
flutter run
```

---

## 🌟 Unique Selling Points (USPs)

- 🎙️ Voice-first accessibility
- 🌐 Multilingual support
- ☁️ Cloud-based scalable architecture
- 🔒 Secure and verified ecosystem
- 🤖 AI-powered worker recommendations
- 🔄 Real-time synchronization
- 🧩 Minimal and user-friendly UI

---

## 📸 Screenshots

Add your application screenshots here.

```bash
/assets/images/
```

Suggested screenshots:
- Home screen
- Voice assistant interaction
- Worker dashboard
- Client booking interface
- AI matching workflow

---

## 🏗️ Architecture & Diagrams

Project diagrams can be stored inside:

```bash
/docs/architecture/
```

Suggested diagrams:
- System Architecture Diagram
- Use Case Diagram
- Data Flow Diagram
- Sequence Diagram
- Cloud Sync Workflow

---

## 🔮 Future Scope

- Support for more Indian languages
- AI fraud detection
- DigiLocker verification integration
- Worker earnings analytics dashboard
- Integration with microfinance systems
- Hybrid IVR support
- Smart worker recommendation engine

---

## ⚠️ Dependencies & Challenges

### Dependencies
- Open-source multilingual STT/TTS models
- Firebase services
- Twilio APIs
- Community onboarding partnerships

### Potential Challenges
- Voice recognition accuracy in rural dialects
- Worker adoption resistance
- Maintaining smooth performance in unstable network conditions
- Data privacy and trust concerns

---

## 🤝 Contribution

Contributions are welcome.

1. Fork the repository  
2. Create a new branch  
3. Commit your changes  
4. Push the branch  
5. Open a Pull Request  

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Team Carbonari

- Aryan Madhavi — Team Leader  
- Riddhi Kale — Team Member  
- Sahil Gangani — Team Member  
- Sankalp Dawada — Team Member  

Institution: K. J. Somaiya Polytechnic, Vidyavihar

---

## 🔗 GitHub Repository

https://github.com/aryan-madhavi/VoiceSewa.git

---

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub.

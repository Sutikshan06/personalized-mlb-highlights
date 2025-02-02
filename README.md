# Personalized MLB Highlights

## 📌 Project Overview
**Personalized MLB Highlights** is an AI-powered system that allows baseball fans to receive customized game highlights based on their favorite teams and players. The system generates video, text, and audio summaries in multiple languages (English, Spanish, and Japanese), making it easier for fans to stay updated.

## 🚀 Features
- **Custom Team & Player Selection**: Fans can choose their favorite teams and players.
- **AI-Generated Video Highlights**: Uses AI to extract key moments from games.
- **Text Summaries**: Provides game recaps using AI-powered text processing.
- **Multi-Language Support**: English, Spanish, and Japanese translations.
- **Audio Summaries**: Converts text highlights into an audio digest.
- **Web-Based Dashboard**: View highlights and receive updates through email notifications.

## 🛠️ Tech Stack
### **Backend**
- Flask / FastAPI (Python) - API for processing highlights
- Google Cloud Functions - Automating video processing
- Firestore / Firebase DB - Storing user preferences
- Google Cloud Storage - Hosting processed highlights

### **Frontend**
- React.js - Web dashboard for user preferences
- Firebase Hosting / Vercel - Deploying frontend

### **AI & Cloud Services**
- Google AutoML Video Intelligence API - Extracting game highlights
- Google Cloud Translate API - Multi-language support
- Google Cloud Speech-to-Text - Converting commentary into text
- Google Cloud Text-to-Speech - Generating audio summaries

## 📂 Project Structure
```
📦 personalized-mlb-highlights
 ┣ 📂 backend        # Flask/FastAPI backend
 ┃ ┣ 📂 models       # AI models for video processing
 ┃ ┣ 📂 api          # API endpoints
 ┃ ┣ 📜 main.py      # Backend entry point
 ┃ ┣ 📜 requirements.txt  # Python dependencies
 ┣ 📂 frontend       # React.js frontend
 ┃ ┣ 📂 src          # Frontend components
 ┃ ┣ 📜 index.js     # React entry point
 ┃ ┣ 📜 App.js       # Main UI component
 ┣ 📂 cloud          # Google Cloud Functions
 ┣ 📂 data           # Sample video data
 ┣ 📜 README.md      # Project documentation
 ┣ 📜 .gitignore     # Ignore unnecessary files
 ┗ 📜 LICENSE        # Open-source license
```

## 🛠️ Setup & Installation
### **1️⃣ Clone the Repository**
```bash
git clone git@github.com:Sutikshan06/personalized-mlb-highlights.git
cd personalized-mlb-highlights
```

### **2️⃣ Backend Setup (Flask/FastAPI)**
```bash
cd backend
python -m venv venv
source venv/bin/activate  # For macOS/Linux
source venv/Scripts/activate  # For Windows
pip install -r requirements.txt
```

### **3️⃣ Frontend Setup (React.js)**
```bash
cd frontend
npm install
npm start
```

### **4️⃣ Google Cloud API Setup**
- Enable **AutoML Video Intelligence, Translate API, Speech-to-Text, and Text-to-Speech**.
- Store your **Google Cloud credentials** in `.env`.

## 📌 Usage
1. Select your favorite **teams and players** in the web dashboard.
2. The AI **extracts highlights** and generates text/audio summaries.
3. Users receive **customized summaries** in their selected language.

## 📽️ Demo Video
🚀 Coming Soon!

## 🤝 Contribution
Feel free to contribute! Open issues, submit PRs, or suggest features.

## 📜 License
MIT License - Free to use and modify.

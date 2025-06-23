# EduLink

## 🧠 Overview

**EduLink** is an AI-powered classroom assistant that enhances real-time student-instructor interaction. It combines intelligent query processing, lecture transcription, secure user management, and responsive cross-platform interfaces.

This monorepo contains all the core services:

- 🎓 **AI Backend** (Python): Handles lecture transcription, semantic search, and LLM query response
- 🔐 **User Backend** (Go): Manages authentication, sessions, and user roles
- 📱 **Flutter App**: Mobile app for students
- 🌐 **React Dashboard**: Instructor web portal

---

## 📚 Table of Contents

- [Technologies Used](#technologies-used)
- [Installation Instructions](#installation-instructions)
- [Usage Instructions](#usage-instructions)
- [Environment Variables](#environment-variables)
- [Project Structure](#project-structure)

---

## 🛠️ Technologies Used

### AI Backend
- **Python**
- **LangChain**
- **Qdrant**
- **Redis**
- **gRPC**

### User Backend
- **Go**
- **PostgreSQL**
- **JWT**
- **gRPC**

### Flutter App
- **Dart**
- **Flutter SDK**

### React Web App
- **React.js**
- **TypeScript**
- **Vite / CRA**

---

## ⚙️ Installation Instructions

### ✅ Prerequisites

Make sure the following are installed:

- Python 3.12+ and pip
- Go 1.20+
- Flutter SDK
- Node.js 18+ and npm/yarn
- PostgreSQL & Redis (locally or cloud)
- Firebase CLI (if used)

---

### AI Services Setup

```bash
cd AI-Backend/
python -m venv venv
pip install -r requirements.txt
```

### User Services Setup

```bash
cd User-Backend/
go mod tidy
./run.bat
```

### Mobile App Setup

```bash
cd student_app/
flutter pub get
flutter run
```

### Web App Setup

```bash
cd Instructor-Dashboard/
npm install
npm run dev
```


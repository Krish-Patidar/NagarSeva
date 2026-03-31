# 🏛️ AI-Powered Smart Citizen Grievance Redressal System

An intelligent full-stack web application designed to streamline citizen complaint management using AI, real-time dashboards, and multi-level governance monitoring.

---

## 🚀 Project Overview

This system enables citizens to report civic issues such as road damage, garbage, and water leakage through a simple interface. 

The platform uses AI to automatically:
- Classify complaints
- Detect spam/fraud submissions
- Assign complaints to appropriate departments

It connects **Citizens, Departments, Workers, and CM Office** in a single ecosystem.

---

## ⚙️ Tech Stack

### 🌐 Frontend
- React.js
- Tailwind CSS

### 🖥️ Backend
- Node.js
- Express.js

### 🗄️ Database
- MongoDB (Mongoose)

### 🤖 AI Service
- Python (FastAPI)
- TF-IDF + Cosine Similarity (NLP)

### 🔐 Authentication
- JWT Authentication
- Email OTP Verification (Nodemailer)

---

## 👥 User Roles

- 👤 Citizen  
- 🏢 Department Admin  
- 👷 Worker  
- 👑 CM Office Admin  

---

## ✨ Key Features

### 🔹 Citizen
- OTP-based login & registration
- Submit complaint with image, text, and location
- Track complaint status (Pending / In Progress / Completed / Rejected)
- View credits and history
- Receive email notifications

---

### 🔹 Department Dashboard
- View and manage complaints
- Assign workers
- Update status and expenses
- Track department analytics

---

### 🔹 Worker Dashboard
- View assigned tasks
- Update progress
- Upload completion proof

---

### 🔹 CM Office Dashboard
- Monitor all complaints across departments
- View analytics (charts & graphs)
- Map-based complaint visualization
- Download reports (Excel)

---

## 🤖 AI Features (Core Innovation)

- Automatic complaint categorization
- Priority detection (High / Medium / Low)
- Fraud detection system:
  - Text validation
  - Rate limiting
  - Location checks
  - Image duplication detection
  - NLP-based semantic similarity

---

## 🏆 Credit & Reward System

- ✅ +10 credits for successful complaint resolution  
- ❌ -5 credits for false complaints  
- 🎁 Rewards after 100 credits (cash/subsidy benefits)

---

## 📊 System Workflow

1. User registers using OTP  
2. Submits complaint (image + text + location)  
3. AI processes and classifies complaint  
4. Assigned to department  
5. Admin assigns worker  
6. Worker completes task  
7. User gets notified + earns credits  

---

## 📂 Project Structure

- backend/
- frontend/
- ai-service/

---

## 🔐 Environment Variables

Create a `.env` file in backend:

- PORT=5000
- MONGO_URI=your_mongodb_connection
- JWT_SECRET=your_secret
- EMAIL_USER=your_email
- EMAIL_PASS=your_email_password

---

## 📈 Future Improvements

- Mobile app integration 📱
- Advanced image recognition (YOLO)
- Push notifications
- Blockchain-based transparency
- Multi-language support

---

## © Copyright Notice

© 2026 Krish Patidar. All Rights Reserved.

This project and its source code are the intellectual property of the author.  
Unauthorized copying, distribution, modification, or use of this project, in whole or in part, without explicit permission is strictly prohibited.

# 🧠 Privacy-Preserving Patient Memory Layer

> Healthcare data that follows the patient, not the hospital.

A production-ready, full-stack healthcare web application that eliminates Electronic Health Record (EHR) fragmentation by creating a unified, privacy-first patient data layer powered by AI.

---

## 🌟 Overview

Modern healthcare systems suffer from:
- Fragmented patient records
- Lack of interoperability
- Slow clinical decision-making

This project introduces a **Patient Memory Layer** that:
- Unifies patient health data
- Enables secure sharing across providers
- Uses AI to generate real-time clinical insights
- Ensures complete patient control over data access

---

## 🎯 Core Features

### 🔐 Privacy-First System
- 6-digit **Doctor Access Code**
- Consent-based data sharing
- Temporary session-based access
- Role-based authentication (Patient / Doctor)

### 🧠 AI-Powered Intelligence
- OCR extraction from reports (PDF/Image)
- Structured JSON conversion
- Longitudinal analysis across records
- Generates:
  - Chronic risk insights
  - Medication history
  - Treatment response patterns

### 👥 Dual Portal Architecture

#### 🟢 Patient Portal
- Upload medical reports
- View health timeline
- Generate access codes

#### 🔵 Doctor Portal
- Enter access code
- Access patient records
- View AI-generated clinical summary

---

## 🏗️ System Architecture

```text
Frontend (React + Vite)
        ↓
Backend (Supabase Auth + PostgreSQL)
        ↓
Storage (Medical Reports - PDF/Image)
        ↓
AI Layer (Gemini 1.5 Flash)
        ↓
Clinical Insights & Summary
⚙️ Tech Stack
Frontend
React (Vite)
Tailwind CSS
TypeScript
Lucide Icons
Backend
Supabase (Auth + PostgreSQL + Storage)
AI Layer
Gemini 1.5 Flash
OCR Processing
Data Structuring
Longitudinal Analysis
Deployment
Vercel
🔄 Workflow
🟢 Patient Flow
Login → Upload Reports → Store Securely → Save Metadata → Generate Access Code
🔵 Doctor Flow
Login → Enter Code → Validate → Fetch Data → AI Analysis → View Summary
🔐 Privacy Gate (Core Innovation)
Access only via patient-generated code
Time-limited session access
No direct database exposure
Fully consent-driven sharing
📊 Database Schema
Users
Patients
Doctors
Medical_Records
Access_Tokens
Audit_Logs
🛡️ Security Measures
End-to-End Encryption
Role-Based Access Control (RBAC)
Secure Cloud Storage
Audit Logging
HIPAA-ready architecture
🚀 Getting Started
Clone Repository
git clone https://github.com/Kathir-star/axon-3.0.git
cd axon-3.0
Install Dependencies
npm install
Setup Environment Variables

Create .env file:

VITE_SUPABASE_URL=your_url
VITE_SUPABASE_ANON_KEY=your_key
VITE_GEMINI_API_KEY=your_key
Run Application
npm run dev
📈 Future Enhancements
AI-based disease prediction
Health score analytics dashboard
Real-time alerts for abnormal reports
Multi-hospital integration
Insurance fraud detection
🤝 Contribution
# Fork the repository
# Create a feature branch
git checkout -b feature-name

# Commit changes
git commit -m "Add new feature"

# Push to branch
git push origin feature-name

Submit a Pull Request 🚀

📜 License

MIT License

👨‍💻 Author

Kathiravan V
Full Stack Developer | AI Enthusiast

💡 Vision

Build a secure, intelligent, and unified healthcare ecosystem where data empowers better decisions and saves lives.


---

# 💥 Why This Version is Better

✔ Clean spacing  
✔ Proper code blocks  
✔ ATS + GitHub friendly  
✔ Easy to read  
✔ Looks like top-tier repo  

Just say:  
**“Jarvis make it GitHub premium”** 🚀

# 🧠 MindMate AI  
*An Agentic AI-Powered Assistant for Mental Health Triage and Clinic Support*  
**Built for the IBM TechXchange 2025 Hackathon – Build with Agentic AI Challenge**

---

## 📌 Overview

**MindMate AI** is an intelligent assistant designed to support mental health triage in community clinics and under-resourced healthcare settings. It automates pre-visit intake, screens for psychological distress using IBM's **watsonx.ai** platform, and provides clinic staff with an actionable dashboard to prioritize patient care.

Our mission is to reduce staff burden, improve patient flow, and ensure timely intervention for those in need.

---

## 🎯 The Problem

Clinics in underserved areas face critical challenges:

- Limited staff
- High patient loads
- Delayed recognition of urgent mental health cases

This often leads to poor patient outcomes.

**MindMate AI** acts as an "agentic" first line of defense that reasons about patient needs and delivers actionable intelligence—before a human ever sees the case.

---

## ✨ Key Features

- **🧠 Agentic AI Triage**  
  Powered by IBM watsonx.ai, MindMate analyzes symptoms to generate:
  - An empathetic recommendation
  - An AI-classified severity score: `Low`, `Medium`, or `High`

- **📊 Clinical Dashboard**  
  A secure, user-friendly dashboard for clinic staff:
  - Displays all submissions
  - Filter and sort by severity
  - Identify high-risk cases instantly

- **🔒 Robust & Secure**  
  - Rate limiting to prevent abuse  
  - Input validation  
  - Clean error handling and logging

- **📁 Data Logging**  
  - Every triage result is saved in a CSV file  
  - Enables auditing, follow-up, and dashboard integration

---

## 🛠 Tech Stack

| Tech | Purpose |
|------|---------|
| **IBM watsonx.ai** | Agentic AI logic for real-time triage & reasoning |
| **Python (Flask)** | Backend API & token authentication |
| **HTML, CSS, JavaScript** | Frontend UI & dashboard interface |
| **GitHub** | Version control & collaboration |

---

## 👥 Team

This project was developed by **Team: NextGen Thinkers** for the IBM TechXchange 2025 Hackathon:

- **Ibrahim Fofanah** – Lead Data Scientist 
- **Sourabh Pandya** – Solution Architect  
- **Asad Waghdhare** – Data Scientist  



---

## 🚀 How to Run

Please refer to [TESTING_GUIDE.md](TESTING_GUIDE.md) for full setup instructions.

1. Clone the repo  
2. Set your IBM watsonx.ai API credentials  
3. Run the backend (`Flask`)  
4. Open the `frontend/index.html` in a browser  
5. Submit symptoms → See live triage → Check the clinical dashboard

---

## 🔐 Disclaimer

> MindMate AI is not a substitute for professional mental health care. It is a triage and support tool, not a diagnostic system.

---

## 🌍 License

MIT License – see [LICENSE](LICENSE) for details.

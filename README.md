# AI-Powered Ransomware Early Detection and Automated Response System

## Project Overview
RansomGuard is an AI-powered cybersecurity project designed to detect ransomware-like activities at an early stage. It monitors system behavior and file activities to identify suspicious patterns and helps reduce potential data loss through automated response mechanisms.

## Features
- Real-time system activity monitoring
- File activity monitoring
- AI-based risk score analysis
- Suspicious file detection
- Automated response for detected threats
- Security incident logging
- Web-based monitoring dashboard
- Security reports

## Technologies Used
- **Programming Language:** Python, JavaScript
- **Frontend:** React.js
- **Backend:** FastAPI
- **Database:** MongoDB
- **System Monitoring:** psutil
- **File Monitoring:** Watchdog
- **Machine Learning:** Scikit-learn, Random Forest
- **File Analysis:** YARA

## System Workflow
1. Monitor system and file activities.
2. Collect system behavior data.
3. Analyze suspicious activity using the detection engine.
4. Calculate a risk score.
5. Identify potential ransomware-like behavior.
6. Trigger the configured response.
7. Record incidents and display results on the dashboard.

## Project Structure
```text
Ransomware-Early-Detection-System/
│
├── backend/
│   ├── app/
│   ├── uploads/
│   └── requirements.txt
│
├── frontend/
│   ├── src/
│   └── package.json
│
├── README.md
└── .gitignore
```

## Installation and Setup

### Backend
```bash
cd backend
python -m venv venv
```

Activate the virtual environment on Windows:
```bash
venv\Scripts\activate
```

Install dependencies:
```bash
python -m pip install -r requirements.txt
```

Run the backend:
```bash
python -m uvicorn app.main:app --reload
```

Backend API:
`http://127.0.0.1:8000`

API documentation:
`http://127.0.0.1:8000/docs`

### Frontend
```bash
cd frontend
npm install
npm run dev
```

## Project Objective
The main objective is to identify ransomware-like behavior before large-scale file encryption occurs and help reduce the impact of ransomware attacks, especially for Micro, Small, and Medium Enterprises (MSMEs).

## Disclaimer
This project is developed for educational and cybersecurity research purposes. Testing should be performed only in a controlled environment using harmless test files and simulations.

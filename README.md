Overview

A web application that allows teachers to mark daily student attendance digitally and automatically notify parents via SMS when a student is absent. Integrated with Azure DevOps for CI/CD, testing, and performance monitoring.

🔹 Features

Teacher login & authentication

Mark daily attendance (Present/Absent)

Automated SMS to parents for absentees

Daily & monthly attendance reports

Azure DevOps Boards for project tracking

Test Plans for manual & exploratory testing

Pipelines for CI/CD automation

Azure Load Testing for performance evaluation

🔹 Tech Stack

Backend: Python (Flask/Django)

Frontend: HTML, CSS, JavaScript (or Flutter if mobile)

Database: MySQL / PostgreSQL

SMS API: Twilio / Fast2SMS

DevOps: Azure DevOps (Pipelines, Boards, Test Plans, Repos, Artifacts)

Cloud: Azure App Service for deployment

🔹 Project Structure
attendance-app/
│── src/                  # App source code
│   ├── api/              # Login, Attendance, SMS APIs
│   ├── templates/        # Frontend templates
│   └── static/           # JS, CSS
│── tests/                # Test cases
│── requirements.txt      # Python dependencies
│── azure-pipelines.yml   # CI/CD config
│── README.md             # Documentation

🔹 Getting Started
1. Clone the Repo
git clone https://github.com/<your-username>/attendance-sms-system.git
cd attendance-sms-system

2. Install Dependencies
pip install -r requirements.txt

3. Run Locally
python app.py


➡ App runs on http://127.0.0.1:5000

🔹 CI/CD Pipeline (Azure DevOps)

Trigger: Every push to main

Steps:

Install dependencies

Run unit tests (pytest)

Deploy to Azure Web App

Config: azure-pipelines.yml

🔹 Testing

Manual Testing: Test Plans in Azure DevOps

Exploratory Testing: Test & Feedback extension

Automated Testing: Pytest integrated in CI pipeline

Load Testing: Azure Load Testing simulating 50+ concurrent users on login, attendance, and SMS APIs

🔹 Results

✅ All pipelines passed

✅ Load test (48 users): 1ms avg response time, 0 errors

✅ Bugs tracked & resolved using Test Plans

🔹 Future Enhancements

Parent portal for attendance reports

Mobile app integration (Flutter)

Dashboard for SMS logs & analytics

🔹 Contributors

231901051 – Project Owner / Developer

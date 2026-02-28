# LoanShield -- Loan Default Prediction System

LoanShield is a Machine Learning based web application that predicts
whether a loan applicant is **Low Risk** or **High Risk** using
financial data.

This project is built using **Flask**, **Machine Learning**, and
**SQLite Database** with a modern analytics dashboard UI.

---

## 🚀 Live Demo

https://YOUR-RENDER-LINK.onrender.com

---

## 🧠 Features

- Loan Default Prediction using Machine Learning model
- Interactive Analytics Dashboard
- Prediction History Tracking
- Risk Visualization Charts
- Delete Prediction Logs
- Responsive Modern UI
- SQLite Database Integration

---

## 🛠️ Technologies Used

- Python (Flask)
- Scikit-learn
- Pandas & NumPy
- SQLite Database
- HTML / CSS / JavaScript
- Chart.js

---

## 📂 Project Structure

    static/
    │── css/
    │── img/
    │── js/

    templates/
    │── home.html
    │── predict.html
    │── result.html
    │── dashboard.html
    │── about.html
    │── navbar.html
    │── footer.html
    │── login.html
    │── signup.html

    app.py
    loan_model.pkl
    loan_database.db
    requirements.txt
    Procfile
    README.md

---

## ⚙️ Installation (Local Setup)

### 1️⃣ Clone Repository

    git clone https://github.com/YOUR-USERNAME/LoanShield.git
    cd LoanShield

### 2️⃣ Install Dependencies

    pip install -r requirements.txt

### 3️⃣ Run Application

    python app.py

### 4️⃣ Open Browser

    http://localhost:10000

---

## ☁️ Deployment (Render)

This project is deployed using **Render Web Service**.

### Steps:

1.  Push project to GitHub
2.  Go to https://render.com
3.  Create **New Web Service**
4.  Connect GitHub repository
5.  Select branch → `main`
6.  Render automatically installs dependencies
7.  App runs using Procfile configuration

---

## ⚙️ Procfile

    web: gunicorn app:app

---

## 🧠 Machine Learning Model

- Model trained using loan applicant financial dataset
- Predicts loan default risk:
  - **0 → Low Risk**
  - **1 → High Risk**
- Model loaded using Joblib

---

## 🗄️ Database

SQLite database automatically creates:

- users table
- prediction history table

Database initializes automatically on first run.

---

## 👨‍💻 Author

Developed by **OM THORIYA**

Academic Machine Learning Project Submission.

---

## ✅ Notes

- No manual database setup required
- Model loads automatically at startup
- Dashboard updates dynamically after predictions
- Designed for educational and demonstration purposes

---

## ⭐ Future Improvements

- User authentication system
- Cloud database integration
- Model retraining pipeline
- Admin analytics panel

---

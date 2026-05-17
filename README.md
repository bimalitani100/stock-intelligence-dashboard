# Stock Intelligence Dashboard

A full-stack desktop application that integrates financial data pipelines, machine learning models, and interactive visualization to analyze and predict stock market trends.

---

##  Features

- 📊 Historical stock data visualization (Yahoo Finance API)
- 🧠 Machine learning-based price prediction (Linear Regression)
- 📉 Technical indicators (MA-20, MA-50, RSI)
- ⚠️ Real-time alert system (±2% price change detection)
- 👤 User authentication (Agent / Customer roles)
- 🗄️ Persistent storage using MySQL
- 📊 Interactive PyQt6 dashboard with Matplotlib

---

##  System Architecture

Data Flow:
API → Data Processing → MySQL → Feature Engineering → ML Model → Dashboard UI

---

## Tech Stack

Python • Pandas • scikit-learn • PyQt6 • MySQL • Matplotlib • Git • Jira

---

##  Machine Learning

- Linear Regression (implemented)
- Random Forest (planned)

### Evaluation Metrics:
- MAE
- RMSE
- R² Score

---

##  My Contribution:

- Designed and implemented ML pipeline
- Built feature engineering system (MA, RSI, volume trends)
- Integrated ML predictions into UI dashboard
- Developed system integration across data, ML, and UI layers
- Managed Jira sprint planning and task tracking
- Maintained Git workflow (feature branching + PR reviews)

---

## Agile Development

- Scrum methodology using Jira
- 4 sprint development cycle
- Feature-based branch strategy
- Pull request review workflow

---

## 📷 Screenshots

(Add here)
- Dashboard UI
- Prediction charts
- Jira board
- Login page (agent view):
<img width="510" height="539" alt="Screenshot 2026-05-17 at 6 16 52 PM" src="https://github.com/user-attachments/assets/7d00d5e8-1698-4205-83fd-665dc2c0e60b" />
-Dashboard (agent view):
<img width="1506" height="941" alt="Screenshot 2026-05-17 at 6 19 23 PM" src="https://github.com/user-attachments/assets/e2df2c52-9008-4e55-b097-75d2e67fa994" />


---

## How to Run

```bash
pip install -r requirements.txt
python main.py

# satellite-telemetry-dashboard
Satellite telemetry system with real-time data, API, and testing
# 🚀 Satellite Telemetry Dashboard

This project simulates a satellite telemetry system that sends real-time data such as temperature, battery level, and location. The system includes a backend API, database storage, visualization, and automated testing.

---

## 📌 Features

- 📡 Simulated satellite data (temperature, battery, location)
- 🌐 REST API to receive telemetry data
- 🗄️ MySQL database for storage
- 📊 Grafana dashboard for visualization (planned)
- 🧪 Automated API testing using Pytest

---

## 🛠️ Tech Stack

- Python
- Flask (API)
- MySQL (Database)
- Grafana (Dashboard)
- Pytest (Testing)

---

'''## 📂 Project Structure'''
satellite-telemetry-dashboard/
│── api/ # Backend API
│── simulator/ # Data generator (satellite simulation)
│── tests/ # Automated tests
│── requirements.txt
---

## 🚀 How it Works

1. The simulator generates random satellite data.
2. Data is sent to the Flask API.
3. API stores data in MySQL database.
4. Dashboard (Grafana) visualizes the data.
5. Pytest validates API functionality.

---

## ▶️ How to Run (Step-by-step)

### 1. Install dependencies
pip install -r requirements.txt

### 2. Start API
python api/app.py

### 3. Run simulator
python simulator/simulator.py

### 4. Run tests
pytest -v

---

## 🎯 Project Goal

This project demonstrates real-time system simulation, API development, and automated testing — inspired by space mission telemetry systems.

---

## 👩‍💻 Author

Aleena Shamsudeen  
Automation Tester | Python | API Testing | Aspiring Space Tech Engineer 🚀

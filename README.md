# 🛡️ AI-Powered Smart Honeypot System

A research-oriented project simulating a dynamic Honeypot environment, where AI models classify and detect various types of cyber attacks such as Port Scans, Brute Force, DDoS, and benign traffic — without using real-world malicious traffic.

## 📌 Features

- 🔄 **Synthetic Honeypot Data Generator** — Generates realistic fake logs to mimic attacker and normal behavior.
- 🧠 **AI Model (Random Forest Classifier)** — Learns from honeypot logs and predicts the nature of new activity.
- 📊 **Visualizations** — Scatter plots and Confusion Matrix for analysis.
- 🔒 **Safe Simulation** — No real malware or attackers; purely educational and research-safe.
- ☁️ **Fully runnable in Google Colab.**

## 🔍 Attack Types Simulated
1. **Benign Users:** Normal browsing / server usage.
2. **Port Scanners:** Attackers scanning open ports.
3. **Brute Force Attackers:** Multiple login failures on sensitive services (SSH, FTP).
4. **DDoS Attackers:** Very high payload and fast repeated requests to exhaust server.

## 🚀 Tech Stack
- Python 3
- Google Colab / Jupyter Notebook
- Libraries: NumPy, Pandas, Scikit-Learn, Matplotlib, Seaborn

## 📈 Results
- Achieved **98%+ accuracy** in classifying simulated honeypot logs.
- Clear separation between attack types shown in scatter plots.
- Confusion Matrix for model performance visualization.

## 🔮 Future Scope
- Deploy dynamic honeypot on cloud (AWS/GCP).
- Integration with real-time network monitoring.
- Publish dataset for research.

## 👤 Author
**Divyanshu Dwivedi**  
[GitHub](https://github.com/divyanshpandit) | [LinkedIn](https://www.linkedin.com/in/divyanshpandit/)



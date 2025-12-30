# ATO Risk Profiler

**Real-time Account Takeover (ATO) fraud detection system**  
_Python | ML | Flask API | Executive Dashboard_

[![Python](https://img.shields.io/badge/Python-3.11-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Flask](https://img.shields.io/badge/Flask-3.0-green.svg)](https://flask.palletsprojects.com/)

## 📊 Executive Dashboard

![Dashboard](data/processed/executive_dashboard.png)

**Key Metrics (100K Transactions):**
| Metric | Value |
|--------|-------|
| **Total Transactions** | 100,000 |
| **Fraud Detected** | 3,000 (3.0%) |
| **Risk Patterns** | 4/4 Detected |
| **API Latency** | <50ms |

## 🎯 Features

- **Rule-based Fraud Scoring**: Amount, device, velocity detection
- **Executive Dashboard**: 4 professional visualizations
- **Production Flask API**: Real-time scoring endpoint
- **Interactive Jupyter Demo**: Live transaction testing
- **100K Synthetic Dataset**: Realistic ATO scenarios

## 🛠️ Tech Stack

Python 3.11 | Pandas | Matplotlib | Flask | Jupyter | Scikit-learn

## 📁 Project Structure

ATO-Risk-Profiler/

├── data/

│ ├── simulated_transactions.csv # 100K ATO dataset

│ └── processed/

│ └── executive_dashboard.png # Executive visualization

├── notebooks/

│ ├── 07_executive_dashboard.ipynb # Dashboard generation

│ └── 08_fraud_api.ipynb # Interactive API demo

└── README.md

## 🚀 Quick Start

1. Clone repository

```
git clone https://github.com/santiago-torterolo/ATO-Risk-Profiler.git
cd ATO-Risk-Profiler
```

2. Install dependencies

```
pip install pandas matplotlib flask jupyter ipywidgets
```

3. Launch Jupyter (recommended)

```
jupyter notebook notebooks/
```

## 🔍 Live Demo - Notebook 08

**Interactive fraud scoring widget:**

1. Open `08_fraud_api.ipynb`
2. Execute all cells
3. **Adjust sliders** → **Score Transaction**

**API Endpoints:**

POST /predict
GET / (status)

## 📈 Risk Patterns Detected

1. **High Velocity** (95%) - Multiple transactions/user
2. **Amount Anomaly** (87%) - Statistical outliers
3. **Geo Risk** (76%) - Unusual merchant locations
4. **Device Risk** (82%) - Suspicious device types

## 💼 Business Impact

Fraud Detection Rate: 3.0% (3K/100K transactions)

False Positive Rate: <1%

Real-time Scoring: <50ms latency

Scalability: 1000+ TPS capable

Deployment: Flask API ready

## 👨‍💻 Author

**Santiago Torterolo**  
_Fraud & Risk Analyst | Python | Data Science_  
[LinkedIn](https://linkedin.com/in/santiago-torterolo-5u) | [Portfolio](https://github.com/santiago-torterolo)

## 📄 License

MIT License - Free for commercial use

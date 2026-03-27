# ⚡ AutoML Studio – End-to-End Automated ML Pipeline

> From raw data → insights → best model — fully automated, transparent, and interactive.

![Python](https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python)
![FastAPI](https://img.shields.io/badge/FastAPI-Backend-green?style=for-the-badge&logo=fastapi)
![React](https://img.shields.io/badge/React-Frontend-blue?style=for-the-badge&logo=react)
![ML](https://img.shields.io/badge/Machine%20Learning-Automated-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Production--Ready-success?style=for-the-badge)

---

## 🚀 Overview

**AutoML Studio** is a full-stack machine learning platform that automates the entire ML lifecycle:

- Data ingestion  
- Exploratory Data Analysis (EDA)  
- Data preprocessing  
- Feature engineering  
- Model training & comparison  
- Best model selection  

All within a **single interactive web application**.

📌 Unlike traditional AutoML tools, this system is **transparent, customizable, and runs locally** — giving users full control over data and decisions.

---

## ✨ Key Highlights

- 🔄 End-to-end ML pipeline automation  
- 📊 Interactive EDA dashboard  
- 🧠 Intelligent preprocessing engine  
- 🤖 28 model combinations evaluated automatically  
- 📈 Performance + resource (time & memory) analysis  
- 🧩 Modular architecture (frontend + backend + ML pipeline)  

---

## ⚙️ System Architecture

The system follows a **layered architecture**:

```
Frontend (React UI)
        ↓
API Layer (FastAPI)
        ↓
Processing Layer (ML Pipeline)
        ↓
Data Layer (Datasets + Models)
```

Each layer is modular → easy to scale and extend.

---

## 🔥 Core Features

### 📂 Multi-Format Data Ingestion
- Supports CSV, Excel, JSON, XML, SQL  
- Automatic validation and parsing  
- Converts all data into unified structure (DataFrame)

---

### 📊 Automated EDA
- Dataset shape, types, summary stats  
- Missing value detection  
- Correlation heatmaps  
- Feature distribution analysis  

---

### 🧹 Advanced Preprocessing Engine
- Missing value handling (drop / median / mode)  
- Multicollinearity detection (correlation > 0.85)  
- Categorical encoding (Label / One-hot)  
- Feature scaling  
- Outlier detection (IQR method)

---

### 🧠 Feature Engineering (4 Variants)
The system creates multiple dataset versions:

1. Raw cleaned data  
2. Log transformation + outlier removal  
3. PCA (fixed components)  
4. PCA (variance-based selection)  

👉 Ensures best preprocessing strategy is selected automatically

---

### 🤖 Automated Model Training

Each dataset variant is trained on **7 algorithms**:

- Logistic / Linear Regression  
- Decision Tree  
- Random Forest  
- AdaBoost  
- Gradient Boosting  
- XGBoost  
- CatBoost  

➡️ Total models trained per run: **28**

---

### ⚖️ Model Evaluation & Selection

- Classification Metrics:
  - Accuracy, Precision, Recall, F1-score, ROC-AUC  

- Regression Metrics:
  - R², MAE, MSE  

✔️ Automatically selects best model  
✔️ Displays full comparison matrix  

---

### ⚡ Resource Efficiency Tracking

- Measures:
  - Execution time  
  - Memory usage  

💡 Helps choose models based on **performance vs cost trade-off**

---

### 📈 Interactive Dashboard

- Dataset preview  
- Visual analytics  
- Model comparison charts  
- Training progress tracking  

---

## 🔄 Workflow

```mermaid
flowchart LR
A[Upload Dataset] --> B[EDA Analysis]
B --> C[Preprocessing]
C --> D[Feature Engineering]
D --> E[Train Models]
E --> F[Compare Performance]
F --> G[Select Best Model]
G --> H[Export Results]
```

---

## 🛠️ Tech Stack

### 🔹 Frontend
- React.js  
- Vite  
- Recharts  
- Axios  

### 🔹 Backend
- FastAPI  
- Uvicorn  

### 🔹 ML & Data
- Python  
- Pandas, NumPy  
- Scikit-learn  
- XGBoost, CatBoost  
- Matplotlib, Seaborn  

---

## 🧪 Performance Insights

- Total models trained per run: **28**
- Avg execution time: **15–25 seconds (500–1000 rows)**
- Best efficiency: Logistic Regression (low resource)
- Best performance balance: XGBoost

---

## 🎯 Use Cases

- 📚 Students learning ML workflows  
- 📊 Data analysts exploring datasets  
- ⚡ Rapid ML prototyping  
- 🧠 Automated baseline model building  

---

## ▶️ Getting Started

```bash
git clone https://github.com/your-username/automl-studio.git
cd automl-studio
pip install -r requirements.txt
uvicorn main:app --reload
```

Frontend:
```bash
cd frontend
npm install
npm run dev
```

---

## 🚀 Future Enhancements

- Hyperparameter optimization (Auto tuning)  
- Deep learning integration  
- Cloud deployment (AWS/GCP)  
- Real-time streaming data support  
- Multi-user collaboration  

---

## 💬 Final Thoughts

This project focuses on:
- ⚡ Speed  
- 🧠 Automation  
- 🔍 Transparency  

Making machine learning **accessible, efficient, and practical** for real-world use.

---

⭐ If you like this project, consider starring the repo!

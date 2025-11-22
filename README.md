# Anomaly-Detection-in-IoT-Sensor-Data
This project identifies unusual or abnormal patterns in IoT sensor readings using machine learning techniques. It helps detect faults, failures, intrusions, and unexpected behavior in real-time sensor environments.
# 📡 Anomaly Detection in IoT Sensor Data

This project focuses on detecting abnormal or unexpected patterns in IoT sensor data using machine learning techniques. IoT systems generate continuous data streams, and identifying anomalies helps prevent equipment failures, detect cyber intrusions, and improve monitoring efficiency. The project implements data preprocessing, feature extraction, model training, and evaluation to accurately detect sensor anomalies.

---

## 📂 Dataset Used
- IoT sensor dataset containing:
  - Timestamp
  - Multiple sensor readings (temperature, voltage, current, pressure, humidity, etc.)
  - Normal vs abnormal patterns

*(If using your own CSV, replace above with actual column names.)*

---

## 🚀 Techniques & ML Concepts Covered

### **1. Data Preprocessing**
- Handling missing values  
- Smoothing noisy signals  
- Normalization / Standardization  

### **2. Feature Engineering**
- Rolling window features  
- Statistical features (mean, variance, skewness)  
- Trend and pattern extraction  

### **3. Machine Learning Models for Anomaly Detection**
- Isolation Forest  
- One-Class SVM  
- Autoencoders (optional if deep learning used)  
- LOF (Local Outlier Factor)  

### **4. Model Selection**
- Comparing traditional ML vs isolation/one-class models  
- Choosing the best model for time-series sensor data  

### **5. Visualization**
- Line plots of sensor readings  
- Highlighting anomaly points  
- Distribution plots of normal vs abnormal values  

---

## 🛠️ Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  
- TensorFlow / Keras (optional for autoencoders)

---

## ⚙️ Project Workflow
1. Load IoT sensor dataset  
2. Data cleaning and normalization  
3. Exploratory Data Analysis (EDA)  
4. Feature engineering  
5. Train anomaly detection models  
6. Evaluate results  
7. Visualize anomaly points on sensor graphs  

---

## 📊 Evaluation Metrics
- Precision (how many detected anomalies are true)  
- Recall (how many true anomalies were found)  
- F1-Score  
- ROC-AUC (if applicable)  

---

## 📁 Project Structure
IoT-Anomaly-Detection/
│-- sensor_data.csv
│-- anomaly_detection.ipynb
│-- README.md
└── models/

---

## 🎯 Outcome
- Successfully detects abnormal behavior in IoT sensor readings  
- Helps prevent device failures and identify intrusions earlier  
- Shows complete end-to-end ML pipeline for anomaly detection  

---

## 🚀 Future Enhancements
- Real-time anomaly detection using streaming data  
- Deploy using Flask / FastAPI  
- Add LSTM-based deep learning for time-series anomalies  
- Integrate with an IoT dashboard  

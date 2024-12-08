# 🌐 **Network Performance Analysis**

## ⭐ **Overview**  
**Network Performance Analysis** is an integrated **Data Science** and **Cybersecurity** project designed to monitor, analyze, and predict key network metrics. This solution provides:  
- 📊 **Real-Time Data Visualization**  
- 🤖 **Predictive Modeling**  
- 🚨 **Anomaly Detection**  

It features a **user-friendly dashboard** for tracking metrics like **latency**, **jitter**, and **bandwidth**, while identifying issues such as **DDoS attacks** or degraded network states.  

---  

## ✨ **Key Features**  

- **🎥 Real-Time Packet Capture**  
  Captures live network packets using **Wireshark** to extract key metrics.  

- **🛠️ Preprocessing and Storage**  
  Data is preprocessed, converted into **CSV**, and stored in **InfluxDB**, a time-series database.  

- **📈 Visualization Dashboard**  
  Metrics are displayed dynamically in **Grafana** and a custom **Flask** web app for an interactive experience.  

- **🤖 Machine Learning Models**  
  - **LSTM**: Predicts average latency trends.  
  - **One-Class SVM**: Detects potential **DDoS attacks**.  
  - **Isolation Forest**: Classifies network states as **Normal**, **Warning**, or **Critical**.  

- **🧑‍💻 User Interaction**  
  - Start/stop live packet capturing.  
  - Export data as **CSV** for further analysis.  
  - Pre-captured data for model predictions.  

---  

## 🛠️ **Technical Workflow**  

### 📥 **Data Collection**  
Live packets are captured using **Wireshark** and stored in **CSV format**.  

### ✨ **Data Processing**  
Preprocessing extracts essential metrics, resolves outliers, and fills missing values.  

### 📂 **Data Storage**  
**InfluxDB** stores data for real-time querying and visualization.  

### 📊 **Visualization**  
Metrics like **latency**, **jitter**, and **bandwidth** are dynamically visualized in **Grafana** and a **Flask web app**.  

### 🤖 **Machine Learning Integration**  
- **LSTM**: Predicts average latency trends.  
- **One-Class SVM**: Detects anomalies and **DDoS attack patterns**.  
- **Isolation Forest**: Classifies network states.  

### 📤 **Output**  
- Real-time metric visualizations.  
- Downloadable **CSV reports**.  
- Predictions for network anomalies.  

---  

## 🏗️ **System Architecture**  
- **Data Collection Layer**: **Wireshark** captures raw packets.  
- **Processing Layer**: Python processes and parses data.  
- **Storage Layer**: **InfluxDB** stores real-time metrics.  
- **Visualization Layer**: **Grafana** and Flask render dashboards.  
- **Prediction Layer**: Machine learning models forecast trends and detect anomalies.  

---  

## 🚀 **Setup Instructions**  

### **Prerequisites**  
- Python 3.8 or above  
- Wireshark (for packet capture)  
- InfluxDB  
- Grafana  
- Flask 

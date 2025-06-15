# 🏭 Factory Anomaly Detection System

An end-to-end machine learning system for real-time anomaly detection on factory sensor data (temperature, humidity, sound).  
This project includes:  
- Data analysis & model development (Jupyter Notebooks)
- Model packaging
- REST API deployment using Flask + AWS Elastic Beanstalk

---

## 🔧 Tech Stack

- Python 3.12
- scikit-learn
- pandas, numpy
- Flask
- AWS Elastic Beanstalk
- Docker 

---

## 📊 Problem Description

In modern factories producing wind turbine components, early detection of abnormal sensor readings can prevent costly breakdowns and defective products.

This system monitors 3 key sensors:
- Temperature
- Humidity
- Sound Level

Using an unsupervised machine learning model, the system detects anomalies in real-time based on incoming sensor data.

---

## 🧪 Model Testing
The system is fully deployed online and can be tested by running the code from test.ipynb notebook.

Simply change the temperature, humidity, and sound volume variables inside the notebook and re-run the prediction cell.

---

## 📂 Project Structure

```bash
├── anomalies_detection.ipynb       # Jupyter Notebook For Data Collection, Model Training and Evaluation
├── test.ipynb                      # Testing notebook
├── sensor_data.xls                 # Training dataset
├── anomaly_detection.zip           # Deployment package (Flask API + Model)
├── Dockerfile (if used locally)    # Docker container file
└── README.md                       # Project documentation

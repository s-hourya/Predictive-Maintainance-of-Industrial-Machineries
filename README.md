# Predictive-Maintainance-of-Industrial-Machineries
(IBM Cloud Integrated)

##  Project Overview
This project predicts machinery failures before they occur using IoT sensor data, machine learning, and IBM Cloud services.  
It helps reduce downtime, optimize maintenance schedules, and cut costs.

## Data Availability
Please note that sample or real sensor data files are not included in this repository due to size and privacy considerations. To run the project successfully, you will need to provide your own datasets in the `data/` folder in CSV format, structured according to the expected schema (e.g., timestamps, sensor readings, failure labels). You can collect data from your own industrial machinery sensors or use publicly available datasets for testing and experimentation.


##  Features
- Real-time sensor data collection (vibration, temperature, acoustic)
- Data preprocessing and feature extraction
- Machine learning models (Random Forest, LSTM, Gradient Boosting)
- IBM Watson Machine Learning deployment
- Real-time dashboard for anomaly alerts

##  Technologies Used
- Python, Pandas, NumPy, Scikit-learn, TensorFlow
- IBM Cloud, Watson Machine Learning, IBM IoT Platform
- Flask/Dash for dashboard
- MySQL / IBM Db2 on Cloud for storage

## Project Structure
Refer to the repository folder structure for details.

##  Installation
```bash
git clone https://github.com/s-hourya/predictive-maintenance.git
cd predictive-maintenance
pip install -r requirements.txt

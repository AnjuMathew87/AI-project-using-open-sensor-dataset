Predictive Maintenance Using Open Industrial Sensor Data
Continuation of my Master Thesis in Industrial Predictive Analytics.

Project Overview
This project focuses on building predictive maintenance models using open industrial datasets. It aims to detect early equipment degradation, predict failures, and support data-driven maintenance decisions.

Problem Statement
Industrial machines generate large volumes of sensor data. Unexpected failures cause downtime and high maintenance costs. This project builds ML and deep-learning models to predict failures before they occur.

 Datasets Used
- NASA C-MAPSS (Turbofan engine RUL)
- UCI Bearing Dataset
- PRONOSTIA Bearing Dataset

 Methods & Models
- Data preprocessing & feature engineering (time + frequency domain)
- Machine learning: Random Forest, XGBoost
- Deep learning: LSTM, GRU, Autoencoders, 1D CNN
- Evaluation metrics: RMSE, F1-score, precision/recall

Tools & Technologies
Python, Pandas, NumPy, Scikit-learn, TensorFlow/Keras, Matplotlib, Jupyter Notebook

 Key Features
- End-to-end predictive maintenance pipeline
- Multi-dataset benchmarking
- Hybrid ML + DL modeling
- Interpretability and maintenance insights
- Modular, reusable framework

Use Cases
- Manufacturing (motors, pumps, bearings)
- Energy & power systems (transformers, turbines)
- Industrial IoT & smart factories
- Transportation (engines, heavy machinery)
- Oil & gas / chemical plants

Results (Current Progress)
- LSTM models show strong performance in predicting degradation trends
- Autoencoders detect early anomalies
- Feature engineering improves accuracy significantly

 Project Structure
project/
│── data/
│── notebooks/
│── src/
│   ├── preprocessing.py
│   ├── feature_engineering.py
│   ├── models.py
│   └── evaluation.py
│── README.md
│── requirements.txt


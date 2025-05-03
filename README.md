
🛡️ DDoS Attack Detection and Prediction Using Machine Learning
This project focuses on detecting and predicting Distributed Denial of Service (DDoS) attacks using machine learning techniques. Built and evaluated in Google Colab, the system leverages powerful ML algorithms to analyze network traffic and identify malicious activity in real time.

🎯 Objective
To develop an intelligent model that can:

Accurately detect DDoS attacks in network traffic

Predict potential threats based on historical data patterns

Enhance cybersecurity defenses using machine learning

🧠 Algorithms Used
Random Forest

XGBoost

LSTM (Long Short-Term Memory)

Weighted Ensemble Model for improved performance

📊 Final Results
Accuracy: 99.76%

Precision: 98.02%

Recall: 99.60%

F1-Score: 98.80%

Model Weights: RF = 0.433, XGBoost = 0.439, LSTM = 0.128

🛠️ Tech Stack
Python (Pandas, NumPy, Scikit-learn, XGBoost, TensorFlow/Keras)

Google Colab (for development and testing)

Matplotlib & Seaborn (for visualization)

📂 Dataset
The dataset contains network traffic features including:

Destination Port

Label (indicating whether traffic is normal or an attack)

Other relevant features like Flow Duration, Total Fwd Packets, etc.

🚀 How to Run
Open the Colab notebook: [Link to your notebook]

Upload the dataset

Run all cells to preprocess data, train models, and evaluate performance

📌 Key Highlights
Data preprocessing with feature selection and normalization

Ensemble learning approach combining multiple models

Performance evaluation using standard classification metrics

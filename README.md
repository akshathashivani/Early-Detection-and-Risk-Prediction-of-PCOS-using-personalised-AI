# Early-Detection-and-Risk-Prediction-of-PCOS-using-personalised-AI
🩺 Overview
This project implements an AI-powered Clinical Decision Support System for early detection and risk assessment of Polycystic Ovary Syndrome (PCOS). The system uses machine learning models to analyze clinical and lifestyle factors, providing explainable predictions to assist healthcare professionals in diagnosis and treatment planning. The methodology incorporates Federated Learning techniques to ensure privacy-preserving model training across distributed data sources.

🎯 Features
Risk Prediction: Real-time PCOS risk assessment based on clinical parameters
Explainable AI: LIME-based explanations for model predictions
Interactive Web Interface: User-friendly Streamlit application
Privacy-Aware Federated Learning: FedAvg implementation for distributed, privacy-preserving model training
Comprehensive Analysis: Considers multiple physiological and lifestyle factors
📊 Datasets
Training Dataset: PCOS_data_without_infertility.csv - Clinical data for model training
Testing Dataset: Real_Time_Testing.csv - Lifestyle survey data for validation
🤖 Model
Algorithm: K-Nearest Neighbors (KNN)
Features: Standardized clinical parameters
Performance: Optimized for accuracy and interpretability
🛠️ Technologies Used
Frontend: Streamlit
Backend: Python
ML Libraries: scikit-learn, joblib, LIME, XGBoost
Federated Learning: Flower (FedAvg implementation)
Data Processing: pandas, numpy
Visualization: matplotlib, seaborn
📋 Prerequisites
Python 3.8+
Virtual environment (recommended)
🚀 Installation
Clone the repository (if applicable) or navigate to the project directory.

Create and activate virtual environment:

python -m venv pcos_env
pcos_env\Scripts\activate  # On Windows
Install dependencies:

pip install -r requirements.txt
▶️ Usage
Run the application:

streamlit run app.py
Access the web interface at http://localhost:8501

Navigate through pages:

Home: Overview of PCOS and project objectives
PCOS Risk Prediction: Input patient data and get predictions with explanations
Screenshots
Home Page


<img width="860" height="509" alt="Screenshot 2026-11-07 at 5 06 45 PM" src="https://github.com/user-attachments/assets/ddb27fc7-e140-4949-a91e-e5a54f743b94" />


Prediction Page



<img width="873" height="505" alt="Screenshot 2026-11-07 at 5 07 24 PM" src="https://github.com/user-attachments/assets/c45730e9-c760-4ca4-ac79-6ae9804b9a6d" />


Explainability Results



<img width="879" height="585" alt="Screenshot 2026-11-07 at 5 08 05 PM" src="https://github.com/user-attachments/assets/55a2e5c2-500b-45db-b340-6ea089d291da" />



📈 Methodology
The system follows a comprehensive approach:

Data Collection: Integration of clinical and lifestyle datasets
Preprocessing: Feature engineering and standardization
Model Training: Comparison of multiple ML algorithms (Logistic Regression, Random Forest, XGBoost, KNN)
Federated Learning: Implementation of FedAvg for privacy-preserving distributed training
Model Selection: KNN selected for optimal performance
Explainability: LIME implementation for prediction transparency
Deployment: Streamlit web application
🤝 Contributing
This is a final implementation project. For modifications or extensions, please ensure:

Maintain code quality and documentation
Test changes thoroughly
Update dependencies if needed
📄 License
This project is for educational and research purposes.

👥 Authors
Developed as part of 7th Semester Final Implementation by:

C Akshatha Shivani,
Kruthika,
Sarojini Vaishnavi Peri,
G Santosh Kumar

Focus: PCOS Risk Analysis and Early Detection using AI

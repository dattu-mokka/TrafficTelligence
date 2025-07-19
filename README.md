🚦 TrafficTelligence: Advanced Traffic Volume Estimation with Machine Learning
TrafficTelligence is a machine learning-based web application that predicts traffic volume using environmental and temporal data. By leveraging historical patterns, it provides accurate traffic forecasts to support smart traffic control, urban planning, and commuter decision-making.

📌 Problem Statement
Traffic congestion is a pressing issue in urban areas. There is a growing need for predictive systems that can anticipate traffic volume and support:

Dynamic traffic signal management
Infrastructure development planning
Smarter commuter navigation
🎯 Project Objectives
Analyze traffic datasets and identify key influencing features
Train and evaluate machine learning models to estimate traffic volume
Build a web-based interface for real-time traffic volume prediction
📊 Dataset Overview
The dataset includes features like:

Holiday: Whether the day is a holiday (1 = Yes, 0 = No)
Temperature (°C)
Rain (mm)
Snow (mm)
Date & Time (used to extract Year, Month, Day, Hour)
Target: Traffic_volume (number of vehicles)
🧠 Machine Learning
🔍 Features
Numerical and categorical preprocessing
Feature scaling using StandardScaler
Missing value imputation with SimpleImputer
🛠️ Models Used
Random Forest Regressor
XGBoost Regressor
📈 Evaluation Metrics
Model	R² Score	RMSE
Random Forest	0.8489	772.73
XGBoost	0.8433	787.06
✅ Random Forest was selected for deployment due to higher R² and lower RMSE.

💻 Tech Stack
Frontend: HTML5, CSS3
Backend: Python, Flask
Libraries: pandas, numpy, scikit-learn, xgboost, matplotlib, seaborn
Deployment: Localhost using Flask
IDE: Anaconda / VS Code
🗂️ Project Structure
TrafficTelligence/
│
├── Project Files/
│   ├── app.py
│   ├── model_training.py
│   ├── traffic_data.csv
│   ├── model.pkl ❗
│   ├── scaler.pkl
│   ├── templates/
│       ├── index.html
│
├── Document/
│   └── TrafficTelligence_Documentation.pdf
│
├── Video Demo/
│   └── traffic_demo.mp4
│
├── TrafficTelligence_banner.png
│
└── README.md
🚀 How to Run This Project
🔧 Install Dependencies
pip install -r requirements.txt
🧠 Train the Model
python model_training.py
🌐 Run Web App
python app.py
Visit http://127.0.0.1:5000 to access the app.

📥 Download Pre-trained Model
Note: GitHub limits file size to 100MB.
Download the trained model (model.pkl) from:

📦 Download model.pkl (Google Drive)

📽️ Demo
🎥 Video Preview:
A short demonstration is available in the "Video Demo" folder.

📄 License
This project is developed for academic and professional learning purposes.
Reuse is permitted with credit.

🙌 Acknowledgments
Dataset sources: Kaggle, UCI Machine Learning Repository
Flask & Scikit-learn communities
Inspiration from real-world traffic intelligence systems
🚗 TrafficTelligence helps pave the way for smarter, congestion-free cities.

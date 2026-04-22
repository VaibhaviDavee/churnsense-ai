ChurnSense AI — ML-Powered Customer Churn Prediction & Retention Platform

ChurnSense AI is a machine learning–driven web application that predicts customer churn, segments users by risk level, and provides actionable insights to improve customer retention strategies in the telecom domain.

📌 Overview

Customer churn is a major challenge in the telecom industry. This project uses Machine Learning to:

Predict whether a customer is likely to churn
Estimate churn probability
Segment customers into risk levels
Provide business insights for retention strategies

🖥️ Features

🔮 Predict Customer

Input individual customer details
Get real-time churn probability
Gauge chart visualization
Output:
✅ Likely to Stay
⚠ High Churn Risk

📂 Bulk Prediction

Upload CSV file with multiple customers
Get predictions and probabilities for all records
Risk segmentation:
Low Risk
Medium Risk
High Risk
Visualizations:
Churn probability distribution
Risk segmentation pie chart

📊 Churn Analytics

Churn rate by:
Contract type
Internet service type
Helps identify high-risk segments
🤖 Model Intelligence
Top 15 features influencing churn
Most important churn driver insight
Model summary:
Algorithm: Random Forest

📊 Dataset

The model is trained on a telecom dataset containing:

Customer demographics
Service usage details
Billing information

🎯 Target Variable:

Churn (Yes / No)

🛠️ Tech Stack

Machine Learning: Random Forest Classifier
Data Processing: pandas, NumPy
Modeling: scikit-learn
Visualization: Plotly
Web App: Streamlit
Model Storage: Pickle

⚙️ Setup & Installation

1️⃣ Clone the Repository
git clone https://github.com/your-username/churnsense-ai.git
cd churnsense-ai

2️⃣ Create Virtual Environment (Recommended)
Windows:
python -m venv venv
venv\Scripts\activate
macOS/Linux:
python3 -m venv venv
source venv/bin/activate

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Train the Model
python train_model.py
✔ This will:
Clean and preprocess data
Encode categorical features
Scale data using StandardScaler
Train Random Forest model
Save model files (.pkl)

5️⃣ Run the Application
streamlit run app.py

📍 Open in browser:

http://localhost:8501

📂 Project Structure
ChurnSense-AI/
│
├── Data/
│   └── Churn.csv
│
├── Saved_Model/
│   ├── churn_model.pkl
│   ├── feature_columns.pkl
│   └── standard_scaler.pkl
│
├── app.py
├── train_model.py
├── requirements.txt
└── README.md

🎯 Project Objective

To build an end-to-end ML system that:
Predicts churn accurately
Identifies high-risk customers
Supports data-driven decision making

🧠 Key Highlights

End-to-end ML pipeline
Real-time + bulk prediction
Interactive dashboards
Business-focused insights

📈 Future Improvements

Add advanced models (XGBoost, LightGBM)
Improve evaluation (F1-score, ROC-AUC)
Deploy on cloud (AWS / Streamlit Cloud)
Integrate database support

👤 Author

Vaibhavi Dave

⭐ Support

If you found this useful, consider giving a ⭐ on GitHub!
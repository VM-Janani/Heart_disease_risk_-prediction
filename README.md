# Heart_disease_risk_-prediction
💓 Heart Disease Risk Prediction & Lifestyle Recommendation System
A web-based machine learning application that predicts heart disease risk using the Framingham dataset, explains the contributing features using SHAP (Explainable AI), and provides personalized lifestyle and dietary recommendations based on key health risk factors.

🛠️ Technologies Used
Python 3.10+

Pandas, NumPy, Scikit-learn – Data processing

XGBoost – Heart disease risk prediction

SHAP – Feature explainability

Streamlit – Web application framework

Matplotlib, Seaborn – Visualizations

📁 Dataset Description
Source: Framingham Heart Study dataset

Features: Age, cholesterol levels, BMI, blood pressure, smoking status, diabetes, etc.

Target Variable: TenYearCHD (1: High risk, 0: Low risk)

**System Architecture

images/system architecture.png

💻 Installation & Setup
bash
Copy
Edit
# 1. Clone the repo
git clone https://github.com/your-username/heart-disease-prediction.git
cd heart-disease-prediction

# 2. Create a virtual environment and activate it
python -m venv venv
source venv/bin/activate    # On Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the Streamlit app
streamlit run app.py
🧾 How to Use
Home Page – Learn about heart disease, machine learning, and the recommendation engine.

Risk Prediction – Enter patient health information to calculate the 10-year heart disease risk score.

Feature Explainability – Visualize SHAP values to understand which features impact the prediction.

Lifestyle Recommendation – Based on significant health indicators, receive suggestions on food and exercise.

🧠 Model Details
Model Used: XGBoost Classifier

Preprocessing: Missing value imputation, feature selection (ANOVA), normalization

Class Imbalance Handling: SMOTE

Evaluation Metrics: Accuracy, Precision, Recall, F1-Score, ROC AUC

Explainability: SHAP summary plot and force plot for feature contribution

📈 Results
Metric	Value
Accuracy	88.3%
ROC AUC	0.95
Precision	92
Recall	High 85
F1-Score	High 88

🖼️ Result Screenshots
recommendation results

images/recommedation 2.png 

images/recommedation 1.png

images/recommedation.png

prediction results

images/high risk.png 

images/low risk.png



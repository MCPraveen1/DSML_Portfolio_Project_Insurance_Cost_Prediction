# DSML_Portfolio_Project_Insurance_Cost_Prediction
Insurance Cost Prediction App  This project predicts medical insurance costs using Machine Learning and demonstrates EDA, visualization, and deployment through multiple tools:

1. EDA with Python (Pandas, Matplotlib, Seaborn).
2. Visualization with Tableau.
3. Interactive Web Apps using Streamlit &amp; Flask.


# Insurance Cost Prediction App

## Project Overview
This project predicts **medical insurance costs** based on patient attributes using **Machine Learning**.  
The workflow includes **Exploratory Data Analysis (EDA)**, **model training**, and **deployment using Streamlit and Flask**.  
Interactive dashboards are created in **Tableau** for insights.

---

## Key Features
- **EDA with Python**
  - Data cleaning, handling missing values, and outlier detection
  - Visualizations using **Matplotlib** & **Seaborn**
  - Correlation and feature importance analysis

- **Machine Learning**
  - Tuned **Random Forest Regressor**
  - Model saved with **Joblib**

- **Deployment**
  - **Streamlit App** for an interactive UI
  - **Flask App** with **Bootstrap-based HTML templates**

- **Visualization Dashboard**
  - **Tableau** dashboards for interactive analytics

---

## Project Structure
Insurance_app/
│
├── Insurance_app_flask/ # Flask App
│ ├── templates/
│ │ ├── index.html # HTML UI
│ ├── static/ # CSS/JS (optional)
│ ├── app.py # Flask main script
│ ├── insurance_model.pkl # Trained ML model
│ └── requirements.txt # Dependencies
│
├── Insurance_app_streamlit/
│ ├── app.py # Streamlit app
│ ├── insurance_model.pkl
│
├── notebooks/
│ └── insurance_cost_analysis.ipynb # EDA and ML modeling
│
├── tableau_dashboard/
│ └── dashboard.twbx # Tableau workbook
│
└── README.md


---

## Tech Stack
- **Python 3.10**
- **Pandas, NumPy, Matplotlib, Seaborn**
- **Scikit-learn (v1.2.2)**
- **Streamlit (v1.25)**
- **Flask**
- **Tableau**

---

## How to Run Locally

### Clone the Repository
```bash
git clone https://github.com/yourusername/insurance-cost-prediction.git
cd insurance-cost-prediction

# Create Virtual Environment
python -m venv insurance_venv
.\insurance_venv\Scripts\activate

# Install Dependencies
pip install -r requirements.txt

# Run Streamlit App
cd Insurance_app_streamlit
streamlit run app.py


Access: http://localhost:8501

# Run Flask App
cd Insurance_app_flask
flask run


Access: http://127.0.0.1:5000

# Tableau Dashboard

The Tableau dashboard includes:

Insurance cost distribution

Correlation between risk factors & premium

Region-wise analysis

Screenshots

Add Streamlit UI screenshot here
Add Flask UI screenshot here
Add Tableau dashboard screenshot here

# Future Enhancements

Deploy on Heroku / Render

Add REST API endpoints

Enhance UI with Bootstrap / Tailwind

# Author
# Praveen MC

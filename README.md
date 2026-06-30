# AI-Powered Customer Churn Prediction & Retention Platform (ChurnShield)

## Overview

ChurnShield is an AI-powered customer churn analysis and retention platform designed for telecom businesses. The project combines data analysis, SQL-driven business insights, and AI-generated customer retention strategies to identify high-risk customers and reduce churn.

The system analyzes customer behavior patterns, detects churn drivers, estimates risk levels, and generates personalized retention recommendations using AI.

---

## Features

* Customer churn analysis using telecom customer data
* Exploratory Data Analysis (EDA)
* Data cleaning and preprocessing
* Missing value handling and duplicate removal
* Business KPI analysis using SQL
* Churn segmentation by customer behavior
* Revenue-at-risk analysis
* High-risk customer identification
* AI-generated personalized retention strategies
* SQLite database integration
* Excel report export functionality
* Data visualization dashboards

---

## Project Workflow

1. Load telecom customer dataset
2. Perform data exploration and preprocessing
3. Analyze churn distribution
4. Visualize important churn drivers
5. Store processed data in SQLite
6. Run SQL business intelligence queries
7. Identify high-risk customers
8. Generate AI-based retention strategies
9. Export results into reports

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SQLite
* OpenAI API / Groq API
* OpenPyXL
* ReportLab

---

## Dataset Information

The project uses a telecom customer dataset containing features such as:

* CustomerID
* Tenure
* Contract Type
* Internet Service
* Monthly Charges
* Total Charges
* Payment Method
* Tech Support
* Senior Citizen
* Churn Status

Target variable:

**Churn**

* Yes → Customer left
* No → Customer retained

---

## Business Questions Solved

The project answers several business-critical questions:

### Customer KPIs

* Total customers
* Churn rate
* Average monthly charges
* Revenue metrics

### Churn Drivers

* Contract type impact
* Internet service impact
* Customer tenure analysis
* Payment method influence

### Revenue Risk Analysis

* Revenue exposed due to churn
* Customer segmentation by risk

### High-Risk Customer Detection

Identification of customers with characteristics such as:

* Month-to-month contracts
* Fiber optic services
* Low tenure
* Electronic payment methods
* Missing technical support

---

## AI Retention Engine

The platform uses an AI agent to generate customized retention strategies for high-risk customers.

Examples:

* Personalized discount recommendations
* Contract upgrade suggestions
* Loyalty rewards
* Technical support improvements
* Service bundle offers

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/churnshield.git
```

Move into project directory:

```bash
cd churnshield
```

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn sqlite3 openai openpyxl reportlab
```

---

## Run Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```bash
AI-Powered Customer Churn Prediction & Retention Platform.ipynb
```

---

## Project Structure

```text
ChurnShield/
│
├── data/
│   └── telecom_churn.csv
│
├── notebooks/
│   └── AI-Powered Customer Churn Prediction & Retention Platform.ipynb
│
├── outputs/
│   ├── ai_retention_strategies.xlsx
│   └── churnshield.db
│
├── images/
│   └── dashboard.png
│
├── README.md
└── requirements.txt
```

---

## Future Improvements

* Train machine learning models for churn prediction
* Add XGBoost and Random Forest models
* Build Streamlit dashboard
* Deploy using Docker
* Integrate real-time customer monitoring
* Add automated email campaign recommendations

---

## Results

The platform provides:

* Customer churn insights
* Business KPIs
* Revenue risk estimates
* AI-generated retention recommendations
* Actionable business decisions

---

## Author

Pravalika Annem

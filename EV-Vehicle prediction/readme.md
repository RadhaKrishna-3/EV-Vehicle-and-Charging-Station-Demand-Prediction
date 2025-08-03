EV Adoption & Charging Demand Forecasting
 A Real-Time Machine Learning Project | AICTE Edunet 2025
From raw data to future insights — predicting the rise of electric vehicles across Washington State.

📘 Table of Contents
 Project Inspiration

📊 Problem Statement

🎯 Project Objectives

🧠 Machine Learning Workflow

🔧 Tech Stack

📁 Folder Structure

🚀 How to Run This Project

📈 Key Results & Visuals

📚 Learnings

💬 Contact

🌟 Project Inspiration
Electric vehicles (EVs) are the future — eco-friendly, efficient, and rapidly adopted worldwide. But to support their rise, charging infrastructure needs to be planned ahead of time.

In this AICTE-Edunet project, I built a complete machine learning pipeline to analyze historical EV registration data from Washington State (USA) and predict future EV adoption rates — a stepping stone to planning charging demand.

This project helped me learn:

Data cleaning from real government data

Time series forecasting and regression

Building and deploying ML models

📊 Problem Statement
“How can we use historical vehicle registration data to forecast the number and percentage of EVs in the future?”

By predicting EV trends, we can:

Estimate charging station requirements

Guide policy and urban planning

Understand regional adoption patterns

🎯 Project Objectives
✅ Clean and preprocess real-world data
✅ Analyze EV adoption trends across cities
✅ Handle outliers and missing values
✅ Train multiple machine learning regression models
✅ Evaluate model performance
✅ Forecast future EV usage
✅ Visualize trends using Streamlit

🧠 Machine Learning Workflow
Data Collection
→ Used public data from Washington State Department of Licensing (2017–2024)

Exploratory Data Analysis (EDA)
→ Uncovered trends, regional patterns, and growth rates in EV adoption

Data Cleaning

Handled missing values

Removed/capped outliers in Percent Electric Vehicles using IQR

Feature Engineering

Converted dates

Grouped by city and time

Added Total Vehicles, Electric Vehicles, Percent EV

Model Building

Trained Linear Regression, Decision Tree, Random Forest models

Compared using MAE, MSE, R² Score

Forecasting & Visualization

Used the best-performing model

Deployed predictions on a Streamlit web app

🔧 Tech Stack
Tool	|  Purpose
Python	|Core programming
Pandas & Numpy|	Data handling
Matplotlib & Seaborn	 | Data visualization
Scikit-learn	  |  Machine learning
Streamlit  |	Web app deployment
Joblib	|  Model saving/loading
google colab 	|  Development

📁 Folder Structure
📦 EV_Adoption_Forecasting
├── 📊 EV_Adoption_Forecasting.ipynb       # Full ML project code
├── 📁 data/                               # Raw & processed data files
├── 🧠 models/
│   ├── rf_model.pkl                       # Trained Random Forest model
├── 🌐 app.py                              # Streamlit Web App Code
├── 📄 requirements.txt                    # Required libraries
└── 📘 README.md                           # Project documentation
🚀 How to Run This Project
Clone this Repository
git clone https://github.com/yourusername/EV_Adoption_Forecasting.git
cd EV_Adoption_Forecasting
Install Required Libraries
pip install -r requirements.txt


Run the Streamlit App
streamlit run app.py
📈 Key Results & Visuals
✅ Highest EV adoption cities
✅ Forecasted Percent EV growth till 2027
✅ Visualized charging demand trends
✅ Outlier-corrected, clean predictions

Sample chart:

matlab
Copy
Edit
City       | Year | Predicted % EV
-----------|------|----------------
Seattle    | 2025 | 9.8%
Redmond    | 2025 | 13.4%
Spokane    | 2025 | 7.2%
📚 Learnings
Real-world datasets are messy and unpredictable

Outlier handling using IQR is crucial before modeling

Each model has its strengths:

Random Forest performed better here

Streamlit makes quick ML deployment easy

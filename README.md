📌 Global Terrorism Data Analysis

🌍 Project Overview

This project analyzes global terrorism trends using machine learning and data visualization. By exploring historical attack patterns, regions affected, and attack methodologies, we aim to derive actionable insights into global terrorism activities.

📊 Dataset Description

**Dataset:** terrorism_dataset.csv & cleaned_terrorism_data.csv

This dataset contains detailed records of global terrorist incidents, including:

**Date & Location**: Country, city, and region of attacks.
**Attack Characteristics:** Attack type, weapons used, and target type.
**Casualties & Damage:** Number of fatalities, injuries, and property loss.
**Terrorist Groups:** Identification of responsible organizations.
**Additional Factors:** Ransom demands, hostages, and other influencing variables.

🎯 Project Objectives

Analyze global terrorism trends over time and identify high-risk regions.
Visualize attack patterns by geographical location and attack type.
Identify common characteristics of terrorist incidents.
Build predictive models to classify future terrorism risks.
Use interactive dashboards (Tableau) for storytelling with data.

**🔍 Methodology**

1️⃣ **Data Cleaning & Preprocessing**

Removed irrelevant or duplicate data.
Handled missing values in key attributes.
Standardized categorical data and encoded necessary variables.

2️⃣ **Exploratory Data Analysis (EDA)**

Trend Analysis: Terrorist incidents over time.
Geospatial Mapping: Attack locations visualized.
Casualty Analysis: Fatalities and injuries distribution.
Terrorist Group Impact: Identified most active groups.

3️⃣ **Machine Learning Modeling**

Classification Models: Random Forest, XGBoost, Logistic Regression.
Clustering Techniques: K-Means for pattern recognition.
Predictive Analysis: Risk profiling based on past incidents.

4️⃣ **Data Visualization & Storytelling**

Interactive Tableau Dashboards for insights.
Geospatial heatmaps for affected areas.

📌 **Key Findings**

The Middle East & South Asia are the most affected regions.
Bombings & armed assaults are the most common attack types.
Specific terrorist groups dominate different regions.


A rise in attacks is observed in certain time periods, linked to global conflicts.


**🛠️ How to Run the Project**

Clone the repository:

git clone https://github.com/naitiknayak196/storytelling-by-tableau-terrorism-dataset.git
cd storytelling-by-tableau-terrorism-dataset

**Install dependencies:**

pip install -r requirements.txt

Run Jupyter Notebook for analysis:

jupyter notebook "Global Terrorism Dataset Analysis.ipynb"

**🔮 Future Enhancements**

Incorporate real-time terrorism data feeds.

Improve predictive modeling for risk assessment.

Develop a web-based dashboard for interactive analysis.

**📂 Repository Structure**

📦 storytelling-by-tableau-terrorism-dataset
 ┣ 📂 data
 ┃ ┣ 📜 terrorism_dataset.csv
 ┃ ┣ 📜 cleaned_terrorism_data.csv
 ┣ 📂 notebooks
 ┃ ┣ 📜 Global Terrorism Dataset Analysis.ipynb
 ┣ 📜 README.md  # This File
 ┣ 📜 requirements.txt  # Dependencies
 ┣ 📜 Tableau Storyline & Data Analysis.pdf  # Project Report

🚀 Created by: Naitik Nayak📩 
Feel free to contribute and improve this project!

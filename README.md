# 🏥 Insurance Charges EDA & Feature Engineering

This repository contains an end-to-end **Exploratory Data Analysis (EDA)** and **Feature Engineering** process performed on the `insurance.csv` dataset.  
The goal is to analyze the factors that affect **medical insurance charges**, clean and preprocess the data, and prepare it for further modeling.

---

## 📂 Project Structure

EDA-and-Feature-Engineering/
│
├── Insurance.ipynb # Jupyter notebook with full EDA & preprocessing
├── insurance.csv # Dataset used for analysis
├── requirements.txt # Python dependencies
├── .gitignore # Ignore unnecessary files
└── README.md # Project documentation


---

## 🎯 Objectives

- Perform **EDA** to understand relationships between features (age, BMI, smoker status, region, etc.) and insurance charges.
- Handle **missing data** (if any), duplicates, and outliers.
- Perform **feature engineering**:
  - Encoding categorical variables (sex, smoker, region)
  - Creating new features if useful
- Visualize data using **Matplotlib** & **Seaborn**.
- Prepare a **clean dataset** for future machine learning models.

---

## 📊 Key Visualizations

- Distribution of charges across different age groups  
- Correlation heatmap between numerical features  
- Boxplots to detect outliers  
- Pairplots to see relationships between multiple variables  


🛠️ Tech Stack
Python 3

Libraries Used:

pandas

numpy

matplotlib

seaborn

scikit-learn (for preprocessing)

Install dependencies using:

bash
pip install -r requirements.txt
🚀 Usage
Clone this repository:

bash

git clone https://github.com/your-username/EDA-and-Feature-Engineering.git
cd EDA-and-Feature-Engineering
Install dependencies:

bash
pip install -r requirements.txt
Open the notebook:

bash

jupyter notebook Insurance.ipynb
Run all cells to reproduce the analysis.

📌 Notes
This project focuses only on EDA and feature preparation.

You can use the processed data as input for a regression model to predict insurance charges.

Contributions and suggestions are welcome!

📜 License
This project is licensed under the MIT License - feel free to use and modify it.



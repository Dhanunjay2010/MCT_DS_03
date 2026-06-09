# MCT_DS_03# Titanic Dataset - Exploratory Data Analysis (EDA) 🚢

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the Titanic Dataset to uncover patterns that influenced passenger survival. The analysis includes data cleaning, feature engineering, statistical insights, and visualizations using Python libraries such as Pandas, Matplotlib, and Seaborn.

This project was completed as part of a Data Science Internship – Task 3.

---

## 🎯 Objectives

* Clean and preprocess the Titanic dataset.
* Handle missing values using imputation techniques.
* Analyze survival patterns across different passenger groups.
* Create meaningful visualizations to support findings.
* Practice Exploratory Data Analysis (EDA) techniques.

---

## 📂 Dataset

The Titanic dataset contains passenger information such as:

* Passenger ID
* Name
* Age
* Gender
* Passenger Class
* Fare
* Embarkation Port
* Family Information
* Survival Status

**Dataset Source:**
https://www.kaggle.com/competitions/titanic/data

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 🧹 Data Cleaning

The following preprocessing steps were performed:

* Filled missing values in the **Age** column using the mean age.
* Filled missing values in the **Embarked** column using the mode.
* Removed the **Cabin** column due to excessive missing values.
* Created a new feature called **FamilySize** using:

```python
FamilySize = SibSp + Parch
```

---

## 📊 Analysis Performed

### 1. Survival Rate by Age Group

Passengers were categorized into:

* Child
* Teen
* Young Adult
* Adult
* Senior

The survival rate for each age group was analyzed.

### 2. Survival Rate by Embarkation Port

Analyzed how survival chances varied based on embarkation location:

* C = Cherbourg
* Q = Queenstown
* S = Southampton

### 3. Survival Rate by Family Size

Investigated the relationship between family size and survival probability.

---

## 📈 Visualizations

### Age Distribution Histogram

Shows the distribution of passenger ages.

### Correlation Heatmap

Displays correlations among numerical features.

### Survival Rate by Family Size

Bar chart illustrating how family size affected survival.

### Survival Rate by Embarkation Port

Comparison of survival rates across embarkation ports.

---

## 🔍 Key Insights

* Survival rates varied across different age groups.
* Embarkation port had an impact on passenger survival.
* Family size influenced survival probability.
* Correlation analysis revealed relationships between passenger features.
* Data preprocessing improved the quality and reliability of analysis.

---

## 📁 Project Structure

```text
Titanic-EDA-Task3/
│
├── train.csv
├── Titanic_EDA_Task3.ipynb
├── README.md
└── images/
    ├── age_distribution.png
    ├── correlation_heatmap.png
    ├── family_size_survival.png
    └── embarkation_survival.png
```

---

## ▶️ How to Run

### Clone the Repository

```bash
git clone https://github.com/your-username/Titanic-EDA-Task3.git
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn
```

### Run the Notebook

Open the Jupyter Notebook and execute all cells.

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

* Data Cleaning
* Feature Engineering
* Exploratory Data Analysis (EDA)
* Data Visualization
* Statistical Interpretation
* Storytelling with Data

---

## 👨‍💻 Author

**Your Name**

Data Science with Python Internship – Task 3

---

⭐ If you found this project helpful, feel free to star the repository.

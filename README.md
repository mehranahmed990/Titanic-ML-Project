# 🚢 Titanic Survival Prediction

## 📌 Project Overview
This project applies machine learning techniques to the famous **Titanic dataset** to predict passenger survival.  
The Titanic disaster of 1912 resulted in the deaths of over 1,500 people. Researchers and data scientists often study this dataset to explore how demographic and social factors influenced survival chances.  

By analyzing passenger information such as age, gender, class, and family size, this project builds predictive models to answer the question:  
**“What kinds of people were more likely to survive the Titanic sinking?”**

---

## 🎯 Purpose of the Project
The main goals of this project are:
- To **explore data preprocessing** and feature engineering on real-world data.  
- To practice building and evaluating **classification models**.  
- To demonstrate how **data science** can be applied to historical datasets to uncover insights.  
- To provide a structured machine learning workflow that can be reused for similar predictive problems.

This project also serves as a **portfolio piece** to showcase skills in:
- Data cleaning and preparation  
- Exploratory Data Analysis (EDA)  
- Machine learning model training and testing  
- Performance evaluation and interpretation  

---

## 📊 Dataset
- **Source:** [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)  
- **Description:** Passenger information including demographics, ticket details, and survival status.  
- **Features:**
  - `Pclass` (Ticket class: 1st, 2nd, 3rd)  
  - `Sex` (Male/Female)  
  - `Age` (Passenger age)  
  - `SibSp` (Number of siblings/spouses aboard)  
  - `Parch` (Number of parents/children aboard)  
  - `Fare` (Ticket price)  
  - `Embarked` (Port of Embarkation: C, Q, S)  
  - `Survived` (Target variable: 0 = Did not survive, 1 = Survived)  

---

## 🔧 Project Workflow
1. **Data Preprocessing**
   - Handle missing values in `Age` and `Embarked`  
   - Convert categorical variables (`Sex`, `Embarked`) into numerical form  
   - Feature engineering (family size, title extraction from names, etc.)

2. **Exploratory Data Analysis (EDA)**
   - Visualize survival rates across gender, class, and age groups  
   - Identify trends and correlations  

3. **Modeling**
   - Train classification models such as:
     - Logistic Regression  
     - Random Forest  
     - Decision Tree  
     - Support Vector Machine (SVM)  
   - Compare performance metrics  

4. **Evaluation**
   - Use accuracy, precision, recall, F1-score, and confusion matrix  
   - Cross-validation for robustness  

---

## 🚀 Results & Insights
- **Gender was the strongest predictor:** women had significantly higher survival rates than men.  
- **Passenger class mattered:** first-class passengers were more likely to survive than those in second or third class.  
- **Age played a role:** children had higher chances of survival.  
- Feature engineering (lik

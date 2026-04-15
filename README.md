# 🚢 Titanic Survival Analysis (EDA Project)
## 📌 Overview
This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to identify key factors that influenced passenger survival. The analysis focuses on uncovering patterns, relationships, and hidden insights using statistical and visual techniques.

## 🎯 Objective
Understand the factors affecting survival
Analyze demographic and socio-economic influences
Identify patterns using univariate, bivariate, and multivariate analysis

## 📂 Dataset
Source: Kaggle Titanic Dataset
Records: ~891 passengers
Features: Demographics, ticket details, family relations

## 🛠️ Tools & Technologies
Python (Pandas, NumPy)
Matplotlib, Seaborn
Jupyter Notebook

## 🔧 Data Preprocessing
### Handled missing values:
Age → Median imputation
Embarked → Mode imputation
Cabin → Dropped (high missing values)
Feature Engineering:
FamilySize (SibSp + Parch + 1)
AgeGroup (Child, Adult, Senior, etc.)
### Encoding:
Label Encoding (Sex)
One-Hot Encoding (Embarked)

## 📊 Key Analysis Performed
Univariate Analysis → Distribution of features
Bivariate Analysis → Survival vs individual features
Multivariate Analysis → Interaction between multiple variables

## 🔍 Key Insights
Gender is the strongest factor → Females had higher survival rates
Class matters → 1st class > 2nd > 3rd in survival probability
Children prioritized → Higher survival among younger passengers
Socio-economic impact → Higher fare → better survival
Family size effect → Medium-sized families had better outcomes
Combined hierarchy observed →
Women > Children > Higher Class > Others

## 🧠 Key Learning
Importance of data cleaning before analysis
How feature interactions reveal deeper insights
Moving from basic EDA → analytical storytelling

## 📈 Project Outcome

This EDA reveals that survival was influenced by a combination of gender, class, and age, forming a hierarchical decision pattern rather than a single-factor dependency.

## 🚀 Future Work
Build predictive models (Logistic Regression, Decision Trees)
Feature importance analysis
Model evaluation and optimization

## 📎 Files Included
Titanic_EDA.ipynb → Complete analysis
Titanic_EDA_MDD.pdf → Detailed documentation
README.md → Project overview

## 🙌 Acknowledgment
Dataset provided by Kaggle

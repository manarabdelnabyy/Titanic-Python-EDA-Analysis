# Titanic-Python-EDA-Analysis
Exploratory Data Analysis (EDA) of the Titanic dataset using Python. Includes data cleaning, feature exploration, and visualizations to uncover patterns in passenger survival rates by age, gender, and class.

# Titanic Exploratory Data Analysis (EDA)

This project explores the famous [Titanic dataset](https://www.kaggle.com/competitions/titanic) to uncover insights about passenger survival.  
It includes data cleaning, transformation, and visualizations to understand the key factors affecting survival.

---

## 📂 Project Structure
- **exploratory-data-analysis-on-titanic-dataset.ipynb** → Jupyter Notebook with full code & outputs  
- **titanic_eda.py** → Python script version (optional)  
- **/data** → Dataset files (train.csv)  

---

## 🔎 Key Steps
1. Data Cleaning  
   - Handle missing values (Age, Embarked, Cabin)  
   - Convert data types (categorical & numerical)  

2. Exploratory Data Analysis  
   - Summary statistics  
   - Survival rate by gender and class  
   - Age distribution and survival  

3. Visualizations  
   - Count plots of survival  
   - Bar plots by gender and passenger class  
   - Age distribution with survival overlay  

---

## 📊 Example Insights
- Female passengers had a much higher survival rate.  
- First-class passengers had better chances of survival than third-class.  
- Younger children had a slightly higher survival rate.  

---

## ⚙️ Requirements
Install the dependencies before running the notebook:

```bash
pip install pandas matplotlib seaborn

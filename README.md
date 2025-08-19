# Titanic Exploratory Data Analysis (EDA)

## Project Overview
This project performs an **Exploratory Data Analysis (EDA)** on the famous Titanic dataset. The goal is to understand the characteristics of the passengers, explore survival rates, and identify patterns that affected survival.

## Dataset
- Source: Kaggle / DataScienceDojo Titanic Dataset
- Files in Repo:
    - Titanic_EDA.ipynb → Jupyter Notebook with full analysis
    - titanic.csv → Original dataset
    - titanic_clean.csv → Cleaned dataset after handling missing values

- Description: Contains passenger information such as age, gender, class, fare, and whether they survived.
- Contains 891 rows and 12 columns, including:
  - PassengerId
  - Survived
  - Pclass
  - Name
  - Sex
  - Age
  - SibSp
  - Parch
  - Ticket
  - Fare
  - Cabin
  - Embarked

## Tools & Libraries
- **Python**
- **Jupyter Notebook**
- **Pandas** – data manipulation
- **NumPy** – numerical operations
- **Matplotlib & Seaborn** – data visualization
- **CSV** – saving cleaned datasets

## Steps Taken
1. **Data Loading & Inspection**
   - Loaded the dataset using Pandas.
   - Checked for missing values, data types, and summary statistics.

2. **Data Cleaning**
   - Filled missing `Age` values with median.
   - Filled missing `Embarked` values with mode.
   - Optional: cleaned `Cabin` column.

3. **Exploratory Visualization**
   - Countplot for survival rates.
   - Survival by gender and passenger class.
   - Scatterplot of Age vs Fare, colored by survival.

4. **Insights**
   - Females had a higher survival rate than males.
   - Younger passengers had better chances of survival.
   - First-class passengers survived more often than third-class passengers.
   - Certain patterns in fare and age influenced survival.

5. **Reporting**
   - Documented analysis in Markdown cells in Jupyter Notebook.
   - Saved cleaned dataset for future use.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/amara2002/Titanic-EDA.git

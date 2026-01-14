# Titanic-dataset-analysis
Analysis the ratio of people died and what the are factors affected
# Titanic Survival Analysis

## Project Description
This project analyzes the **Titanic passenger dataset** to understand the factors that influenced passenger survival during the Titanic disaster.

The primary goal of this project is to perform **data cleaning, preprocessing, and exploratory data analysis (EDA)** in order to uncover meaningful insights related to survival patterns based on passenger demographics, ticket class, fare, and family information.

No advanced predictive modeling is the main focus; instead, the project emphasizes **data understanding and insight generation**.

---

## Dataset Overview

### Dataset Name
**Titanic Dataset**

### Description
The Titanic dataset contains information about passengers aboard the RMS Titanic, including demographic details, ticket information, and survival status.

It is one of the most widely used datasets for learning data analysis, data preprocessing, and exploratory data analysis techniques.

### Target Variable
- **Survived**
  - `0` → Did not survive
  - `1` → Survived

---

### Key Features

#### Passenger Information
- `PassengerId` – Unique passenger identifier  
- `Name` – Passenger name  
- `Sex` – Gender of the passenger  
- `Age` – Age of the passenger  

#### Ticket & Travel Details
- `Pclass` – Passenger class (1st, 2nd, 3rd)  
- `Ticket` – Ticket number  
- `Fare` – Ticket fare paid  
- `Cabin` – Cabin number  

#### Family Information
- `SibSp` – Number of siblings/spouses aboard  
- `Parch` – Number of parents/children aboard  

#### Port of Embarkation
- `Embarked` – Port where the passenger boarded the ship  

---

## Data Preprocessing
- Handled missing values in columns such as `Age`, `Cabin`, and `Embarked`
- Dropped non-informative or highly missing columns
- Converted categorical variables into numerical format
- Cleaned and structured the dataset for analysis
- Verified data consistency and data types

---

## Key Insights from the Analysis

After analyzing the Titanic dataset through extensive data preprocessing and exploratory data analysis covering multiple questions, the following overall insights were derived:

- **Survival was highly influenced by social and demographic factors.** Gender and passenger class played a significant role in determining survival outcomes.

- **Female passengers had a much higher survival rate** compared to male passengers, reflecting evacuation priorities during the disaster.

- **Passenger class was strongly correlated with survival.** First-class passengers were more likely to survive, while third-class passengers faced the highest mortality rates.

- **Age affected survival probability.** Children had better survival chances, whereas elderly passengers were less likely to survive.

- **Economic status mattered.** Passengers who paid higher fares generally had higher survival rates, suggesting better access to lifeboats and safer locations on the ship.

- **Family size influenced survival outcomes.** Passengers traveling with small families showed better survival rates than those traveling alone or in large groups.

- **Port of embarkation showed variation in survival patterns**, indicating differences in passenger composition and class distribution.

- **Missing data patterns revealed structural inequalities**, especially in cabin information, which was more frequently missing for lower-class passengers.

- **The dataset reflects clear social stratification**, where wealth, class, and gender significantly shaped survival chances during the Titanic disaster.

---

## Conclusion
The overall analysis demonstrates that survival on the Titanic was not random but was shaped by a combination of **social status, demographics, and economic factors**.  
This project highlights the power of exploratory data analysis in uncovering meaningful insights from historical datasets.

---

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

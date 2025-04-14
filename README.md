# Elevate_labs_task_5

# Titanic Survival Exploratory Data Analysis (EDA)

## Overview
This project conducts an Exploratory Data Analysis (EDA) on the Titanic dataset to uncover patterns and factors influencing passenger survival. The analysis includes visualizations, statistical summaries, and correlation studies to derive insights.

## Dataset
The dataset (`train.csv`) contains information for 891 passengers, including:
- **Survived**: Survival status (0 = No, 1 = Yes)
- **Pclass**: Passenger class (1st, 2nd, 3rd)
- **Sex**: Gender
- **Age**: Age of passenger
- **Fare**: Ticket fare
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
- Other features: PassengerId, Name, SibSp, Parch, Ticket, Cabin.

**Missing Values**: 
- `Age` (177 missing), `Cabin` (687 missing), `Embarked` (2 missing).

## Code Structure
The analysis is performed in a Jupyter Notebook (`Elevate_task_5.ipynb`). Key steps include:
1. **Data Loading & Initial Checks**: Shape, data types, missing values.
2. **Univariate Analysis**: Distributions of `Survived`, `Sex`, `Pclass`, `Age`, and `Fare`.
3. **Bivariate Analysis**: Survival vs. `Sex`, `Pclass`, and `Embarked`.
4. **Multivariate Analysis**: Correlation heatmap and pair plots.

## Key Insights
- 🚺 **Gender Impact**: 74% of females survived vs. 19% of males.
- 🎫 **Class Privilege**: 63% of 1st-class passengers survived, compared to 24% in 3rd class.
- 💵 **Fare Correlation**: Higher fares (linked to 1st class) correlated with higher survival.
- 👶 **Age Trend**: Children under 10 had higher survival rates.
- ⚓ **Embarked Variation**: Passengers from Cherbourg (C) had the highest survival rate.

## Visualizations
1. **Count Plots**: Survival, gender, and passenger class distributions.
2. **Histograms**: Age and fare distributions.
3. **Heatmap**: Correlation between numerical features.
4. **Pair Plots**: Relationships between `Survived`, `Age`, `Fare`, and `Pclass`.

## How to Run
1. **Google Colab**: Open the notebook directly using [this Colab link](https://colab.research.google.com/) (upload the notebook and dataset).
2. **Locally**:
   - Install dependencies:  
     ```bash
     pip install pandas numpy matplotlib seaborn jupyter
     ```
   - Launch Jupyter Notebook and run `Elevate_task_5.ipynb`.

## Conclusion
The EDA highlights socio-economic factors (class, fare) and demographics (gender, age) as critical determinants of survival. These insights align with the historical "women and children first" protocol and the advantage of wealthier passengers.

---

**Dataset Source**: [Kaggle Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data)  
**Author**: [Your Name]  
**Contact**: [Your Email/LinkedIn]  

# Titanic Data Analysis

## Overview
This project provides an exploratory data analysis (EDA) of the Titanic dataset using Python. 
The analysis focuses on understanding passenger survival based on features such as age, gender, class, and fare.

## Dataset
The dataset contains information about Titanic passengers, including:
- `survived` : Survival (0 = No, 1 = Yes)
- `pclass` / `class` : Ticket class (First, Second, Third)
- `sex` : Gender
- `age` : Age in years
- `fare` : Passenger fare
- Other features: `sibsp`, `parch`, `embarked`, etc.

The dataset is publicly available and widely used for learning purposes.

## Analysis
The following analyses are performed:
1. **Data cleaning**: Handling missing values and converting categorical variables to numeric.
2. **Descriptive statistics**: Overview of the data using `.info()`, `.describe()`, and `.shape()`.
3. **Data visualization**: 
   - Count plots for survival overall and by gender/class.
   - Boxplots for age distribution by survival.
   - Heatmap for correlation between numeric features.
4. **Insights**:
   - Younger passengers and women had higher survival rates.
   - First-class passengers had a higher chance of survival.
   - Fare shows positive correlation with survival.

## Tools & Libraries
- Python 3.x
- Pandas
- Seaborn
- Matplotlib

## Usage
1. Clone the repository:
```bash
git clone https://github.com/username/titanic-analysis.git
## Author
- Sara Hosseini
- GitHub: https://github.com/Sara-Hosseini

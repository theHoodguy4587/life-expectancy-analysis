# Life Expectancy Analysis: Data Cleaning, EDA, and Linear Regression

## Overview
This project analyzes the factors influencing life expectancy across different countries from 2000 to 2015. The dataset, sourced from the World Health Organization (WHO) and the United Nations (UN), includes various health, economic, and social indicators that may impact life expectancy. The primary focus of this project is on data cleaning, exploratory data analysis (EDA), and building a linear regression model to identify key predictors of life expectancy.

## Dataset
- **Source**: WHO Global Health Observatory & UN economic data
- **Timeframe**: 2000 - 2015
- **Countries**: 193 (after cleaning, some countries were removed due to missing data)
- **Observations**: 2,938 rows
- **Features**: 22 columns (including 20 predictor variables)
  
### Broad Categories of Predictors:
1. **Immunization Factors** (e.g., Hepatitis B, Polio, Diphtheria coverage)
2. **Mortality Factors** (e.g., Infant mortality rate, Adult mortality rate)
3. **Economic Factors** (e.g., GDP, Health expenditure per capita)
4. **Social Factors** (e.g., Schooling, Alcohol consumption)

## Project Goals
- **Data Cleaning:** Handle missing values and remove inconsistencies in the dataset.
- **Exploratory Data Analysis (EDA):** Understand the distribution, trends, and relationships between variables.
- **Linear Regression Modeling:** Identify key predictors affecting life expectancy and analyze their impact.

## Methodology
### 1. Data Cleaning
- Handled missing values using appropriate imputation techniques.
- Removed countries with excessive missing data (e.g., Vanuatu, Tonga, Togo, Cabo Verde).
- Checked for data inconsistencies and outliers.

### 2. Exploratory Data Analysis (EDA)
- Visualized trends in life expectancy over time.
- Analyzed correlations between predictor variables and life expectancy.
- Compared life expectancy across different economic and social groups.

### 3. Linear Regression Model
- Built a multiple linear regression model to predict life expectancy.
- Evaluated model performance using R-squared, adjusted R-squared, and residual analysis.
- Identified significant predictors and their impact on life expectancy.


## Tools & Libraries
- **Programming Language:** Python 
- **Libraries Used (Python)**:
  - pandas (for data manipulation)
  - numpy (for numerical operations)
  - matplotlib & seaborn (for visualization)
  - scikit-learn (for regression modeling)


## Results & Insights
- Identified key variables that significantly impact life expectancy.
- Found strong correlations between schooling, GDP, and life expectancy.
- Analyzed the effect of immunization rates and mortality rates on life expectancy.
- Developed a predictive model to estimate life expectancy based on available data.

## Future Work
- Explore non-linear regression models for better accuracy.
- Include additional social and environmental factors.
- Compare results with other machine learning models (e.g., Random Forest, Gradient Boosting).

## License
This project uses data from WHO and UN under their respective data usage policies. The analysis and code are available under the MIT License.

---

### Author: [Senitha Gunathilaka]
### Contact: [senitha02@gmail.com]

For any questions or suggestions, feel free to reach out!

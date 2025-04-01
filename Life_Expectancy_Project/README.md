# Life Expectancy Analysis

## Project Overview
This project analyzes life expectancy data to uncover key factors affecting longevity across different countries. Using data visualization and statistical modeling, the notebook explores correlations between socioeconomic, health, and environmental factors with life expectancy. 

## Workflow and Code Breakdown

### 1. Data Loading and Preprocessing
The dataset is loaded using pandas, and the first few rows are inspected to understand its structure. Missing values are handled through imputation or removal depending on their impact.

### 2. Exploratory Data Analysis (EDA)
- **Correlation Matrix:** The correlation between life expectancy and various factors like GDP, schooling, healthcare expenditure, and immunization rates is visualized.
- **Distribution Analysis:** Histograms and box plots illustrate the distribution of life expectancy across different regions and income levels.

#### Key Findings:
- Countries with higher GDP per capita tend to have higher life expectancy.
- Immunization rates and healthcare expenditure show a positive correlation with life expectancy.
- Lower-income countries generally have lower life expectancy due to limited healthcare access.

### 3. Analyzing the Impact of Health Factors
- **Mortality Rates vs. Life Expectancy:** Infant and adult mortality rates are examined in relation to life expectancy.
- **HIV/AIDS Prevalence:** The impact of HIV/AIDS on reducing life expectancy is quantified.
- **Immunization Effects:** The correlation between childhood immunization rates and increased life expectancy is explored.

#### Key Findings:
- High infant mortality rates significantly reduce the average life expectancy in a country.
- HIV/AIDS prevalence negatively impacts life expectancy, especially in sub-Saharan Africa.
- Countries with higher immunization coverage tend to have longer life expectancy.

### 4. Socioeconomic Influence on Life Expectancy
- **Education and Income Levels:** The relationship between schooling years, GDP per capita, and life expectancy is investigated.
- **Comparison of Developed vs. Developing Countries:** A comparative analysis highlights disparities in life expectancy trends based on economic development.

#### Key Findings:
- Higher levels of education correlate with increased life expectancy.
- Developed countries show stable and high life expectancy rates, whereas developing nations have greater variability.

### 5. Predictive Modeling for Life Expectancy
A regression model is built to predict life expectancy based on health and socioeconomic indicators.
- **Feature Selection:** The most important variables are selected using feature importance analysis.
- **Model Training and Evaluation:** A machine learning model (e.g., linear regression, decision trees, or random forest) is trained and tested for accuracy.

#### Key Findings:
- The model successfully predicts life expectancy with reasonable accuracy.
- GDP per capita, healthcare expenditure, and education are strong predictors of life expectancy.

## Conclusion
This project provides insights into how different factors contribute to life expectancy disparities worldwide. The findings can help policymakers focus on healthcare, education, and economic improvements to enhance global life expectancy.




# Obesity Estimation Project

## Project Overview

This R-based project aims to analyze the key factors contributing to obesity by exploring a dataset of 2,111 observations. The project involves data preprocessing, statistical analysis, and data visualization to identify factors such as diet, physical activity, and demographics that influence obesity. Insights from this analysis are intended to guide obesity prevention and management efforts.

---

## Files in the Repository

### 1. **Obesity Estimation RMD File**
- **File**: `obesity_project_rmd_file.pdf`
- **Description**: Contains the R code for data exploration, analysis, and visualization. It covers data cleaning, regression analysis, and statistical tests to explore the relationship between obesity levels and various lifestyle and demographic factors.

### 2. **Statistical Report PDF**
- **File**: `Statistics_report.pdf`
- **Description**: A comprehensive report summarizing the methodology, statistical analysis, and key findings of the project. It provides detailed insights into how different factors affect obesity levels, including regression results and visualizations.

---

## Methodology

### 1. **Data Preprocessing**
- Cleaned the dataset to handle missing values, outliers, and inconsistencies.
- Ensured that all variables were properly formatted for analysis (e.g., converting categorical variables to factors).

### 2. **Descriptive Statistics**
- Summarized the main features of the dataset, including variables like age, gender, weight, height, and lifestyle factors (e.g., physical activity, diet).
- Calculated measures such as mean, median, and standard deviation for each relevant feature.

### 3. **Statistical Analysis**
- Applied correlation analysis to identify relationships between continuous variables (e.g., BMI, age, weight, height).
- Performed **regression analysis** (linear and logistic) to identify significant predictors of obesity.
- Conducted **ANOVA** tests to explore differences in obesity levels based on categorical variables (e.g., gender, family history).

### 4. **Visualization**
- Used **ggplot2** for creating various visualizations such as:
  - Histograms for distribution of continuous variables like weight and BMI.
  - Scatter plots to show relationships between variables (e.g., physical activity vs. BMI).
  - Boxplots to compare obesity levels across different groups (e.g., gender).

---

## Key Findings and Limitations

### Key Findings:
- **Significant Predictors**: High-calorie food consumption, low physical activity, and family history of obesity were identified as major factors contributing to obesity.
- **Gender-Specific Insights**: Gender was found to influence obesity levels, with men and women exhibiting different patterns of obesity risk.
- **Correlation with Lifestyle**: Variables like diet and physical activity showed strong correlations with BMI, indicating their critical role in obesity management.

### Limitations:
- **Observational Data**: The study uses observational data, so causality cannot be definitively established.
- **Missing Data**: Some data points had missing values, which were handled through imputation or exclusion, but this may have impacted results.
- **Potential Bias**: The dataset may not fully represent all demographics, which could limit the generalizability of the findings.

---

## Applications

- **Public Health Interventions**: The insights gained from this project can inform public health campaigns targeting obesity prevention, especially by focusing on diet and physical activity.
- **Personalized Health Plans**: The findings can be used by healthcare professionals to develop personalized health and wellness plans based on a patient’s demographics and lifestyle factors.
- **Future Research**: This analysis can be expanded to include other factors such as genetics or psychological components of obesity, and longitudinal data could help establish causal relationships.

---

## How to Run

### 1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/obesity-estimation.git

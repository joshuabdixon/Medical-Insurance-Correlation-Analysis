# Medical Insurance Correlation Analysis

This repository demonstrates my analytical approach to exploring correlations between various lifestyle factors and medical insurance costs. The goal was to identify key variables that significantly impact insurance costs to inform decision-making regarding insurance benefits.

## Approach
To achieve this, I systematically analysed an anonymised dataset, focusing on key factors such as BMI, smoker status, age, and number of children, using a combination of visualisations and statistical methods. This approach helped uncover patterns and correlations that could impact insurance costs.

## Statistical Techniques and Libraries
The following statistical techniques and Python libraries were used to conduct the analysis:

- **Statistical Techniques**:
  - Pearson correlation coefficient for linear relationships.
  - Spearman correlation coefficient for non-linear relationships.
  
- **Python Libraries**:
  - `pandas` for data manipulation and analysis.
  - `numpy` for numerical operations.
  - `matplotlib.pyplot` and `seaborn` for data visualisation.
  - `scipy.stats` for statistical calculations.

## Problem Statement and Objectives
Medical insurance costs vary among employees, and the goal was to understand the factors contributing to this variation. The objective was to explore correlations between key variables and insurance costs to identify significant relationships and provide actionable insights for the organisation.

## Key Findings
Through the analysis, I found the following key relationships between variables and insurance costs:

- **BMI and Insurance Costs**: A positive correlation between BMI and insurance costs, indicating that higher BMI generally leads to higher costs.
- **Smoking and Insurance Costs**: A clear separation in costs between smokers and non-smokers, with smokers typically paying more.
- **Age and Insurance Costs**: A very weak correlation between age and insurance costs, suggesting age may not be a significant factor.
- **Number of Children and Insurance Costs**: A very weak correlation, indicating minimal impact on insurance costs.

## Recommendations
Based on the findings, I suggest the following recommendations:

- **BMI Focus**: Encourage healthier lifestyles to reduce insurance costs.
- **Smoking Cessation Programs**: Implement programs to help reduce insurance costs over time.
- **Review Age and Family Factors**: Given their minimal impact, these factors may not require extensive focus in insurance planning.

## Methodology and Analysis
Here are the main components of the analysis, along with the statistical techniques used:

- **Data Visualisation**: Scatterplots and boxplots were used to visually examine relationships between variables and insurance costs.
- **Pearson and Spearman Correlation**: Pearson correlation was used for linear relationships (e.g., BMI and insurance costs), while Spearman correlation was used for non-linear relationships (e.g., age and insurance costs).
- **Correlation Matrix**: A Spearman correlation matrix was generated to assess the relationships among all variables.

## Limitations
While conducting this analysis, I was mindful of potential biases and limitations:

- **Outliers**: Notable outliers were observed, which could affect correlation results.
- **Nominal Variables**: Pearson and Spearman correlations were not suitable for nominal variables like smoker status. Future analysis will require Point Biserial Correlation.

## Conclusion
This analysis has identified key factors that impact medical insurance costs. BMI and smoking status are the primary variables influencing insurance costs, suggesting targeted programs could lead to reduced costs. Further analysis may be required to explore other factors and validate the findings.

Thank you for exploring this repository. If you have any questions or would like to discuss opportunities, please feel free to contact me.

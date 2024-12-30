# Machine Learning Analysis of County-Level Voting Behavior

## Project Overview
This study explores socio-economic and educational factors influencing voting patterns across U.S. counties using machine learning techniques. Using data from the 2020 Presidential Election, Harvard Dataverse, and USDA Economic Research Service, I analyzed how factors such as urbanization, income, and education levels impact county-level political preferences.

## Key Findings
- Bachelor's Degree percentage emerged as the strongest predictor of voting behavior
- County Median Household Income was the second most influential factor
- Urban Influence Code ranked third in importance
- Naive Bayes classifier demonstrated superior probability calibration with a Brier score of 0.10

## Data Sources
- 2020 Presidential Election Data
- Harvard Dataverse
- USDA Economic Research Service

## Methodology
### Data Preprocessing
- Dataset split: 50/25/25 (training/testing/validation)
- Feature selection focusing on socio-economic indicators

### Model Selection
Compared multiple classifiers:
- Naive Bayes (selected for final analysis)
- Logistic Regression
- Random Forest
- LDA

### Evaluation Metrics
- Brier Score
- AUC
- ROC
- F1 Score
- Log Score
- Calibration Plots

## Results
### Model Performance
- Naive Bayes achieved the best Brier score (0.10)
- Other models showed higher scores (0.74-0.76)
- Selected Naive Bayes for superior probability calibration

### Feature Importance
1. Bachelor's Degree or Higher Percentage
2. County Median Household Income
3. Urban Influence Code
4. Unemployment Rate
5. County Income Percentile

## Limitations
- Limited predictor set
- Dataset imbalance (predominantly Republican counties)
- Lower precision and recall for Democrat class
- Regional variations not fully accounted for

## Future Work
- Explore additional demographic factors
- Analyze regional trends over time
- Investigate region-specific predictors
- Include multiple election cycles
- Expand feature set (age, race, etc.)

## Technologies Used
- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib

## Contributors
Lokesh Hariharan

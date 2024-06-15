# Student Success in Portuguese Subject: Data Science Project

## Goal

This data science project aimed to explore and understand the factors influencing student success in the Portuguese subject. The primary goals were twofold:
1. Build a predictive model for initial Portuguese grades ('G1.Port') using linear regression.
2. Develop a classification model categorizing students into five performance levels based on their 'G1.Port' grades.

## Data Background

The dataset encompassed a diverse set of features, including demographic, social, and school-related attributes collected through school reports and questionnaires. Noteworthy features included student grades, family background, parental education, and lifestyle choices. The dataset provided a rich foundation for investigating the intricate dynamics influencing academic outcomes in the Portuguese subject.

## Approach Used

The project followed a systematic approach:
1. **Data Preprocessing**: Handled missing values, dropped unnecessary columns, and encoded non-numeric features.
2. **Exploratory Data Analysis**: Visualized grade distributions, examined correlations, and created a new categorical variable for classification.
3. **Model Development**:
    - Linear regression for grade prediction.
    - Logistic regression for multi-level classification.
    - Subsequent implementations of Decision Tree and Random Forest models were also investigated.

## Results

- **Linear Regression**: Limited predictive capabilities indicated by a mean squared error (MSE) of 0.798.
- **Decision Tree Model**: After feature selection, achieved an accuracy of 77.48%.
- **Random Forest Model**: Exhibited an impressive initial accuracy of 84.77%.

These results underscore the effectiveness of decision tree-based methods in enhancing predictive performance.

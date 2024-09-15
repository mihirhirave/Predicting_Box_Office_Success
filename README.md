# Predicting Box Office Success

## Overview
This project analyzes factors influencing domestic opening weekend box office revenues for movies. It employs various statistical techniques, including linear regression and Principal Component Analysis (PCA), to identify key determinants of box office success.

## Dataset
The dataset includes information about movies such as:
- Box office revenue
- Production budget
- Star power
- Movie genre (e.g., action, horror, animated)
- MPAA rating
- Sequel status
- "Buzz" variables (addict, cmngsoon, fandango, cntwait3)

## Analysis Steps

1. **Data Preprocessing**
   - Log transformation of skewed variables
   - Standardization of variables for PCA

2. **Linear Regression Analysis**
   - Models with traditional variables
   - Models incorporating "buzz" variables

3. **Principal Component Analysis (PCA)**
   - Applied to "buzz" variables
   - Applied to "buzz" variables and other continuous variables

4. **Model Comparison**
   - Evaluation using R-squared and Adjusted R-squared
   - Significance testing of variables

## Key Findings

- "Buzz" variables significantly improve model performance
- PCA helps in dimensionality reduction while maintaining model performance
- Surprising non-significance of some traditional variables (e.g., star power)
- Importance of movie genre (action, animated) and MPAA rating (PG) in predicting box office success

## Tools and Libraries Used

- Python
- Pandas (for data manipulation)
- Scikit-learn (for PCA and regression analysis)
- Matplotlib or Seaborn (for visualizations)

## Managerial Takeaways

1. Buzz generation is crucial for opening weekend success
2. High budgets and star power don't guarantee success
3. Action and animated movies with PG ratings tend to perform well
4. Effective marketing strategies can significantly impact box office performance

## Future Work

- Incorporate additional variables (e.g., release date, competition)
- Explore non-linear relationships and interaction effects
- Conduct time series analysis to understand trends over time

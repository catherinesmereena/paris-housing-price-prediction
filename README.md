# paris-housing-price-prediction
Linear and stepwise regression models to predict housing prices in Paris using property size, neighborhood features, and amenities.

Predictive Analysis of Housing Prices in Paris

This project explores the use of Linear and Stepwise Regression models to predict housing prices in Paris. Built as part of the ALY6020 Predictive Analytics course at Northeastern University, the project aims to identify key property features that drive real estate prices.

##  Objective
To support property developers and investors by analyzing which home features significantly impact market prices using a data-driven regression approach.

##  Data Preparation
- Dropped columns with high missing values (e.g., `floors`, `cityCode`)
- Applied median imputation for columns like `cityPartRange`, `hasGuestRoom`
- Outlier capping using the IQR method
- Feature engineering and multicollinearity reduction using VIF analysis

##  Modeling & Evaluation
- Built initial linear regression and refined it with stepwise selection
- **R² score:** 0.754
- Strongest predictor: `squaremeters`
- Used AIC for model comparison between training and test sets

##  Files Included
- `Assignment_week2-2.ipynb`: Jupyter notebook with full code
- `Assignment_week2.docx`: Final report
- `paris_housing_regression.csv`: Original dataset

##  Tech Stack
- Python, Pandas, Scikit-learn, Statsmodels
- Matplotlib, Seaborn
- Jupyter Notebook

##  Key Takeaways
- Property size has the greatest impact on price.
- Stepwise regression enhanced interpretability while preserving performance.
- Amenity features had limited statistical influence, guiding future investment focus.

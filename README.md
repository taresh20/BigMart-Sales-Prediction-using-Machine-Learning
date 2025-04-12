# 🛒 BigMart Sales Prediction using Machine Learning

**Objective:**  
To predict sales of products at BigMart outlets using regression-based machine learning models.

**Steps Taken:**

## Data Preprocessing:
- Handled missing values and categorical encoding (Label & One-Hot Encoding)
- Feature engineering: created new features like `Item_Visibility_MeanRatio` and `Outlet_Age`
- Scaled numerical data using StandardScaler

## Model Building & Evaluation:
- Tried multiple models:
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor (best performing)
- Evaluated using RMSE, R² Score

## Insights Discovered:
- Outlet size and item MRP are major influencers on sales
- Model achieved an R² score of around 85% on test data

## Deployment & Visualization:
- Built interactive dashboard with predictions using Streamlit (optional)
- Plotted feature importance for business insights

**Tools Used:**  
Python, Scikit-Learn, Pandas, NumPy, Matplotlib, Jupyter Notebook


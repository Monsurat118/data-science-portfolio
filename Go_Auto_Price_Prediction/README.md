# Go Auto Vehicle Price Prediction

##  Overview
This project builds a machine learning model to predict used vehicle prices based on features such as mileage, year, make, model, and condition. The goal is to help dealerships estimate fair market value and support data-driven pricing decisions.

##  Key Objectives
- Understand key factors influencing vehicle prices.
- Perform exploratory data analysis (EDA) on real dealership-style datasets.
- Train and compare regression models (Linear Regression, Random Forest, XGBoost).
- Evaluate model performance using RMSE and R².

##  Dataset
- Vehicle listings dataset (cleaned in notebook)
- Features include:
  - `year`, `make`, `model`
  - `mileage`
  - `engine`, `fuel_type`
  - `transmission`
  - `drivetrain`

##  Tools & Technologies
- Python, Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter/Colab

##  Results
- Best model: **Random Forest Regressor**
- Achieved strong predictive accuracy with minimal overfitting.
- Feature importance shows mileage, age, and model as key price drivers.

##  How to Run
1. Open the `.ipynb` notebook  
2. Install required libraries  
3. Run all cells to reproduce results  

##  Future Improvements
- Add hyperparameter tuning (GridSearch/Optuna)
- Deploy model using Flask or FastAPI
- Build a simple pricing dashboard

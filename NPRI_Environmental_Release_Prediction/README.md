# NPRI Environmental Release Prediction Model

##  Overview
This project predicts pollutant release levels using historical NPRI (National Pollutant Release Inventory) data. It focuses on building a classification/regression model to support environmental risk assessment and regulatory planning.

##  Key Objectives
- Prepare time-series environmental data for ML.
- Build predictive models for pollutant release categories.
- Identify which facilities and substances contribute most to emissions.
- Support long-term forecasting to inform sustainability decisions.

##  Dataset
- NPRI dataset (cleaned and transformed)
- Features:
  - Substance type
  - Facility locations
  - Release levels over time
  - Treatment vs. recycling comparisons

##  Tools & Technologies
- Python (Pandas, NumPy, Scikit-learn)
- Seaborn / Matplotlib
- Jupyter/Colab

##  Results
- Built classification model with strong accuracy
- Identified predictors with the largest impact on emissions
- Created visual EDA to explain pollutant distributions

##  How to Run
1. Load the dataset provided in the notebook
2. Install required libraries
3. Run the notebook from top to bottom

##  Future Improvements
- Introduce an LSTM model for time-series forecasting
- Explore geospatial visualization of emissions
- Build an interactive dashboard (Streamlit)

# Northern Saw-whet Owl (NSWO) Migration Analysis

##  Overview
This project analyzes bird migration patterns using Motus Wildlife Tracking System data. It explores movement patterns, detection frequency, migration timing, and factors influencing owl behavior.

##  Key Objectives
- Conduct EDA on movement and detection patterns.
- Clean and restructure telemetry datasets.
- Apply machine learning (Random Forest, Gradient Boosting) to predict movement events.
- Build logistic models to classify migration behaviors.
- Use SHAP for explainable AI insights.

##  Dataset
- Motus telemetry data (cleaned)
- Fields include:
  - Tag ID
  - Timestamp
  - Receiver location
  - Signal strength
  - Movement labels

##  Tools & Technologies
- Python (Pandas, NumPy)
- Scikit-learn
- Matplotlib & Seaborn
- SHAP for explainability

##  Results
- Achieved strong classification accuracy for movement prediction
- Identified key predictors influencing owl travel
- Visualized temporal and geographical migration patterns

##  How to Run
1. Open the notebook
2. Install dependencies
3. Run the analysis and review visualizations

##  Future Improvements
- Add geospatial mapping using Folium/GeoPandas
- Expand dataset to include weather variables
- Deploy model as an API for researchers

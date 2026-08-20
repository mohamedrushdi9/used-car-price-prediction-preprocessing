# AI_Preprocessing_2025-Y2-S1-KU-11
Collaborative data preprocessing project for IT2011

Project Overview

The project focuses on Used Car Price Prediction using machine learning regression techniques.
  •	Problem: Used car pricing is inconsistent, influenced by multiple variables.
  •	Goal: Build a supervised ML model to predict resale value accurately.
  •	Stakeholders:
    o	Buyers → avoid overpaying
    o	Sellers → set competitive prices
    o	Financial institutions → fair loan valuations
    
Dataset Details

Dataset Name: 
•	Vehicle dataset
Direct Link: 
•	https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho?select=Car+details+v3.csv
Platform:  
•	Kaggle
Type of dataset: 
•	Tabular: 8128 Records

Group Member Roles

1. Clean textual and numerical inconsistencies and handle missing values
      Konara K.M.D.T - IT24102948
   
3. Encode categorical variables (One-hot for nominal, ordinal mapping )
	    Karunarathna M. M. G. A. S - IT24100136
   
5. Remove outliers (e.g., filter unrealistic selling_price, extreme km_driven.)
	    Rathnayake R.M.T.P - IT24100511
   
7. Feature engineering - Create derived features such as km_per_year, car_age, and interaction terms.
	    Abeynayake. D.A. - IT24100971
   
9. Feature selection reduction - Correlation analysis, RandomForest importance, RFE.
	    Rushdi M.R - IT24101405
   
11. Scale numerical features - Standard Scale applied to numerical values (mileage, engine, etc.).
	    Dissanayake H.M.C.P - IT24102141 


How to Run the Code

1. Clone or unzip the project folder.

2. Check that the data is available
Raw dataset: data/raw/Car details v3.csv
If not, download the dataset from Kaggle: https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho?select=Car+details+v3.csv
Place the file Car details v3.csv inside a folder called data/raw/.

3. Open Jupyter Notebook / Google Colab:

Run the notebook step by step (notebooks/2025_Y2_S1_KU_11_pipeline.ipynb).
  1. Clean textual and numerical inconsistencies, handling missing and duplicate values
  2. Categorical Encoding
  3. Remove outliers 
  4. Feature Engineering
  5. Feature Selection
  6. Scale numerical features 

## My Contribution

- Contributed to Feature Engineering by creating derived features
  from the original dataset.
- Contributed to Feature Selection and Reduction using:
  - Correlation Analysis
  - Random Forest Feature Importance
  - Recursive Feature Elimination (RFE)

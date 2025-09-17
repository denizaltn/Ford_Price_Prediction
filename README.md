
# Ford Focus Price Prediction Model 🚗💰

This project uses **machine learning** techniques to predict the prices of **Ford Focus** cars. 

The dataset is taken from Kaggle: [Used Car Dataset - Ford and Mercedes](https://www.kaggle.com/datasets/adityadesai13/used-car-dataset-ford-and-mercedes?select=ford.csv).  

## 🔍 Objective
The second-hand car market has highly dynamic pricing. This project aims to predict car prices using historical data to provide better insights for buyers and sellers.  

## 🛠️ Technologies Used
- Python 3.11  
- Pandas, NumPy → Data processing  
- Matplotlib, Seaborn → Visualization  
- Scikit-learn → Preprocessing, model selection  
- XGBoost → Price prediction model  

## 📊 Project Steps
1. **Data Loading & Exploration**  
   - Dataset loaded from Kaggle.  
   - Missing and incorrect values checked.  

2. **Data Preprocessing**  
   - Selected features: `year`, `mileage`, `tax`, `mpg`, `engineSize`.  
   - Cleaned missing values and encoded categorical variables.  

3. **Exploratory Data Analysis (EDA)**  
   - Visualized distributions of features.  
   - Generated correlation matrix.  

4. **Modeling**  
   - Train-test split applied.  
   - XGBoost Regressor trained on data.  
   - Predictions made on the test set.  

5. **Evaluation**  
   - Calculated MSE and RMSE.  
   - Visualized prediction performance.  


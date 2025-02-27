## Medical Charges Analysis

-> This is a small project work, It uses Linear Regression to estimate medical charges based on factors like age, BMI, number of children, smoking habits, and gender.

## 📂 Files
- `medical_charges_analysis.py` → Main Python script for data preprocessing and model training.
- `medical.csv` → Dataset 

## 📚 Libraries Used  
The following Python libraries were used:  
- `pandas` → Data manipulation and preprocessing  
- `numpy` → Numerical computations  
- `matplotlib` → Data visualization  
- `seaborn` → Statistical plots  
- `plotly.express` → Interactive plots  
- `sklearn.linear_model.LinearRegression` → Building the regression model  
- `sklearn.model_selection.train_test_split` → Splitting dataset into training and testing sets  
- `sklearn.metrics` → Model evaluation (MSE, RMSE, R²)  

## 🔍 Methods Used  
1. **Data Preprocessing**  
   - Encoding categorical variables (`sex`, `smoker`)  
   - Handling numerical features (`age`, `bmi`, `children`)  

2. Model Training
   - Used **Linear Regression** from `sklearn.linear_model` 

3. Model Evaluation  
   - **Mean Absolute Error (MAE)**  
   - **Mean Squared Error (MSE)**  
   - **Root Mean Squared Error (RMSE)**  
   - **R-squared Score (R²)**  

4. Visualization 
   - Scatter plot of **Actual vs Predicted Charges**

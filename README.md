Bangalore House Price Prediction


A Machine Learning project that predicts house prices in Bangalore using property features such as location, area type, total square feet, number of bedrooms, bathrooms, and balconies.


Project Overview

This project uses a Linear Regression model to estimate house prices based on historical Bangalore housing data.
The dataset was cleaned, preprocessed, and feature engineered before training the model to improve prediction accuracy.



Features

- Data Cleaning and Preprocessing
- Missing Value Handling
- Feature Engineering
- Outlier Detection and Removal
- One-Hot Encoding of Categorical Features
- Linear Regression Model
- Model Evaluation using R² Score, MAE, and RMSE
- Model Serialization using Pickle
- Feature Metadata stored in JSON format


Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Pickle
- JSON
- Jupyter Notebook



Project Workflow

1. Load the dataset.
2. Clean missing and inconsistent data.
3. Convert `total_sqft` into numerical values.
4. Perform feature engineering by creating:
   - BHK
   - Square Feet per BHK
   - Price per Square Foot
5. Remove outliers.
6. Encode categorical variables.
7. Split the data into training and testing sets.
8. Train the Linear Regression model.
9. Evaluate the model.
10. Save the trained model and feature metadata.


 
 Model Performance

R² Score : 0.90
Mean Absolute Error (MAE) : 10.27 Lakhs
Root Mean Squared Error (RMSE) : 15.16 Lakhs



Future Improvements

- Deploy the model using Flask or Streamlit.
- Compare Linear Regression with Random Forest and XGBoost.
- Develop a web interface for real-time house price prediction.


Author

Sakshi Parmeshwar Raut

GitHub: https://github.com/sakshi-1515
LinkedIn: www.linkedin.com/in/sakshi-parmeshwar-raut

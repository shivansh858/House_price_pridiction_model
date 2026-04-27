🚀 House Price Prediction using Machine Learning

This project focuses on building a robust machine learning model to accurately predict housing prices based on a wide range of features. The dataset is sourced from the well-known Kaggle competition “House Prices – Advanced Regression Techniques.”


🎯 Objective

To develop a high-performance regression model capable of predicting house prices with strong generalization on unseen data.


📊 Dataset
Source: Kaggle Competition – House Prices: Advanced Regression Techniques
Contains detailed information on residential homes, including numerical and categorical features.


🏆 Model Performance
Achieved 87.16% R² Score, 
demonstrating strong predictive capability.

🛠️ Tech Stack
NumPy – Numerical computations
Pandas – Data manipulation and analysis
Matplotlib & Seaborn – Data visualization
Scikit-learn – Model building and evaluation
XGBoost – Advanced gradient boosting


🔍 Project Workflow
1. Data Loading & Exploration
Imported training and test datasets from CSV files
Performed Exploratory Data Analysis (EDA)
Used visualizations (histograms, box plots, heatmaps) to understand distributions, correlations, and missing values

2. Data Preprocessing
Handled missing values using imputation and feature selection
Applied one-hot encoding for categorical variables
Standardized numerical features for better model performance

3. Model Selection & Training
Evaluated multiple regression algorithms:
Linear Regression
SVR
SGD Regressor
KNN Regressor
Decision Tree
Random Forest
Gradient Boosting
XGBoost
MLP Regressor
Used cross-validation to compare models based on R² score
Selected GradientBoostingRegressor as the best-performing model


4. Prediction & Output
Trained the final model on the full dataset
Generated predictions on test data
Saved results in submission.csv for Kaggle submission


📁 Project Files
house_price_prediction.ipynb → Complete workflow (EDA, preprocessing, modeling)
submission.csv → Final predictions
gbr.pkl → Trained Gradient Boosting model (ready for deployment)


💡 Key Takeaways
Strong understanding of end-to-end ML pipeline
Effective feature engineering and preprocessing techniques
Model comparison and selection using cross-validation
Practical experience with real-world structured datasets

🔗 Let’s Connect & Collaborate
For discussions, collaborations, or opportunities, feel free to reach out:
👉 www.linkedin.com/in/shivansh-b2o0r0n5

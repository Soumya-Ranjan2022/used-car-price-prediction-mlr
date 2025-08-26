Used Car Price Forecasting via Multiple Linear Regression

A machine learning project to forecast used car prices using Multiple Linear Regression (MLR).

📌 Project Overview

This project applies Multiple Linear Regression (MLR) to predict the prices of used cars based on various features such as age, mileage (KM), fuel type, horsepower (HP), engine capacity (CC), transmission type, number of doors, weight, and quarterly tax.

The goal is to analyze factors influencing car prices and build a regression model that can forecast prices effectively.

⚙️ Workflow

Data Preprocessing

Handle missing values

Encode categorical variables

Normalize/scale numerical features

Exploratory Data Analysis (EDA)

Statistical summaries

Correlation heatmaps

Distribution plots & pairplots

Model Building

Implement Multiple Linear Regression

Check assumptions (linearity, multicollinearity, homoscedasticity, normality of residuals)

Model Evaluation

R² and Adjusted R²

Root Mean Squared Error (RMSE)

Residual analysis

Insights

Identify key features affecting used car prices

Understand business implications in pricing strategy

📊 Dataset

The dataset contains features such as:

Age: Age of the car (in years)

KM: Mileage in kilometers

FuelType: Type of fuel (Petrol/Diesel/CNG)

HP: Horsepower

Automatic: Transmission type (Manual/Automatic)

CC: Engine capacity

Doors: Number of doors

Weight: Car weight

Quarterly_Tax: Tax associated with the car

Price: Target variable (used car price)

🚀 Technologies Used

Python

Pandas & NumPy – Data manipulation

Matplotlib & Seaborn – Data visualization

Scikit-learn & Statsmodels – Model building and evaluation

Jupyter Notebook – Interactive development

📈 Results

Built a regression model explaining the relationship between car features and price.

Identified age, mileage, fuel type, horsepower, and weight as major influencing factors.

Achieved a good fit with R² and Adjusted R², validating the effectiveness of MLR.

📂 Repository Structure
├── data/                  # Dataset (if included or linked)  
├── notebooks/             # Jupyter notebooks for analysis  
├── scripts/               # Python scripts for preprocessing & modeling  
├── results/               # Plots, residuals, evaluation metrics  
├── README.md              # Project documentation  

🔮 Future Improvements

Compare with advanced models (Ridge, Lasso, Random Forest)

Hyperparameter tuning for better performance

Deploy the model as a web app for real-time predictions

👨‍💻 Author

Soumya

Data Science & Machine Learning Enthusiast

💼 LinkedIn
 | 📧 Email

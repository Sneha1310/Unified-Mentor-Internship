# 💻 Laptop Price Analysis & Prediction

## 📌 Objective
The goal of this project is to analyze laptop specifications and predict their prices using machine learning techniques.  

## 📊 Dataset
- Dataset contains laptop details such as Company, Type, RAM, Weight, CPU, GPU, OS, and Price.  
- Each row represents a laptop with its configuration and corresponding price.  

## ⚙️ Steps / Methodology
1. Data Cleaning & Preprocessing  
   - Handled missing values  
   - Converted categorical variables to numerical (encoding)  
   - Feature scaling for numerical columns  

2. Exploratory Data Analysis (EDA)  
   - Visualized distribution of prices  
   - Analyzed relationships between features (RAM, GPU, Storage, etc.) and price  

3. Model Building  
   - Applied multiple algorithms: Linear Regression, Decision Tree, Random Forest, Gradient Boosting  
   - Compared performance using metrics (R², MAE, RMSE)  

4. Model Evaluation  
   - Random Forest & Gradient Boosting gave the best results  
   - Identified key predictors of laptop price  

## 📌 Key Findings
- RAM, GPU, and CPU significantly influence laptop prices.  
- SSD storage impacts price more than HDD.  
- Higher screen resolution and dedicated graphics lead to premium pricing.  

## 🛠 Tech Stack
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

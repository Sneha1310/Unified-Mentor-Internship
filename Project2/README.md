# Customer Satisfaction Prediction 🛒🤝

## 📌 Overview
This project predicts **customer satisfaction** using survey and support ticket data.  
The goal is to analyze key factors affecting satisfaction and build a machine learning model to predict it.

---

## 📂 Dataset
The dataset includes:
- **Customer demographics** (Age, Gender, Income, Education)  
- **Support-related features** (Ticket Type, Priority, Channel, Resolution Time)  
- **Feedback scores & overall satisfaction**  
- **Optional text fields** (Ticket Descriptions)

---

## 🔑 Steps Implemented
1. **Data Preprocessing**
   - Removed duplicates and handled missing values
   - Encoded categorical variables (Label Encoding / One-Hot Encoding)
   - Scaled numerical features

2. **Exploratory Data Analysis (EDA)**
   - Distribution plots for customer age, priority, and channels
   - Correlation heatmap for numerical variables
   - Satisfaction trends by ticket priority and channel

3. **Feature Engineering**
   - Created ratios and handled text features using **TF-IDF**

4. **Model Building**
   - Built a **Random Forest Classifier** within a preprocessing pipeline
   - Trained & tested using an 80-20 split

5. **Model Evaluation**
   - Accuracy score, classification report, and confusion matrix
   - Feature importance analysis

---

## 📊 Results
- Achieved good **prediction accuracy** on customer satisfaction.  
- Key drivers of satisfaction include **ticket priority, resolution speed, and service quality**.  
- Text data (ticket descriptions) adds predictive value.  

---

## 🛠️ Tech Stack
- **Python**, **Pandas**, **NumPy**  
- **Matplotlib, Seaborn** (EDA & Visualization)  
- **Scikit-learn** (ML models & pipeline)  

---

## 📌 Conclusion
This project shows how customer feedback and service interactions can be modeled using ML to predict satisfaction.  
Businesses can use these insights to **improve support processes** and **prioritize high-impact factors** for customer retention.  

---

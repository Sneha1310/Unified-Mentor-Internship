# 🧪 Exploratory Data Analysis of COVID-19 Clinical Trials

## 📌 Objective
The goal of this project is to explore the COVID-19 Clinical Trials dataset from **ClinicalTrials.gov** to gain insights into trial status, phases, demographics, and trends over time.

## 📊 Dataset
- Source: [ClinicalTrials.gov](https://clinicaltrials.gov/)  
- Format: CSV (original XML converted to structured data)  
- Key columns: `Status`, `Phases`, `Age`, `Gender`, `Conditions`, `Outcome Measures`, `Start Date`, `Primary Completion Date`.

## 🛠️ Steps Performed
1. **Data Loading & Cleaning**
   - Standardized column names
   - Handled missing values (median for numerics, "Missing" for categories)
   - Dropped unnecessary columns

2. **Univariate Analysis**
   - Distribution of trial **status**, **phases**, **age groups**, and **gender**

3. **Bivariate Analysis**
   - Relationship between **status and phases**
   - Common **conditions vs. outcome measures**

4. **Time-Series Analysis**
   - Trends in trials initiated over time

5. **Data Export**
   - Cleaned dataset saved as `cleaned_covid_clinical_trials.csv`

## 📈 Key Findings
- Majority of trials are **Completed** or **Ongoing**
- Most trials fall under **Phase 2** and **Phase 3**
- Adults were the main demographic studied
- Trial numbers increased significantly during major COVID-19 outbreak periods

## 🖥️ Tech Stack
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

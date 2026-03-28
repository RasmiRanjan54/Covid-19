# COVID-19 Data Analysis using Python

##  Project Overview
This project focuses on analyzing COVID-19 patient and case-level data to understand
disease trends, patient severity, and risk factors. The goal is to extract meaningful
insights using data cleaning, exploratory data analysis (EDA), and visualization techniques.

The project is designed with a structured workflow suitable for real-world data analysis
and showcases a strong foundation in Python-based analytics.

---

##  Dataset Description
The dataset contains COVID-19 related patient and case data including:
- Patient demographics (Age)
- Hospitalization indicators (ICU, Intubation)
- Chronic medical conditions (Diabetes, Hypertension, Obesity, etc.)
- Time-series COVID case data for trend analysis

Each row represents an individual patient or a daily reported record, depending on the dataset file.

---

##  Tools & Technologies Used
- Python
- Pandas & NumPy (Data handling & analysis)
- Matplotlib & Seaborn (Static visualizations)
- Plotly (Interactive visualizations)
- Jupyter Notebook
- VS Code

---

##  Data Analysis Workflow

### 1️⃣ Data Loading & Validation
- Loaded datasets using relative paths
- Verified structure using `.shape()`, `.head()`, and `.info()`

### 2️⃣ Data Cleaning
- Handled missing values based on medical and logical reasoning
- Binary medical indicators filled conservatively
- Numerical attributes handled using statistical methods (median)

### 3️⃣ Exploratory Data Analysis (EDA)
- Age distribution analysis
- ICU admission analysis by age
- Chronic disease distribution and severity analysis
- Feature engineering to capture overall comorbidity burden

### 4️⃣ Visualization
- Histograms and boxplots for demographic insights
- Countplots for disease prevalence
- Correlation heatmap for relationship analysis
- Interactive time-series plots using Plotly

---

## 📊 Key Insights
- Older patients have a significantly higher likelihood of ICU admission
- Presence of chronic diseases increases severity risk
- ICU admissions are strongly associated with comorbidity burden
- Rolling averages help identify clearer COVID-19 trends over time

---

## 📁 Project Structure

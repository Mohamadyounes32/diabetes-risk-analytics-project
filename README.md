# GlucoPulse – Diabetes Risk & Population Health Analytics

## Project Overview

GlucoPulse is an end-to-end healthcare analytics project built using Python, Machine Learning, and Power BI.

The project analyzes diabetes risk factors using the CDC BRFSS 2015 dataset and provides interactive dashboards to identify high-risk populations, understand health patterns, and support data-driven healthcare decisions.

---

## Business Problem

Diabetes is one of the most common chronic diseases worldwide and is influenced by multiple demographic, behavioral, and health-related factors.

The goal of this project is to:

* Identify the strongest diabetes risk factors.
* Analyze population health indicators.
* Segment the population into meaningful health groups.
* Build an interactive dashboard for decision-makers.

---

## Dataset Information

**Source:** CDC BRFSS 2015 Health Indicators Dataset

**Records:** 229,474

**Features:** 23

**Target Variable:**

* Diabetes_binary

  * 0 = No Diabetes
  * 1 = Diabetes

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* K-Means Clustering
* Jupyter Notebook
* Power BI
* Git & GitHub

---

## Project Workflow

### 1. Data Cleaning

* Data quality assessment
* Missing value validation
* Data type verification
* Feature preparation

### 2. Exploratory Data Analysis (EDA)

* Diabetes prevalence analysis
* Demographic analysis
* Health indicator exploration
* Lifestyle factor investigation

### 3. Population Health Analysis

* Physical health assessment
* Mental health assessment
* Healthcare access evaluation
* Lifestyle behavior analysis

### 4. Population Segmentation

K-Means clustering was used to identify population segments based on:

* BMI
* Physical Health
* Mental Health
* Age
* Health Indicators

Three clusters were identified:

* Low Risk Population
* Medium Risk Population
* High Risk Population

### 5. Power BI Dashboard Development

An interactive dashboard was built to communicate insights and support decision-making.

---

## Key Findings

### Diabetes Prevalence

* Approximately 15.3% of the population reported having diabetes.

### BMI Impact

* Individuals with diabetes have significantly higher BMI compared to non-diabetic individuals.

### Major Risk Factors

The strongest diabetes-associated risk factors include:

* High Blood Pressure
* High Cholesterol
* Heart Disease
* Physical Inactivity

### Age Impact

* Diabetes prevalence increases substantially with age.
* Older populations represent the highest-risk groups.

### Population Segmentation

Three distinct population health segments were identified:

| Cluster   | Risk Level  |
| --------- | ----------- |
| Cluster 0 | Low Risk    |
| Cluster 2 | Medium Risk |
| Cluster 1 | High Risk   |

---

## Dashboard Pages

### 1. Executive Overview

* Total Population
* Diabetes Cases
* Diabetes Rate
* Average BMI
* Age Group Analysis
* Population Risk Overview

![Overview Dashboard](images/overview.png)

---

### 2. Risk Factor Analysis

* Hypertension Analysis
* Cholesterol Analysis
* Smoking Analysis
* Physical Activity Analysis
* Risk Factor Ranking

![Risk Factor Analysis](images/risk_analysis.png)

---

### 3. Population Health Analysis

* Physical Health Indicators
* Mental Health Indicators
* Healthcare Access
* Demographic Insights
* Lifestyle Analysis

![Population Health Analysis](images/population_health.png)

---

### 4. Population Segmentation

* Low Risk Cluster
* Medium Risk Cluster
* High Risk Cluster
* Cluster Comparison

![Cluster Segmentation](images/clustering.png)

---

## Power BI Dashboard

The complete interactive Power BI dashboard is available in:

```text
dashboard/Diabetes_Risk_Analytics.pbix
```

---

## Results

* Identified major diabetes risk factors associated with increased diabetes prevalence.
* Discovered three distinct population health segments using K-Means clustering.
* Developed a four-page interactive Power BI dashboard.
* Generated actionable healthcare recommendations for high-risk populations.
* Applied population segmentation techniques to support data-driven healthcare decisions.

---

## Repository Structure

```text
diabetes-risk-analytics-project/
│
├── data/
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_exploratory_data_analysis.ipynb
│   ├── 03_statistical_analysis.ipynb
│   ├── 04_clustering_analysis.ipynb
│   ├── 05_population_health_analysis.ipynb
│   └── 06_powerbi_preparation.ipynb
│
├── dashboard/
│   └── Diabetes_Risk_Analytics.pbix
│
├── images/
│   ├── overview.png
│   ├── risk_analysis.png
│   ├── population_health.png
│   └── clustering.png
│
├── requirements.txt
│
└── README.md
```

---

## Author

**Mohamad Younes**

Healthcare & Data Analytics Portfolio Project

GitHub:
https://github.com/Mohamadyounes32

---

## Future Improvements

* Predictive Diabetes Risk Modeling
* Advanced Feature Engineering
* Time-Series Health Monitoring
* Deployment using Streamlit

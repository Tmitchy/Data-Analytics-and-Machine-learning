# Data-Analytics-and-Machine-learning

---

# 📊 Glassdoor Job Market Data Analysis

## Overview
This repository presents a **comprehensive data analytics and machine learning project** conducted on the *Glassdoor Job Market Dataset* (`Tabular_DS_Jobs.csv`). The project follows the **full data science lifecycle**, from data cleaning and exploratory analysis to hypothesis testing, predictive modeling, and an introduction to deep learning concepts.

The analysis was implemented using **Python in Google Colab**, focusing on uncovering patterns in salaries, job locations, company characteristics, seniority, and technical skill requirements in the data science job market.

---

## 📁 Dataset Summary
- **Source:** Glassdoor job postings  
- **Rows:** 649  
- **Columns:** 18+ features after feature engineering  

### Key Features
- Job information: *Job Title, Job Description, Job Type, Seniority*
- Salary details: *Minimum, Maximum, and Average Salary*
- Company attributes: *Rating, Size, Revenue, Ownership Type, Industry, Sector, Company Age*
- Location data: *Job State, Headquarters, Same State Indicator*
- Skills (binary): *Python, Excel, Hadoop, Spark, AWS, Tableau, Big Data*

---

## 🎯 Project Objectives
- Clean and prepare real-world job market data for analysis  
- Explore salary trends across locations, industries, and company attributes  
- Perform hypothesis testing to validate salary and seniority relationships  
- Build predictive models for salary estimation and seniority classification  
- Apply clustering and association rule mining to uncover hidden job market patterns  
- Introduce deep learning concepts in job market analytics  

---

## 🛠️ Tools & Technologies Used
- **Programming Language:** Python  
- **Environment:** Google Colab  
- **Libraries:**
  - Data Handling: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`
  - Statistics: `scipy`
  - Machine Learning: `scikit-learn`

---

## 📌 Project Structure & Analysis

### 1️⃣ Data Cleaning & Preparation
- Removed duplicates and handled missing values
- Standardized column names and formats
- Engineered features such as *Company Age*, *Same State*, and salary metrics
- Saved cleaned dataset for reuse

### 2️⃣ Descriptive Analytics & Visualization
- Summary statistics for salary (mean, median, mode, standard deviation)
- Salary distribution by job state
- Company rating distribution
- Visual analysis of regional salary variations

### 3️⃣ Hypothesis Testing & Multivariate Analysis
- **t-test:** Compared salaries between same-state and different-state job locations  
- **Chi-square test:** Tested independence between seniority and company type  
- **Correlation heatmap:** Examined relationships among numerical variables  

### 4️⃣ Predictive Analytics
- Salary trend analysis using company founding year
- **Linear Regression:** Predicting average salary
- **K-Means Clustering:** Grouping jobs by salary and company rating
- **Classification Model:** Predicting seniority using salary, rating, and company age
- **Association Rules:** Identifying skill relationships (e.g., *Python → Tableau*)

### 5️⃣ Deep Learning Concepts
- Strategies for handling missing data based on missing patterns and proportions
- Comparison between traditional machine learning and deep learning approaches

---

## 🛡️ Relevance to a SOC Analyst Role

This project provides **strong foundational skills directly applicable to a Security Operations Center (SOC) Analyst role**, even though the dataset focuses on job market data.

### Key Transferable Skills

- **Data Cleaning & Log Preparation**  
  SOC analysts routinely clean, normalize, and validate security logs (SIEM data, alerts, network events). The data preprocessing and feature engineering performed here mirrors real-world log analysis tasks.

- **Pattern Detection & Anomaly Identification**  
  Techniques such as clustering, correlation analysis, and exploratory data analysis are essential for identifying abnormal behavior, suspicious trends, and potential security incidents.

- **Statistical Thinking & Hypothesis Testing**  
  Hypothesis testing builds analytical reasoning skills needed to assess whether observed security events are random noise or indicators of compromise.

- **Machine Learning for Threat Detection**  
  Predictive models, classification, and clustering form the basis of modern SOC tooling, including:
  - Alert prioritization  
  - Threat classification  
  - Behavioral analytics  

---

## ✅ Key Outcomes of This Project

- Developed a **complete, end-to-end data analytics workflow** using real-world, noisy data  
- Gained hands-on experience in **data cleaning, feature engineering, and validation**  
- Demonstrated the ability to **extract meaningful insights from large datasets**  
- Applied **statistical reasoning** to test assumptions and validate findings  
- Built and evaluated **predictive models** for regression and classification tasks  
- Used **clustering techniques** to uncover hidden structures in job market data  
- Identified **strong skill relationships** using association rule mining  
- Strengthened **Python programming and analytical problem-solving skills**  
- Improved ability to **communicate technical findings through visualizations and reports**  
- Established a strong foundation for applying **machine learning and analytics to cybersecurity and SOC environments**

---

## 📎 Notes
- This project was developed as part of an academic data analytics assignment.
- All analysis was performed using Python in Google Colab.
- The cleaned dataset and analysis scripts are included in this repository.


# **PowerCo Churn Analysis – BCGX Data Science Job Simulation**

This repository contains my work for the **BCGX Data Science Job Simulation** via **Forage**, where I analyzed customer churn for **PowerCo**, a major energy provider. The project follows a **real-world data science workflow**, from **business understanding** to **predictive modeling** and **recommendations**.

Will upload the respective code in a while

---

## **Project Overview**  
PowerCo is experiencing **customer churn** and wants to understand its causes, particularly whether **price sensitivity** is a key factor. Through **data analysis, feature engineering, and machine learning modeling**, this project predicts churn and provides actionable recommendations.

---

## **Tasks Breakdown**  

### **Task 1: Business Understanding & Hypothesis Framing**  
📌 **Objective**: Understand PowerCo’s churn issue and define a structured analysis approach.  
✅ **What I Did**:  
- Framed the problem using **BCG’s Data Science methodology**.  
- Identified **key factors** affecting churn (e.g., price, contract terms, customer engagement).  
- Outlined **data requirements** and proposed **EDA techniques** for deeper investigation.  
- Drafted a **professional email** to stakeholders summarizing the approach.  

---

### **Task 2: Exploratory Data Analysis (EDA)**  
📌 **Objective**: Perform **EDA** to analyze trends in churn and pricing.  
✅ **What I Did**:  
- Merged **customer data and pricing data** for analysis.  
- Checked for **missing values, data distributions, and correlations**.  
- Visualized **pricing trends vs. churn** using **boxplots and heatmaps**.  
- Found that **price sensitivity alone does not explain churn**—other factors matter more.  

---

### **Task 3: Feature Engineering & Data Preparation**  
📌 **Objective**: Engineer new features to improve churn prediction accuracy.  
✅ **What I Did**:  
- Extracted **time-based features** (activation year, tenure, renewal dates).  
- Created a **key feature**: **Difference between off-peak prices in December and January** to measure price sensitivity.  
- Computed **rolling price variance metrics** to analyze **pricing fluctuations over time**.  
- Merged all features into a **cleaned dataset for modeling**.  

---

### **Task 4: Predictive Modeling & Evaluation**  
📌 **Objective**: Train a **Random Forest model** to predict churn and evaluate its performance.  
✅ **What I Did**:  
- Trained a **Random Forest Classifier** with **optimized hyperparameters**.  
- Evaluated using **Accuracy, Precision, Recall, F1-score, and ROC-AUC**.  
- Found that **contract tenure and customer engagement were stronger churn predictors than pricing**.  
- Visualized a **confusion matrix and feature importance plot** to interpret results.  

---

### **Task 5: Findings & Recommendations (Executive Summary)**  
📌 **Objective**: Present **data-driven insights** and **business recommendations**.  
✅ **What I Did**:  
- Summarized key findings in an **executive summary for stakeholders**.  
- Recommended **targeted retention strategies** for high-risk customers (e.g., loyalty programs, pricing incentives).  
- Suggested **operational changes** to improve customer retention.  
- Delivered insights in a structured **PowerCo Churn Report**.  

---

## **Key Takeaways**  
✅ **Price sensitivity alone does not drive churn**—contract tenure and engagement are bigger factors.  
✅ **Predictive modeling helps identify at-risk customers early**, allowing proactive retention strategies.  
✅ **Feature engineering significantly improves model performance** by capturing business-relevant trends.  
✅ **A data-driven approach enables PowerCo to make informed business decisions** to reduce churn.  

---

## **Technologies Used**  
- **Python (Pandas, NumPy, Seaborn, Matplotlib, Scikit-Learn)**  
- **Random Forest Classifier for predictive modeling**  
- **Jupyter Notebooks for EDA & Modeling**  
- **FPDF for report generation**  

---

## **Next Steps**  
🚀 **Further Optimization**: Try **XGBoost or Logistic Regression** for comparison.  
📊 **Customer Segmentation**: Cluster customers to create **personalized retention plans**.  
🔍 **A/B Testing**: Evaluate the impact of **pricing and engagement strategies** on churn reduction.  

---

This project was an **incredible experience**, reinforcing my passion for **Data Science, Machine Learning, and Data Engineering**. 🚀 I’m excited to apply these skills in **real-world business problems**!  

Let’s connect! 🤝  

#DataScience #MachineLearning #ChurnPrediction #BCGX #Forage #OpenToWork  


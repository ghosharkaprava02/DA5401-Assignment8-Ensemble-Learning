# DA5401-Assignment8-Ensemble Learning  
### Ensemble Learning for Complex Regression  
**Modeling on Bike Share Data**

---

**Name:** Arkaprava Ghosh  
**Roll Number:** DA25C003  
**Date:** Sunday, November 09, 2025  

---

##  Repository Structure  
- **DA5401_Assignment8_DA25C003.ipynb** — Main Jupyter Notebook containing code implementation, analysis, and results  
- **README.md** — This documentation file  

---

## Overview  
This repository contains my submission for **Assignment 8 of DA5401 – Ensemble Learning for Complex Regression**.  
The objective of this assignment is to apply and compare **ensemble learning techniques**—**Bagging**, **Boosting**, and **Stacking**—to a **complex, real-world regression problem** using the **Bike Sharing Demand Dataset** (over 17,000 hourly records).

As a data scientist for a city’s **bike-sharing program**, my goal is to accurately **predict the hourly bike rental count (`cnt`)**, which is influenced by **weather**, **time of day**, and **seasonal trends**. The dataset exhibits **non-linear patterns** and **high variability**, making it a suitable challenge for exploring ensemble methods.

---

##  Objectives & Methods  
The assignment focuses on understanding how ensemble techniques address **bias** and **variance**, and how model diversity can improve predictive performance.

- **Bagging Regressor** → Reduces **variance** by training multiple models on random subsets and averaging predictions.  
- **Gradient Boosting Regressor** → Reduces **bias** by sequentially correcting previous errors and capturing complex relationships.  
- **Stacking Regressor** → Combines **diverse base models** (KNN, Bagging, and Gradient Boosting) using a **Ridge Regression** meta-learner to optimally blend predictions.

Model performance is compared using the **Root Mean Squared Error (RMSE)** to evaluate accuracy and generalization.

---

##  Workflow Overview  
1. **Data Loading & Exploration** – Imported the Bike Sharing dataset, checked for missing values, and explored key features.  
2. **Data Preprocessing** – Handled encoding, scaling, and feature transformations.  
3. **Model Training** – Implemented and tuned Bagging, Boosting, and Stacking regressors.  
4. **Performance Evaluation** – Calculated and compared RMSE values to assess each method’s effectiveness.  

---

## Key Results  
The **Stacking Regressor** achieved the **lowest RMSE of 47.81**, outperforming the **Gradient Boosting Regressor (48.22)**, **Baseline (98.10)**, and **Bagging Regressor (114.42)**.  

This demonstrates how stacking effectively combines diverse models to balance **bias and variance**, leveraging the unique strengths of each approach for improved predictive power.

---

##  Conclusion  
This assignment highlights how **ensemble learning** techniques—particularly stacking—can enhance performance in complex regression tasks.  
By combining models with different learning behaviors, we can achieve a balance between **generalization** and **accuracy**, resulting in more robust predictions.

Ensemble methods like these play a key role in modern machine learning pipelines, especially for **real-world forecasting problems** where data is noisy, non-linear, and dynamic.

---

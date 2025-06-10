# Patient Length of Stay (LOS) Prediction
Machine learning project to predict patient Length of Stay (LOS) in hospitals using a multiclass classification approach, with extensive EDA, model training, and hyperparameter tuning.

-----CODE IN RMD FILE
-----RESULT IN THE WORD FILE



This repository contains a comprehensive data science project aimed at predicting the **Length of Stay (LOS)** of patients in hospitals using machine learning techniques. The goal is to support healthcare management by enabling better resource allocation, infection control, and treatment optimization.

## Project Context

The COVID-19 pandemic highlighted the critical need for efficient hospital management. One key metric is **Length of Stay (LOS)** — knowing it in advance can help hospitals allocate beds, plan logistics, and improve patient care.

This project uses a labeled dataset (`LOS.csv`) where the **LOS is a categorical variable** representing stay duration from less than 10 days to more than 100 days. The task is to build accurate models that can classify each patient's LOS at the time of admission.

---

##  Objectives

- Perform exploratory data analysis to understand data characteristics.
- Preprocess the dataset using an appropriate `tidymodels` recipe.
- Build and evaluate at least **8 distinct classification models**.
- Use AUC, accuracy, and confusion matrix as evaluation metrics.
- Visualize and compare model performance using ROC curves and other plots.
- Tune hyperparameters using different grid search strategies.
- Select the best model for final deployment-ready evaluation.

---

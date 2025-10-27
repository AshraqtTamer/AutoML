# 🧠 AutoML Project — FLAML, LazyPredict & MLflow

This project demonstrates **Automated Machine Learning (AutoML)** using three main tools:
- **[FLAML](https://github.com/microsoft/FLAML)** — Fast Lightweight AutoML for efficient model tuning  
- **[LazyPredict](https://github.com/shankarpandala/lazypredict)** — Quick model benchmarking for regression and classification  
- **[MLflow](https://mlflow.org/)** — Tracking and managing machine learning experiments  

---

## 📘 Overview

The notebook automates the process of:
1. Loading and preparing datasets  
2. Automatically selecting and tuning models with **FLAML**  
3. Comparing multiple ML algorithms quickly using **LazyPredict**  
4. Logging metrics, parameters, and models with **MLflow**

This is ideal for anyone looking to streamline ML experimentation and evaluation.

---

## 📊 Datasets Used

| Section | Dataset | Task | Source |
|----------|----------|------|--------|
| FLAML | `USA_HousingFinal.csv` | Regression (predict house prices) | Custom CSV |
| LazyPredict | `Iris` | Classification | scikit-learn |
| LazyPredict | `California Housing` | Regression | scikit-learn |

---

## ⚙️ Installation

Run the following commands in your environment (e.g., Google Colab or local):

```bash
!pip install flaml lazypredict mlflow scikit-learn pandas

# Supply Chain Data Segmentation
**Kyle R. Hudson — Northwest Missouri State University**
MS Data Analytics Capstone Project

## Project Overview
This project sits at the intersection of consumer behavior analytics and supply chain logistics. Using the Customer Shopping Trends dataset from Kaggle, the goal is to route customer orders to the most appropriate warehouse to maximize on-time delivery while minimizing fulfillment cost.

## Problem Statement
Given a diverse customer base purchasing products across multiple categories, how can orders be routed to the most appropriate warehouse to maximize the likelihood of on-time delivery while minimizing fulfillment cost?

## Dataset
- **Source:** [Customer Shopping Trends Dataset — Kaggle](https://www.kaggle.com/datasets/iamsouravbanerjee/customer-shopping-trends-dataset)
- **Format:** CSV
- **Records:** 3,900
- **Attributes:** 18

## Warehouse Locations
Orders are routed to one of six regional distribution centers:

| Warehouse | Location | Region |
|---|---|---|
| Lewisberry_PA | Lewisberry, PA | Northeast / Mid-Atlantic |
| Marietta_GA | Marietta, GA | Southeast |
| Irving_TX | Irving, TX | South / Southwest |
| Lees_Summit_MO | Lee's Summit, MO | Midwest |
| Reno_NV | Reno, NV | Mountain / Intermountain West |
| Union_City_CA | Union City, CA | West Coast |

## Project Phases
1. Problem Definition & Scope
2. Data Understanding & EDA
3. Data Preparation & Feature Engineering
4. Analytics & Modeling
5. Warehouse Optimization Logic
6. Evaluation & Validation
7. Visualization & Reporting
8. Documentation & Presentation

## Repository Contents
| File | Description |
|---|---|
| `eda.ipynb` | Exploratory Data Analysis notebook |
| `model.ipynb` | Warehouse assignment classification model |
| `Dataset/Customer Shopping Trends/shopping_trends_project.csv` | Working dataset |
| `Mod5/confusion_matrix_rf.png` | Random Forest confusion matrix |
| `Mod5/feature_importance_rf.png` | Random Forest feature importance chart |

## Models
| Model | Accuracy |
|---|---|
| Random Forest | 73.97% |
| Logistic Regression | 28.21% |

## Tools & Libraries
- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- Jupyter Notebook

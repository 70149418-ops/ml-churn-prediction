# Customer Churn Prediction — ML Semester Project

**Course:** CS-13410 Introduction to Machine Learning · Fall 2026 · The University of Lahore
**Group members:** Name 1, Name 2, Name 3, Name 4

## Project
We predict whether a telecom customer will leave the company ("churn") using the
IBM Telco Customer Churn dataset (7,043 customers, 21 columns). Binary classification;
main metrics: F1-score and ROC-AUC.

## Files
| File | What it is |
|---|---|
| `ML_Project_Churn.ipynb` | Main notebook — one section per project part |
| `Telco-Customer-Churn.csv` | Dataset |
| `requirements.txt` | Python libraries needed |

## Progress
- [x] Part 1 — Data Preparation & Pipeline
- [ ] Part 2 — Supervised Learning Baseline (Naive Bayes vs Decision Tree)
- [ ] Part 3 — Ensembles & Hyperparameter Optimisation
- [ ] Part 4 — Neural Network, Unsupervised Learning & Interpretability
- [ ] Part 5 — Final report & viva

## How to run
```
pip install -r requirements.txt
jupyter notebook ML_Project_Churn.ipynb
```
Or open the notebook in Google Colab — it downloads the dataset automatically if the CSV is missing.

## Dataset source
IBM, "Telco Customer Churn": https://github.com/IBM/telco-customer-churn-on-icp4d

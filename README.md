# Creep Life Prediction using Machine Learning

## Overview

This project focuses on predicting the **high-temperature creep life of materials** using Machine Learning techniques.
Creep is a time-dependent deformation that occurs under constant stress at elevated temperatures, and accurate prediction is crucial for material design and safety.

---

## Objective

* Predict creep life based on experimental data
* Compare performance of different ML models
* Analyze model accuracy and generalization

---

## Dataset

The dataset consists of experimental creep data with features such as:

* Time
* Strain
* Temperature
* Stress (if available)

---

## Technologies Used

* Python 
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* XGBoost

---

## Machine Learning Models

The following models were implemented and compared:

* Linear Regression
* Polynomial Regression
* Random Forest Regressor 
* XGBoost Regressor 

---

## Evaluation Metrics

Since this is a regression problem, the following metrics were used:

* Mean Squared Error (MSE)
* R² Score

---

## Key Findings

* Random Forest performed better than XGBoost on this dataset
* XGBoost required careful hyperparameter tuning
* Data showed non-linear relationships

---

## Model Performance

| Model | Mean Squared Error (MSE) | R² Score |
|------|--------------------------|---------|
| Linear Regression | 4.2557 | 0.0039 |
| Polynomial Regression | 3.727 | 0.1276 |
| Random Forest Regression | 0.8157 | 0.8091 |
| XGBoost Regression | 1.0423 | 0.7560 |


## How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com//creep_life-prediction.git
```

2. Navigate to the project folder:

```bash
cd creep_life-prediction
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Run the script:

```bash
python main.py
```

---

## Sample Workflow

* Data preprocessing
* Feature selection
* Train-test split
* Model training
* Prediction & evaluation

---

## Future Work

* Apply Deep Learning models
* Use larger experimental datasets
* Feature engineering (log transformations, etc.)
* Hyperparameter optimization

---

## Author

**Randhir Kumar**

---

## Acknowledgment

This project is based on experimental creep data and aims to bridge material science with machine learning.

---
## Conclusion

The study demonstrates that creep behavior is highly non-linear, and ensemble models like Random Forest are more effective than traditional regression techniques for accurate prediction.

---
## Contact

Feel free to reach out for collaboration or suggestions!

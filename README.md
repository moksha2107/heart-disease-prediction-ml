# Heart Disease Prediction using Machine Learning

## Overview

This project focuses on predicting heart disease using multiple machine learning algorithms and feature selection techniques. It combines statistical feature selection methods with ensemble learning models to improve prediction accuracy and reliability.

## Features

* Data preprocessing and cleaning
* Feature selection using:

  * Chi-Square
  * ANOVA
  * Mutual Information
* Multiple ML models:

  * Naive Bayes
  * SVM
  * Random Forest
  * XGBoost
  * Logistic Regression
  * KNN
  * Decision Tree
  * AdaBoost
  * Bagging
* Ensemble models:

  * Voting Classifier
  * Stacking Classifier
* SMOTE for handling imbalanced data
* Flask-based web interface for predictions

## Tech Stack

* Python
* Scikit-learn
* TensorFlow / Keras
* Pandas, NumPy
* Matplotlib, Seaborn
* Flask

## Dataset

* UCI Heart Disease Dataset

## Methodology

1. Data Collection & Preprocessing
2. Feature Selection (ANOVA, Chi2, MI)
3. Model Training & Evaluation
4. Ensemble Learning (Voting & Stacking)
5. Deployment using Flask

## Results

* Voting Classifier Accuracy: ~86%
* Stacking Classifier Accuracy: 100% (experimental result)

## How to Run

```bash
git clone https://github.com/your-username/heart-disease-prediction-ml.git
cd heart-disease-prediction-ml
pip install -r requirements.txt
python app.py
```

Open:
http://127.0.0.1:5000/


## Future Improvements

* Integration of Explainable AI (XAI)
* Deep Learning models
* Larger datasets for generalization

## License

MIT License

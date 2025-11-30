# Heart Disease Prediction Project

This project predicts the presence of heart disease using a classification model built with Python. It demonstrates the full data science workflow: data loading, cleaning, EDA, feature engineering, model training (Logistic Regression and Random Forest), evaluation, and interpretation.

## Dataset

* Source: [Kaggle Heart Failure Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)
* Format: CSV (`heart.csv`)

## Features

* Demographic: Age, Sex
* Clinical: Chest Pain Type, RestingBP, Cholesterol, FastingBS, RestingECG, MaxHR, ExerciseAngina, Oldpeak, ST_Slope
* Target: HeartDisease

## Models

* Logistic Regression
* Random Forest

## Results

* Accuracy: ~89% (Logistic Regression), ~88% (Random Forest)
* ROC-AUC: 0.93 (Random Forest)
* Key features: ST_Slope, MaxHR, Cholesterol, Oldpeak, ExerciseAngina

## Interactive Dashboard

Explore the full interactive analysis, including EDA, feature importance, and prediction results, via Zoho Analytics:

[Open Dashboard](https://analytics.zoho.com/open-view/3185229000000010233)

Or embed directly on your website:

```html
<iframe src="https://analytics.zoho.com/open-view/3185229000000010233" width="100%" height="600"></iframe>
```

## How to Use

1. Download the dataset (`heart.csv`) and place it in the same folder as the notebook.
2. Run the Jupyter Notebook cells sequentially.
3. Optionally, view predictions and insights on the interactive dashboard.

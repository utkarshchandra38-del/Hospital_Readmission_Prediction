# Hospital Readmission Prediction

A machine learning project that predicts whether a patient is likely to be readmitted to the hospital within 30 days using Logistic Regression with L2 regularization.

## Features

- Data exploration using `shape`, `info`, and `describe`
- Missing value handling
- Mode imputation for categorical features
- Median imputation for numerical features
- Conversion of `age` to numeric format
- Feature scaling using StandardScaler
- Train-test split
- Logistic Regression with L2 regularization
- ROC-AUC evaluation
- Confusion matrix and classification report
- Analysis of False Positives (FP) and False Negatives (FN)
- Prediction results exported to CSV

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## Model

**Logistic Regression with L2 Regularization**

The model predicts:

- `0` → No readmission within 30 days
- `1` → Readmission within 30 days

## Evaluation

The model is evaluated using:

- ROC-AUC
- Confusion Matrix
- Precision
- Recall
- F1-score

## Output

The project generates `predictions.csv`, containing:

- Readmission probability
- Predicted readmission status

## Project Structure

```text
Hospital-Readmission-Prediction/
│
├── Hospital_Readmission_Prediction.ipynb
├── hospital_readmission.csv
├── predictions.csv
└── README.md

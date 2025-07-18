# Credit Card Fraud Detection using Machine Learning

This project is a comprehensive midterm submission that replicates, evaluates, and enhances the methodology described in the research paper:

**Dornadula, V. N., & Geetha, S. (2019).** _Credit Card Fraud Detection using Machine Learning Algorithms_. Procedia Computer Science, 165, 631–638. https://doi.org/10.1016/j.procs.2020.01.057

## Project Structure

| File Name                                  | Task Description                                                                           |
| ------------------------------------------ | ------------------------------------------------------------------------------------------ |
| `Mid_Term_Project_Replication_Nenko.ipynb` | **Task 1** – Reproducing models from the original paper using Random Forest, Decision Tree |
| `midterm_Bishnu.ipynb`                     | **Task 2** – Applying the same methodology to a similar (new) dataset                      |
| `111project_ml_midterm_basit_shah.ipynb`   | **Task 3** – Hyperparameter tuning of Random Forest and Decision Tree                      |
| `midterm_Bishnu_new_models.ipynb`          | **Task 4** – Testing new models (Logistic Regression, SGD, Isolation Forest, LOF, XGBoost) |

## Tasks Completed

### Task 1 – Reproduce Research Paper

- Implemented all models used in the paper
- Evaluated with Accuracy, Precision, and MCC
- Used SMOTE for handling class imbalance

### Task 2 – Apply to Similar Dataset

- Loaded and preprocessed a similar public dataset
- Followed same methodology (scaling, SMOTE, classification)

### Task 3 – Parameter Tuning

- Tuned using new parameters
- Compared results before and after tuning

### Task 4 – Try New Models

- Added SGDClassifier and XGBoost
- SVM was attempted but replaced with SGD due to long runtime
- Compared performance across all models

## Evaluation Metrics

Each model was evaluated using the following:

- **Accuracy**
- **Precision**
- **Matthews Correlation Coefficient (MCC)**

These metrics help assess performance on highly imbalanced data.

## ⚙️ Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
```

Contents of `requirements.txt`:

```
pandas
numpy
matplotlib
seaborn
scikit-learn
imbalanced-learn
xgboost
```

## Notes

- The original dataset used in the paper was from [Kaggle Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).
- For Task 2, a similar structure dataset was chosen to evaluate generalizability (https://www.kaggle.com/datasets/bannourchaker/frauddetection).
- SMOTE was consistently applied to address class imbalance issues.
- All notebooks use structured pipelines for clarity and reproducibility.

## Conclusion

This project not only replicates the work in a popular machine learning paper but also tests the robustness and scalability of its methods using:

- A new dataset
- Hyperparameter optimization
- Additional modern algorithms

## Contributors

- Alemu Nenko
- Bishnu Koirala
- Basit Shah

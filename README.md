# Rock vs Mine Prediction

A beginner-friendly sonar signal classification project that uses logistic regression to identify whether an underwater object is a rock (`R`) or a mine (`M`). The project is implemented in `Untitled-1.ipynb` and uses `sonardata.csv` as the dataset.

## Project overview

- `Untitled-1.ipynb`: Jupyter notebook for loading data, training a model, evaluating performance, and predicting a sample sonar signal.
- `sonardata.csv`: Raw sonar dataset with 60 numeric features and a label column.
- `README.md`: This project documentation.

## Dataset details

The dataset contains sonar returns from objects detected underwater:
- 60 numeric feature columns representing sonar signal strengths
- final column is the label: `R` for rock, `M` for mine

## What the notebook does

1. Imports `numpy`, `pandas`, and scikit-learn tools
2. Loads `sonardata.csv` into a pandas DataFrame
3. Inspects the dataset with `head()`, `shape`, and `describe()`
4. Checks label distribution and mean feature values by class
5. Splits data into features (`X`) and target labels (`Y`)
6. Uses `train_test_split` to create training and test sets
7. Trains a `LogisticRegression` model on the training set
8. Evaluates accuracy on both training and test sets
9. Classifies a sample input signal as rock or mine

## Requirements

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- scikit-learn

## How to run

1. Open `Untitled-1.ipynb` in Jupyter Notebook or JupyterLab.
2. Ensure `sonardata.csv` is in the same folder.
3. Run all notebook cells in order.

## Notes and recommendations

- The current model is a simple baseline using logistic regression.
- You can improve this project by adding feature scaling, cross-validation, or alternative classifiers like SVM, Random Forest, or Gradient Boosting.
- For better model evaluation, consider using a validation set and metrics such as precision, recall, and confusion matrix.

## License

This project is for learning and experimentation with sonar signal classification.

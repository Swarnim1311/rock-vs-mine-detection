# Rock vs Mine Prediction

A simple beginner ML project that uses logistic regression to predict whether an underwater object is a rock (`R`) or a mine (`M`) using sonar signal data. The whole project is done in `Untitled-1.ipynb` and uses `sonardata.csv` as the dataset.

## Project Overview

* `Untitled-1.ipynb` → Jupyter notebook where the data is loaded, the model is trained, tested, and used for prediction
* `sonardata.csv` → Dataset containing sonar signal values
* `README.md` → Documentation for the project

## Dataset Details

The dataset contains sonar signals from underwater objects:

* 60 numerical feature columns representing sonar signal strengths
* Last column contains the label:

  * `R` = Rock
  * `M` = Mine

## What the Notebook Does

1. Imports `numpy`, `pandas`, and scikit-learn libraries
2. Loads `sonardata.csv` using pandas
3. Checks the dataset using `head()`, `shape`, and `describe()`
4. Looks at label distribution and average values for each class
5. Separates features (`X`) and labels (`Y`)
6. Splits the dataset into training and testing sets
7. Trains a `LogisticRegression` model
8. Checks accuracy on both training and testing data
9. Predicts whether a sample sonar signal is a rock or mine

## Requirements

* Python 3.x
* Jupyter Notebook
* pandas
* numpy
* scikit-learn

## How to Run

1. Open `Untitled-1.ipynb` in Jupyter Notebook or JupyterLab
2. Make sure `sonardata.csv` is in the same folder
3. Run all the cells one by one

## Notes

* Right now the project uses a simple logistic regression model as a baseline.
* It can be improved by adding feature scaling, cross-validation, or trying models like SVM, Random Forest, or Gradient Boosting.
* You can also use metrics like precision, recall, and confusion matrix for better evaluation.

## License

This project is for learning and experimentation with sonar signal classification.

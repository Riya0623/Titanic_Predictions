
# Titanic Survival Prediction :ship:

This script performs data analysis and builds a predictive model for the Titanic dataset to predict survival based on various features. It includes steps such as data exploration, visualization, feature engineering, data preprocessing, model training, and evaluation.
The script will train a RandomForestClassifier model and generate predictions for the test set. The output will be saved to resultfile.csv.

## Usage :computer:

To use this script, you need to have the following:

- Python 3.x installed
- Required libraries: pandas, numpy, matplotlib, seaborn
- Titanic dataset: `train.csv` and `test.csv`

## Data Description :file_folder:
train.csv
This file contains the training data for the Titanic dataset.
Each row represents a passenger on the Titanic.
The columns include:
PassengerId: Unique identifier for each passenger.
Survived: Target variable indicating whether the passenger survived (1) or not (0).
Pclass: Ticket class (1st, 2nd, or 3rd).
Name: Name of the passenger.
Sex: Gender of the passenger (male or female).
Age: Age of the passenger in years.
SibSp: Number of siblings or spouses aboard the Titanic.
Parch: Number of parents or children aboard the Titanic.
Ticket: Ticket number.
Fare: Fare paid for the ticket.
Cabin: Cabin number.
Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).
test.csv
This file contains the test data for the Titanic dataset.
Similar to train.csv, each row represents a passenger on the Titanic.
However, the Survived column is not included in this file since it's the target variable we're trying to predict.
The columns in test.csv are the same as train.csv, except for the absence of the Survived column.

Clone the repository and run the script using a Python interpreter. Make sure to have the dataset files in the same directory.

```bash
python titanic_prediction.py

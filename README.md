# Titanic Passenger Survival Prediction using Random Forest Classifier

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This is a Python script that uses a Random Forest Classifier to predict the survival of passengers aboard the Titanic based on various features. The script takes a CSV file containing the training data and another CSV file containing the test data with passenger information.

## Prerequisites

Before running the script, ensure you have the following installed:

- Python 3.x
- Pandas
- NumPy
- scikit-learn (sklearn)

You can install the required libraries using pip:

```
pip install pandas numpy scikit-learn
```

## Usage

To use this script, follow these steps:

1. Clone this repository:

```
git clone https://github.com/tdwan100/TitanicSurvivorPrediction.git
cd TitanicSurvivorPrediction
```

2. Make sure you have your training data in a CSV file with relevant columns ('Sex', 'Pclass', 'SibSp', 'Parch', and 'Fare'). Name this file appropriately, for example, `train.csv`.

3. Prepare your test data in a separate CSV file with the same columns as the training data. Name this file accordingly, e.g., `titanic_predictions.csv`.

4. Run the script with the appropriate arguments:

```
python script.py train.csv
```

Replace `train.csv` with the name of your training data file. The script will read the file, perform data processing, train the Random Forest Classifier, make predictions on the test data, and save the results to `titanicresults.csv`.

## Important Note

Make sure your CSV files contain the necessary columns and are formatted correctly. The script assumes that the 'Survived' column exists in the training data (`td` DataFrame). If your training data doesn't have the 'Survived' column, you'll need to modify the script accordingly.

## Troubleshooting

If you encounter any issues with the script or have questions, feel free to create an issue in this repository or contact the author.

## Disclaimer

This script is provided for educational and demonstration purposes only. The accuracy of the predictions may vary depending on the data and features used. It should not be used for critical applications or making real-world decisions. The author and contributors are not responsible for any misuse or damages caused by this script.

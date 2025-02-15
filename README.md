# Naive Bayes Classifier

## Overview
This project implements a **Naive Bayes Classifier** for statistical classification using Python. The classifier leverages the Naive Bayes theorem, which assumes independence between features, making it particularly effective for text classification, spam detection, and other probabilistic tasks.

## Features
- Implements **Naive Bayes classification** for categorical and numerical data.
- Uses **scikit-learn** for modeling and training.
- Supports **data visualization** with matplotlib and seaborn.
- Loads and processes **financial datasets** using yFinance and pandas.

## Installation
To install the required dependencies, run:

```bash
pip install -r requirements.txt
```

### Requirements
The project uses the following Python libraries:

- `yfinance` - Fetches financial data from Yahoo Finance.
- `pandas` - Data manipulation and analysis.
- `numpy` - Numerical computations.
- `scikit-learn` - Machine learning algorithms.
- `matplotlib` - Data visualization.
- `seaborn` - Statistical data visualization.

## Usage
To run the classifier:

```bash
jupyter notebook main.ipynb
```

## Example
1. Load dataset using `pandas`.
2. Preprocess and split the data.
3. Train a Naive Bayes classifier using `scikit-learn`.
4. Evaluate model accuracy and visualize results.

## Project Structure
```
/Naive-Bayes-Classifier
│── main.ipynb          # Jupyter notebook with model implementation
│── requirements.txt    # Required dependencies
│── README.md           # Project documentation
```

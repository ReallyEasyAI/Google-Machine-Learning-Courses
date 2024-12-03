# Google Machine Learning Courses

This repository contains programming exercises from Google's Machine Learning Crash Course. These exercises are implemented using Jupyter Notebooks and use the Keras library to build and evaluate models.

## Repository Structure

- **`binary_classification_rice.ipynb`**: A notebook focused on building a binary classifier for distinguishing between two species of Turkish rice. Includes evaluation metrics and model performance analysis.
- **`linear_regression_taxi.ipynb`**: A notebook that demonstrates how to build a linear regression model to predict the fare of taxi rides in Chicago using real-world data.
- **`requirements.txt`**: Contains the list of Python dependencies required to run the notebooks.

## Notebook Details

### 1. Binary Classification: Rice Dataset
This notebook trains a binary classifier to separate two species of Turkish rice, Osmançik and Cammeo. The steps include:

- Examining the dataset derived from rice images.
- Building and training a binary classifier.
- Calculating and analyzing evaluation metrics like AUC and ROC.

**Dataset**: [Cinar and Koklu 2019 Osmançik and Cammeo rice dataset](https://www.kaggle.com/).

**Learning Objectives**:
- Train a binary classification model.
- Evaluate model performance at different thresholds.
- Compare AUC and ROC curves.

---

### 2. Linear Regression: Taxi Fare Prediction
This notebook demonstrates how to use a linear regression model to predict taxi fares in Chicago. Key tasks include:

- Loading and exploring the dataset from the [City of Chicago Taxi Trips dataset](https://www.chicago.gov/).
- Experimenting with different features for the regression model.
- Tuning hyperparameters and comparing training results using root mean squared error (RMSE).

**Dataset**: Subset of the City of Chicago Taxi Trips data from a two-day period in May 2022.

**Learning Objectives**:
- Use Pandas to process and explore datasets.
- Build and tune a linear regression model.
- Visualize loss curves and analyze model accuracy.

---

## Getting Started

### Prerequisites
To run these notebooks, you need Python 3.x installed along with the required libraries listed in `requirements.txt`. You can install the dependencies by running:

```bash
pip install -r requirements.txt

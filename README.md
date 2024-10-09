# Binary Classification Web App - Mushroom Edibility Predictor 🍄

This web application, built with **Streamlit**, allows users to classify mushrooms as either **edible** or **poisonous** based on various features. It provides multiple classification models for evaluation, including Support Vector Machine (SVM), Logistic Regression, and Random Forest. The app also includes visual metrics to help evaluate the model's performance.

## Features

- **Binary Classification Models**:
  - Support Vector Machine (SVM)
  - Logistic Regression
  - Random Forest
- **Interactive UI**: Set model hyperparameters via sidebar options.
- **Performance Metrics Visualization**:
  - Confusion Matrix
  - ROC Curve
  - Precision-Recall Curve
- **Raw Data Display**: Option to view the raw dataset.

## Data

The dataset used is the **Mushroom Classification Dataset** from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Mushroom). It consists of 23 species of mushrooms categorized as edible or poisonous.

## Usage

1. Select a **classification model** from the sidebar: SVM, Logistic Regression, or Random Forest.
2. Adjust the **model hyperparameters** to tune the model's performance.
3. Click on the **Classify** button to run the model.
4. View the results including **accuracy**, **precision**, and **recall** scores.
5. Optionally, choose to display **Confusion Matrix**, **ROC Curve**, or **Precision-Recall Curve**.
6. Toggle the checkbox to **Show raw data** to inspect the dataset.

   
## Technologies Used

- **Streamlit**: Frontend web framework for building the UI.
- **Pandas**: Data manipulation and preprocessing.
- **Scikit-learn**: Machine learning models and evaluation metrics.
- **NumPy**: Numerical computing.


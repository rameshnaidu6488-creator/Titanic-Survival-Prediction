# Titanic-Survival-Prediction
# Titanic Survival Prediction

## Project Overview

This project uses Machine Learning to predict whether a passenger survived the Titanic disaster based on passenger information such as age, gender, passenger class, fare, and embarkation point.

The project covers the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and evaluation.

---

## Dataset

The dataset used in this project is the Titanic dataset from Kaggle.

Features include:

* Passenger Class (Pclass)
* Sex
* Age
* SibSp
* Parch
* Fare
* Embarked
* Survival Status (Target Variable)

Target Variable:

* 0 = Did Not Survive
* 1 = Survived

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

---

## Project Workflow

### 1. Data Loading

* Imported the Titanic dataset.
* Inspected dataset structure and data types.

### 2. Data Cleaning

* Handled missing values.
* Filled missing values in Age using median values.
* Filled missing values in Embarked using mode values.
* Removed unnecessary columns.

### 3. Exploratory Data Analysis (EDA)

* Survival distribution analysis.
* Gender-wise survival analysis.
* Passenger class analysis.
* Embarkation point analysis.
* Correlation analysis and visualizations.

### 4. Feature Engineering

* Encoded categorical variables.
* Prepared features for machine learning models.

### 5. Model Training

* Split data into training and testing datasets.
* Applied machine learning algorithms.
* Trained the model using the training dataset.

### 6. Model Evaluation

* Accuracy Score
* Confusion Matrix
* Classification Report
* ROC-AUC Analysis

---

## Results

The model successfully predicts passenger survival based on available passenger information.

Performance metrics were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC Score

---

## Repository Structure

```text
Titanic-Survival-Prediction/
│
├── MLProjecttitanic.ipynb
├── README.md
└── requirements.txt
```

---

## How to Run

1. Clone the repository.

```bash
git clone <repository-url>
```

2. Open the notebook in Google Colab or Jupyter Notebook.

3. Install required libraries.

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

4. Run all notebook cells.

---

## Future Improvements

* Try additional machine learning models.
* Hyperparameter tuning.
* Feature selection techniques.
* Deployment using Streamlit or Flask.
* Model comparison and optimization.

---

## Author

Machine Learning Project: Titanic Survival Prediction

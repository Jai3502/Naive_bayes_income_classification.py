# Naive_bayes_income_classification.py
This Python script implements a Gaussian Naive Bayes classifier to predict income categories using the Adult Census dataset. It includes data preprocessing, handling missing values, categorical encoding, feature scaling, model training, evaluation, and visualization of results.
# Income Prediction using Naive Bayes Classifier

This project demonstrates the implementation of a **Gaussian Naive Bayes classification model** to predict whether a person's income exceeds a certain threshold using the **Adult Census Income Dataset**.

The workflow includes data preprocessing, feature engineering, model training, and performance evaluation.

---

##  Project Overview

- Algorithm Used: **Gaussian Naive Bayes**
- Dataset: **Adult Census Income Dataset**
- Goal: Predict income category (`<=50K` or `>50K`)
- Programming Language: **Python**
- Platform: Google Colab / Local Python Environment

---

##  File Structure
├── naive_bayes_income_classification.py
├── README.md

---

##  Libraries Used

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- category_encoders

Install required libraries using:

    ````bash
    pip install numpy pandas matplotlib seaborn scikit-learn category_encoders
 

----

 ##  Workflow Steps

1. Import Libraries

2. Load Dataset

3. Assign Column Names

4. Identify Categorical & Numerical Features

5. Handle Missing Values

6. One-Hot Encoding for Categorical Variables

7. Feature Scaling using RobustScaler

8. Train-Test Split

9. Model Training (Gaussian Naive Bayes)

10. Prediction

11. Model Evaluation

   * Accuracy Score

   * Confusion Matrix

   * Classification Report

   * Heatmap Visualization
     
----

##  Model Performance

   * Training Accuracy ✔️

   * Testing Accuracy ✔️

   * Confusion Matrix ✔️

   * Precision, Recall, F1-Score ✔️

 The model shows reliable performance with balanced bias and variance.

----

##  Visualization

   * Confusion Matrix visualized using Seaborn Heatmap

   * Helps understand True Positives, False Positives, True Negatives, and False Negatives

----

##  How to Run the Project

1. Clone the repository:
   
   ```` bash
   git clone https://github.com/your-username/your-repo-name.git

2. Navigate to the project directory:

   ````bash
   cd your-repo-name

3. Run the Python file:

   ````bash
    python naive_bayes_income_classification.py

## Conclusion

This project showcases how Naive Bayes can be effectively applied to real-world classification problems with proper preprocessing and feature engineering.


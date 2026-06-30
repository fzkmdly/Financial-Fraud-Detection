# Financial Fraud Detection Model

## Project Overview
This project focuses on building a machine learning classification model to accurately identify fraudulent transactions. The primary goal is to develop a robust system that maximizes the detection of actual fraud (high recall) while keeping false alarms to a minimum.

## Dataset
* **Source:** https://www.kaggle.com/datasets/mosapabdelghany/credit-card-fraud-detection
* **Description:** Content The dataset contains transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

  It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

  Given the class imbalance ratio, we recommend measuring the accuracy using the Area Under the Precision-Recall Curve (AUPRC). Confusion matrix accuracy is not meaningful for unbalanced classification.

## Tech Stack
* **Language:** Python
* **Data Manipulation & Analysis:** Pandas, NumPy
* **Data Visualization:** Seaborn, Matplotlib
* **Machine Learning:** Scikit-Learn

## Methodology
1. **Data Cleaning & Preprocessing:** * Handled missing values and performed data type optimization.
   * Addressed class imbalance using techniques like [sebutkan jika ada, misal: SMOTE / Undersampling].
2. **Exploratory Data Analysis (EDA):** * Analyzed feature distributions and correlations using Seaborn visualizations.
3. **Modeling:** * Developed and compared multiple classification algorithms to find the best fit for the data. Models tested include:
     * K-Nearest Neighbors (KNN)
     * Decision Trees
     * Naive Bayes
4. **Evaluation:** * Assessed models focusing on metrics suitable for imbalanced datasets rather than relying solely on standard accuracy.

## Key Results
* **Best Model:** Decision Tree Classifier
* **Performance Metrics:**
  * **Precision:** 0.9970
  * **Recall:** 0.9988
  * **F1-Score:** 0.9979

## How to Run
1. Clone this repository: `git clone https://github.com/fzkmdly/Financial-Fraud-Detection/`
2. Open the Jupyter Notebook: `FraudDetectionv2.ipynb`
3. Run the cells sequentially to reproduce the analysis and model training.

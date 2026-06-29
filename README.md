# Financial Fraud Detection Model

## Project Overview
This project focuses on building a machine learning classification model to accurately identify fraudulent transactions. The primary goal is to develop a robust system that maximizes the detection of actual fraud (high recall) while keeping false alarms to a minimum.

## Dataset
* **Source:** [Masukkan sumber data, misal: Kaggle - Credit Card Fraud Detection dataset]
* **Description:** [Sebutkan jumlah baris/kolom, misal: The dataset contains 284,807 transactions, out of which 492 are fraudulent, making it highly unbalanced.]

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

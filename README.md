# Support Vector Machine (SVM) for Classification: Telecom Churn

## Overview
This repository contains a Jupyter Notebook implementing an end-to-end Support Vector Machine (SVM) pipeline for predicting Customer Churn. It analyzes a real-world Telecom Churn dataset and demonstrates the predictive power and distinct boundary styles between different SVM configurations (Linear vs. Radial Basis Function / RBF kernels).

## Objectives
- **Data Preprocessing**: Handles real-world categorical data, boolean mapping, and Feature Scaling (crucial for SVM operations).
- **Dimensionality Reduction**: Utilizes Principal Component Analysis (PCA) to compress features into a 2D space, allowing clear, visualizable decision boundaries without losing the integrity of the core data variance.
- **Model Training**: Constructs and trains SVM models using both Linear and RBF kernels on the PCA-reduced data.
- **Performance Evaluation**: Evaluates models using standard metrics:
  - Accuracy
  - Precision
  - Recall
  - Area Under the ROC Curve (AUC)
- **Visualizations**: 
  - Plots the mathematical decision boundaries of both internal kernels.
  - Plots ROC Curves and comparative AUC values.
  - Displays a detailed Confusion Matrix for the finalized model configuration.

## Technologies Used
- **Python**: Primary programming language.
- **scikit-learn**: For advanced dataset preprocessing (PCA, Label Encoding, Data Scaling), SVM modeling, and evaluation metrics computation.
- **pandas**: Tabular raw data ingestion.
- **matplotlib**: Detailed chart plotting and visual mapping.

## Project Structure
- `svm_classification.ipynb`: The primary interactive Jupyter Notebook detailing step-by-step code and commentary.
- `churn-bigml-*.csv`: Telecom Churn Datasets loaded by the model natively. 
- `README.md`: Formal project documentation.

## Running the Notebook
1. Clone this repository:
   ```bash
   git clone https://github.com/lobadiah/Support-Vector-Machine-SVM-for-Classification.git
   ```
2. Navigate to the directory:
   ```bash
   cd Support-Vector-Machine-SVM-for-Classification
   ```
3. Open `svm_classification.ipynb` with Jupyter Notebook, JupyterLab, or your IDE:
   ```bash
   jupyter notebook svm_classification.ipynb
   ```
4. Execute the cells sequentially to observe data transformations and modeling mechanics in action!

## Key Takeaways
Because real-world user behaviors inherently form non-linear patterns, utilizing flexible, multi-dimensional kernels (such as RBF) generally contours boundary lines that strictly rigid linear algorithms cannot accommodate, thereby heavily optimizing the isolation of Churn demographics.

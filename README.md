# Support Vector Machine (SVM) for Classification

## Overview
This repository contains a Jupyter Notebook implementing an end-to-end Support Vector Machine (SVM) pipeline for binary classification. The project demonstrates the impact of using different SVM kernels (Linear vs. Radial Basis Function / RBF) on a non-linearly separable dataset.

## Objectives
- **Dataset Generation**: Generates a labeled synthetic dataset (`make_moons`) ideal for demonstrating non-linear decision boundaries.
- **Model Training**: Constructs and trains SVM models using both Linear and RBF kernels.
- **Performance Comparison**: Compares the models against several vital metrics:
  - Accuracy
  - Precision
  - Recall
  - Area Under the ROC Curve (AUC)
- **Visualizations**: 
  - Plots the decision boundaries of both models.
  - Plots ROC Curves for evaluating True/False Positive Rates.
  - Displays the Confusion Matrix for the final model algorithm.

## Technologies Used
- **Python**: Primary programming language.
- **scikit-learn**: For dataset generation, SVM modeling, and evaluation metrics computation.
- **pandas**: Structured dataset formatting.
- **matplotlib**: Detailed chart plotting and visual analysis.

## Project Structure
- `svm_classification.ipynb`: The primary interactive Jupyter Notebook detailing the step-by-step implementation.
- `svm_results.png`: Saved visualizations output directly from the modeling process.
- `README.md`: Project documentation.

## Running the Notebook
1. Clone this repository:
   ```bash
   git clone https://github.com/lobadiah/Support-Vector-Machine-SVM-for-Classification.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Support-Vector-Machine-SVM-for-Classification
   ```
3. Open `svm_classification.ipynb` with Jupyter Notebook, JupyterLab, or your preferred IDE:
   ```bash
   jupyter notebook svm_classification.ipynb
   ```
4. Execute the cells sequentially to observe dataset creation, training, calculation of metrics, and generated plots.

## Results Summary
The implementation highlights why non-linear boundary algorithms (like RBF) successfully compartmentalize datasets such as `make_moons` where strict linear boundary models fall short. This directly reflects within the higher Accuracy and AUC scores provided by the RBF-configured models compared to their Linear counterparts!

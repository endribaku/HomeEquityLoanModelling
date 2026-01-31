Home Equity Loan Default Prediction
==================================

Student: Endri Baku  
Course: Artificial Intelligence  
Assignment: Midterm Coverage (Kaggle Competition)  
Kaggle Username: EndriBaku  

----------------------------------
Project Overview
----------------------------------
This project focuses on predicting whether a home equity loan applicant
will default on their loan. The task is formulated as a binary
classification problem using a real-world financial dataset.

The dataset contains 5,960 loan records with 12 input features related
to loan amount, property value, employment, and credit history.
The target variable (BAD) indicates whether the applicant defaulted.

----------------------------------
Methodology
----------------------------------
The project follows a standard machine learning pipeline:

1. Data inspection and exploratory data analysis (EDA)
2. Missing value handling using median (numeric) and mode (categorical)
3. One-hot encoding of categorical variables
4. Feature scaling using StandardScaler
5. Baseline model using Logistic Regression
6. Deep Learning model using an Artificial Neural Network (ANN)
7. Handling class imbalance via class weighting
8. Decision threshold optimization based on F1-score
9. Kaggle submission and evaluation

The ANN model is selected as the final model due to its ability to
capture nonlinear relationships among credit risk features.

----------------------------------
Evaluation
----------------------------------
The dataset is imbalanced (approximately 20% default cases), therefore
the F1-score is used as the primary evaluation metric.

The final model achieves a competitive F1-score on the Kaggle public
leaderboard, demonstrating effective balance between precision and recall.

----------------------------------
Files Included
----------------------------------
- Notebook (.ipynb): Full implementation and analysis
- submission.csv: Kaggle submission file
- requirements.txt: Python dependencies
- README.txt: Project description (this file)
- Screenshot: Kaggle submission result (attached separately)

----------------------------------
Reproducibility
----------------------------------
The project was developed using Python 3.10.19.
All required libraries and versions are specified in requirements.txt.

The notebook can be run end-to-end in the Kaggle environment or locally
after installing the listed dependencies.

----------------------------------
Notes
----------------------------------
The Kaggle submission follows the provided sample submission format.
Predictions are generated using an optimized decision threshold to
align with the F1-score evaluation metric.

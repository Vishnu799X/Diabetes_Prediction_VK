[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)
# Prima Indian DataSets Diabetes prediction
:link: Research paper link: https://dl.acm.org/citation.cfm?id=3297737#

## Description about dataset
The Prima Indian Diabetes Dataset has been used in this study, provided by the UCI Machine Learning Repository. The dataset has been originally collected from the National Institute of Diabetes and Digestive and Kidney Diseases. The dataset consists of some medical distinct variables, such as pregnancy record, BMI, insulin level, age, glucose concentration, diastolic blood pressure, triceps skin fold thickness, diabetes pedigree function etc.  This dataset has 768 patient’s data where all the patients are female and at least 21 years old.  The number of true cases are 268 (34.90%) and the number of false cases are 500 (65.10%), respectively, in the dataset.
I used six classification techniques, artificial neural network (ANN), Support Vector Machine (SVM), Decision tree (DT), random forest (RF), Logistics Regression (LR) and Naïve Bayes (NB). 

1. Dataset Collection
Use the Pima Indian Diabetes Dataset from the UCI Machine Learning Repository.

It includes medical features like:

Pregnancies, Glucose, Blood Pressure, Skin Thickness, Insulin

BMI, Diabetes Pedigree Function, Age

Outcome (target: 1 = diabetic, 0 = non-diabetic)

2. Data Understanding
Total Records: 768 female patients

Class Distribution:

Positive (Diabetic): 268 (34.90%)

Negative (Non-diabetic): 500 (65.10%)

3. Data Preprocessing
Handle Missing or Zero Values: Some values like insulin or skin thickness may be 0, which could be unrealistic.

Feature Scaling: Apply normalization/standardization (e.g., StandardScaler) to balance feature impact.

Train-Test Split: Divide data (e.g., 80% for training, 20% for testing) for unbiased model evaluation.

4. Model Selection
Apply six classification algorithms:

 Logistic Regression (LR): Probabilistic linear classifier.

 Naive Bayes (NB): Probabilistic classifier based on Bayes’ Theorem.

 Support Vector Machine (SVM): Maximizes margin between classes.

 Decision Tree (DT): Tree-based flowchart decision-making model.

 Random Forest (RF): Ensemble of decision trees for better generalization.

 Artificial Neural Network (ANN): Deep learning model mimicking the human brain.

5. Model Training
Feed training data into each classifier.

Adjust hyperparameters (if needed) to improve performance.

6. Model Evaluation
Use metrics like:

Accuracy

Confusion Matrix

Precision, Recall, F1-score (if class imbalance matters)

Compare model performance on the test dataset.

7. Conclusion & Interpretation
Identify which model performs best.

Analyze strengths and weaknesses.

Consider trade-offs: accuracy vs interpretability vs complexity.


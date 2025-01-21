
# Predictive Maintenance with Machine Learning

# Dataset Overview
The AI4I 2020 Predictive Maintenance Dataset includes:

Sensor Readings: Air temperature, Process temperature, Rotational speed, Torque, Tool wear.
Product Metadata: Product type (L, M, H).
Target Variables:
Failure (binary: 0 for no failure, 1 for failure).
Failure Type (categorical: Heat Dissipation, Power, Overstrain, Tool Wear, Random Failures).
The dataset comprises 10,000 samples and is free of null values.
# Data Preprocessing
Encoding categorical variables into numerical formats.
Addressing class imbalance using clustering and sampling techniques.
Data Splitting: 70% training, 15% validation, and 15% testing.
# Exploratory Data Analysis
Histograms & KDE Plots: Examined feature distributions.
Boxplots: Identified and visualized outliers.
Heatmaps: Analyzed correlations among features.
Countplots: Visualized categorical feature distributions.
# Machine Learning Models
Logistic Regression
K-Nearest Neighbors (KNN)
Support Vector Machine (SVM)
Naïve Bayes
Random Forest Classifier (RFC)
Decision Tree Classifier (DTC)
# Evaluation Metrics
Accuracy: Ratio of correct predictions to total samples.
Precision: Ratio of true positives to total predicted positives.
Recall: Ratio of true positives to total actual positives.
F1 Score: Harmonic mean of Precision and Recall.
# Results
Failure Detection Task
Top-performing Models: KNN and RFC.
KNN: Achieved the highest accuracy (90%) and balanced F1 score.
RFC: Demonstrated excellent accuracy and efficiency.
Failure Type Classification Task
Top-performing Models: Logistic Regression and DTC.
Logistic Regression: Consistently high accuracy across classes.
DTC: Best F1 score, effectively managing imbalanced classes.


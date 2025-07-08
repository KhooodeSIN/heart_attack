This code builds a heart disease prediction model using a dataset. It performs data preprocessing,
feature selection, scaling, and model training with different machine learning algorithms. 
The goal is to predict whether a person has heart disease (binary classification).

Steps performed:

1. Loaded and explored the dataset (heart.csv), plotted correlations and target distribution.

2. Selected the best 8 features using SelectKBest with chi-square.

3. Scaled features using StandardScaler.

4. Split data into training and testing sets.

Models used:

1. Logistic Regression

2. Decision Tree Classifier

3. Random Forest Classifier

4. XGBoost Classifier

5. Evaluation:

.Calculated and displayed classification report (precision, recall, f1-score).

.Computed custom F2-score to focus more on recall.

.Plotted confusion matrices for each model.

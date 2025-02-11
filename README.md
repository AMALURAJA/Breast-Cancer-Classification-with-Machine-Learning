# Breast-Cancer-Classification-with-Machine-Learning

### Dataset

The dataset is loaded from sklearn.datasets.load_breast_cancer() and consists of features related to breast cancer diagnosis.

## Preprocessing

Checked for missing values and handled them accordingly.

Applied feature scaling using StandardScaler to normalize the dataset.

Split the dataset into training (80%) and testing (20%) sets.

## Explanation of Preprocessing Steps

Checking for Missing Values: Although the dataset does not contain missing values, checking ensures data integrity in case of future changes or modifications.

Feature Scaling: Applied StandardScaler to ensure all features have the same scale, improving the performance of distance-based models such as k-NN and SVM.

Train-Test Split: The dataset was split into 80% training and 20% testing to evaluate model performance effectively.

These preprocessing steps are necessary to enhance model accuracy and ensure fair comparisons between different classifiers.

## Classification Algorithms Implemented

The following classification algorithms are implemented:

### Logistic Regression: A linear model that estimates the probability of a binary outcome. It is suitable for this dataset as it is simple, interpretable, and works well when the features are properly scaled.

### Decision Tree Classifier: A non-linear model that splits the data based on feature thresholds. It is useful for understanding feature importance and handling non-linearly separable data.

### Random Forest Classifier: An ensemble of decision trees that improves accuracy and reduces overfitting. It is suitable for this dataset because it provides robustness against noise and better generalization.

### Support Vector Machine (SVM): A model that finds the optimal hyperplane for classification. It is effective when the dataset is well-separated and works well with feature scaling.

### k-Nearest Neighbors (k-NN): A distance-based algorithm that classifies data points based on the majority vote of neighbors. It is useful for pattern recognition but can be computationally expensive for large datasets.

## Model Evaluation

Trained each model and evaluated their performance using accuracy_score.

Compared the models and identified the best and worst-performing classifiers based on accuracy.

## Results

The results are printed in the notebook, displaying the accuracy of each classifier along with the best and worst-performing models.

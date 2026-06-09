# Task 5 - Decision Trees and Random Forests

## Objective
Learn tree-based models for classification and ensemble learning.

## Dataset
Heart Disease Dataset

## Steps Performed
1. Loaded and explored dataset
2. Split data into training and testing sets
3. Trained Decision Tree Classifier
4. Visualized the Decision Tree
5. Controlled overfitting using max_depth
6. Trained Random Forest Classifier
7. Compared accuracies
8. Analyzed feature importance
9. Performed 5-fold cross-validation

## Tools Used
- Python
- Pandas
- Matplotlib
- Scikit-learn

## Results

### Decision Tree
Accuracy: 98.54%

### Random Forest
Accuracy: 98.54%

### Cross Validation
Scores:
[1.00, 1.00, 1.00, 1.00, 0.9854]

Average Accuracy:
99.71%

### Feature Importance
Most important features:
1. cp
2. ca
3. thalach
4. oldpeak
5. thal

### Conclusion
Both Decision Tree and Random Forest achieved excellent performance on the Heart Disease dataset. Random Forest provided robust predictions and identified chest pain type (cp), number of major vessels (ca), maximum heart rate achieved (thalach), oldpeak, and thal as the most important predictors. Cross-validation confirmed strong model generalization with an average accuracy of 99.71%.

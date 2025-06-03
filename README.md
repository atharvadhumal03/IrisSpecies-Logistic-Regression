# IrisSpecies-Logistic-Regression
A machine learning project implementing multiclass classification to identify iris flower species based on their physical measurements. This project demonstrates the complete ML pipeline from data exploration to model evaluation, achieving 100% accuracy on the test set.

## 📊 Project Overview
This project uses logistic regression to classify iris flowers into three species (Setosa, Versicolor, and Virginica) based on four physical features:

1. Sepal length
2. Sepal width
3. Petal length
4. Petal width

The project showcases fundamental machine learning concepts including data visualization, train-test splitting, model training, and comprehensive evaluation metrics.

## 🎯 Results Summary
### Model Performance
| Metric | Score |
|----------|----------|
| Test Accuracy    |  100%     |
| Test Total Samples    | 30     |
| Misclassifications    | 0     |

### Per-Class Performance
| Species | Precision | Recall | F1-Score | Support |
|---------|-----------|--------|----------|---------|
| Iris-setosa | 1.00 | 1.00 | 1.00 | 9 |
| Iris-versicolor | 1.00 | 1.00 | 1.00 | 12 |
| Iris-virginica | 1.00 | 1.00 | 1.00 | 9 |

### Confusion Matrix
| Actual/Predicted | Setosa | Versicolor | Virginica |
|------------------|---------|------------|-----------|
| **Setosa** | 9 | 0 | 0 |
| **Versicolor** | 0 | 12 | 0 |
| **Virginica** | 0 | 0 | 9 |

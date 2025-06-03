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

## 🔍 Methodology
1. Data Exploration and Visualization

- Loaded the Iris dataset using pandas
- Created scatter plots to visualize feature relationships using matplotlib and seaborn
- Identified clear separability between species, especially for Setosa
- Observed that petal measurements provide better class separation than sepal measurements

2. Data Preprocessing

Feature-target separation: Split dataframe into features (X) and target labels (y)
Train-test split: 80-20 split resulting in:

- Training set: 120 samples
- Test set: 30 samples


No scaling required: Logistic regression converged without feature scaling

3. Model Development

- Algorithm: Logistic Regression with default hyperparameters
- Solver: 'lbfgs' (default)
- Multi-class strategy: 'auto' (one-vs-rest)
- Maximum iterations: 100 (sufficient for convergence)

4. Model Evaluation
Comprehensive evaluation using multiple metrics:

- Confusion Matrix: Perfect diagonal matrix with no misclassifications
- Classification Report: Precision, recall, and F1-score all equal to 1.0
- Test Set Composition: 9 Setosa, 12 Versicolor, 9 Virginica samples



## 📁 Dataset Information
The Iris dataset is one of the most famous datasets in machine learning, introduced by statistician Ronald Fisher in 1936. It contains:

- 150 samples total (50 samples per species)
- 4 features (all measurements in centimeters)
- 3 target classes (flower species)
- No missing values
- No duplicate values

### Target Distribution

Setosa: 50 samples (33.3%)
Versicolor: 50 samples (33.3%)
Virginica: 50 samples (33.3%)


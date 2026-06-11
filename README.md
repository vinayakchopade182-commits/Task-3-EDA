# Task-3-EDA
EDA-Exploratory Data Analysis
# EDA Report — Task 3

## Dataset: Iris
## Source: Seaborn built-in dataset
## Shape: 150 rows × 5 columns
## Species: setosa, versicolor, virginica (50 each)

## 1. Summary Statistics
- sepal_length: mean=5.84, range=4.3–7.9
- petal_length: mean=3.76, range=1.0–6.9
- No missing values found

## 2. Patterns Identified
- Setosa is clearly separable from other species
- Versicolor and Virginica overlap slightly
- Petal length & width are strong species indicators

## 3. Correlation Findings
- petal_length & petal_width → highly correlated (0.96)
- sepal_length & petal_length → strongly correlated (0.87)
- sepal_width has low correlation with other features

## 4. Graphs Created
- Histogram → feature distributions
- Boxplot → spread and outliers
- Heatmap → correlations between features
- Pairplot → patterns across all features
- Countplot → species distribution
- Violin plot → petal length by species

## Interview Answers:

### What is EDA?
EDA (Exploratory Data Analysis) is the process of
analyzing datasets to summarize their main characteristics
using statistics and visualizations before applying
any model.

### Why check correlation?
Correlation tells us how strongly two variables are
related. Highly correlated features can cause
redundancy in models, and it helps us pick the most
important features.

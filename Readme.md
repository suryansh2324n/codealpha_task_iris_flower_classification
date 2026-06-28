# Iris Flower Classification

## Overview
This project uses Machine Learning to classify Iris flowers into three species:

- Iris Setosa
- Iris Versicolor
- Iris Virginica

The classification is based on four flower measurements:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

## Technologies Used
- Python
- Scikit-learn
- NumPy
- Pandas

## Dataset
The Iris dataset is loaded from the Scikit-learn library.

Dataset Information:
- Total Samples: 150
- Features: 4
- Classes: 3

## Machine Learning Algorithm
Random Forest Classifier

## Steps Performed
1. Load Iris Dataset
2. Split Data into Training and Testing Sets
3. Train the Random Forest Model
4. Predict Flower Species
5. Evaluate Model Performance

## Performance Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## How to Run

Install dependencies:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

Run the project:

```bash
python iris_classification.py
```

## Sample Prediction

Input:

```text
[5.1, 3.5, 1.4, 0.2]
```

Output:

```text
Setosa
```

## Conclusion

The model successfully classifies Iris flowers with high accuracy using machine learning techniques. This project demonstrates the basic concepts of supervised learning and classification.
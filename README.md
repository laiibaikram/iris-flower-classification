# Iris Flower Classification using KNN

## Project Overview
This project uses Machine Learning to classify Iris flowers into three species:
- Setosa
- Versicolor
- Virginica

The model uses four flower measurements:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

## Objectives
- Load and understand the Iris dataset.
- Split data into training and testing sets.
- Apply feature scaling using StandardScaler.
- Train a K-Nearest Neighbors (KNN) model.
- Make predictions.
- Evaluate the model using Confusion Matrix and F1 Score.

## Technologies Used
- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib

## Model Details
- Algorithm: K-Nearest Neighbors (KNN)
- K Value: 5
- Feature Scaling: StandardScaler
- Dataset: Iris Dataset
- Training Data: 80%
- Testing Data: 20%

## Model Results

| Metric | Score |
|---|---:|
| Accuracy | 93.33% |
| Precision | 94.44% |
| Recall | 93.33% |
| F1 Score | 93.27% |

## Example Prediction
Input measurements: `[5.1, 3.5, 1.4, 0.2]`

Predicted Flower: **Setosa**

## How to Run

Install the required libraries:

```bash
pip install -r requirements.txt
```

Run the project:

```bash
python main.py
```

## Learning Outcomes
- Understanding Machine Learning basics.
- Data preprocessing and feature scaling.
- Training a KNN classification model.
- Evaluating model performance.

## Author
DecodeLabs – Artificial Intelligence Project 2

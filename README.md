# Iris-Flower-Classification using Machine Learning

This project uses Machine Learning to classify iris flowers into three species: Setosa, Versicolor, and Virginica based on their sepal and petal measurements.
## Project Overview
- Algorithm: Logistic Regression
- Dataset: Iris Dataset (150 samples, 4 features)
- Language: Python
- Libraries: scikit-learn, pandas, NumPy, Matplotlib, joblib
## Dataset
The Iris dataset contains 150 samples with 4 features:
- Sepal length (cm)
- Sepal width (cm)
- Petal length (cm)
- Petal width (cm)
Three species to classify:
- Setosa
- Versicolor
- Virginica
## How to Run
1. Clone the repository:
```bash
git clone https://github.com/yourusername/iris-classification-ml.git
cd iris-classification-ml
```
2. Install dependencies:
```bash
pip install pandas numpy matplotlib scikit-learn joblib
```
##  Project Structure

iris-classification-ml/
├── iris_classification.py        # Main script
├── iris_model.pkl                # Trained model (after running)
├── README.md                     # This file
└── requirements.txt              # Dependencies

## Results

### Model Performance
- Algorithm: Logistic Regression
- Train-Test Split: 80% training (120 samples), 20% testing (30 samples)
- Test Accuracy: 96-100% depending on split
- Note: Results may vary slightly depending on train-test split randomness


### Evaluation Metrics
- Classification Report (precision, recall, F1-score for each species)
- Confusion Matrix visualization
  
## Features
- End-to-end ML pipeline from data loading to prediction
- Model training and evaluation using Logistic Regression
- Performance evaluation using classification metrics and confusion matrix
- Model saving using joblib for reuse
  
## Example Prediction
The script includes a sample prediction for a new flower:
Sample features: [5.1 3.5 1.4 0.2]
Predicted class: Setosa

## Key Learnings
This project helped me understand:
- Loading and exploring datasets with pandas
- Data preprocessing and train-test splitting
- Training supervised learning models
- Model evaluation metrics (accuracy, precision, recall, F1)
- Visualizing results with confusion matrices
- Saving and loading trained models

## Acknowledgement
- Iris dataset from scikit-learn
- Google Colab for development environment



  


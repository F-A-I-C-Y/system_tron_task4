# Iris Flower Classification

This project demonstrates the classification of Iris flowers into three species: **setosa**, **versicolor**, and **virginica**, based on their sepal and petal measurements. The dataset used is the famous Iris dataset, commonly employed for introductory machine learning tasks.

## Dataset
The dataset contains 150 samples with the following features:
- `sepal_length`
- `sepal_width`
- `petal_length`
- `petal_width`
- `species` (target variable)

## Objective
Train a machine learning model to classify the species of Iris flowers based on their measurements.

## Files
- **Task 4 - IRIS FLOWER CLASSIFICATION.ipynb**: The Jupyter notebook containing the complete workflow, including data preprocessing, model training, and evaluation.
- **IRIS.csv**: The dataset file used in the project.
- **iris_classifier.pkl**: The trained Random Forest classifier model saved for future use.

## Requirements
The following Python libraries are required:
- pandas
- scikit-learn
- joblib (optional, for saving the model)


## Steps to Run
1. Open the Jupyter notebook `Task 4 - IRIS FLOWER CLASSIFICATION.ipynb`.
2. Ensure the dataset file `IRIS.csv` is in the same directory.
3. Follow the instructions in the notebook to execute each cell sequentially.
4. Review the accuracy and classification report generated after training the model.

## Results
The Random Forest classifier achieves approximately **90% accuracy** on the test dataset. The detailed classification report is generated within the notebook.

## Output
- The trained model is saved as `iris_classifier.pkl` for reuse.
- Predictions can be made using the saved model by loading it with:
```
import joblib
model = joblib.load('iris_classifier.pkl')
```

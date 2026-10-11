# Iris Flower Classification Using Machine Learning

## 1. Project Overview

This project uses machine learning to classify Iris flowers into three species: Setosa, Versicolor, and Virginica, based on their measurements.

## 2. Objective

The main objective is to build a classification model that predicts the species of an Iris flower using the K-Nearest Neighbors (KNN) algorithm.

## 3. Dataset

The project uses the Iris flower dataset, which contains the following measurements:

* Sepal length
* Sepal width
* Petal length
* Petal width

The target variable represents the flower species.

## 4. Technologies Used

* Python
* Pandas
* Seaborn
* Matplotlib
* Scikit-learn

## 5. Project Workflow

1. Import the required Python libraries.
2. Load and explore the dataset.
3. Check for missing values and generate descriptive statistics.
4. Visualize sepal measurements using a scatter plot.
5. Separate the input features and target variable.
6. Split the dataset into training and testing sets.
7. Standardize the features using StandardScaler.
8. Train the KNN classification model.
9. Predict flower species using the test data.
10. Evaluate the model using accuracy, precision, and a confusion matrix.

## 6. Machine Learning Algorithm

**K-Nearest Neighbors (KNN)** is a supervised machine learning algorithm that classifies a data point based on the classes of its nearest neighbors.

In this project, the model uses `n_neighbors=5`.

## 7. Model Evaluation

The model's performance is evaluated using:

* **Accuracy:** Measures the proportion of correct predictions.
* **Precision:** Measures how many predicted instances of a class are correct, calculated using weighted averaging.
* **Confusion Matrix:** Displays the number of correct and incorrect predictions for each class.

The actual evaluation results are displayed when the notebook is executed.

## 8. Project Files

* `Iris_Flower_Classification.ipynb` — Jupyter Notebook containing the Python code.
* `iris_dataset.csv` — Dataset file used in the initial data-loading step.

## 9. How to Run the Project

1. Download or clone this repository.

2. Install the required libraries using the command below:

   ```bash
   pip install pandas seaborn matplotlib scikit-learn
   ```

3. Ensure `iris_dataset.csv` is in the same folder as the notebook.

4. Open `Iris_Flower_Classification.ipynb` in Jupyter Notebook or Google Colab.

5. Run the notebook cells in order to train and evaluate the model.

## 10. Conclusion

This project demonstrates how machine learning can classify Iris flowers using their measurements. It provides practical experience with data exploration, visualization, feature standardization, model training, and classification evaluation.

## Author

Student Machine Learning Project


Task 6: K-Nearest Neighbors (KNN) Classification
Objective:
Understand and implement KNN for classification problems using the Iris dataset.
Dataset
Filename: Iris.csv
Source: Iris Dataset (Kaggle / UCI ML Repository)
Steps in the Notebook

Upload Dataset:
The first cell will prompt you to upload Iris.csv.
Data Loading & Inspection
Load the dataset with Pandas and view the first few rows.
Feature Selection & Normalization
Remove Id and Species columns from features.
Normalize features using StandardScaler.

Train-Test Split
Split into training and testing sets (80-20 split).
KNN Model Training
Experiment with different values of k (1 to 20).
Plot accuracy vs. k.
Select the best k based on accuracy.

Model Evaluation
Train with the best k.
Calculate accuracy on the test set.
Display a confusion matrix.
Visualization
Apply PCA to reduce features to 2 dimensions.
Plot the dataset in 2D for visualization.

Requirements
pandas
matplotlib
scikit-learn

Expected Output
Plot showing accuracy vs. K values.
Confusion matrix.
PCA visualization of the Iris dataset.
Final accuracy score.
How to Run in Google Colab
Open the .ipynb file in Google Colab.

Upload Iris.csv when prompted.

Run all cells sequentially.

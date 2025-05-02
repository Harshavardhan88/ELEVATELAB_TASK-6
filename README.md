# ELEVATELAB_TASK-6

# K-Nearest Neighbors (KNN) Classification on Iris Dataset

## Objective:

Implement and understand the K-Nearest Neighbors algorithm using the classic Iris dataset, with full preprocessing, model evaluation, and decision boundary visualization.


## Dataset:

- **Source**: `Iris.csv`
- **Classes**:
 
  - Iris-setosa  
  - Iris-versicolor  
  - Iris-virginica
- **Features**:

 SepalLengthCm, SepalWidthCm, PetalLengthCm, PetalWidthCm



## Preprocessing Steps:

1. **Dropped non-predictive 'Id' column**
2. **Checked and removed null values**
3. **Removed duplicate rows**
4. **Standardized features** using `StandardScaler`



## Steps Performed:

- **Train/Test Split**: 80/20 using `train_test_split`
- **Model Training**:
  - `KNeighborsClassifier` for K = 1 to 20
  - Selected best `K` using highest accuracy
- **Evaluation**:
  - Used `accuracy_score`
  - Confusion matrix with `ConfusionMatrixDisplay`
- **Visualization**:
  - Accuracy vs K plot
  - 2D PCA-based decision boundary visualization

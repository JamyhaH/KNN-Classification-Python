
# K-Nearest Neighbors (KNN) Classification Using Python

## Project Overview
This project implements a supervised machine learning algorithm, K-Nearest Neighbors (KNN), to classify observations into three categories.

The dataset contains 541 observations and 27 input features.

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Google Colab

## Methodology
1. Loaded the dataset using Pandas.
2. Selected 27 input features and one target variable.
3. Split the data into 80% training and 20% testing sets.
4. Standardized features using StandardScaler.
5. Trained KNN models with k = 3 and k = 5.
6. Evaluated model performance.

## Model Results

| Model | Accuracy |
|---|---|
| KNN (k = 3) | 97.25% |
| KNN (k = 5) | 96.33% |

## KNN (k = 3): Sensitivity and Specificity

| Class | Sensitivity | Specificity |
|---|---|---|
| Class 0 | 96.15% | 98.80% |
| Class 1 | 100.00% | 98.81% |
| Class 2 | 96.55% | 98.04% |

## KNN (k = 5): Confusion Matrix

| Actual / Predicted | Class 0 | Class 1 | Class 2 |
|---|---|---|---|
| Class 0 | 25 | 0 | 1 |
| Class 1 | 0 | 24 | 1 |
| Class 2 | 1 | 1 | 56 |

## Key Findings
- KNN with k = 3 achieved 97.25% testing accuracy.
- KNN with k = 5 achieved 96.33% testing accuracy.
- Both models performed well on the selected test set.
- Feature scaling was used to support distance-based classification.

## How to Run
1. Open KNN_Classification_Project.ipynb in Google Colab.
2. Obtain GCL.csv from an authorized source.
3. Upload the dataset into Colab.
4. Update the dataset file path if necessary.
5. Run the notebook cells in order.

Note: The course dataset is not included in this public repository.

## Skills Demonstrated
- Python programming
- Supervised machine learning
- Data preprocessing
- Feature standardization
- Multiclass classification
- Model evaluation
- Data visualization

## Author
Jamyha Hubbard

M.S. Artificial Intelligence Science in Medicine

University of Louisville


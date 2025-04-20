# Parameter Optimization using SVM

This project demonstrates parameter tuning for a Support Vector Machine (SVM) classifier using `GridSearchCV` from Scikit-learn. It includes:

- Data preprocessing
- Standardization
- Model training
- Hyperparameter optimization using GridSearchCV
- Learning curve visualization

## Dataset Used

**Name:** MAGIC Gamma Telescope Data Set  
**Source:** UCI Machine Learning Repository  
**File:** `magic04.data`

This dataset is used to distinguish between gamma and hadron events in a high-energy telescope experiment.

- Number of Instances: 19,020
- Number of Attributes: 10 real-valued features and 1 class label (`g` for gamma, `h` for hadron)

## How to Run

1. Upload the `magic04.data` file when prompted.
2. The notebook will read the dataset and perform preprocessing.
3. SVM model will be trained and optimized using GridSearchCV.
4. Final accuracy and learning curves will be displayed.

## Requirements

- Python 3.x
- scikit-learn
- pandas
- matplotlib
- seaborn

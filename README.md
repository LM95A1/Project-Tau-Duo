# Project Tau Duo
Project Four Repository for Group Two, designated codename Tau Duo.

## Introduction

The UFC Predictions Notebook is an exhaustive study that aims to predict the outcomes of UFC fights using machine learning models. The project encapsulates a multitude of aspects, including data preprocessing, feature engineering, model training, hyperparameter tuning, evaluation, and performance visualization. The ultimate goal is to identify the most effective machine learning algorithm that can predict UFC fight outcomes with high accuracy.

## Table of Contents

1. Libraries Used
2. Notebook Structure
3. Data Loading and Cleansing
4. Data Exploration and Visualization
5. Feature Engineering
6. Model Building and Evaluation
7. Conclusion and Future Scope

## Libraries Used

### General Purpose Libraries
- **Pandas**: Used for data manipulation and analysis.
- **NumPy**: Used for numerical operations.
- **Matplotlib.Pyplot**: Used for data visualization.

### Scikit-Learn Suite
- **Utilities**: 
  - `train_test_split`: For splitting the dataset into training and testing sets.
  - `GridSearchCV`: For hyperparameter tuning.
- **Metrics**: 
  - `accuracy_score`, `precision_score`, `recall_score`, `f1_score`, `classification_report`, `mean_squared_error` for evaluating model performance.
- **Models**: 
  - `DummyClassifier`, `DecisionTreeClassifier`, `BaggingClassifier`, `RandomForestClassifier`, `AdaBoostClassifier` for building predictive models.

### Additional Modeling Tools
- **Support Vector Machine (SVM)**: 
  - `SVC` from `sklearn.svm` for non-linear model building.
- **XGBoost**: 
  - An optimized gradient-boosting machine learning library.

### Deep Learning Library
- **Keras**: Used for constructing neural network models.
  - Components: `Sequential`, `Dense`, `Adam`, `LabelEncoder`, `to_categorical`, `EarlyStopping`.

## Notebook Structure

### Data Loading and Cleansing
- The dataset is imported from a CSV file.
- Irrelevant columns are dropped.
- Missing values are addressed.

### Data Exploration and Visualization
- Statistical summaries are generated to understand the dataset's features.
- Various visualizations like histograms, scatter plots, and 3D scatter plots are used to identify trends and correlations in the data.

### Feature Engineering
- New features are crafted from existing data to improve the predictive power of the models.
- Feature selection is done based on importance scores to further optimize the models.

### Model Building and Evaluation

#### Dummy Classifier
- Serves as a baseline model for comparison.
- Uses a 'most frequent' strategy to make predictions.

#### Random Forest Classifier
- An ensemble learning method that fits multiple decision tree classifiers.
- Hyperparameter tuning is extensively performed through GridSearchCV.
- Several versions are explored with varying parameters to optimize performance.

#### AdaBoost Classifier
- Boosting algorithm that focuses on classification problems.
- Combined with decision trees to form a strong predictor.

#### Support Vector Machine (SVM)
- Effective for high-dimensional spaces.
- Kernel trick is used for non-linear classification.

#### XGBoost Classifier
- An optimized distributed gradient boosting library.
- Used for solving machine learning problems in a fast and accurate way.

#### Keras Neural Network
- Deep learning model built using the Keras library.
- Multiple layers with varying numbers of nodes are used.

### Performance Metrics
- Models are evaluated based on accuracy, precision, recall, and F1 Score.
- ROC curves are plotted to visualize the trade-off between sensitivity and specificity.
- Confusion matrices are generated to measure the performance of each model in detail.

### Team Members

- Lester Molinares
- Dustin Shaddix
- Thomas Gresco
- Adam Glantz
- Juliano Miguel Lacson
- Darrell Reives

---

### Conclusion and Future Scope

The notebook concludes by highlighting the Random Forest Classifier as the most effective model for this specific UFC prediction project. However, it emphasizes that machine learning is not a one-size-fits-all tool. Depending on the nature of the problem, dataset, and requirements, different machine learning models can be more effective. The notebook also suggests directions for future work, such as incorporating more features or using more advanced algorithms.

By offering a step-by-step guide through the machine learning pipeline, from data preprocessing to model evaluation, this notebook serves as a comprehensive resource for anyone interested in applying machine learning algorithms to predict UFC fights.

---


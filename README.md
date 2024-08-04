# Iris Dataset Analysis & Classification

This project analyzes and classifies the famous Iris dataset using various machine learning models.

## Loading the Dataset

- Installed the `ucimlrepo` package and fetched the Iris dataset.
- Combined feature data and target labels into a single DataFrame for easier manipulation.
- Displayed initial statistics and information about the dataset, including the number of samples per class.

## Data Preprocessing

- Checked for any null values in the dataset.

## Exploratory Data Analysis (EDA)

- **Histograms**: Plotted histograms to visualize the distribution of sepal length, sepal width, petal length, and petal width.
- **Scatterplots**: Created scatterplots to explore relationships between different features and visualize the distribution of iris species.
- **Correlation Matrix**: Computed and visualized the correlation matrix to understand the relationships between features. High correlations suggest that some features might be redundant.

## Label Encoding

- Converted the categorical labels into numeric form using Label Encoding to prepare the data for machine learning models.

## Model Training

- **Train-Test Split**: Split the dataset into training (70%) and testing (30%) sets.

- **Logistic Regression**
  - Trained a Logistic Regression model.
  - Evaluated its performance with accuracy.
  - Accuracy 100.0

- **K-Nearest Neighbors (KNN)**
  - Trained a KNN model.
  - Assessed its accuracy.
  - Accuracy 97.77777777777777

- **Decision Tree**
  - Trained a Decision Tree model.
  - Checked its performance.
  - Accuracy 95.55555555555556

- **Naive Bayes**
  - Used Gaussian Naive Bayes to train and evaluate the model.
  - Accuracy 95.55555555555556

- **Support Vector Machine (SVM)**
  - Trained an SVM model.
  - Measured its accuracy.
  - Accuracy: 97.77777777777777

- **Random Forest**
  - Trained a Random Forest model.
  - Evaluated its performance.
  - Accuracy: 97.77777777777777

- **Gradient Boosting**
  - Applied Gradient Boosting.
  - Assessed its accuracy.
  - Accuracy: 97.77777777777777

- **AdaBoost**
  - Trained an AdaBoost model.
  - Checked its performance.
  - Accuracy: 93.33333333333333

- **Extra Trees**
  - Used the Extra Trees classifier for training and evaluation.
  - Accuracy: 95.55555555555556

- **CatBoost**
  - Trained a CatBoost model.
  - Measured its performance.
  - Accuracy: 97.77777777777777

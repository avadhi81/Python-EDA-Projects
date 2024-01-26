# Heart Disease Detection EDA Project

## Introduction

This project aims to perform Exploratory Data Analysis (EDA) on a heart disease dataset obtained from the UC Irvine Machine Learning Repository. The primary goal is to gain insights into the dataset, identify patterns, and lay the foundation for developing a heart disease detection model.

## Technologies, Libraries, and Dependencies

The project utilizes the following technologies, libraries, and dependencies:

- **Python:** The primary programming language for data analysis and visualization.
  
- **Libraries and Packages:**
  - **ucimlrepo:** A Python package for fetching datasets from the UC Irvine Machine Learning Repository.
  - **pandas:** A powerful data manipulation and analysis library.
  - **numpy:** A library for numerical operations in Python.
  - **matplotlib:** A 2D plotting library for creating static, animated, and interactive visualizations.
  - **seaborn:** A statistical data visualization library based on Matplotlib.
  - **scikit-learn:** A machine learning library providing simple and efficient tools for data analysis and modeling.
  - **Google Colab:** An online platform for running Python code in a collaborative environment, utilized for EDA.
  
- **Machine Learning Models:**
  - **Logistic Regression:** Used for binary classification tasks.
  - **Random Forest Classifier:** An ensemble learning model for classification tasks.
  - **Support Vector Machine (SVM):** A supervised learning model for classification and regression tasks.

- **Other Tools:**
  - **Jupyter Notebooks:** Interactive notebooks used for developing and presenting code.
  - **Git and GitHub:** Version control system and repository hosting platform for collaborative development.

## Features of the Dataset

The heart disease dataset comprises various features, including age, gender, chest pain type, resting blood pressure, cholesterol levels, and other health indicators. The target variable 'num' indicates the presence (1) or absence (0) of heart disease.

## Exploratory Data Analysis Highlights

During the exploratory data analysis, various insights were obtained:

- The dataset includes both categorical and numerical features.
- Categorical variables such as sex, chest pain type (cp), and thalassemia type (thal) were identified and converted to object type for better representation.
- Missing values were checked, and the dataset appears to be complete.
- The distribution of target classes ('num') indicates that the dataset is somewhat balanced, with both disease and no-disease cases present.
- Descriptive statistics and visualizations were generated for features like age, gender, chest pain, and thalassemia, providing an overview of the dataset's characteristics.

## Data Preprocessing

- Categorical columns, including sex, cp, fbs, restecg, exang, slope, ca, and thal, were identified and converted to object type.
- The dataset was further examined for unique values and value counts in specific categorical columns.

## Statistical Analysis and Visualization

- Basic statistics of the dataset were generated, providing insights into the central tendencies and variabilities of numerical features.
- Count plots were created to visualize the distribution of categorical variables, such as gender, chest pain type, and thalassemia, with respect to the target variable.
- Pair plots and scatter plots were generated to understand relationships between continuous features and the target variable.

## Model Training and Evaluation

### Logistic Regression Model

- Logistic Regression was chosen as the initial model for binary classification.
- The dataset was split into training and testing sets.
- The model was trained on the training set and evaluated on the testing set, yielding an accuracy score, classification report, and confusion matrix.

### Random Forest Classifier Model

- A Random Forest Classifier was implemented to explore the performance of an ensemble model.
- The model was trained on the same training set, and evaluation metrics were obtained and compared with the Logistic Regression model.

### Support Vector Machine (SVM) Model

- A Support Vector Machine (SVM) model was implemented as an alternative to explore non-linear relationships in the data.
- Similar to the other models, the SVM model was trained, evaluated, and compared.

The accuracy scores, classification reports, and confusion matrices for each model provide insights into their performance on the heart disease dataset.

## Conclusion

This exploratory data analysis project lays the groundwork for understanding the patterns and characteristics present in the heart disease dataset. Further steps could involve feature engineering, advanced modeling techniques, and fine-tuning to improve the accuracy and robustness of the heart disease detection model.

## Dataset link: https://archive.ics.uci.edu/dataset/45/heart+disease

## Team Member Contribution:

Avadhi Shah

Brinda Patel

Ankush Gurhnani

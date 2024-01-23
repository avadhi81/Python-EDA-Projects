# Python-EDA Projects
### Exploring Malicious URLs: EDA with Logistic Regression & Random Forest

### Overview
This project focuses on exploring and analyzing malicious URLs using Exploratory Data Analysis (EDA) techniques. The analysis involves the use of Logistic Regression and Random Forest models to gain insights into patterns within URLs, allowing users to identify potential threats and take preventive measures.

### Team Members
- Avadhi Shah
- Urmil Trivedi
- Dhyey Dave

### Project Description

#### Objective
The primary goal of this project is to enable users to closely examine suspicious web links by employing Logistic Regression and Random Forest models for Exploratory Data Analysis. By studying patterns in data and extracting essential features, users can make informed decisions about the potential harm associated with a given URL.

#### Code Structure

##### 1. Importing Libraries and Data
The initial section imports essential libraries such as NumPy, Pandas, Matplotlib, Seaborn, and tools for Google Colab file uploads. The code prompts users to upload a CSV file containing URL data and performs basic checks.

##### 2. URL Data Processing Class
The `URLDataProcessor` class is designed to process URLs and extract various features. It includes methods for calculating URL length, hostname length, path length, first directory length, extracting the top-level domain (TLD), and counting characters and substrings. These features provide insights into the structure and content of a given URL.

##### 3. Data Analysis
The project includes comprehensive data analysis, such as calculating URL attributes (length, hostname length, path length, etc.) and generating visualizations like heatmaps and histograms to identify patterns and correlations.

##### 4. Machine Learning Models
The code implements machine learning models,including Decision Tree and Random Forest classifiers and Logistic Regression , to predict whether a URL is malicious or benign based on its features. The models are trained and evaluated using accuracy scores and confusion matrices.

##### 5. Feature Extraction for New URLs
A section of the code demonstrates how to extract features for new URLs and predict their labels using a pre-trained Decision Tree model.

### Instructions for Use

1. **Uploading Data:**
   - Ensure your dataset is in CSV format.
   - Use the provided code to upload your CSV file to the Google Colab environment.

2. **Data Analysis:**
   - Explore the data analysis section to understand various attributes of the URLs.
   - Examine visualizations like heatmaps and histograms to identify patterns.

3. **URL Data Processing:**
   - Utilize the `URLDataProcessor` class to extract features from URLs for further analysis.

4. **Machine Learning Models:**
   - Train and evaluate machine learning models (Decision Tree, Random Forest) for URL classification.

5. **Feature Extraction for New URLs:**
   - Use the provided code to extract features for new URLs and predict their labels using a pre-trained model.

### Dependencies
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Google Colab (for file uploads)
- scikit-learn
- tld (Top-Level Domain extraction)
- tabulate
- Regex
- Warning (for handling convergence warnings)

### Contribution Guidelines
If you wish to contribute to this project, please follow standard GitHub contribution practices. Fork the repository, create a new branch for your changes, and submit a pull request.

### DATASET SOURCE: KAGGLE LINK:https://www.kaggle.com/datasets/sid321axn/malicious-urls-dataset

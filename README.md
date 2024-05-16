# Employee-Satisfaction-Predictive-Model
This project explores the application of machine learning (ML) to predict employee satisfaction, leveraging two popular algorithms: K-Nearest Neighbors (KNN) and Random Forest Classification. By analysing whether employees would leave an organisation or not.
## Table of Contents

- [Introduction](#introduction)
- [Objectives](#objectives)
- [Dataset](#dataset)
- [Dataset Description](#dataset-description)
- [Project Structure](#project-structure)
- [Methodology](#methodology)
- [Results](#results)
- [Conclusion](#conclusion)
- [License](#license)
- [How to Use](#how-to-use)
- [Contributing](#contributing)

## Introduction

Employee satisfaction is vital for organizational success, boosting productivity, motivation, and loyalty. Using KNN and random forest classifiers, organizations can analyze factors impacting satisfaction, helping to predict and improve employee contentment, thus reducing turnover and enhancing performance.

## Objectives

- Train machine learning models on employee satisfaction data to predict leave or not.
- Compare the performance of KNN and Random Forest algorithms in predicting employee satisfaction.
- Identify the most effective model for future deployment in employee satisfaction assessments.

## Dataset
The project utilizes the employee satisfaction dataset made available by Tawfik Elmetwally, comprising various parameters relating to an employee

**Data Source:** (https://www.kaggle.com/datasets/tawfikelmetwally/employee-dataset) by Tawfik Elmetwally

### Dataset Description

Each entry in the dataset represents employee satisfaction parameters:

- **Education**: The degree, institution, and area of study of each employee's education
- **Joining Year**: The year of each employee's employment, showing the length of their employment.
- **City**: The city or place of employment of every employee.
- **Payment Tier**: Classification of employees into various salary groups.
- **Age**: The age of employees
- **Gender**: Employee gender
- **Ever Benched**: Shows if a worker has been without work temporarily
- **Experience in Current Domain**: Work experience of employees
- **Leave or Not**: shows if employees will leave or not (0 for employees who are willing to leave and 1 for employees who will stay)
  
## Project Structure

1. **Library Importation**: Setup of the Python environment with necessary libraries.
2. **Dataset Importation**: Loading the water potability data from a CSV file.
3. **Data Analysis**: Employing descriptive statistics and data visualization for an in-depth understanding of the dataset.
4. **Data Pre-processing**: Cleaning and preparing the data for analysis.
5. **Model Training**: Applying machine learning algorithms to the training data.
6. **Model Evaluation**: Assessing model performance using precision, recall, and confusion matrices.

## Methodology

The methodology encompasses data pre-processing, cleaning, exploration, and handling of missing values and outliers. 
Feature engineering is performed to standardize input variables, and the dataset is split into training and test sets. Finally, 
KNN and Random Forest Classification models are trained and evaluated.

## Model Training and Evaluation

Two machine learning models are explored:

- **KNN**: A straightforward method that classifies water based on the majority vote of its nearest neighbors.
- **Random Forest Classifier**: An ensemble technique that uses multiple decision trees to improve prediction accuracy.

Performance metrics such as accuracy, precision, recall, and F1-score are used to evaluate the models.
## Results

The project's findings indicate that the Random Forest Classifier outperforms the KNN model across all evaluation metrics, demonstrating higher efficiency in classifying employee satisfaction.
## Conclusion

The Random Forest model, with its superior performance, is recommended for future deployment in employee satisfaction tasks. Its effectiveness in accurately identifying the satisfaction of employees, whether they would leave or not, underscores its reliability for practical applications.
## License

This project is open source and available under the [MIT License](LICENSE), promoting free use, modification, and distribution of the software, ensuring that contributions are welcomed and recognized.

## How to Use

1. Clone this repository.
2. Install required libraries
3. Execute the Jupyter notebooks to interact with the datasets and models.
4. Modify and experiment with the models as per your dataset and requirements.

## Contributing

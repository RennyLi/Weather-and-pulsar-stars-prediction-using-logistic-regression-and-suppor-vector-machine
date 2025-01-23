# Weather and Pulsar Stars Prediction Using Logistic Regression and Support Vector Machine

This repository contains the implementation of **Logistic Regression** and **Support Vector Machine (SVM)** for two different tasks. The project aims to showcase the use of these machine learning algorithms for classifying and predicting weather patterns and pulsar star data.

## Datasets

1. **Weather Dataset (`weatherAUS.csv`)**
   - This dataset contains weather data from Australia, and is used for a **Logistic Regression** task. The data includes various weather features like temperature, humidity, pressure, and weather conditions (e.g., rain or no rain).
   - Features: Temperature, Humidity, Wind Speed, Pressure, Rainfall, etc.

2. **Pulsar Stars Dataset (`pulsar_stars.csv`)**
   - This dataset contains data on pulsar stars, and is used for a **Support Vector Machine (SVM)** task. It consists of various attributes derived from the analysis of the pulsar stars.
   - Features: Various signal attributes derived from pulsar star observations (used for classification).

## Objectives

### Logistic Regression Task (Weather Prediction)

1. **Data Preprocessing**:
   - Load the weather dataset (`weatherAUS.csv`) into a pandas DataFrame.
   - Handle missing values and categorical variables as necessary.
   - Normalize or standardize features if required.
   
2. **Model Training**:
   - Use **Logistic Regression** to predict weather conditions (e.g., rain or no rain) based on the features.
   - Split the data into training and testing sets.
   - Train the model using **sklearn's LogisticRegression**.
   
3. **Evaluation**:
   - Evaluate the model performance using accuracy and confusion matrix.
   - Use **cross-validation** to ensure the robustness of the model.

### Support Vector Machine Task (Pulsar Stars Classification)

1. **Data Preprocessing**:
   - Load the pulsar stars dataset (`pulsar_stars.csv`) into a pandas DataFrame.
   - Perform any necessary preprocessing such as scaling or normalization.

2. **Model Training**:
   - Train a **Support Vector Machine (SVM)** model to classify pulsar stars as either "pulsar" or "non-pulsar."
   - Split the data into training and testing sets.
   - Use **sklearn's SVC** to implement the model.
   
3. **Evaluation**:
   - Evaluate the model using accuracy, precision, recall, and F1-score.
   - Perform **cross-validation** to assess model performance.

## Code Structure

- **`119010148_Logistic_Regression.ipynb`**: Jupyter notebook for implementing Logistic Regression for the weather prediction task.
- **`119010148_Support_Vector_Machine.ipynb`**: Jupyter notebook for implementing Support Vector Machine for pulsar star classification.
- **`weatherAUS.csv`**: CSV file containing the weather dataset for Logistic Regression.
- **`pulsar_stars.csv`**: CSV file containing the pulsar stars dataset for SVM.
- **`task description.pdf`**: A PDF file containing detailed descriptions of the tasks and instructions for the assignment.
- **`119010148_homework2.pdf`**: Report containing solutions for the written problems in the assignment.

## Results

- **Logistic Regression (Weather Prediction)**: The model predicts weather conditions based on multiple weather-related features. The evaluation includes accuracy and confusion matrix metrics.
- **Support Vector Machine (Pulsar Stars Classification)**: The model classifies pulsar stars using SVM, and its performance is evaluated based on metrics like accuracy, precision, recall, and F1-score.

## Conclusion

This project demonstrates the use of **Logistic Regression** for predicting weather conditions and **Support Vector Machines** for classifying pulsar stars. By applying these algorithms, we gain insight into the effectiveness of different machine learning techniques for classification tasks. The project also highlights the importance of proper data preprocessing and evaluation techniques in ensuring the accuracy and reliability of predictive models.

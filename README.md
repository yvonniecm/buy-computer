# Predicting Computer Purchase Using Machine Learning

## Introduction

This project aims to predict whether a person will buy a computer based on several factors such as age, income, student status, and credit rating. The project leverages the Gaussian Naive Bayes classifier, a popular algorithm in machine learning, known for its simplicity and effectiveness in handling classification tasks.

By analyzing a dataset containing attributes like age, income, student status, and credit rating, the model provides predictions on whether a person is likely to purchase a computer. This type of prediction can be particularly useful for marketing strategies, helping companies to target potential customers more effectively based on their profiles.

The dataset used for this project includes categorical data that is converted into numerical values to make it suitable for machine learning algorithms. The model's performance is evaluated using various metrics such as accuracy, precision, recall, and the confusion matrix, providing a comprehensive assessment of its predictive capabilities.

## Features

1. **Data Preprocessing**:
   - **Conversion of Categorical Data**: Transforming categorical attributes such as age, income, student status, and credit rating into numerical values to facilitate the training of the machine learning model.
   - **Handling Missing Values**: Ensuring the dataset is clean and ready for analysis by managing any missing or inconsistent data entries.

2. **Model Training**:
   - **Gaussian Naive Bayes Classifier**: Utilizing the Gaussian Naive Bayes algorithm, which is suitable for classification tasks with continuous input features, to predict the likelihood of a person buying a computer.
   - **Train-Test Split**: Dividing the dataset into training and testing sets to validate the model's performance and ensure it generalizes well to unseen data.

3. **Model Evaluation**:
   - **Accuracy, Precision, and Recall**: Calculating these metrics to evaluate the model's performance, providing insights into its correctness and reliability.
   - **Confusion Matrix**: Generating a confusion matrix to visualize the model's performance in terms of true positives, true negatives, false positives, and false negatives.
   - **Classification Report**: Providing a detailed report that includes precision, recall, f1-score, and support for each class.

4. **Test Case Scenarios**:
   - **True Positive and True Negative**: Demonstrating the model's ability to correctly identify instances where a person will or will not buy a computer.
   - **False Positive and False Negative**: Highlighting areas where the model may incorrectly predict outcomes, which are critical for understanding the limitations and areas for improvement.

5. **Data Visualization**:
   - **Pie Chart**: Visualizing the distribution of income levels within the dataset, providing insights into the economic background of the participants.
   - **Bar Plot**: Comparing the credit ratings across different age groups to understand the relationship between age and financial credibility.
   - **Horizontal Bar Graph**: Displaying the frequency of different credit ratings, helping to identify common financial profiles within the dataset.

This comprehensive approach ensures that the project not only predicts computer purchase likelihood accurately but also provides meaningful insights through data visualization and thorough model evaluation. These features make the project a valuable tool for businesses aiming to enhance their marketing strategies by targeting the right audience based on predictive analysis.

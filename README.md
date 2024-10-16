
# Naive Bayes Classification

This repository contains the implementation of a Naive Bayes classification model for a data mining task. The model is applied to the "Social Network Ads" dataset to predict whether a user will make a purchase based on their age and estimated salary.








## Features

- Data Preprocessing: The dataset is split into training and test sets, followed by feature scaling to improve model performance.
- Naive Bayes Classification: A Naive Bayes model is used for binary classification (whether a purchase is made or not).
- Visualization of Results: Visualization of decision boundaries on both the training and test sets to interpret model behavior.
- Confusion Matrix: Used to evaluate the performance of the model.


## Requirements
Make sure you have Python installed along with the following libraries:

- numpy
- pandas
- scikit-learn
- matplotlib

You can install them via:
- pip install numpy pandas scikit-learn matplotlib

## Project Structure
- naive_bayes.py: The main Python script that includes the entire process from data import to result visualization.
- dataset/Social_Network_Ads.csv: The dataset used in this project, containing columns for User ID, Gender, Age, Estimated Salary, and Purchased (target variable).
## Dataset
The dataset used in this project contains the following columns:

- User ID: A unique identifier for each user.
- Gender: The gender of the user (Male/Female).
- Age: The age of the user.
- Estimated Salary: The estimated salary of the user.
- Purchased: Whether the user made a purchase (1 for Yes, 0 for No).
## License

This project is licensed under the [MIT](https://choosealicense.com/licenses/mit/) License. Feel free to modify and use it as per your needs.


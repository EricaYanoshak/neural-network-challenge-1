# Neural Network Challenge 1
## Create a Model to Predict Student Loan Repayment
Using the features in the provided dataset to predict whether a borrower will repay their loan, a neural network model was created that provides a more accurate interest rate for the borrower, increasing the likelihood that an applicant will repay their student loans. 

## Installation
The following libraries and dependencies were used to successfully run this project:
- import pandas as pd
- import tensorflow as tf
- from tensorflow.keras.layers import Dense
- from tensorflow.keras.models import Sequential
- from sklearn.model_selection import train_test_split
- from sklearn.preprocessing import StandardScaler
- from sklearn.metrics import classification_report
- from pathlib import Path

## Methodology
### Part 1: Prepare the Data for Use on a Neural Network Model
Using `Pandas` and `scikit-learn’s StandardScaler()`, data was preprocessed to compile and evaluate the neural network model.

### Part 2: Compile and Evaluate Model Using a Neural Network
Using `TensorFlow` to design a deep neural network model, this project model used the dataset’s features to predict the credit quality of a student based on the features in the dataset. This is done by:
1. Considering the number of inputs, layers and neurons on each layer
2. Compiling and fitting the project model
3. Evaluating the project model and calculating its loss and accuracy
4. Save the project moel

### Part 3: Predict Loan Repayment Success Using Neural Network Project Model
Using the saved project, predictions were made on reserved testing data.

### Part 4: Essentials to Creating a Recommendation System for Student Loans
* To provide a comprehensive view of the student's financial and academic situation, essential data would include student profiles (age, education level, GPA, field of study), financial information (income, financial aid), loan history, credit score, and geographic location.
* The system would use context-based filtering, which leverages personal and situational factors, making it more suitable than collaborative or content-based filtering.
* Key challenges include ensuring data privacy and security, as sensitive financial data could be at risk, and preventing bias to avoid discrimination against students from marginalized backgrounds.

## References Used
- Class notes and activities from AI Bootcamp, Model 18. (2023). edX Boot Camps LLC
- This project took advantage of [Xpert Learning Assistant](https://bootcampspot.instructure.com/courses/6141/external_tools/313) to help with coding errors




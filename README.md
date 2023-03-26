# Placement-prediction-model
This is cgpa prediction model. The dataset is also created by me. 
This is an example code for building a placement prediction model in Python using the scikit-learn library. The model uses logistic regression to predict the placement prospects of a new student based on their academic performance, skills, and experience.
Dependencies

This code requires the following dependencies:

    *pandas
    *scikit-learn

These can be installed using pip by running:

pip install pandas scikit-learn

Data

The placement data used in this example is assumed to be stored in a CSV file named placement_data.csv. The file should contain the following columns:

    *cgpa
    *iq
    *placement_status

The placement_status column indicates whether the student was placed or not.
Usage

To use this code, follow these steps:

    1-Load the placement data from the CSV file using pandas.
    2-Prepare the input features (X) and target variable (y) by dropping the placement_status column from the input data and storing it separately as the target variable.
    3-Split the data into training and testing sets using the train_test_split function from scikit-learn.
    4-Train a logistic regression model using the fit method of the LogisticRegression class.
    5-Evaluate the accuracy of the model on the test set using the score method of the LogisticRegression class.
    6-Make a placement prediction for a new student by passing their input features as a list to the predict method of the model.

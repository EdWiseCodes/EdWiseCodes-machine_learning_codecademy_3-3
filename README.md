machine_learning_codecademy_3-3

As part of the Codecademy Data Science course, I was tasked with building machine learning models using data from the dating
application OKCupid. As the last project in the course where I was provided with data to work with (rather than sourcing it myself), this project was intended as an opportunity to demonstrate the programming, data visualisation, data analysis, and machine learning competencies I'd developed over the course. 

The goal of my project is to create a machine learning classification model that can predict whether a user was male or female. Below I go into more detail about the goals of the project, the data used, the analysis performed, and the evaluations undertaken.

**Project Goals**

As stated above, the primary goal of the project is to create a machine learning classification model that can predict whether a user was male or female. The reason this goal was selected was to ensure that there was enough data to build a successful machine learning model (as m/f is a compulsory column to sign up to the site), allowing me to try (and optimise) several different classification algorithms.

**Data**

The data covers the responses of OKCupid users to a number of questions, both multiple choice and longer written 'essay' questions. Each row represents an OkCupid user and each column is a different question. The data provided is in the csv file: `profiles.csv`.

**Analysis**

Firstly, I perform exploratory data analysis on the dataset, including basic descriptive statistics and data visualisation, to evaluate which variables to include in the machine learning model. After preparing and splitting the data, several different classification algorithms from the supervised learning family of machine learning models are used in an attempt to predict whether a given user is male or female. I then attempt to optimise these models.

**Evaluation**

The project concludes by evaluating the different optimised machine learning models built in the previous step. We use accuracy, precision, recall, and F1 scores to compare the quality of the models.

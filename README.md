# Mobile-Phone-Addiction
Mobile phone overuse among youth and students is becoming a serious issue in India and globally. The goal is to predict mobile addiction levels based on features such as time spent, purpose of use, and behavioral symptoms.
.
This project focuses on detecting and predicting the level of mobile phone addiction in teenagers using a machine learning approach. It utilizes behavioral and usage patterns such as screen time, sleep duration, and social media usage. The project explores both regression (to predict addiction level) and classification (to detect if a teen is addicted or not).

#Objectives#
-Predict the addiction level on a scale of 0 to 10 (regression).

-Classify whether a teen is addicted (binary classification based on threshold).

-Analyze which features contribute most to predicting mobile phone addiction.


Dataset Description
The dataset includes the following features:

Age: Age of the teenager

Gender: Male or Female

Daily_Usage_Hours: Average daily phone usage

Sleep_Hours: Average sleep hours per night

Time_on_Social_Media: Time spent on platforms like Instagram, Snapchat, etc.

Screen_Time_Before_Bed: Phone screen time before sleeping

Family_Communication: Self-reported quality of family communication (score-based)

Addiction_Level: Label from 0 to 10 indicating how addicted the user is

A binary target column Is_Addicted is also created where addiction level > 6.5 is marked as addicted (1) and otherwise 0.

#Machine Learning Models Used
Linear Regression – to predict addiction level (continuous output).
Random Forest Classifier – to classify whether a teen is addicted or not.

#Results
Regression (Addiction Level Prediction)
Mean Squared Error: ~ ()

R² Score: ~ ()

Classification (Is Addicted or Not)
Accuracy: ~ (91%)

Classification Report: Includes precision, recall, and F1-score for addicted vs not addicted classes.

-Features like Daily_Usage_Hours, Screen_Time_Before_Bed, and Time_on_Social_Media had strong influence on addiction prediction.
-A regression threshold of 6.5 was found useful to define the binary addiction label.
-High accuracy was achieved using a Random Forest classifier.

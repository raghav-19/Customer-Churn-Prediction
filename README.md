# Customer Churn Prediction for Subscription

## Author : Raghav Raipuria

## Introduction to Challenge
In this Case Study we will be working for a fintech company that wants to provide its customers with a paid mobile app subscription that will allow them to track all of their finances in one place. To attract customers, the company releases a free version of their app with some of the main features unlocked.

The company has tasked you to identify which users will most likely not enroll in the paid product, so that additional offers can be given to them. Because of the costs of these offers, the company does not want to offer them to everybody, especially customers who were going to enroll anyways.

Market: The target audience is customers who use a company's free product. In this case study, this refers to users who installed (and used) the company's free mobile app.

Product: The paid memberships often provide enhanced versions of the free products already given for free, alongside new features.

Goal: The objective of this model is to predict which users will not subscribe to the paid membership, so that greater marketing efforts can go into trying to "convert" them to paid users.

## Dataset
By working for the company, we have access to each customer's app behavior data. This data allows us to see the date and time of app installation, as well as the features the users engaged with within the app. App behavior is characterized as the list of app screens the user looked at, and whether the user played the financial mini-games available.

The app usage data is only from the user's first day in the app. This limitation exists because users can enjoy a 24-hour free trial of the premium features, and the company wants to target them with new offers shortly after the trial is over.

Above mentioned Dataset is stored in file - "appdata10.csv"

Luckily Company also provided list of top screen used by user to reduce number of feature in file - "top_screens.csv"

## Files
"fintech_eda.py" and "fintech_eda.ipynb" are python and notebook files respectively for performing Data Cleaning with Statistical Analysis that stores the data in "new_appdata10.csv" after data cleaning and adding new feature related to top_screen and first_open and enrolled_time.

"fintech_model.py" and "fintech_model.ipynb" are python and notebook files respectively for creating Logistic Regression & XGboost Model, comparision on based of Classification Metrics such as confusion_matrix, accuracy, precision, recall, f1_score.

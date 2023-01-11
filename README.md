# british-airways-grad-challenge

## Problem Statement
Customers are more empowered than ever because they have access to a wealth of information at their fingertips. This is one of the reasons the buying cycle is very different to what it used to be. Today, if you’re hoping that a customer purchases your flights or holidays as they come into the airport, you’ve already lost! Being reactive in this situation is not ideal; airlines must be proactive in order to acquire customers before they embark on their holiday.

This is possible with the use of data and predictive models. The most important factor with a predictive model is the quality of the data you use to train the machine learning algorithms. For this task, you must manipulate and prepare the provided customer booking data so that you can build a high-quality predictive model.

## Objectives
- Explore and prepare the customer booking data for use in a predictive model
- Train a machine learning model to predict the likelihood of a customer making a booking
- Evaluate the model's performance and interpret the results to understand the contributions of each variable to the model's predictive power
- Summarize findings in a single slide for presentation to management
## Evaluation Criteria
- Accuracy of the predictive model
- Interpretability of the model and its contributions from each variable
- Quality of the summary slide presentation
## Data Description
The dataset for this project is a customer booking data provided in the Customer Booking.csv file. It includes various features such as customer demographics and past booking information.
- num_passengers = number of passengers travelling
- sales_channel = sales channel booking was made on
- trip_type = trip Type (Round Trip, One Way, Circle Trip)
- purchase_lead = number of days between travel date and booking date
- length_of_stay = number of days spent at destination
- flight_hour = hour of flight departure
- flight_day = day of week of flight departure
- route = origin -> destination flight route
- booking_origin = country from where booking was made
- wants_extra_baggage = if the customer wanted extra baggage in the booking
- wants_preferred_seat = if the customer wanted a preferred seat in the booking
- wants_in_flight_meals = if the customer wanted in-flight meals in the booking
- flight_duration = total duration of flight (in hours)
- booking_complete = flag indicating if the customer completed the booking

## Resources
- [scikit-learn: Machine Learning in Python](https://scikit-learn.org/stable/supervised_learning.html)
- [scikit-learn: Evaluation Metrics in Python](https://scikit-learn.org/stable/modules/model_evaluation.html)
- Customer Booking.csv
## Evaluation Metric
The primary evaluation metric for this project will be the accuracy of the predictive model. This will be measured through cross-validation and the calculation of appropriate evaluation metrics such as precision, recall, and F1 score.

## Solution

1. [BA customer reviews analysis](BA_reviews_analysis.ipynb)
2. [BA customer booking prediction](booking_prediction.ipynb)

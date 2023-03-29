# Project-STEDI-Human-Balance-Analytics

This repository is a use case for developing a Data lakehouse in Amazon Web Service (AWS). For that we are going to implement Spark jobs in AWS Glue, that allows us to process data from multiple sources, categorize the data, and curate it to be queried in the future for multiple purposes.
The use case is based on a company STEDI that analyze sensor data from the STEDI team to build a data lakehouse solution for sensor data that trains a machine learning model.

The STEDI Team has been hard at work developing a hardware STEDI Step Trainer that:
1. It trains the user to do a STEDI balance exercise.
2. It sensors on the device that collect data to train a machine-learning algorithm to detect steps.
3. It has a companion mobile app that collects customer data and interacts with the device sensors.

The Step Trainer is just a motion sensor that records the distance of the object detected. The app uses a mobile phone accelerometer to detect motion in the X, Y, and Z directions. The STEDI team wants to use the motion sensor data to train a machine learning model to detect steps accurately in real-time. Privacy will be a primary consideration in deciding what data can be used. Some early adopters have agreed to share their data for research purposes. Only these customers’ Step Trainer and accelerometer data should be used in the training data for the machine learning model.



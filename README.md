# Road-traffic-accident-severity-prediction-ML

## Introduction
- This is a multiclass classification project to classify the severity of road accidents into three categories. This project is based on real-world data, and the dataset is also highly imbalanced. There are three types of injuries in a target variable: minor, severe, and fatal.

- Road accidents are the major cause of unnatural deaths around the world. All governments work hard to raise awareness about the rules and regulations that must be followed when driving a vehicle on the road in order to reduce fatalities. Thus, it is necessary to have a mechanism that predicts the severity of such accidents and helps in reducing fatalities.

## Problem statement
- The target feature is “Accident_severity,” which is a multi-class variable. The task is to classify this variable based on the other 32 features step-by-step by going through each data science process and task. 

- We will work on the end-to-end project on which we developed a machine-learning solution to predict the severity of road accidents in order to take necessary precautions by the investigation agency.

## Data description
This dataset is sourced from Kaggle of an Addis Ababa Sub-city, Ethiopia. The data set was prepared from manual documents of road traffic accidents for the years 2017–20. The features are,
- Time — time of the accident (In 24 hours format)
- Day_of_week — A day when an accident occurred
- Age_band_of_driver —The age group of the driver
- Sex_of_driver — Gender of driver
- Educational_level — Driver’s highest education level
- Vehical_driver_relation — What’s the relation of a driver with the vehicle
- Driving_experience — How many years of driving experience the driver has
- Type_of_vehicle — What’s the type of vehicle
- Owner_of_vehicle — Who’s the owner of the vehicle
- Service_year_of_vehicle — The last service year of the vehicle
- Defect_of_vehicle — Is there any defect on the vehicle or not?- Area_accident_occured — Locality of an accident site
- Lanes_or_Medians — Are there any lanes or medians at the accident site?
- Road_allignment — Road alignment with the terrain of the land
- Types_of_junction — Type of junction at the accident site
- Road_surface_type — A surface type of road
- Road_surface_conditions — What was the condition of the road surface?
- Light_conditions — Lighting conditions at the site
- Weather_conditions — Weather situation at the site of an accident
- Type_of_collision — What is the type of collision
- Number_of_vehicles_involved — Total number of vehicles involved in an accident
- Number_of_casualties — Total number of casualties in an accident
- Vehicle_movement — How the vehicle was moving before the accident occurred
- Casualty_class — A person who got killed during an accident
- Sex_of_casualty — What the gender of a person who got killed
- Age_band_of_casualty — Age group of casualty
- Casualty_severtiy — How severely the casualty was injured
- Work_of_casualty — What was the work of the casualty
- Fitness_of_casualty — Fitness level of casualty
- Pedestrain_movement — Was there any pedestrian movement on the road?
- Cause_of-accident — What was the cause of an accident?
- Accident_severity — How severe an accident was? (Target variable)

## Model building
- Encoding : Converting categorical variables into numerical representations for machine learning algorithms. 

- Feature selection using chi-square :To determine if there is a significant association between categorical features and the target variable. we have categorical data and  want to identify the most relevant features for your classification problem.

- Imbalance data treatment using the ‘SMOTE’ technique :To address the problem of imbalanced datasets, where one class (the minority class) has significantly fewer instances than the other class (the majority class).

- Splitting the Data Frame: : Dividing the dataset into 2 data frames independent features and dependent feature i.e., target variable to evaluate 

- Train test split : Dividing the dataset into training and testing sets to evaluate model performance.



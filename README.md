# Road Accident Severity Predictor

## Introduction

This is a multiclass classification project that classifies the severity of road accidents into three categories:  
- Minor  
- Severe  
- Fatal

The project uses a real-world dataset that is highly imbalanced.  
Road accidents are one of the leading causes of unnatural deaths globally. Being able to predict the severity of an accident can help in timely emergency response and implementation of road safety measures.

---

## Objective

- To learn and implement machine learning pipelines using real-world data.
- To classify accident severity (`Accident_severity`) using 31 relevant features.
- To evaluate the model using F1 Score, Confusion Matrix, and Classification Report.

---

## Problem Statement

Given 31 features related to the driver, vehicle, environment, and casualty, predict the class of `Accident_severity`.  
This is a multi-class classification task with an imbalanced dataset.

---

## Dataset Description

Here are the features used in the dataset:

| Feature | Description |
|--------|-------------|
| Time | Time of the accident (24-hour format) |
| Day_of_week | Day the accident occurred |
| Age_band_of_driver | Age group of the driver |
| Sex_of_driver | Gender of the driver |
| Educational_level | Driver’s education level |
| Vehicle_driver_relation | Relation of driver with the vehicle |
| Driving_experience | Driving experience in years |
| Type_of_vehicle | Type of vehicle |
| Owner_of_vehicle | Ownership status |
| Service_year_of_vehicle | Last service year |
| Defect_of_vehicle | Any vehicle defects |
| Area_accident_occured | Area of the accident |
| Lanes_or_Medians | Presence of lanes/medians |
| Road_allignment | Road alignment type |
| Types_of_junction | Junction type |
| Road_surface_type | Surface type |
| Road_surface_conditions | Surface conditions |
| Light_conditions | Lighting at the scene |
| Weather_conditions | Weather during accident |
| Type_of_collision | Collision type |
| Number_of_vehicles_involved | Vehicles involved |
| Number_of_casualties | Casualties in accident |
| Vehicle_movement | Vehicle movement |
| Casualty_class | Class of casualty |
| Sex_of_casualty | Casualty gender |
| Age_band_of_casualty | Age group of casualty |
| Casualty_severity | Severity of injury |
| Work_of_casualty | Casualty’s occupation |
| Fitness_of_casualty | Fitness level |
| Pedestrian_movement | Pedestrian movement |
| Cause_of_accident | Cause of the accident |
| Accident_severity | Target variable |

---

## Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

## Project Structure
Accident_severity_predictor/
│
├── Accident_severity_Predictor.py         # Script for training and saving pipeline
├── Road_accident_sevrity.ipynb            # Notebook with analysis and model building
├── pipe_dataset_road_accident.csv         # Cleaned and transformed dataset
├── piped.pkl                              # Serialized pipeline model
├── img.jpg                                # Project-related visualization/image
├── README.md                              # Project documentation

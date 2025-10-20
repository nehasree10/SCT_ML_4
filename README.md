🌳 Decision Tree Classifier on Bank Marketing Dataset
📘 Overview

This project implements a Decision Tree Classifier to predict whether a customer will subscribe to a term deposit based on the Bank Marketing dataset from the UCI Machine Learning Repository.
It demonstrates end-to-end data handling — from extraction and preprocessing to model training, evaluation, and visualization.

🧠 Key Features

✅ Automatically extracts nested ZIP files containing the dataset

✅ Encodes categorical columns using LabelEncoder

✅ Splits data into training and testing sets

✅ Trains a Decision Tree Classifier

✅ Evaluates model performance using accuracy and classification report

✅ Visualizes the trained decision tree for better interpretability

🧩 Technologies Used

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Google Colab

📂 Dataset Details

The dataset is the Bank Marketing Dataset from the UCI Machine Learning Repository
.

Folder Structure after Extraction:

bank+marketing.zip
│
└── bank-additional.zip
     └── bank-additional-full.csv


Key Columns:

Feature	Description
age	Age of the customer
job	Type of job (e.g., admin, technician, services)
marital	Marital status
education	Education level
balance	Average yearly account balance
housing	Has a housing loan?
loan	Has a personal loan?
contact	Communication type
month, day_of_week	Last contact date
duration	Duration of the last contact
campaign	Number of contacts during this campaign
pdays, previous, poutcome	Information about previous campaigns
y	Target — whether client subscribed to a term deposit (yes / no# SCT_ML_4

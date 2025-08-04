Healthcare Stroke Data Dashboard
This repository contains the R Shiny application for interactively exploring a healthcare dataset related to stroke prediction.

Purpose of the App
The "Healthcare Stroke Data Dashboard" is designed to provide a user-friendly interface for data exploration and analysis of stroke-related health data. It allows users to:

View overall summary statistics of the dataset.

Examine the frequency and distribution of stroke occurrences.

Analyze how stroke rates vary across different demographic and health-related factors.

Dynamically filter the dataset based on gender, age range, and smoking status.

Download the filtered data for further offline analysis.

This interactive tool aims to help researchers, healthcare professionals, and anyone interested in public health to gain quick insights into the dataset and identify potential risk factors associated with stroke.

Data Source
The dataset used in this application is sourced from:
"Healthcare Dataset Stroke Data"

Original Source: Kaggle (or similar public domain dataset).

Description: This dataset contains 12 features, including patient ID, gender, age, hypertension, heart disease, ever married status, work type, residence type, average glucose level, BMI, smoking status, and stroke outcome.

Note: The data used in this application has undergone a cleaning and transformation process as detailed in the project's R scripts (e.g., handling missing BMI values, converting categorical variables to factors, creating age groups).

Instructions to Run the App
To run this Shiny application on your local machine, please follow these steps:

Prerequisites: Ensure you have R and RStudio installed on your computer.

Install R Packages: Open RStudio and install the necessary R packages by running the following commands in your R console:

install.packages(c("shiny", "dplyr", "ggplot2", "DT", "shinythemes"))

Download the Application Files:

Create a new directory on your computer (e.g., stroke_dashboard_app).

Inside this directory, create a file named app.R and paste the entire R code provided for the Shiny application into it.

Create a subdirectory within stroke_dashboard_app named output_data.

Place your cleaned dataset file, healthcare-dataset-stroke-data_cleaned.csv, into the output_data directory.
Your final directory structure should look like this:

stroke_dashboard_app/
├── app.R
└── output_data/
    └── healthcare-dataset-stroke-data_cleaned.csv

Run the App:

Open RStudio.

Navigate to the stroke_dashboard_app directory (you can do this via File > Open Project... or Session > Set Working Directory > Choose Directory...).

Open the app.R file.

Click the "Run App" button located in the top-right corner of the script editor pane.

The application should launch in your default web browser or RStudio's Viewer pane.

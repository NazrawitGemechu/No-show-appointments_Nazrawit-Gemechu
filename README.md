
 # Medical Appointment No Shows - Data Analysis Assignment

## Overview
This project analyzes the "Medical Appointment No Shows" dataset from Kaggle to uncover factors influencing whether a patient will show up for their scheduled appointment. The analysis follows a systematic process, including data wrangling, exploratory data analysis (EDA), feature engineering, and predictive modeling using a Random Forest Classifier.

## Dataset
The dataset used in this analysis is sourced from Kaggle, titled "Medical Appointment No Shows." It encompasses information about medical appointments, including patient age, gender, scheduled and appointment dates, and whether the patient showed up.

## Project Steps

### Step 1: Wrangle Data
- **Gather Data:** Loaded the dataset and displayed the first few rows for a quick overview.
- **Assess Data:** Checked for missing values and duplicates, removing any redundant rows.
- **Clean Data:** Converted date columns to datetime format, calculated waiting times, and handled negative waiting times.

### Step 2: Perform EDA
- **Explore Distribution:** Visualized the distribution of the target variable "No-show."
- **Visualize Relationships:** Explored relationships between features and the target variable, focusing on age's impact on no-show appointments.

### Step 3: Draw Conclusions
- **Overall No-show Rate:** Calculated and displayed the overall no-show rate.
- **No-show Rate by Day of the Week:** Explored factors affecting no-shows, such as the day of the week.

### Prediction
- **Feature Importance:** Trained a Random Forest Classifier, identified feature importance, and drew conclusions about factors influencing no-show appointments.
- **Overall Prediction Accuracy:** Evaluated the model's accuracy and provided a classification report.

## Findings and Key Insights
- **Overall No-show Rate:** The analysis revealed an overall no-show rate of 20.19%, indicating the proportion of appointments where patients did not show up.
- **Day of the Week Impact:** Further exploration found variations in no-show rates based on the day of the week, with the following no show for each days of the week DayOfWeek
    - **Friday       0.212261**
    - **Monday       0.206471**
    - **Saturday     0.230769**
    - **Thursday     0.193541**
    - **Tuesday      0.200936**
    - **Wednesday    0.196892**
- **Predictive Model Insights:**  Age and Scholarship are important factors in predicting no-show

## Conclusion
This project provided valuable insights into the factors influencing medical appointment no-shows. 
- **Dataset Source:** [Kaggle - Medical Appointment No Shows]https://www.kaggle.com/datasets/joniarroba/noshowappointments

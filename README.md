# Exploratory Data Analysis of Medical Appointment No-Shows in Brazil

## Introduction

The aim of this project is to explore and analyze a dataset containing information from 100k medical appointments in Brazil. The dataset focuses on the question of whether or not patients show up for their appointment, and includes several features such as Scheduled Day, Neighborhood, Scholarship, and the status of the patient's attendance.

## Dataset Description

The following are the features of the dataset:
- `ScheduledDay`: Indicates the date when the patient booked their appointment.
- `Neighborhood`: Indicates the location of the hospital.
- `Scholarship`: Indicates whether or not the patient is enrolled in the Brazilian welfare program Bolsa Família.
- `No-show`: Indicates whether or not the patient showed up to their appointment. It contains 'No' if the patient attended and 'Yes' if the patient did not attend.

## Research Questions

The following are the research questions to be explored in this project:
- How many patients attended or did not attend their appointment?
- What is the age distribution of patients who attended or did not attend their appointments?
- Which neighborhoods (hospital locations) had both high patient-appointment attendance and low patient-appointment attendance?
- Did patients who received an SMS attend or not attend their appointment?
- Which health condition or reason was the most frequent in terms of patient-appointment attendance?
- What scheduled day had the most attendance of patient-appointments?
- How many patients are enrolled or not enrolled in the Brazilian welfare program Bolsa Família?
- Are no-show appointments associated with a certain gender?

## Package Dependencies

The following are the packages that need to be installed before running the analysis:
- `numpy`
- `pandas`
- `matplotlib`

You can install these packages using either `pip` or `conda`. If you have `pip` installed, you can run the following command in your terminal:

```bash
pip install numpy pandas matplotlib
conda install numpy pandas matplotlib

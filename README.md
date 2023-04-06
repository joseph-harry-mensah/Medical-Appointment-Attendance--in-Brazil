# Investigating No-Show Medical Appointments in Brazil

This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. 

The `ScheduledDay` column tells us on what day the patient booked their appointment. The `Neighborhood` column indicates the location of the hospital. The `Scholarship` column indicates whether or not the patient is enrolled in the Brazilian welfare program Bolsa Família. The last column of the dataset indicates `No` if the patient showed up to their appointment, and `Yes` if they did not show up.

## Questions

The following are the questions I sought to answer through exploratory data analysis on this dataset:

- How many patients attended or did not attend their appointment?
- What ages of patients attended or did not attend their appointments?
- Which neighborhoods had both high patient-appointment attendance and low patient-appointment attendance?
- Did patients who received an SMS attend or not attend their appointment?
- What health condition or reason was most frequent in terms of patient-appointment attendance?
- What scheduled day had the most attendance of patient-appointments?
- How many patients are enrolled or not enrolled in the Brazilian welfare program Bolsa Família?
- Are no-show appointments associated with a certain gender?

## Dependencies

The following Python packages were used for the analysis:

- NumPy
- Pandas
- Matplotlib

You can install these packages using either `pip` or `conda`.

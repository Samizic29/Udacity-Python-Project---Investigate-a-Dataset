# Investigate a Dataset - [Medical Appointment No Shows]

## Dataset

> This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row. It consists of 14 variables:

- AppointmentId: Identification of each appointment
- Gender: Male or Female
- ScheduleDay: The day the patient set up their appointment
- AppointmentDay: The day of appointment
- Age: The patient age
- Neighbourhood: Where the appointment take place
- Scholarship: True / False (Indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família.
- Hypertension: True (1) / False (0)
- Diabetes: True (1) / False (0)
- Alcoholism: True (1) / False (0)
- Handicap: True (1) / False (0)
- SMS_received: True (1) / False (0)
- No-show: Yes / No (‘No’ if the patient showed up to their appointment, and ‘Yes’ if they did not show up.)

## Data Wrangling

> In the section, It involve gathering, accessing and cleaning of the data. The dataset was gathered, accessed it to inspect any outliers in the data and clean the data for analysis.

### Assessment

- Clean the column names for consistent column names
- Replace no-show values with integer values for better analysis
- Changing the data types of some columns
- Drop columns that are not important to the analysis

## Summary of Findings

> After analysis and exploration:

- Females show up more to their appointment compare to Male Gender.
- Young patients tend to show up more to their appointment compare to adult patients
- Hypertensive patients do not show up more to their appintment compare to Non-Hypertensive patients
- Patients do not show up more to their appintment compare to Non-Diabetic patients
- Non-Alcoholic patients tend to show up more to their appintment compare to Alcoholic patients
- Patient with scholarship show up more to their appointment compare to non-scholarship patients

## Limitation

- There is no location of the patients: The location of patients should be provided to help explore more analysis on the no show appointments.

# Patients Overview

This analysis explores the factors that influence patient satisfaction in a hospital setting, based on inpatient records. Understanding these drivers helps the management identify operational areas that impact patient experience and quality of care.

We first start by understanding the satisfaction of the patients and factors that could influence it. The Patient's dataset, provided valuable insight about this.

The patient's dataset highlights the patients' age, arrival and departure dates and times, the service provided and the satisfaction score.

![Patients Overview](/Resources/Power%20BI%20files/Snapshots/Patients%20Overview.png)

The average patient satisfaction for the duration the data was collected, was **79 %**. This metric indicates a generally positive patient perception.

## Key Factors Influencing the Scores.

The dataset only includes patients that were admitted in the hospital and no outpatients. The factors that I have assessed to determine their influence on the patient satisfaction are:

 1. Services Provided to the patients
 2. Duration of the patients' stay
 3. Patients' age

### Services Provided to the Patients
According to the dataset, the services provided are:

- Emergency
- General Medicine
- Intensive Care Unit (ICU)
- Surgery

![Patients Satisfaction by Service Graph](/Resources/Power%20BI%20files/Snapshots/Patients%20Service.png)

The data shows that Patient satisfaction is generally similar across all the services provided in the hospital (between **78 and &0**). This suggests that the services provided are not a direct area of weakness in the hospital.

Patient satisfaction remains consistent across all service departments, suggesting balanced care quality.

### Patients' stay duration 
![Patients Satisfaction by Hospital Stay](/Resources/Power%20BI%20files/Snapshots/Patients%20Stay.png)

The graph shows the satisfaction of the patients according to their stay length in the hospital. Again, the values are within the same range and close to the mean (**77 to 80**). The patients' stay is not a limiting factor to patient satisfaction.

### Patients' Age

![Patients Satisfaction by Age Graph](/Resources/Power%20BI%20files/Snapshots/Patients%20Age.png)

Patient satisfaction also remains consistent across all age groups, suggesting balanced care quality.

---

Since satisfaction remains steady across departments and age groups, the hospital demonstrates consistent care standards. However, this consistency also means improvements must come from broader systemic changes rather than isolated service enhancements.


## Unsatisfied Patients
The visualisations above did not provide direct results. We therefore created a threshold to distinguish satisfied patients from the unsatisfied.
The threshold for determining satisfaction is **70**.

![Unsatisfied Patients](/Resources/Power%20BI%20files/Snapshots/Unsatisfied%20Patients%20Overview.png)

Using this new metric, we see that **24 %** of the patients were unsatisfied. 

Interestingly, patients aged around **77** reported notably lower satisfaction. This could indicate that older patients face unmet needs — possibly accessibility challenges, communication barriers, or comfort issues — that merit further investigation.



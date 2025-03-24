# Hospital Emergency Room Dashboard

## Project Overview

This project analyzes emergency room visit data to uncover insights about patient demographics, wait times, satisfaction, and referral patterns. The goal is to monitor hospital operations, improve response time, and enhance the quality of care using Power BI dashboards.

The dataset contains over 9,000 patient records, offering a comprehensive view of ER activity based on age, gender, race, department referrals, admission status, and timing.

---
## Dashboard

![image](https://github.com/user-attachments/assets/5825e626-79e8-4d1a-af66-6448e5c99822)


<p align="center">
  View the full Power BI report <a href="https://app.powerbi.com/groups/me/reports/f117c351-36cd-4d97-859c-a01664249390/3fef9643b86e01c759fa?experience=power-bi">HERE</a>
  
## Dataset Description

The following table outlines the variables used in the analysis:

| Column Name                     | Description                                                       |
|--------------------------------|-------------------------------------------------------------------|
| Patient Id                     | Unique identifier for each patient                               |
| Patient Admission Date         | Timestamp when the patient was admitted to the ER                |
| Patient First Inital           | First letter of the patient's first name                         |
| Patient Last Name              | Patient's last name                                              |
| Patient Gender                 | Gender of the patient (Male, Female, Non-Conforming)             |
| Patient Age                    | Age of the patient at the time of admission                      |
| Patient Race                   | Race of the patient                                              |
| Admitted vs Not Admitted       | Admission outcome (Admitted / Not Admitted)                      |
| Department Referral            | Department the patient was referred to (e.g., Ortho, Neuro)      |
| Patient Admin Flag             | Boolean indicating if the patient was admitted                   |
| Target Status                  | Whether the patient was seen within the 30-minute target         |
| Patient Satisfaction Score     | Satisfaction score provided by patient (scale of 0–10)           |
| Patient Waittime               | Time (in minutes) the patient waited before being seen           |
| Patients CM                    | Count metric for Power BI visuals (usually set as 1 per record)  |

---

## Summary Metrics

![image](https://github.com/user-attachments/assets/f5707d78-e69b-4254-bccf-210135e2554a)

- **Total Patients:** 9,216
- **Average Wait Time:** 35.3 minutes
- **Average Patient Satisfaction Score:** 4.99
- **Patients Referred to Departments:** 3,816
- **Patients Admitted:** 4,612 (50%)
- **Patients Seen Within 30 Minutes:** 5,467 (59.32%)

---

## Key Insights

### Admission Status

![image](https://github.com/user-attachments/assets/11749c55-a75c-4572-b55f-6562eef25639)


- Patients are nearly evenly split between **admitted (50.04%)** and **not admitted (49.96%)**.
- Balanced admission suggests effective triage, but opportunities may exist to reduce unnecessary ER use.

### Gender Breakdown

![image](https://github.com/user-attachments/assets/326b0bd6-ace5-49a7-8bb6-4a0067e31e2e)

- **Male:** 4,481 (48.68%)
- **Female:** 4,718 (51.05%)
- **Non-Conforming:** 25 (0.26%)

### Wait Time Performance

![image](https://github.com/user-attachments/assets/a61da1b3-cc4b-455c-a554-a9efd2e3ffa7)

- **Within Target (≤ 30 min):** 59.32%
- **Missed Target:** 40.68%
- Improving triage or staffing during peak hours could enhance these results.

### Referrals by Department

![image](https://github.com/user-attachments/assets/82b6be29-3772-4f07-b63a-fa896b05082b)

| Department           | Patients Referred |
|----------------------|-------------------|
| None                 | 5,400             |
| General Practice     | 1,000             |
| Orthopedics          | 1,000             |
| Physiotherapy        | 300               |
| Cardiology           | 200               |
| Neurology            | 120               |
| Gastroenterology     | 123               |
| Renal                | 100               |

Most patients were **not referred** to another department, indicating that issues were resolved in the ER or didn’t require further treatment.

### Age Group Distribution

![image](https://github.com/user-attachments/assets/d8752079-9028-4920-8e3a-4c479d7b935a)

Age groups 10–69 are fairly evenly represented, with a peak in ages **10–19** and **30–39**.

### Peak Time Analysis

![image](https://github.com/user-attachments/assets/fea6a87b-66c3-4cb1-a24c-4edb74248448)

- **Busiest Day:** Saturday (1,377 patients)
- **Busiest Hour:** 19:00–20:00
- Recommend staffing adjustments during peak weekend evenings.

### Race Demographics

![image](https://github.com/user-attachments/assets/db31a4ec-0807-4cd6-a494-079aca6d49f4)

| Race                          | Count |
|-------------------------------|-------|
| White                         | 2,571 |
| African American              | 1,951 |
| Two or More Races             | 1,557 |
| Asian                         | 1,060 |
| Declined to Identify          | 1,030 |
| Pacific Islander              | 549   |
| Native American/Alaska Native| 498   |

Diversity in racial demographics requires culturally competent care and language support strategies.

---

## Recommendations

1. **Optimize Peak Hour Staffing:** Reinforce staff during 6 PM to 10 PM, especially on weekends.
2. **Reduce Wait Times:** Implement faster triage systems and digital check-ins to increase the percentage of patients seen within 30 minutes.
3. **Target Satisfaction Improvement:** Investigate lower-scoring cases and align staff training accordingly.
4. **Monitor Non-Referred Cases:** Determine if non-referrals result from resolved issues or missed opportunities for further care.
5. **Enhance Cultural Competence:** Use racial demographics to train staff and tailor patient engagement strategies.



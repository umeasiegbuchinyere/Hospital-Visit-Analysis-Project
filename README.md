# Hospital-Visit-Analysis-Project

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/728b7172-0864-4863-8f64-03f54b01038e" />

# Table of Content
- [Project Overview](#Project-Overview)
- [Data Source](#Data-Source)
- [Problem Statement](#Problem-Statement)
- [Tools Used](#Tools-Used)
- [Skills Demonstrated](#Skills-Demonstrated)
- [Data Analysis](#Data-Analysis)
- [Visualisations](#Visualisations)
- [Insights from Analysis](#Insights-from-Analysis)
- [Conclusion and Recommendations](#Conclusion-and-Recommendations)

# Project Overview
This project analyzes hospital patient data to uncover key insights on treatment outcomes, cost drivers, and diagnosis trends. By examining factors such as age, gender,
insurance type, and admission method across hospital locations, the analysis aims to identify high-risk conditions, assess healthcare equity, and support data-driven decisions
for improving patient care and resource allocation.

# Data Source
This dataset is a simulated hospital records dataset created for analytical and educational purposes. It mimics real-world healthcare data by including key fields such as 
patient demographics, diagnosis codes (ICD-10), admission types, treatment costs, and outcomes. While not drawn from a live healthcare system, it is structured to reflect common 
trends in hospital data for the purpose of exploring healthcare insights and decision-making.

# Problem Statement
Despite increasing healthcare access, hospitals face challenges in managing treatment outcomes, cost efficiency, and equitable care delivery. This dataset aims to explore how 
patient demographics, diagnoses, admission types, and insurance coverage influence treatment costs and health outcomes—helping to identify gaps, high-risk conditions, and 
opportunities for improved hospital resource allocation and patient care.

# Tools used
- Excel

# Skills Demonstrated
The table was Formatted and Duplicate value were checked.

# Data Analysis
The following Pivot Chart were drew from the data
-	Diagnosis vs Outcome
-	Hospital Location vs Average Treatment cost
-	Admission type vs Outcome
-	Insurance type vs Average Treatment cost
-	Diagnosis vs Treatment cost
-	Age Group vs Outcome
-	Gender and Ethnicity vs Diagnosis

# Visualisations
A comprehensive dashboard was developed by assembling the pivot charts to allow for interactive insights into health.

Slicer Application: Slicers were added via Insert > Slicer, allowing dynamic filtering by fields such as Gender and Ethnicity.

<img width="536" height="707" alt="hospital snip" src="https://github.com/user-attachments/assets/1dbd5553-aa22-4784-a633-028ae0809497" />

# Insights from Analysis
Older age, emergency or referral admission, and certain diagnoses (e.g., GERD, Type 2 Diabetes) are associated with poorer outcomes and higher treatment costs. Insurance and hospital
location also significantly impact treatment expenses.

## Diagnosis and Outcome
-	Hypertension has the best outcome — all patients recovered or were referred; no deaths.
-	GERD and Type 2 Diabetes each recorded 2 deaths, the highest among diagnoses.
-	Anxiety and Asthma show a balanced distribution across recovered, referred, and deceased.

## Treatment Cost by Hospital Location
-	New York has a higher average treatment cost ($1,826.67) compared to Chicago ($1,663.33).
-	May indicate higher service costs or treatment intensity in New York.

## Admission Type and Outcome
-	Emergency admissions had the highest number of deaths (3) and recoveries (7).
-	Scheduled admissions had no deaths, suggesting better planning and lower risk.
-	Referral cases also had 3 deaths, possibly indicating late or complex cases.

## Insurance Type and Treatment Cost
-	Public insurance patients had the highest average cost ($1,995).
-	Private insurance incurred the lowest average cost ($1,590).
-	Suggests inefficiencies or more complex cases in the public system.

## Diagnosis and Treatment Cost
-	Anxiety is the least expensive to treat ($1,466.67), while GERD and Hypertension are the most expensive (both above $1,880).
-	Cost seems linked to severity and treatment complexity.

## Age Group and Outcome
-	Ages 53–62 and 63–73 recorded the highest death rates (2 each).
-	Ages 43–52 had the best outcomes, all recovered.
-	Suggests older age groups face higher risk of mortality or complications.

## Gender, Ethnicity, and Diagnosis Distribution
-	Females and males are equally represented (15 each).
-	White males have the highest count (6), suggesting demographic concentration.
-	Asian and Black females had the highest number of diagnoses among women.

# Conclusion and Recommendations

Conclusion

The analysis of hospital patient data reveals clear patterns in healthcare outcomes and costs. Diagnoses such as GERD and Type 2 Diabetes are associated with higher mortality 
and treatment costs, while Hypertension, though common, shows better outcomes. Emergency and referral admissions carry higher risks compared to scheduled visits, indicating the
value of early detection and planned care. Treatment costs also vary by hospital location and insurance type, with public insurance patients incurring higher average costs, 
possibly due to more complex cases or systemic inefficiencies. Furthermore, older age groups are more vulnerable to severe outcomes, emphasizing age-related healthcare risks.

Recommendations

1. Strengthen Preventive and Early Diagnosis Programs
-	Focus on early screening for GERD and Type 2 Diabetes, especially among high-risk age groups.
-	Encourage routine checkups to reduce emergency and referral admissions.
2. Improve Care Coordination for Referral Cases
-	Referral admissions had notable mortality—suggest better triaging and information sharing between facilities.
3. Enhance Management Protocols for High-Cost Conditions
-	Standardize care pathways for Hypertension and GERD to manage costs without compromising outcomes.
4. Address Disparities Across Insurance Types
-	Investigate why public insurance is linked to higher treatment costs and optimize service delivery for these patients.
5. Target High-Risk Age Groups with Tailored Interventions
-	Implement specialized care strategies for patients aged 53 and above, where mortality rates increase.
6. Audit Hospital Resource Allocation
-	Given New York’s higher treatment cost, conduct internal audits to assess efficiency and value delivery.

# Back to Top
[Table of Content](#Table-of-Content)











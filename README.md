# Patients Emergency Room Visit Report Dashboard

<p align="center">
 <br/>
<img src="https://scitechdaily.com/images/Emergency-Room-Hospital-777x517.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />



<h2>Overview</h2>
This healthcare analytics project aims to address important challenges and opportunities within the Emergency Room of our healthcare system through data analysis. We aim to understand and improve how efficiently we schedule appointments, increase patient satisfaction, allocate resources better based on changing demand, evaluate how administrative tasks affect patient experiences, assess the effectiveness of our referral system, and gain insights into the diverse healthcare needs across different groups of people. Additionally, there is a need for an interactive dashboard to visualize and communicate the findings effectively. Through careful data analysis and the development of an interactive dashboard, our goal is to make informed decisions and improve the quality of care for our patients.


<h2>Key Metrics</h2>

Here are the aspects I covered in my analysis:
- <b>Average Wait Time:</b> Identified typical wait times for patient appointments to assess the efficiency of our scheduling processes and identify areas for improvement.
- <b>Patient Satisfaction:</b> Helped with understanding the factors influencing patient satisfaction is crucial for enhancing the overall patient experience and improving the quality of care we provide. 
- <b>Total Patient Visits Monthly:</b> Analyzed the monthly patient visit volume helps us understand the demand for healthcare services over time, enabling better resource allocation and capacity planning.
- <b>Administrative vs. Non-Administrative Appointments:</b> Distinguished between different appointment types allows us to evaluate the impact of administrative processes on wait times and patient satisfaction.
- <b>Referrals and Walk-In Patients:</b> Examinined the balance between referred and walk-in patients provides insights into the referral system's effectiveness and its implications for the patient experience.
- <b>Patient Visits by Age Group and Race:</b> Analyzed patient visits by age group and race helps us understand the diversity of healthcare needs and preferences among different demographic segments, informing tailored healthcare strategies and interventions.


<h2>Data Dictionary</h2>

- <b>date:</b> The date and time of the patient's appointment.
- <b>patient_id:</b> Unique identifier for each patient. 
- <b>patient_gender:</b> Gender of the patient (M for male, F for female).
- <b>patient_gender:</b> Gender of the patient (M for male, F for female).
- <b>patient_age:</b> Age of the patient at the time of the appointment.
- <b>patient_sat_score:</b> Satisfaction score given by the patient for their experience. (null if not applicable)
- <b>patient_first_inital:</b> The first initial of the patient's first name. 
- <b>patient_last_name:</b> The last name of the patient. 
- <b>patient_race:</b> Race or ethnicity of the patient. 
- <b>patient_admin_flag:</b> A boolean value indicating whether the appointment involves administrative processes (TRUE or FALSE). 
- <b>patient_waittime:</b> The amount of time the patient waited before being seen by a healthcare provider. 
- <b>department_referral:</b> The department or specialty to which the patient was referred, if any. (None if not applicable) 


<h2>Dashboard Features </h2>
Below are the highlighted features of the dashboard, along with their respective visualizations and functionalities. I designed these features to address the business problems outlined for this project by providing comprehensive information and ensuring a user-friendly experience, facilitating insightful data-driven decision-making:


- <b>Summary of Patient Visits:</b> Provides a breakdown of total patient visits categorized by administrative assistance. It distinguishes between patients scheduled through administrative assistance and those not scheduled through administrative assistance.
- <b>Walk-in Patients vs. Referred Patients:</b> Displays the number of walk-in patients and patients referred to specific departments.
- <b>Average Satisfaction:</b> Shows the average satisfaction score given by patients, providing insights into the overall patient experience.
- <b>Service Not Rated:</b> Indicates the number of services not rated by patients, highlighting areas where feedback may be lacking.
- <b>Average Wait Time:</b> Presents the average wait time experienced by patients before being seen by a healthcare provider.
- <b>Yearly Trends:</b> Line graph displaying total patient visits over the years.
- <b>Week Type:</b> Bar chart illustrating total patient visits categorized by week type (e.g., weekdays vs. weekends).
- <b>Age Group Distribution:</b> Bar chart showing total patient visits by different age groups.
- <b>Monthly Trends:</b> Area line graph depicting total patient visits over the months.
- <b>Department Referral:</b> Bar chart indicating total patient visits by deferral categorized by department name.
- <b>Patient Gender: </b>Provides a breakdown of patient visits by gender, including male, female, and unknown categories.
- <b>Average Satisfaction and Wait Time Scores:</b> Displays average satisfaction and wait time scores per patient race and age group using a heatmap, allowing users to filter and analyze data based on patient race and age group.
- <b>Filter for Visit Moments (AM/PM):</b> Allows users to filter patient visits based on visit moments, distinguishing between visits occurring in the morning (AM) and afternoon/evening (PM).




<h2>Key Findings</h2>
<b>1. Booking Insights:</b>
Among 9,216 patient visits, precisely half, or 50.0%, were arranged with administrative aid, while 49.96% were self-arranged.

<b>2. Patient Pathways:</b>
A majority, 58.59%, are walk-in patients, showing a preference for immediate care, while 41.41% are referrals, indicating the influence of medical recommendations.

<b>3. Referral Preferences:</b>
Within referred patients, the top three referrals are General Practice (48.2%), Orthopedics (26%), and Physiotherapy (7.2%), showcasing the diverse medical needs addressed.

<b>4. Growth Spurt:</b>
Over the 2019-2020 period, we observe a notable 5.9% surge in total patient visits, reflecting increased healthcare demand and utilization.

<b>5. Patience Tested:</b>
The average wait time stands at 35.26, a pivotal metric shaping patient experience and service efficiency.

<b>6. Satisfaction Snapshot:</b>
Despite an average satisfaction score of 5.47, only 24.9% of patients provide feedback, underscoring the need for enhanced engagement.

<b>7. Weekday Rush:</b>
Weekdays witness a significant 72% higher patient turnout compared to weekends, highlighting the role of schedule convenience in patient access.

<b>8. Monthly Peaks and Valleys:</b>
August sees the highest patient footfall with 1,024 visits, comprising 11% of total visits, while February records the lowest at 431 visits, representing 4.7% of the total.

<b>9. Gender Distribution:</b>
Males account for 48.7% of visits, females for 51.1%, and a negligible 0.3% are of unknown gender, providing insights into patient demographics and healthcare utilization patterns.
 



<h2>Recommendations</h2>


Based on the data-driven insights revealed in our healthcare analysis, I propose the following recommendations:

<b>1. Booking Optimization:</b>
Implement streamlined booking processes to balance administrative and self-arranged appointments, ensuring efficient resource allocation and patient satisfaction.

<b>2. Patient Pathway Enhancement:</b>
Develop targeted referral pathways for high-demand specialties like General Practice, Orthopedics, and Physiotherapy to optimize patient flow and improve access to specialized care.

<b>3. Capacity Planning:</b>
Anticipate and accommodate the observed growth in patient visits by optimizing staffing levels, scheduling, and facility resources to prevent bottlenecks and maintain service quality.

<b>4. Wait Time Management:</b>
Introduce strategies such as appointment scheduling optimization, triage protocols, and staff training to minimize wait times and enhance the patient experience.

<b>5. Feedback Engagement:</b>
Implement proactive feedback collection mechanisms to encourage more patients to provide satisfaction ratings, allowing for continuous improvement initiatives and better understanding of patient needs.

<b>6. Strategic Scheduling:</b>
Adjust staffing and resource allocation based on weekday versus weekend patient visit patterns to ensure optimal resource utilization and service delivery alignment with patient demand.

<b>7. Seasonal Resource Allocation:</b>
Recognize and prepare for seasonal fluctuations in patient volume, such as the peak in August and the dip in February, by adjusting staffing levels and resource allocation accordingly.

<b>8. Gender-Specific Services:</b>
Tailor services and outreach efforts to address the specific healthcare needs and preferences of different gender groups, ensuring equitable access and personalized care delivery.


<h2>Screenshot of the Patients ER Visits Dashboard</h2>
 
<p align="center">
 <br/>
<img src="https://i.imgur.com/pOtbnx3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<h2>Tools Used</h2>

- <b>Power BI</b>

 

<h2>Environments Used </h2>

- <b>Power BI Desktop</b>
- <b>Windows 10</b> 

<b>Full View of Dashboard in Power BI [here](https://springboarddac-my.sharepoint.com/:u:/g/personal/priscilla_annor-gyamfi_springboarddac_onmicrosoft_com/Eda3sJ4Q-2ZFp2D7vu1oL0gBtadjS_TKoUMOe7Zq1ro8Ig?e=ncf9zj)
</b>

<br />
<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

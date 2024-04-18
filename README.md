# Patients Emergency Room Visit Report Dashboard

<p align="center">
 <br/>
<img src="https://i.imgur.com/hXvOdZM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />



<h2>Overview</h2>
<b>This healthcare analytics project aims to address important challenges and opportunities within the Emergency Room of our healthcare system through data analysis. We aim to understand and improve how efficiently we schedule appointments, increase patient satisfaction, allocate resources better based on changing demand, evaluate how administrative tasks affect patient experiences, assess the effectiveness of our referral system, and gain insights into the diverse healthcare needs across different groups of people. Additionally, there is a need for an interactive dashboard to visualize and communicate the findings effectively. Through careful data analysis and the development of an interactive dashboard, our goal is to make informed decisions and improve the quality of care for our patients.</b>


<h2>Key Metrics</h2>

<b>Here are the aspects I covered in my analysis:</b>
- <b>Average Wait Time: Identified typical wait times for patient appointments to assess the efficiency of our scheduling processes and identify areas for improvement.</b>
- <b>Patient Satisfaction: Helped with understanding the factors influencing patient satisfaction is crucial for enhancing the overall patient experience and improving the quality of care we provide. </b>
- <b>Total Patient Visits Monthly: Analyzed the monthly patient visit volume helps us understand the demand for healthcare services over time, enabling better resource allocation and capacity planning.</b>
- <b>Administrative vs. Non-Administrative Appointments: Distinguished between different appointment types allows us to evaluate the impact of administrative processes on wait times and patient satisfaction.</b>
- <b>Referrals and Walk-In Patients: Examinined the balance between referred and walk-in patients provides insights into the referral system's effectiveness and its implications for the patient experience.</b>
- <b>Patient Visits by Age Group and Race: Analyzed patient visits by age group and race helps us understand the diversity of healthcare needs and preferences among different demographic segments, informing tailored healthcare strategies and interventions.</b>


<h2>Data Dictionary</h2>

- <b>date: The date and time of the patient's appointment.</b>
- <b>patient_id: Unique identifier for each patient. </b>
- <b>patient_gender: Gender of the patient (M for male, F for female).</b>
- <b>patient_gender: Gender of the patient (M for male, F for female).</b>
- <b>patient_age: Age of the patient at the time of the appointment.</b>
- <b>patient_sat_score: Satisfaction score given by the patient for their experience. (null if not applicable)</b>
- <b>patient_first_inital: The first initial of the patient's first name. </b>
- <b>patient_last_name: The last name of the patient. </b>
- <b>patient_race: Race or ethnicity of the patient. </b>
- <b>patient_admin_flag: A boolean value indicating whether the appointment involves administrative processes (TRUE or FALSE). </b>
- <b>patient_waittime: The amount of time the patient waited before being seen by a healthcare provider. </b>
- <b>department_referral: The department or specialty to which the patient was referred, if any. (None if not applicable) </b>


<h2>Dashboard Features </h2>
<b>Below are the highlighted features of the dashboard, along with their respective visualizations and functionalities. I designed these features to address the business problems outlined for this project by providing comprehensive information and ensuring a user-friendly experience, facilitating insightful data-driven decision-making:

</b>

- <b>Summary of Patient Visits: Provides a breakdown of total patient visits categorized by administrative assistance. It distinguishes between patients scheduled through administrative assistance and those not scheduled through administrative assistance.</b>
- <b>Walk-in Patients vs. Referred Patients:</b> Displays the number of walk-in patients and patients referred to specific departments.
- <b>Average Satisfaction:</b> Shows the average satisfaction score given by patients, providing insights into the overall patient experience.
- <b>Service Not Rated:</b> Indicates the number of services not rated by patients, highlighting areas where feedback may be lacking.
- <b>Average Wait Time:</b> Presents the average wait time experienced by patients before being seen by a healthcare provider.
- <b>Yearly Trends:</b> Line graph displaying total patient visits over the years.
- <b>Week Type: Bar chart illustrating total patient visits categorized by week type (e.g., weekdays vs. weekends).</b>
- <b>Age Group Distribution: Bar chart showing total patient visits by different age groups.</b>
- <b>Monthly Trends: Area line graph depicting total patient visits over the months.</b>
- <b>Department Referral: Bar chart indicating total patient visits by deferral categorized by department name.</b>
- <b>Patient Gender: Provides a breakdown of patient visits by gender, including male, female, and unknown categories.</b>
- <b>Average Satisfaction and Wait Time Scores: Displays average satisfaction and wait time scores per patient race and age group using a heatmap, allowing users to filter and analyze data based on patient race and age group.</b>
- <b>Filter for Visit Moments (AM/PM): Allows users to filter patient visits based on visit moments, distinguishing between visits occurring in the morning (AM) and afternoon/evening (PM).</b>




<h2>Key Findings</h2>
<b>Booking Insights:</b>
Among 9,216 patient visits, precisely half, or 50.0%, were arranged with administrative aid, while 49.96% were self-arranged.

<b>Patient Pathways:</b>
A majority, 58.59%, are walk-in patients, showing a preference for immediate care, while 41.41% are referrals, indicating the influence of medical recommendations.

<b>Referral Preferences:</b>
Within referred patients, the top three referrals are General Practice (48.2%), Orthopedics (26%), and Physiotherapy (7.2%), showcasing the diverse medical needs addressed.

<b>Growth Spurt:</b>
Over the 2019-2020 period, we observe a notable 5.9% surge in total patient visits, reflecting increased healthcare demand and utilization.

<b>Patience Tested:</b>
The average wait time stands at 35.26, a pivotal metric shaping patient experience and service efficiency.

<b>Satisfaction Snapshot:</b>
Despite an average satisfaction score of 5.47, only 24.9% of patients provide feedback, underscoring the need for enhanced engagement.

<b>Weekday Rush:</b>
Weekdays witness a significant 72% higher patient turnout compared to weekends, highlighting the role of schedule convenience in patient access.

<b>Monthly Peaks and Valleys:</b>
August sees the highest patient footfall with 1,024 visits, comprising 11% of total visits, while February records the lowest at 431 visits, representing 4.7% of the total.

<b>Gender Distribution:</b>
Males account for 48.7% of visits, females for 51.1%, and a negligible 0.3% are of unknown gender, providing insights into patient demographics and healthcare utilization patterns.
 



<h2>Recommendations</h2>

- <b>Implement Strategies to Reduce Forced Outages:
Develop proactive maintenance plans to address equipment reliability issues and minimize forced outages.
Enhance monitoring systems to detect potential failures early and prevent unplanned downtime.
Invest in workforce training to ensure efficient response and resolution of forced outage incidents.</b>
- <b> Optimize Scheduled Outages:
Review and streamline scheduled maintenance processes to minimize downtime while ensuring effective performance and reliability.
Coordinate scheduled outages more effectively to reduce their duration and minimize their impact on energy loss.</b>
- <b>Prioritize Investments in Reliable Energy Providers and Facilities:
Conduct thorough assessments of energy providers and facilities to identify areas for improvement and prioritize investments in enhancing reliability.
Collaborate with unreliable providers to address underlying issues and improve outage management practices.</b>
- <b>Address Operational Issues Promptly:
Establish protocols for addressing operational issues that lead to real-time forced outages, focusing on rapid response and resolution to minimize disruptions.
Strengthen communication and collaboration among relevant stakeholders to ensure effective coordination in managing operational issues.</b>
- <b>Continuously Monitor and Evaluate Performance:
Establish performance metrics and key performance indicators (KPIs) to monitor the effectiveness of outage management initiatives.
Conduct regular performance reviews and evaluations to identify areas for improvement and make necessary adjustments to outage management strategies.</b>

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

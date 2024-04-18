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

- <b>Summary of Patient Visits: Provides a breakdown of total patient visits categorized by administrative assistance. It distinguishes between patients scheduled through administrative assistance and those not scheduled through administrative assistance.</b>
- <b>Walk-in Patients vs. Referred Patients: Displays the number of walk-in patients and patients referred to specific departments.</b>
- <b>Average Satisfaction: Shows the average satisfaction score given by patients, providing insights into the overall patient experience.</b>
- <b>Service Not Rated: Indicates the number of services not rated by patients, highlighting areas where feedback may be lacking.</b>
- <b>Average Wait Time: Presents the average wait time experienced by patients before being seen by a healthcare provider.</b>
- <b>Total Patients Visits by Various Categories:
  
Yearly Trends: Line graph displaying total patient visits over the years.
Week Type: Bar chart illustrating total patient visits categorized by week type (e.g., weekdays vs. weekends).
Age Group Distribution: Bar chart showing total patient visits by different age groups.
Monthly Trends: Area line graph depicting total patient visits over the months.
Department Referral: Bar chart indicating total patient visits by deferral categorized by department name.
Patient Gender: Provides a breakdown of patient visits by gender, including male, female, and unknown categories.</b>
- <b>Average Satisfaction and Wait Time Scores: Displays average satisfaction and wait time scores per patient race and age group using a heatmap, allowing users to filter and analyze data based on patient race and age group.</b>
- <b>Filter for Visit Moments (AM/PM): Allows users to filter patient visits based on visit moments, distinguishing between visits occurring in the morning (AM) and afternoon/evening (PM).</b>


<h2>Key Metrics and Visualizations </h2>

- <b>KPI's: I visualized the calculated total Revenue, Number of Units, Total Units and Total Customers from all stores and their respective location for the given period, 2016 through to 2018.</b>
- <b>Profitability at a Glance: I ensured an easy way of navigating clear graphs of revenues by year, month, store, top customers, sales rep, category name and state. </b>
- <b>Geographic Mapping: I visualized the revenue coverage geographically using maps to depict regional disparities .</b>

















<h2>Key Findings</h2>

- <b>The year 2017 stands out with the highest revenue, totaling 3.85 million dollars, which accounts for 40.79% of the total revenue generated between 2016 and 2018.</b>
- <b>April emerges as the month with the highest revenue, reaching 1.35 million dollars, while December records the lowest revenue at 0.52 million dollars. This pattern could be attributed to increased bike purchases during the spring and summer seasons.</b>
- <b>New York, NY leads in revenue, generating 5.83 million dollars, representing 68% of the total revenue, followed by California, CA. Conversely, Texas, TX records the lowest revenue. The high population density in New York could contribute to its dominance in sales.</b>
- <b>Baldwin Bikes store tops the revenue chart with 67.91%, followed by Santa Cruz Bikes store at 20.87%, and Rowlett Bikes store with 11.22%. The location of Baldwin Bikes in New York likely contributes to its higher revenue.</b>
- <b>Among the bike categories, Mountain bikes dominate sales, constituting 35.33% of total revenue, while Children bikes contribute the least at 3.82%.</b>
- <b>Pamelia Newman emerges as the top customer, with a total revenue of $37.80K.</b>
- <b>Marcelene Boyer stands out as the top Sales Rep, generating a total revenue of $2.94 million.</b>



 



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

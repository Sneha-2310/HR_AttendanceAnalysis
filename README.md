<h2>Employee Attendance Data Analysis for the HR </h2>
<hr>
<h3>Table of Contents</h3>
<ul><li>Project Aim</li>
<li>Data Sources</li>
<li>Recommendations</li></ul>
<hr>
<h3>Project Aim </h3>
Determine the working preferences of your staff, since work from home, hybrid modes, and other options are accessible. <br>
The quantity of sick leaves must be examined since they may be a source of worry for covid.<br> 

<h3>Data Sources:</h3>
The primary dataset used for this analysis is the "Attendance Sheet.xlsx" file, containing detailed information about the attendance of the staff of xyz company,<br> 
The data contains information about work leave, half work leave, workfrom home, sick leave and presence at office for each employee for the month of april, may and june.<br><br>
<h3>Tools</h3>
<ul><li>Excel - Data Cleaning</li>
<li>SQL Server - Data Analysis</li>
<li>PowerBI - Creating reports</li>
<li>Data Cleaning/Preparation</li>
</ul>
In the initial data preparation phase, we performed the following tasks:<br>
Data loading and inspection.<br>
Handling missing values.<br>
Data cleaning and formatting.<br>
<br>
We then prepared the 'hrData.csv file'
<br><br>
Data Analysis<br><br>
<u><b>SQL CODE:</b></u> <br>
<br>
<img width="409" alt="image" src="https://github.com/Sneha-2310/HR_AttendanceAnalysis/assets/98509803/c9e0b153-c937-4f52-88c5-6dd1535f4538">
<br>

This gives us the total present percentage for each employee seprately in decsending order 
<br><br>
<img width="409" alt="image" src="https://github.com/Sneha-2310/HR_AttendanceAnalysis/assets/98509803/63e10f99-e4bf-4812-8169-b7983db5c503">
<br>
This gives us the  total work from home percentage for each employee seprately.
<br><br>
<img width="409" alt="image" src="https://github.com/Sneha-2310/HR_AttendanceAnalysis/assets/98509803/5a265e64-4d42-47bc-b74a-8ea49225c7c7">
<br>
This gives us the  Sick leave percentage for each employee seprately.
<br><br>
<img width="600" alt="image" src="https://github.com/Sneha-2310/HR_AttendanceAnalysis/assets/98509803/f5cc59dc-8b77-4962-a8bf-ffeb97ce9e5f">
<br><br>
Above is data extracted for each weekday seperately<br><br>
<img width="600" alt="image" src="https://github.com/Sneha-2310/HR_AttendanceAnalysis/assets/98509803/5a7394a2-2bfd-42bc-9637-564568adb450">
<br><br>
Above is the total data for each date
<br>
Next, we made a dashboard of this data as shown below
<h3><u>PowerBI Dashboard</u></h3>
<br>
<img width="700" alt="image" src="https://github.com/Sneha-2310/HR_AttendanceAnalysis/assets/98509803/eb475150-f25b-4130-b4b9-caccc1ae8ae8">
<br><br>
<img width="600" alt="image" src="https://github.com/Sneha-2310/HR_AttendanceAnalysis/assets/98509803/55b627c2-d68e-4413-a594-0cc9a5daec7a">
<br><br>
<img width="468" alt="image" src="https://github.com/Sneha-2310/HR_AttendanceAnalysis/assets/98509803/fa652ae3-62a1-439d-a810-00ca052a4ff7">
<br><br>
The dashboard provides us a dynamic insight to the data of employee seprately.<br>
We can see the trend of employee attendance based on weekday and over the month.
<br><br>
<h3><u>Recommendations :</u></h3>
The trend shows that there has been an increase in the number of work from home employees. We can make arrangements for a hybrid mode.<br>
This can improve space utilisation and reduce infrastructure costs.<br>
Also there has been a sudden increase in the number of sick leaves in the month of May.<br>
We need to take particular sanitization and isolation precautions, as well as administer flu vaccines, to tackle the situation.<br>





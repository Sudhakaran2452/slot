# Ex03 Time Table
## Date:13.03.2024

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM

```
<html>
<head>
     <title>Slot Timetable</title>
</head>
<body>
<center>
<img src="/static/logo.png" height="100" width"550">
</center>
<br>
     <table align="center" width="550" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
     <caption><b>Time Table - SUDHAKARAN S (22002452)</b></caption>
<tr align="center">
	<th bgcolor="yellow">Day/Time</th>
	<th bgcolor="yellow">Monday</th>
	<th bgcolor="yellow">Tuesday</th>
	<th bgcolor="yellow">Wednesday</th>
	<th bgcolor="yellow">Thursday</th>
 	<th bgcolor="yellow">Friday</th>
</tr>
<tr align="center">
	<th bgcolor="yellow">8-10</th>
	<td>ML</td>
	<td>DPSD</td>
	<td>FWAD</td>
	<td colspan="2">Free Slot</td>
</tr>
<tr align="center">
	<th bgcolor="yellow">10-12</th>
	<td>Free slot</td>
	<td>FWAD</td>
	<td>ML</td>
	<td>Free Slot</td>
	<td>DPSD</td>
</tr>
<tr>
	<th bgcolor="yellow">12-1</th>
	<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
	<th bgcolor="yellow">1-3</th>
	<td>FWAD</td>
	<td>CNS</td>
	<td>DBMS</td>
	<td>PQT</td>
	<td>PQT</td>
</tr>
<tr align="center">
	<th bgcolor="yellow">3-5</th>
	<td colspan="3">Free slot</td>
	<td>DPSD</td>
    <td>Free slot</td>
</tr>
</table>
</br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI410</td>
<td>Introduction To Machine Learning</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI414</td>
<td>Fundamentals Of Web Application Development</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19CS404</td>
<td>Database Management System and Its Application</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19CS412</td>
<td>Cryptography and Queuning Theory </td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19EC303</td>
<td>Digital Principles and System Design</td>
</tr>
<tr>
    <td align="center">6.</td>
    <td align="center">19MA218</td>
    <td>Probablity and Queuening Theory</td>
    </tr>
</table>
</body>
</html>

```
## OUTPUT
![alt text](<Screenshot 2024-03-18 141534.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

# Ex02 Time Table
## Date:

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
<title>slot Timetable</title>    
</head>
<body>
<center>
<img src="c:\Users\admin\OneDrive\Pictures\logo.png" height="100" width="500">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="10" border="7" bgcolor="white">
<caption><b>SLOT TIME TABLE -DEEPIKA V(212224240030)</b></caption>
<tr align="center">
<th bgcolor="yellow">Day/Time</th>
<th bgcolor="yellow">Monday</th>
<th bgcolor="yellow">Tuesday</th>
<th bgcolor="yellow">Wednesday</th>
<th bgcolor="yellow">Thursday</th>
<th bgcolor="yellow">Friday</th>
<th bgcolor="yellow">Saturday</th>
</tr>

<tr align="center">
<th bgcolor="yellow">8-10</th>
<td>Fundamentals of Web Development</td>
<td>Fundamentals of Web Development</td>
<td>DataBase Management System</td>
<td>-</td>
<td>DataBase Management System</td>
<td>-</td>

</tr>

<tr align="center">
<th bgcolor="yellow">10-12</th>
<td>-</td>
<td>Python Programming</td>
<td>Fundamentals of Web Development</td>
<td>DataBase Management System</td>
<td>Fundamentals of Web Development</td>
<td>-</td>
</tr>

<tr>
<th bgcolor="yellow">12-1</th>
<td colspan="6" align="center">L U N C H</td>
</tr>

<tr align="center">
<th bgcolor="yellow">1-3</th>
<td>DataBase Management System</td>
<td>-</td>
<td>Mentor Meet</td>
<td>Fundamentals of Web Development</td> 
<td>Python Programming</td>
<td>DataBase Management System</td>

</tr>

<tr align="center">
<th bgcolor="yellow">3-5</th>
<td>-</td>
<td>-</td>
<td>Python Programming</td>
<td>Python Programming</td>
<td>-</td>
<td>Python Programming</td>
</tr>

</table>
<br>
<table align="center" cellspacing="3" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>Fundamentals of Web Appilication Development(WEB)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19CS404</td>
<td>DataBase Management System</td>
</tr>

<tr>
<td align="center">5.</td>
<td align="center">19AI301</td>
<td>Python Programming(PYTHON)</td>
</tr>

</table>
</body>
</html>
```
## OUTPUT
<img width="1920" height="1200" alt="outputt" src="https://github.com/user-attachments/assets/a7d6fa7d-aa47-4c23-bbf4-5e3561050765" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

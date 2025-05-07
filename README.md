# Ex03 Time Table
## Date:28/04/2024

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
TIME.HTML
```
<html>
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="C:\Users\admin\slot_timetable\logo.png" height="100" width="500">
</center>
<br>
<table align="center" width="500" cellspacing="3" cellpadding="2" border="2" bgcolor="yellow">
<caption><b>SLOT TIME TABLE - AJAY KUMAR(212223047001)</b></caption>
<tr align="center">
<th bgcolor="cyan">Day/Time</th>
<th bgcolor="cyan">Monday</th>
<th bgcolor="cyan">Tuesday</th>
<th bgcolor="cyan">Wednesday</th>
<th bgcolor="cyan">Thursday</th>
<th bgcolor="cyan">Friday</th>
<th bgcolor="cyan">Saturday</th>
</tr>
<tr align="center">
<th bgcolor="pink">8-10</th>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>INTRO TO ML</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="pink">10-12</th>
<td>OPS USING JAVA</td>
<td>FREE SLOT</td>
<td>FWAD</td>
<td>FREE SLOT</td>
<td>OPS USING JAVA</td>
<td>THEORY OF COMPUTATION</td>
</tr>
<tr>
<th bgcolor="pink">12-1</th>
<td colspan="6" align="center">L U N C H    B R E A K </td>
</tr>
<tr align="center">
<th bgcolor="pink">1-3</th>
<td>THEORY OF COMPUTATION</td>
<td>FREE SLOT</td>
<td>MENTOR MEET</td>
<td>CAREER DEVELOPMENT</td>
<td>FREE SLOT</td>
<td>INTRO TO ML</td>
</tr>
<tr align="center">
<th bgcolor="pink">3-5</th>
<td>DATA STRUCTURES</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FWAD</td>
<td>DATA STRUCTURES</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="2" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center"><b><font color = red>19AI414</font></b></td>
<td><b><font color = red>Fundamentals of Web Application Development (FWAD)</font></b></td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI307</td>
<td>OPS USING JAVA</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19AI410</td>
<td>INTRO TO ML</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19EY708</td>
<td>CAREER DEVELOPMENT</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19CS407</td>
<td>THEORY OF COMPUTATION</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19AI408</td>
<td>DATA STRUCTURES</td>
</tr>
</table>
</body>
</html>
```
## OUTPUT
![Screenshot 2025-05-07 035503](https://github.com/user-attachments/assets/cf6c1547-ef43-4665-b009-efa76ee8e4af)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

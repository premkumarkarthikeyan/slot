# Experiment_Time_Table

## AIM
To Write a html webpage page to display your timetable.

# ALGORITHM
### STEP 1
create a simple table using table tag

### STEP 2
Add header row using th tag

### STEP 3
Add your timetable

### STEP 4
Execute the program

# CODE
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="/static/images/logo.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" 
bgcolor="cyan">
<caption><b>SLOT TIME TABLE - PREMKUMAR K (22004793)</b></caption>
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
<td>CP</td>
<td>FREE SLOT</td>
<td>PHY</td>
<td>MAT</td>
<td>CP</td>
</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>
<td>FREE SLOT</td>
<td> ENG </td>
<td>FWAD</td>
<td>FWAD</td>
<td>MAT</td>
</tr>
<tr>
<th bgcolor="yellow">12-1</th>
<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th>
<td> FREE SLOT </td>
<td>DE</td>
<td>DE</td>
<td>ENG</td>
<td>SS</td>
</tr>
<tr align="center">
<th bgcolor="yellow">3-5</th>
<td>MAT</td>
<td colspan="2"> FREE SLOT </td>
<td>PHY</td>
<td>FWAD</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>Fundamentals of Web Application Development (FWAD)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19EN101</td>
<td>Communicative English (ENG)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19PH214</td>
<td>Physics for Quantum Computing (PHY)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19AI304</td>
<td>Fundamentals of C programming (CP)</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19MA211</td>
<td>Statistics and Numerical Methods (MAT)</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19EY701</td>
<td>Soft Skills (SS)</td>
</tr>
<tr>
<td align="center">7.</td>
<td align="center">19EE404</td>
<td>Digital Electronics(DE)</td>
</tr>
</table>
</body>
</html>
```

# OUPUT
![OUTPUT](http://premkumark.student.saveetha.in:8000/static/images/out (2).png?raw=true)

# HTML VALIDATOR
![HTML VALIDATOR](http://premkumark.student.saveetha.in:8000/static/images/valid.png?raw=true)

# RESULT
The program for creating slot time table is completed successfully
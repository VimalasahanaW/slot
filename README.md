# Ex03 Time Table
## Date:15-11-2023

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
<title>TIME TABLE - ODD JUNIOR</title>
<body>
<center>
<img src ="/static/logo.png" height="100" width="540">
</center>
<table border="6" align="center" cellspacing="5">
<caption><b>TIME TABLE - ODD JUNIOR</b></caption>
<tr>
<th bgcolor="Thistle">Days/Time</th>
<th bgcolor="Thistle">8.00AM-10.00AM</th>
<th bgcolor="Thistle">10.00AM-12.00PM</th>
<th bgcolor="Thistle">12.00AM-1.00PM</th>
<th bgcolor="Thistle">1.00PM-3.00PM</th>
<th bgcolor="Thistle">3.00PM-5.00PM</th>
</tr>
<tr>
<th bgcolor="Thistle">MONDAY</th>
<td bgcolor="Lavender" align="center">C-programming</td>
<td bgcolor="Lavender" align="center">Soft skills</td>
<td bgcolor="Lavender" align="center">LUNCH</th>
<td bgcolor="Lavender">Principles of Chemistry</td>
<td bgcolor="Lavender" align="center">Free Slot </td>
</tr>
<tr>
<th bgcolor="Thistle">TUESDAY</th>
<td bgcolor="Lavender">Communicative English</td>
<td bgcolor="Lavender" align="center">C-programming</td>
<td bgcolor="Lavender" align="center">LUNCH</td>
<td bgcolor="Lavender" align="center">EDM</td>
<td bgcolor="Lavender" align="center">Free Slot</td>
</tr>
<tr>
<th bgcolor="Thistle">WEDNESDAY</th>
<td bgcolor="Lavender">Fundamentals of Web</td>
<td bgcolor="Lavender" align="center">Free Slot</td>
<td bgcolor="Lavender" align="center">LUNCH</td>
<td bgcolor="Lavender">Principles of Chemistry</td>
<td bgcolor="Lavender">Calculus and Matrix</td>
</tr>
<tr>
<th bgcolor="Thistle">THURSDAY</th>
<td bgcolor="Lavender" align="center">EDM</td>
<td bgcolor="Lavender">Fundamentals of Web</td>
<td bgcolor="Lavender" align="center">LUNCH</td>
<td bgcolor="Lavender">Communicative English</td>
<td bgcolor="Lavender" align="center">Free Slot</td>
</tr>
<tr>
<th bgcolor="Thistle">FRIDAY</th>
<td bgcolor="Lavender" align="center">Free Slot</td>
<td bgcolor="Lavender" align="center">Free Slot</td>
<td bgcolor="Lavender" align="center">LUNCH</td>
<td bgcolor="Lavender">Fundamentals of Web</td>
<td bgcolor="Lavender">Calculus and Matrix</td>
</tr>
</table>
<table align="center" cellspacing="3" cellpadding="15" border="2">
<tr align="center">
<th bgcolor="LightGrey">S.NO</th>
<th bgcolor="LightGrey">SUBJECT CODE</th>
<th bgcolor="LightGrey">SUBJECT NAME</th>
</tr>
<tr>
<th bgcolor="LightGrey">1</th>
<td align="center" bgcolor="WhiteSmoke">19MAI414</td>
<td bgcolor="WhiteSmoke">Fundamentals of Web Applications Development</td>
</tr>
<tr>
<th bgcolor="LightGrey">2</th>
<td align="center" bgcolor="WhiteSmoke">19CY205</td>
<td bgcolor="WhiteSmoke">Principles of Chemistry in Engineering</td>
</tr>
<tr>
<th bgcolor="LightGrey">3</th>
<td align="center" bgcolor="WhiteSmoke">19MA201</td>
<td bgcolor="WhiteSmoke">Calculus and Matrix Algebra</td>
</tr>
<tr>
<th bgcolor="LightGrey">4</th>
<td align="center" bgcolor="WhiteSmoke">19AI302</td>
<td  bgcolor="WhiteSmoke">Engineering Design and Modelling</td>
</tr>
<tr>
<th bgcolor="LightGrey">5</th>
<td align="center" bgcolor="WhiteSmoke">19EN101</td>
<td bgcolor="WhiteSmoke">Communicative English</td>
</tr>
<tr>
<th bgcolor="LightGrey">6</th>
<td align="center" bgcolor="WhiteSmoke">19AI304</td>
<td bgcolor="WhiteSmoke">Fundamentals of C Programming</td>
</tr>
<tr>
<th bgcolor="LightGrey">7</th>
<td align="center" bgcolor="WhiteSmoke">19EY701</td>
<td bgcolor="WhiteSmoke">Soft Skills</td>
</tr>
</body>
</html>
```

## OUTPUT
![Alt text](<Screenshot 2023-11-15 111158.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

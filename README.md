# Ex03 Time Table

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

## CODE

<!DOCTYPE html>
<html lang="en">
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="c:\Users\Danush S\Downloads\logo.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
<caption><b>SLOT TIME TABLE - DANUSH s(212221040033)</b></caption>
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
<td colspan="3">FREE SLOT</td>
<td>PHY</td>
<td>CHE</td>
</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>
<td>GER</td>
<td> FREE SLOT </td>
<td>FWAD</td>
<td>FWAD</td>
<td>PHY</td>
</tr>
<tr>
<th bgcolor="yellow">12-1</th>
<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th>
<td colspan="2"> FREE SLOT </td>
<td>MAT</td>
<td>MAT</td>
<td>SS</td>
</tr>
<tr align="center">
<th bgcolor="yellow">3-5</th>
<td colspan="2"> FREE SLOT </td>
<td>GER</td>
<td>CHE</td>
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
<td align="center">19EN612</td>
<td>German Basic (GER)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19PH206</td>
<td>Physics for Information Technology (PHY)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19CY205</td>
<td>Principles of Chemistry in Engineering (CHE)</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19MA201</td>
    <td>Calculus and Matrix Algebra (MAT)v    
    </td>
    </tr>
  
## OUTPUT
![Screenshot 2023-10-07 093850](https://github.com/danush564/slot/assets/98585166/a3f2caa3-7665-4545-8c46-843fb9c233c6)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

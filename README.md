# Ex02 Time Table
# Date:
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
<!doctype html>
<html>
<head>
<title>	slot time table </title>
<style>
table,th,td
{ 
border: 2px double;
text-align:center
}
#clr
{
background-color:yellow
}
#time{
text-align:center
}

</style>
</head>
<body align="center">
<img src="logo.png" height=100 width=450><br>
&nbsp <b> SLOT TIME TABLE - NIVEDHA K (25013942)</b>
<table align="center">
<thead>
<tr style="background-color:yellow">
<th>Day/Time</th>
<th>Monday</th>
<th>Tuesday</th>
<th>Wednesday</th>
<th>Thursday</th>
<th>Friday</th>
<th>Saturday</th>
</tr>
</thead>

<tbody style="background-color:aqua">

<tr>
<td id="clr">8-10</td>
<td colspan=2>PUBLIC SPEAKING</td>
<td>FWAD</td>
<td>FREE SLOT</td>
<td>PUBLIC SPEAKING</td>
<td>FREE SLOT</td>
</tr>

<tr>
<td id="clr">10-12</td>
<td>FREE SLOT</td>
<td>FWAD</td>
<td>PUBLIC SPEAKING</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>C PROGRAMMING</td>
</tr>

<tr>
<td id="clr">12-1</td>
<td colspan=5>LUNCH</td>
</tr>

<tr>
<td id="clr">1-3</td>
<td colspan=2>C PROGRAMMING</td>
<td>MENTOR MEETT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
</tr>

<tr>
<td id="clr">3-5</td>
<td colspan=3>FWAD</td>
<td>C PROGRAMMING</td>
<td>FREE SLOT</td>
<td>C PROGRAMMING</td>
</tr>


</tbody>
</table>
<br>
<br>
<br>
<br>
<table align="center">
<tr>
<th> S.No </th>
<th> Subject Code </th>
<th style="text-align:center"> Subject Name</th>

</tr>
<tr>
<td style="text-align:center"> 1. </td>
<td style="text-align:center"> 19AI414</td>
<td style="text-align:left"> Fundamentals of Web Application Development(FWAD)</td>
</tr>
<tr>
<td style="text-align:center"> 2. </td>
<td style="text-align:center"> 19EN105</td>
<td style="text-align:left"> PUBLIC SPEAKING</td>
</tr>
<tr>
<td style="text-align:center"> 3. </td>
<td style="text-align:center"> 19AI304</td>
<td style="text-align:left"> Physics for Information Technology(PHY)</td>
</tr>

</body>

</html>

# OUTPUT 
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/f7c4a618-1384-4e2f-a403-e7c329c6e525" />


# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

# Ex03 Time Table
## Date:24-10-2025

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
<!DOCTYPE html>

<head>
    <title>Slot Timetable</title>
</head>

<body>
    <div align="center">
        <img src="/static/logo.png" width="543.49">
    </div>
    <br>
    <center><b>SLOT TIME TABLE - SOMALARAJU ROHINI (212224240156)</b></center>
    <table border="4" bordercolor="gray" align="center" bgcolor="cyan" cellpadding="5" width="543.48">
        <tr bgcolor="yellow">

            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
            </b>
        </tr>
        <tr>
            <td bgcolor="yellow" align="center"><b>8-10</b></td>
            <td colspan="6" bgcolor="cyan" align="center">FREE SLOT</td>
        </tr>
        <tr>
            <td bgcolor="yellow" align="center"><b>10-12</b></td>
            <td bgcolor="cyan" align="center">EVS</td>
            <td bgcolor="cyan" align="center">PHY</td>
            <td bgcolor="cyan" align="center">C</td>
            <td bgcolor="cyan" align="center">FWAD</td>
            <td bgcolor="cyan" align="center">CN</td>
            <td bgcolor="cyan" align="center">HVPE</td>
        </tr>
        <tr>
            <td bgcolor="yellow" align="center"><b>12-1</b></td>
            <td colspan="5" align="center" bgcolor="cyan">L U N C H</td>
        </tr>
        <tr>
            <td bgcolor="yellow" align="center"><b>1-3</b></td>
            <td bgcolor="cyan" align="center">CN</td>
            <td bgcolor="cyan" align="center">FWAD</td>
            <td bgcolor="cyan" align="center">MENTOR MEET</td>
            <td bgcolor="cyan" align="center">PHY</td>
            <td bgcolor="cyan" align="center">RA</td>
            <td bgcolor="cyan" align="center">C</td>
        </tr>
        <tr>
            <td bgcolor="yellow" align="center"><b>3-5</b></td>
            <td bgcolor="cyan" align="center">CHEM</td>
            <td colspan="2" align="center" bgcolor="cyan">FREE SLOT</td>
            <td bgcolor="cyan" align="center">CHEM</td>
            <td colspan="2" align="center" bgcolor="cyan">FREE SLOT</td>
        </tr>

    </table>
    <br>
    <table border="1" align="center" cellpadding="5">
        <tr>
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
            <td align="center">19CY801</td>
            <td>Environmental sciences and sustainability</td>
        </tr>
        <tr>
            <td align="center">3.</td>
            <td align="center">19CS406</td>
            <td>Computer networkS</td>
        </tr>
        <tr>
            <td align="center">4.</td>
            <td align="center">19CY205</td>
            <td>Principles of Chemistry in Engineering (CHE) </td>
        </tr>
        <tr>
            <td align="center">5.</td>
            <td align="center">19EY709</td>
            <td>Reasoning Ability</td>
        </tr>
        <tr>
            <td align="center">6.</td>
            <td align="center">19HS801</td>
            <td>Human values and professional ethics</td>
        </tr>
        <tr>
            <td align="center">7.</td>
            <td align="center">19PH814</td>
            <td>Physics for quantum computing</td>
        </tr>
        <tr>
            <td align="center">8.</td>
            <td align="center">ECA-M</td>
            <td>Mentor meet</td>
        </tr>

    </table>


</body>
```

## OUTPUT

![alt text](<Screenshot 2025-10-24 222846.png>)




## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

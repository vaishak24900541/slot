# Ex03 Time Table
## Date:17.04.2025

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
        <img src="/static/logo.png" height="100" width="540">
    </center>
    <br>
    <table align="center" width="540" cellspacing="4" cellpadding="5" border="5" bgcolor="cyan">
    <caption><b>TIME TABLE - Vaishak.M (212224040355)</b></caption>
    <tr align="center">
        <th bgcolor="white">Day/Time</th>
        <th bgcolor="green">Monday</th>
        <th bgcolor="green">Tuesday</th>
        <th bgcolor="green">Wednesday</th>
        <th bgcolor="green">Thursday</th>
        <th bgcolor="green">Friday</th>
        <th bgcolor="green">Saturday</th>
    </tr>
    <tr align="center">
        <th bgcolor="green">8-10</th>
        <td>Free Slot</td>
        <td>Free Slot</td>
        <td>Career Development Skills</td>
        <td>Introduction to Machine learning</td>
        <td>Free Slot</td>
        <td>Blockchain for Business</td>
    </tr>
    <tr align="center">
        <th bgcolor="green">10-12</th>
        <td>Blockchain for Business</td>
        <td>Python Programming</td>
        <td>Digital Electronics</td>
        <td>Fundamentals of Web Application Development</td>
        <td>Free Slot</td>
        <td>Principles of Chemistry in Engineering</td>
    </tr>
    <tr align="center">
        <th bgcolor="red">12-1</th>
        <td colspan="6" style="text-align:center;">Lunch Hour</td>
    </tr>
    <tr align="center">
        <th bgcolor="green">1-3</th>
        <td>Digital Electronics</td>
        <td>Fundamentals of Web Application Development</td>
        <td>Mentor meet</td>
        <td>Principles of Chemistry in Engineering</td>
        <td>Python Programming</td>
        <td>Introduction to Machine learning</td>
    </tr>
    <br>
    </table>

    <br>

    <table align="center" cellspacing="2" cellpadding="7" border="2" style="margin-top:20;">
    <tr align="center">
        <th>S.No.</th>
        <th>Subject Code</th>
        <th>Subject Name</th>
    </tr>

    <tr>
        <td align="center">1.</td>
        <td align="center">19AI414</td>
        <td align="center">Fundamentals of web development(FWAD)</td>
    </tr>

    <tr>
        <td align="center">2.</td>
        <td align="center">19AI301</td>
        <td align="center">Python Programming(P PROGRAM)</td>
    </tr>

    <tr>
        <td align="center">3.</td>
        <td align="center">19CY205</td>
        <td align="center">Principles of Chemistry in Engineering(CHEM)</td>
    </tr>

    <tr>
        <td align="center">4.</td>
        <td align="center">19AI410</td>
        <td align="center">Introduction to Machine learning(ML)</td>
    </tr>
    <tr>
        <td align="center">5.</td>
        <td align="center">19AI547</td>
        <td align="center">Blockchain for Business(BCB)</td>
    </tr>
    <tr>
        <td align="center">6.</td>
        <td align="center">19EE404</td>
        <td align="center">Digital Electronics(DE)</td>
    </tr>
    <tr>
        <td align="center">7.</td>
        <td align="center">19EY708</td>
        <td align="center">Career Development Skills(CDS)</td>
    </tr>

    </table>
</body>
</html>


    
```

## OUTPUT
![alt text](<Screenshot 2025-04-17 212059.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

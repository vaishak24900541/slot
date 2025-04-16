# Ex03 Time Table
## Date:16.04.2025

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
        <th bgcolor="red">Day/Time</th>
        <th bgcolor="yellow">Monday</th>
        <th bgcolor="yellow">Tuesday</th>
        <th bgcolor="yellow">Wednesday</th>
        <th bgcolor="yellow">Thursday</th>
        <th bgcolor="yellow">Friday</th>
    </tr>
    <tr align="center">
        <th bgcolor="yellow">8-10</th>
        <td>Web development</td>
        <td>Free Slot</td>
        <td>Communicative English</td>
        <td>Introduction to Machine Learning</td>
        <td>Blockchain for Business</td>
    </tr>
    <tr align="center">
        <th bgcolor="yellow">10-12</th>
        <td>Blockchain for Business</td>
        <td>Python Programming</td>
        <td>Digital Electronics</td>
        <td>Web development</td>
        <td>Free Slot</td>
    </tr>
    <tr align="center">
        <th bgcolor="yellow">12-1</th>
        <td colspan="6" style="text-align:center;">Lunch Hour</td>
    </tr>
    <tr align="center">
        <th bgcolor="yellow">1-3</th>
        <td>Digital Electronics</td>
        <td>Web development</td>
        <td>Mentor meet</td>
        <td>Principles of Chemistry</td>
        <td>Python Programming</td>
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
        <td align="center">Fundamentals of web development</td>
    </tr>

    <tr>
        <td align="center">2.</td>
        <td align="center">19AI301</td>
        <td align="center">Python Programming</td>
    </tr>

    <tr>
        <td align="center">3.</td>
        <td align="center">19AI547</td>
        <td align="center">Blockchain for Business</td>
    </tr>

    <tr>
        <td align="center">4.</td>
        <td align="center">19AI410</td>
        <td align="center">Introduction to Machine learning</td>
    </tr>
    <tr>
        <td align="center">5.</td>
        <td align="center">19EN101</td>
        <td align="center">Communicative English</td>
    </tr>
    <tr>
        <td align="center">6.</td>
        <td align="center">19EE404</td>
        <td align="center">Digital Electronics</td>
    </tr>

    <tr>
        <td align="center">7.</td>
        <td align="center">19CY205</td>
        <td align="center">Principles of Chemistry in Engineering</td>
    </tr>
    <tr>
        <td align="center">8.</td>
        <td align="center">SH7801</td>
        <td align="center">Human values and Professional ethics</td>
    </tr>

    </table>
</body>
</html>

```

## OUTPUT
![alt text](<Screenshot 2025-04-16 230148.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

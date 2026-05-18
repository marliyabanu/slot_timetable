# Ex02 Time Table
## Date:18/5/26

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
<html>
<head>
    <title>Slot Time Table - YOUR NAME</title>
</head>
<body>
    <IMG SRC="/static/logo.png"HEIGHT="150"WIDTH="500"BORDER=6>
    <h2>Saveetha Engineering College</h2>
    <h3>SLOT TIME TABLE - B MARLIYA BANU</h3>

    <table border="1">
        <tr BGCOLOR="YELLOW">
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">8-10</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>OS</td>
            <td>OS</td>
            <td>OS</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">10-12</td>
            <td>OS</td>
            <td>WEB</td>
            <td>WEB</td>
            <td>FREE SLOT</td>
            <td>WEB</td>
        </tr>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">12-1</td>
            <td COLSPAN=5 ALIGN="CENTER">LUNCH</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">1-3</td>
            <td>FREE SLOT</td>
            <td>WEB</td>
            <td>MENTOR MEET</td>
            <td>C-PROGROM</td>
            <td>C-PROGRAM</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">3-5</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>C-PROGRAM</td>
            <td>C-PROGRAM</td>
            <td>FREE SLOT</td>
        </tr>
    </table>

    <h3>Subjects</h3>
    <table border="1">
        <tr>
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19CS405</td>
            <td>Operating System</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19AI304</td>
            <td>Fundamentals of C Programming</td>
        </tr>
    </table>
</body>
</html>
```

## OUTPUT
![Output](static/Output.png)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

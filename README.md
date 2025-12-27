
# Ex03 Time Table
## Date:13.10.2025

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <html>
<head>
    <title>Slot Time Table - GEETHU NEEPA T K (25013790)</title>
</head>
<body>
    <IMG SRC="/static/logo.png"HEIGHT="150"WIDTH="500"BORDER=6>
    <h2>Saveetha Engineering College</h2>
    <h3>SLOT TIME TABLE - GEETHU NEEPU T K (25013790)</h3>

    <table border="1">
        <tr BGCOLOR="YELLOW">
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">8-10</td>
            <td>C-Programe</td>
            <td>Com-English</td>
            <td>C-Programe</td>
            <td></td>
            <td>Com-English</td>
            <td>Com-English</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">10-12</td>
            <td>Web-Application</td>
            <td>Web-Application</td>
            <td></td>
            <td></td>
            <td></td>
            <td>Com-English</td>
        </tr>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">12-1</td>
            <td COLSPAN=6 ALIGN="CENTER">LUNCH</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">1-3</td>
            <td></td>
            <td>Web-Application</td>
            <td>Mentor Meet</td>
            <td>C-Programe</td>
            <td>C-Programe</td>
            <td>C-Programe</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">3-5</td>
            <td></td>
            <td></td>
            <td>Web-Application</td>
            <td></td>
            <td></td>
            <td>Web-Application</td>
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
            <td>19EN101</td>
            <td>Communicative English</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>Training Saveetha</td>
            <td>Fundamentals of C Programming</td>
        </tr>
    </table>
</body>
</html>
</body>
</html>

## OUTPUT
<img width="1919" height="1028" alt="Screenshot 2025-12-27 180058" src="https://github.com/user-attachments/assets/aef68d70-c0de-4c89-bdbe-d8ad7f1f33da" />

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

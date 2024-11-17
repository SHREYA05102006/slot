# Ex03 Time Table
## Date:17.11.24

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
'''
    <html>
    <head>
        <title>Slot Timetable</title>
    </head>
    <body>
        <center>
            <img src="/static/logo.png" height="100" width="540">
        </center>
        <br>
        <table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
            <caption><b>SLOT TIME TABLE-SHREYA V (24000632)</b></caption>
            <tr align="center">
                <th bgcolor="#FA8072">Day/Time</th>
                <th bgcolor="#FA8072">Monday</th>
                <th bgcolor="#FA8072">Tuesday</th>
                <th bgcolor="#FA8072">Wednesday</th>
                <th bgcolor="#FA8072">Thursday</th>
                <th bgcolor="#FA8072">Friday</th>
                <th bgcolor="#FA8072">Saturday</th>
            </tr>
            <tr align="center">
                <th bgcolor="#fdc8bc">8-10</th>
                <th bgcolor="white">free</th>
                <th bgcolor="#e8daef">chem</th>
                <th bgcolor="#fdebd0">c</th>
                <th bgcolor="white">free</th>
                <th bgcolor="white">free</th>
                <th bgcolor="#d1f2eb">digital electronic</th>
            </tr>
            <tr align="center">
                <th bgcolor="#fdc8bc">10-12</th>
                <th bgcolor="#d0ece7">web</th>
                <th bgcolor="#eaeded">ds</th>
                <th bgcolor="#d0ece7">web</th>
                <th bgcolor="#f2d7d5">eng</th>
                <th bgcolor="#d1f2eb">digital electronic</th>
                <th bgcolor="#DE3163">cd</th>
            </tr>
            <tr align="center">
                <th bgcolor="#fdc8bc">1-3</th>
                <th bgcolor="#fdebd0">c</th>
                <th bgcolor="#f2d7d5">eng</th>
                <th bgcolor="#6495ED">mentor</th>
                <th bgcolor="#e8daef">chem</th>
                <th bgcolor="#eaeded">ds</th>
                <th bgcolor="#d0ece7">web</th>
            </tr>
        </table>
        <br>
        <table align="center" width="540" cellspacing="2" cellpadding="4" border="5">
            <tr align="center">
                <th>sno</th>
                <th>subject code</th>
                <th>subject name</th>
            </tr>
            <tr align="center">
                <th>1.</th>
                <th>19AI414</th>
                <th>fundamentals of web application</th>
                
            </tr>
            <tr align="center">
                <th>2.</th>
                <th>19CY205</th>
                <th>principles of chemistry in engineering</th>

            </tr>
            <tr align="center">
                <th>3.</th>
                <th>19AI403</th>
                <th>introduction to data science</th>
            </tr>
            <tr align="center">
                <th>4.</th>
                <th>19AI304</th>
                <th>fundamental of c programming</th>
            </tr>
            <tr align="center">
                <th>5.</th>
                <th>19EE404</th>
                <th>digital electronics</th>
            </tr>
            <tr align="center">
                <th>6.</th>
                <th>19EN101</th>
                <th>communicative english</th>
            </tr>
            <tr align="center">
                <th>7.</th>
                <th>19EY708</th>
                <th>career development</th>
                
            </tr>

    </body>
    <html>

'''


## OUTPUT
![alt text](<Screenshot (87).png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

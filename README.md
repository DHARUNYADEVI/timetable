# Experiment_Time_Table

## AIM
To Write a html webpage page to display your timetable.

# ALGORITHM
### STEP 1
create a django-admin interface.
### STEP 2
create a static folder and inert HTML code.
### STEP 3
create a simple table using ```<table>```tag in html.
### STEP 4
Add header row using ```<th>```tag.
### Step 5
execute the program using runserver command.

### PROGRAM
```
<html>
    <head>
        <tittle></tittle>
    </head>
    <body>
        <center>
            <img src="/static/logo.png" height="100" width="540">
        </center>
        <table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
        <caption><br>SLOT TIME TABLE - DHARUNYADEVI(23013594)</caption></caption>
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
        <td >FREE SLOT</td>
        <td>DIGITAL ELECTRONICS</td>
        <td>DIGITAL ELECTRONICS</td>
        <td>SOFT SKILLS</td>
        <td>CALCULAS AND MATRIX ALGEBRA</td>
        </tr>
        <tr align="center">
        <th bgcolor="yellow">10-12</th>
        <td>FREE SLOT</td>
        <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
        <td> FREE SLOT</td>
        <td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
        <td>FREE SLOT</td>
        </tr>
        <tr>
        <th bgcolor="yellow">12-1</th>
        <td colspan="5" align="center">L U N C H</td>
        </tr>
        <tr align="center">
        <th bgcolor="yellow">1-3</th>   
        <td >FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
        <td>COMMUNICATIVE ENGLISH</td>
        <td>FREE SLOT</td>
        <td>COMMUNICATIVE ENGLISH</td>
        <td>FREE SLOT</td>
        </tr>
        <tr align="center">
        <th bgcolor="yellow">3-5</th>
        <td>FREE SLOT</td>
        <td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
        <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
        <td>CALCULAS AND MATRIX ALGEBRA</td>
        <td>FREE SLOT</td>
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
        <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
        </tr>
        <tr>
        <td align="center">2.</td>
        <td align="center">19EN101</td>
        <td>COMMUNICATIVE ENGLISH</td>
        </tr>
        <tr>
        <td align="center">3.</td>
        <td align="center">19EE404</td>
        <td>DIGITAL ELECTRONICS</td>
        </tr>
        <tr>
        <td align="center">4.</td>
        <td align="center">19CY205</td>
        <td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
        </tr>
        <tr>
        <td align="center">5.</td>
        <td align="center">19MA201</td>
        <td>CALCULAS AND MATRIX ALGEBRA</td>
        </tr>
        <tr>
        <td align="center">6.</td>
        <td align="center">19EY701</td>
        <td>SOFT SKILLS</td>
        </br>
        </tr>
        </table>
        </body>
        </html>
```

## OUTPUT
## ![Screenshot from 2023-11-21 17-29-47](https://github.com/DHARUNYADEVI/timetable/assets/147473847/436d8f12-8d45-4a48-a205-ba1f9d1f7cb5)


## RESULT
The programfor creating slot timetable using basic HTML tag is executed successfully


# Experiment_Time_Table

## AIM
To Write a html webpage page to display your timetable.

# ALGORITHM
### STEP 1
create a simple table using table tag
### STEP 2
Add header row using th tag
### STEP 3
Add your timetable
### STEP 4
Execute the program

# CODE
```
<!DOCTYPE html>
<html>
    <head>
        <title>Timetable</title>
    </head>
    <body>
        <center>
        <img src="/static/images/logo.jpg" height="100" width="540">
        </center>
        <br>
        <table align="center" width="650" cellspacing="2" cellpadding="4" border="5" bgcolor="yellow">
            <caption><b>TIMETABLE - PRANAV (22006076)</b></caption>
        <tr align="center">
        <th bgcolor="yellow">DAY/TIME</th>
        <th bgcolor="yellow">MONDAY</th>
        <th bgcolor="yellow">TUESDAY</th>
        <th bgcolor="yellow">WEDNESDAY</th>
        <th bgcolor="yellow">THURSDAY</th>
        <th bgcolor="yellow">FRIDAY</th>
        </tr>
        <tr align="center">
        <th bgcolor="yellow">8-10</th>
        <td bgcolor="yellow">PYTHON</td>
        <td bgcolor="yellow">WEB</td>
        <td bgcolor="yellow">MAT</td>
        <td bgcolor="yellow">PHY</td>
        <td bgcolor="yellow">CHEM</td>
        </tr>
        <tr align="center">
        <th bgcolor="yellow">10-12</th>
        <td bgcolor="yellow">CHEM</td>
        <td bgcolor="yellow">DPSD</td>
        <td bgcolor="yellow">PHY</td>
        <td bgcolor="yellow">MAT</td>
        <td bgcolor="yellow">OS</td>
        </tr>
        <tr>
        <th bgcolor="yellow">12-1</th>
        <td colspan="5" align="center">L U N C H</td>
        </tr>
        <tr align="center">
        <th bgcolor="yellow">1-3</th>
        <td colspan="2">FREE SLOT</td>
        <td bgcolor="yellow">DPSD</td>
        <td bgcolor="yellow">PHY</td>
        <td bgcolor="yellow">MAT</td>
        </tr>
        <tr align="center">
        <th bgcolor="yellow">3-5</th>
        <td bgcolor="yellow">ENGLISH</td>
        <td bgcolor="yellow">OS</td>
        <td bgcolor="yellow">WEB</td>
        <td COLSPAN="2">FREE SLOT</td>
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
            <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT (FWAD)</td>
            </tr>
            <tr>
            <td align="center">2.</td>
            <td align="center">19EN101</td>
            <td>COMMUNICATIVE ENGLISH</td>
            </tr>
            <tr>
            <td align="center">3.</td>
            <td align="center">19PH206</td>
            <td>PHYSICS (PHY)</td>
            </tr>
            <tr>
            <td align="center">4.</td>
            <td align="center">19CY205</td>
            <td>PRINCIPLES OF CHEMISTRY IN ENGINEERING (CHE)</td>
            </tr>
            <tr>
            <td align="center">5.</td>
            <td align="center">19MA201</td>
            <td>MATHS (MAT)</td>
            </tr>
            <tr>
            <td align="center">6.</td>
            <td align="center">19CS205</td>
            <td>OPERATING SYSTEM (OS)</td>
            </tr>
        </table>


    </body>
</html>
```

# OUPUT

![out](https://user-images.githubusercontent.com/121292280/233130601-93bf4c28-b431-44f9-8321-bcd754d66108.png)
# RESULT
The Program for creating TimeTable is completed successfully.

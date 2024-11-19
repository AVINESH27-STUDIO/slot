# Ex03 Time Table
## Date:12/11/2024

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
    <body>
        <img src="/static/logo.png">
        <table border="1" cellspacing="15" cellpadding="2">
            <caption>Timetable  NAME : AVINESH  REF.NO:24013574</caption>
            <tr bgcolor="cyan">
                <th>timetable</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>thursday</th>
                <th>friday</th>
                <th>saturday</th>
            </tr>
            <tr>
                <td>8-10</td>
                <td>free slot</td>
                <td>c.A</td>
                <td>python</td>
                <td>free slot</td>
                <td>D.E</td>
                <td>D.E</td>
                
            </tr>
            <TR>
                <td>10-12</td>
                <td>python</td>
                <td>C.a</td>
                <td>Carrier development</td>
                <td>maths</td>
                <td>pysics</td>
                <td>free slot</td>

            </TR>
            <tr>
                <td>12-1</td>
                <td  align=center colspan="6"> Lunch </td>
                
            </tr>
            <tr>
                <td>1-3</td>
                <td>fwad</td>
                <td>fwad</td>
                <td>mentor meeting</td>
                <td>physics</td>
                <td>maths</td>
                <td>physics</td>
            </tr>
            </table><br>
        
        <table border="1" cellspacing=10>
            <tr>
                <th>S.no</th>
                <th>course code</th>
                <th>course name</th>
            </tr>
            <tr>
                <td>1.</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Application Development(FWAD)</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>19AI301</td>
                <td>Python Programming</td>

            </tr>
            <tr>
                <td>3.</td>
                <td>19CS305</td>
                <td>Computer Architecture</td>

            </tr>
            <tr>
                <td>4.</td>
                <td>19EE404</td>
                <td>Digital Electronics</td>
            </tr>
            <tr>
                <td>5.</td>
                <td>18EY708</td>
                <td>Carrer Development</td>
            </tr>
            <tr>
                <td>6.</td>
                <td>19MA222</td>
                <td>Probability Queueing Models</td>
            </tr>
            <tr>
                <td>7.</td>
                <td>Mentor Meeting</td>
                <td>ECA-M -SCOFT</td>
                

            </tr>
            <tr>
                <td>8.</td>
                <td>SH3214</td>
                <td>Physics and Quantum computing</td>
            </tr>
        </table>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2024-11-19 215050.png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

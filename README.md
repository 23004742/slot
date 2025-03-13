# Ex03 Time Table
## Date:

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

<body>
<center><table border="4">
    <center><img src="4j3-1.png" height="400 cm" width="450"></center>
    <caption>TIME TABLE</caption>
<tr> 
<td bgcolor="lavender">Day/Time</td>
<td bgcolor="lavender">Monday</td>
<td bgcolor="lavender">Tuesday</td>
<td bgcolor="lavender">Wednesday</td>
<td bgcolor="lavender">Thursday</td>
<td bgcolor="lavender">Friday</td>
<td bgcolor="lavender">Saturday</td>
</tr>
<tr>
    <td bgcolor="cyan">8-10</td>
    <td bgcolor="pink">CE</td>
    <td bgcolor="pink">FREE SLOT</td>
    <td bgcolor="pink">FREE SLOT</td>
    <td bgcolor="pink">WEB</td>
    <td bgcolor="pink">FREE SLOT</td>
    <td bgcolor="pink">FREE SLOT</td>
</tr>
<tr>
    <td bgcolor="cyan">10-12</td>
    <td bgcolor="pink">FREE SLOT</td>
    <td bgcolor="pink">FREE SLOT</td>
    <td bgcolor="pink">RA</td>
    <td bgcolor="pink">C</td>
    <td bgcolor="pink">C</td>
    <td bgcolor="pink">WEB</td>
</tr>
<tr>
    <td bgcolor="cyan">12-1</td>
    <th colspan="6">LUNCH BREAK</th>
    
</tr>
<tr>
    <td bgcolor="cyan">1-3</td>
    <td bgcolor="pink">BEEE</td>
    <td bgcolor="pink">PROB</td>
    <td bgcolor="pink">MENTOR MEET</td>
    <td bgcolor="pink">CE</td>
    <td bgcolor="pink">PROB</td>
    <td bgcolor="pink">FREE SLOT</td>
</tr>
<tr>
    <td bgcolor="cyan">3-5</td>
    <td bgcolor="pink">EMPD</td>
    <td bgcolor="pink">CHEM</td>
    <td bgcolor="pink">BEEE</td>
    <td bgcolor="pink">CHEM</td>
    <td bgcolor="pink">EMPD</td>
    <td bgcolor="pink">FREE SLOT</td>
</tr>
</table></center>
<br>
<center><table border="4">
    <caption style="color: blueviolet;"> COURSE NAME</caption> 
    <tr>
        <th>S.no</th>
        <th>Subject code</th>
        <th>Subject name</th>
    </tr>
    <tr>
        <td>1.</td>
        <td>19MA222</td>
        <td>Probability and Queeing Models(PROB)</td>
    </tr> 
    <tr>
        <td>2.</td>
        <td>19EY709</td>
        <td>Reasoning ability(RA)</td>
    </tr>
    <tr>
        <td>3.</td>
        <td>19EN101</td>
        <td>Communicative English(CE)</td>
    </tr>
    <tr>
        <td>4.</td>
        <td>19EE305</td>
        <td>Basic,Electrical,Electronics and Mesurement Engineering(BEEE)</td>
    </tr>
    <tr>
        <td>5.</td>
        <td>19CY205</td>
        <td>Principles of Chemistry in Engineering(CHEM)</td>
    </tr>
    <tr>
        <td>6.</td>
        <td>19AI414</td>
        <td>Fundamental of Web Application(WEB)</td>
    </tr>
    <tr>
        <td>7.</td>
        <td>19AI305</td>
        <td>Advanced C Programming(C)</td>
    </tr>
    <tr>
        <td>8.</td>
        <td>19AI303</td>
        <td>Engineering Mechanics and Product Development(EMPD)</td>
    </tr>   
</table></center>
</body>
</html>

## OUTPUT
![image](https://github.com/user-attachments/assets/7c50992b-e7db-4496-9985-de97e6e2d547)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

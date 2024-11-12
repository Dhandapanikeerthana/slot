# Ex03 Time Table
## Date:12.11.2024

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
html>
    <body>
        <img src="logo.png">
        <table border="1" cellspacing="15" cellpadding="2">
            <caption>SLOT TIME TABLE-KEERTHANA(24900211)</caption>
            <tr bgcolor="red">
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
                 </tr>
                 <tr>
                    <td bgcolor="green">8-10</td>
                    <td>Free Slot</td>
                    <td>Career Development</td>
                    <td>Python</td>
                    <td>Physics</td>
                    <td>Web</td>
                    <td>English</td>
                </tr>
                <tr>
                    <td bgcolor="green">10-12</td>
                    <td>Python</td>
                    <td>EVS</td>
                    <td>English</td>
                    <td>BEEE</td>
                    <td>Free Slot</td>
                    <td>Physics(Lab)</td>
                </tr>
                <tr>
                    <td bgcolor="green">12-1</td>
                    <td colspan="6">LUNCH BREAK</td>
                   
                </tr>
                <tr>
                    <td bgcolor="green">1-3</td>
                    <td>Web</td>
                    <td>Web</td>
                    <td>Mentor Class</td>
                    <td>Free Slot</td>
                    <td>BEE</td>
                    <td>Free Slot</td>
                </tr>
                <tr>
                    <td bgcolor="green">3-5</td>
                    <td>Free Slot</td>
                    <td>Free Slot</td>
                    <td>Chemistry</td>
                    <td>Chemistry</td>
                    <td>Free Slot</td>
                    <td>Freee Slot</td>
                </tr>

                 </tr>
        </table>
        <table>
            <table border="1">
            <tr>
                <th>S.no</th>
                <th>Course Code</th>
                <th>Course Name</th>
             </tr>
             <tr>
                <td>1.</td>
                <td>19AI301</td>
                <td>Python Programming</td>
             </tr>
             <tr>
                <td>2.</td>
                <td>19AI414</td>
                <td>Fundamental of Web Application</td>
             </tr>
             <tr>
                <td>3.</td>
                <td>19EY708</td>
                <td>Careeer Development Skills</td>
            </tr>
            <tr>
                <td>4.</td>
                <td>SH4801</td>
                <td>Environmental Sciences and Sustainability</td>
            </tr>
            <tr>
                <td>5.</td>
                <td>SE3214</td>
                <td>Physics for Quantum Computing</td>
            </tr>
            <tr>
                <td>6.</td>
                <td>4W1-1</td>
                <td>Communicative English</td>
            
            </tr>
            <tr>
                <td>7.</td>
                <td>19EE305</td>
                <td>BEE</td>
            </tr>
            <tr>
                <td>8.</td>
                <td>4L3-1</td>
                <td>Chemistry</td>
            </tr>
            <tr>
                <td>9.</td>
                <td>ECA-M-SCOFT</td>
                <td>Mentor Meet</td>
            </tr>


        </table>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot (15).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

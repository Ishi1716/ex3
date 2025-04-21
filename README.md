# Ex03 Time Table
## Date:21-04-2025

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
    <body bgcolor="white">
        <img src="/static/logo.png" alt="" width="1275">
        <table border="5" cellpadding="22" aling="center" bgcolor="cyan">
            <caption aling="center">YASHASWINI S 212224220123 </caption>
     
        <tr bgcolor="yellow">
            <th>Day/Time</th><th>Monday</th><th>Tuesday</th><th>Wednesday</th><th>Thursday</th><th>Friday</th><th>Saturday</th>
        </tr>
        <tr>
            <th>8-10</th><th colspan= "3">FREE SLOT</th><th>Calculas and Matrix</th><th>FREE SLOT</th><th>FWAD</th>
        </tr>
        <tr>
            <th>10-12</th><th>Fundamental of c</th><th>Digital Elecrtonics</th><th> Communication English </th><th> FREE SLOT</th><th> Fundamental Of C</th><th>FWAD</th>
        </tr>
        <TR>
            <th>12-1</th><th colspan="6">LUNCH TIME</th>
        </TR>
        <tr>
            <th>1-3</th><th>Calculas And Matrix</th><th>FWAD</th><th>Mentor Meet</th><th>FWAD</th><th>Digital Electronic</th><th>Career Development</th>
        </tr>
        <tr>
            <th>3-5</th><th colspan="6">FREE SLOT</th>
            </tr>
            
        
        

        
            
        </table>
        <table border="5" cellpadding="22" aling="center" bgcolor="cyan" width="1255">
            <tr>
                <th>S.NO</th><th>SUBJECT CODE</th><th>SUBJECT NAME</th>
            <tr>
                <th>1.</th><th>19MA201</th><th>Calculas and Matrix</th>
            </tr>
            <tr>
                <th>2.</th><th>19EE404</th><th>Digital Elecrtonics</th>
            </tr>
            <TR>
                <th>3.</th><th>19EN101</th><th>Communicative English</th>
            </TR>
            <tr>
                <th>4.</th><th>19AI414</th><th>Fundamental Of Wed Application Developement</th>
            </tr>
            <tr>
                <th>5.</th><th>19EY708</th><th>Career Developement</th>
                </tr>
                <tr>
                    <th>6.</th><th>19AI304</th><th>Fundamental Of c Programming</th>
                    </tr>

        </table>


    </body>
        
    
</html>
```

## OUTPUT

![Screenshot 2025-04-16 193118 (1)_cleanup (1)-fotor-202504211270](https://github.com/user-attachments/assets/7a75541d-7a87-4f7a-9826-2c5e89599672)




## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

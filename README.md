# Ex03 Time Table
## Date:16/11/2024

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
    <header> <img src="logo.png" alt="LOGO" height="200" width="400"> </header>
    <title>SLOT TIME TABLE</title>
    <body ALIGN="CENTER">
       
        <FONT SIZE="50" COLOR="RED" FACE="CURSIVE">SCHEDULE</FONT>    
    <table BORDER="2" CELLPADDING="20" CELLSPACING="5" align="CENTER" BGCOLOR="BLACK" >
        <caption>TIMETABLE</caption>
        <tr>
            <th><FOnt COLOR="red" FACE="CURSIVE">DAY/TIME</FOnt></th>
            <th><FOnt COLOR="red" FACE="CURSIVE">8-10</FOnt></th>
            <TH><FOnt COLOR="red" FACE="CURSIVE">10-12</FOnt></TH>
            <TH><FOnt COLOR="red" FACE="CURSIVE" >1-3</FOnt></TH>
            <TH><FOnt COLOR="red" FACE="CURSIVE">3-5</FOnt></TH>
        </tr>
        <TR>
            <TH BGCOLOR="RED">MONDAY</TH>
            <TD>-</TD>
            <TD><FONT COLOR="WHITE" FACE="CURSIVE">CRYPTOCURRENCY</FONT></TD>
            <TD><FONT COLOR="WHITE" FACE="CURSIVE">PYTHON</FONT></TD>
            <TD>-</TD>
        </TR>
        <TR>
            <TH bgcolor="=BLUE">TUESDAY</TH>
            <TD>-</TD>
            <TD><FONT COLOR="WHITE" FACE="CURSIVE">CALCULUS</FONT></TD>
            <TD><FOnt COLOR="WHITE" FACE="CURSIVE">WEB APP</FONT></TD>
            <TD>-</TD>
        </TR>
        <TR>
            <TH bgcolor="YELLOW">WEDNESDAY</TH>
            <TD><FOnt COLOR="WHITE" FACE="CURSIVE">CRYPTOCURRENCY</FONT></TD>
            <TD><FONT COLOR=WHITE FACE="CURSIVE">DIGITAL ELECTRONICS</FONT></TD>
            <TD><FOnt COLOR="WHITE" FACE="CURSIVE">MENTOR MEET</FOnt></TD>
        <TR>
            <TH bgcolor="VIOLET">THURSDAY</TH>
            <TD><FOnt COLOR="WHITE" FACE="CURSIVE">PHYSICS</FOnt></TD>
            <TD><FOnt COLOR="WHITE" FACE="CURSIVE">DIGITAL ELECTRONICS</FOnt></TD>
            <TD><FOnt COLOR="WHITE" FACE="CURSIVE">WEB APP</FOnt></TD>
            <TD>-</TD>
        </TR>
        <TR>
            <TH bgcolor="ORANGE">FRIDAY</TH>
            <TD></TD>
            <TD><FOnt COLOR="WHITE" FACE="CURSIVE">PYHTHON</FOnt></TD>
            <TD><FOnt COLOR="WHITE" FACE="CURSIVE">PHYSICS</FOnt></TD>
            <TD><FOnt COLOR="WHITE" FACE="CURSIVE">CDS</FOnt></TD>
        </TR>
        <TR>
            <TH bgcolor="GREEN">SATURDAY</TH>
            <TD>-</TD>
            <TD><FOnt COLOR="WHITE" FACE="CURSIVE">WEB APP</FOnt></TD>
            <TD><FOnt COLOR="WHITE" FACE="CURSIVE">CALCULUS</FOnt></TD>
            <TD>-</TD>
        </TR>
    </table>
    </body>
</html>
<html>
    <body ALIGN="CENTER">
       
        <FONT SIZE="50" COLOR="RED" FACE="CURSIVE">SCHEDULE</FONT>    
    <table BORDER="2" CELLPADDING="20" CELLSPACING="5" align="CENTER" BGCOLOR="BLACK" >
        <caption>COURSES</caption>
        <tr>
            <th><FOnt COLOR="red" FACE="CURSIVE">Fundamentals of WEB</FOnt></th>
           
        <TR>
            <TH BGCOLOR="RED">CRYTOCURRENCY</TH>
            
        </TR>
        <TR>
            <TH bgcolor="=BLUE">MATHS</TH>
           
        </TR>
        <TR>
            <TH bgcolor="YELLOW">PHYSICS</TH>
        <TR>
      
        </TR>
        <TR>
            <TH bgcolor="ORANGE">CDS</TH>
        </TR>
        <TR>
            <TH bgcolor="GREEN">PYTHON</TH>
        </TR>
        <TR>
            <TH bgcolor="GREEN">Digital Electronics</TH>
        </TR>
    </table>
    </body>
</html>

```

## OUTPUT
![alt text](<Screenshot 2024-11-16 172345.png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

# Ex03 Time Table
## Date:15-03-2-24

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
    <head>
        <title>MY TIME TABLE</title>
    </head>
    <body>
        <center>
           <img src="logo.png" height="150" width="1000">   
        </center>
           <br>
           <table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="khaki">
           <caption><b>SLOT TIME TABLE - KALIKIRI VAISHNAVI (21222340081)</b></caption>
           <tr align="center">
           <th bgcolor="olivedrab">Day/Time</th>
           <th bgcolor="olivedrab">MONDAY</th>
           <th bgcolor="olivedrab">TUESDAY</th>
           <th bgcolor="olivedrab">WEDNESDAY</th>
           <th bgcolor="olivedrab">THURSDAY</th>
           <th bgcolor="olivedrab">FRIDAY</th>
           <th bgcolor="olivedrab">SATURDAY</th>
           </tr>
           <tr align="center">
           <th bgcolor="olivedrab">8-10</th>
           <td> FREE SLOT </td>
           <td> FREE SLOT </td>
           <td> MATHS </td>
           <td> FREE SLOT</td>
           <td> FWAD </td>
           <td> COMMUNICATIVE ENGLISH </td>
           </tr>
           <tr align="center">
           <th bgcolor="olivedrab">10-12</th>
           <td> SOFTWARE ENGINEERING </td>
           <td> COMPUTER NETWORKS </td>
           <td> ADVANCED C PROGRAM </td>
           <td> FREE SLOT</td>
           <td> COMPUTER NETWORKS </td>
           <td> FREE SLOT</td>
           </tr>
           <tr>
           <th bgcolor="olivedrab">12-1</th>
           <td colspan="6" align="center">L U N C H</td>
           </tr>
           <tr align="center">
           <th bgcolor="olivedrab">1-3</th>
           <td> COMMUNICATIVE ENGLISH </td>
           <td> FWAD </td>
           <td> FREE SLOT</td>
           <td> FWAD </td>
           <td> ADVANCED C PROGRAM </td>
           <td> CREATIVE SKILLS </td>
           </tr>
           <tr align="center">
           <th bgcolor="olivedrab">3-5</th>
           <td> MATHS </td>
           <td> FREE SLOT</td>
           <td> SOFTWARE ENGINEERING </td>
           <td> FREE SLOT</td>
           <td> FREE SLOT</td>
           <td> FREE SLOT</td
           </tr>
           </table>
           <br>
           <table align="center" cellspacing="2" cellpadding="4" border="2">
           <tr align="center">
           <th>S.NO.</th>
           <th>SUBJECT CODE</th>
           <th>SUBJECT NAME</th>
           </tr>
           <tr>
           <td align="center">1.</td>
           <td align="center">19AI414</td>
           <td>FUNDAMENTALS OF WEB APPLICATION</td>
           </tr>
           <tr>
           <td align="center">2.</td>
           <td align="center">19CS408</td>
           <td>SOFTWARE ENGINEERING</td>
           </tr>
           <tr>
           <td align="center">3.</td>
           <td align="center">19CS406</td>
           <td>COMPUTER NETWORKS</td>
           </tr>
           <tr>
           <td align="center">4.</td>
           <td align="center">19EN101</td>
           <td>COMMUNICATIVE ENGLISH</td>
           </tr>
           <tr>
           <td align="center">5.</td>
           <td align="center">19MA222</td>
           <td>PROBABILITY AND QUEUEING MODELS (MAT)</td>
           </tr>
           <tr>
           <td align="center">6.</td>
           <td align="center">19EY702</td>
           <td>CREATIVE SKILLS (S)</td>
           </tr>
           </table>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot (88).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

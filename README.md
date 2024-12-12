# Ex03 Time Table
# Date:12.12.2024
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
````
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <head><title>SEC timetable</title></head>
  
    
        <body>
            <center><img src="saveetha title logo.png" height="150" width="600"></center>
            <center><h3>THARUN.V(24005351)</h3></center>
            <style>
               
                table{
                    border-collapse:collapse;
                }
            </style>
            <center><table border="10"width="800"height="300">
                <tr>
                    <th bgcolor="red">day/time</th>
                    <th bgcolor="red">Monday</th>
                    <th bgcolor="red">Tuesday</th>
                    <th bgcolor="red">Wednesday</th>
                    <th bgcolor="red">Thursday</th>
                    <th bgcolor="red">Friday</th>
                    <th bgcolor="red">Saturday</th>
                </tr>
                <tr>
                    <th bgcolor="red">8-10</th>
                    <th colspan="1" align="center"bgcolor="cyan">FREE SLOT</th>
                    <th bgcolor="cyan">Environmental science</th>
                    <th align="center"bgcolor="cyan">FREE SLOT</th>
                    <th align="center"bgcolor="cyan">FREE SLOT</th>
                    <th align="center"bgcolor="cyan">FREE SLOT</th>
                    <th align="center"bgcolor="cyan">FREE SLOT</th>
                    </tr>
                <tr>
                    <th bgcolor="red">10-12</th>
                    <th bgcolor="cyan">Web development</th>
                    <th bgcolor="cyan">Physics</th>
                    <th bgcolor="cyan">C programming</th>
                    <th bgcolor="cyan">Communicative english</th>
                    <th bgcolor="cyan">C programming</th>
                    <th bgcolor="cyan">Probality and queueing models</th>
                </tr>
                <tr>
                    <th bgcolor="red">12-01</th>
                    <th bgcolor="green">Lunch</th>
                    <th bgcolor="green">Lunch</th>  
                    <th bgcolor="green">Lunch</th>  
                    <th bgcolor="green">Lunch</th>  
                    <th bgcolor="green">Lunch</th>  
                    <th bgcolor="green">Lunch</th>                  
                </tr>
                <tr>
                    <th bgcolor="red">01-03</th>
                    <th bgcolor="cyan">B.eee</th>
                    <th bgcolor="cyan">Communicative english</th>
                    <th bgcolor="cyan">Mentor meet</th>
                    <th bgcolor="cyan">Web development</th>
                    <th bgcolor="cyan">Probability and queueing models</th>
                    <th bgcolor="cyan">Physics</th>
                </tr>
                <tr>
                    <th bgcolor="red">03-05</th>
                    <th colspan="0"align="center"bgcolor="cyan">FREE SLOT</th>
                    <th align="center"bgcolor="cyan">FREE SLOT</th>
                    <th bgcolor="cyan">B.eee</th>
                    <th align="center"bgcolor="cyan">FREE SLOT</th>
                    <th bgcolor="cyan">Career developmemt</th>
                    <th bgcolor="cyan">Web developmemt</th>
                </tr>
            </table>
            <br>
            <table border="3" width="600">
                <tr>
                    <td>S.no</td>
                    <td>Subject code</td>
                    <td>Subject name</td>
                </tr>
                <tr>
                    <td>01</td>
                    <td>19AI304</td>
                    <td>C programming</td>
                </tr>
                <tr>
                    <td>02</td>
                    <td>19AI414</td>
                    <td>Web development</td>
                </tr>
                <tr>
                    <td>03</td>
                    <td>19EE305</td>
                    <td>B.eee</td>
                </tr>
                <tr>
                    <td>04</td>
                    <td>19EN101</td>
                    <td>Communicative english</td>
                </tr>
                <tr>
                    <td>05</td>
                    <td>19EY708</td>
                    <td>Career developmemt</td>
                </tr>
                <tr>
                    <td>06</td>
                    <td>19MA222</td>
                    <td>Probability and queueing models</td>
                </tr>
                <tr>
                    <td>07</td>
                    <td>SH3214</td>
                    <td>Physics</td>
                </tr>
                <tr>
                    <td>08</td>
                    <td>SH3214</td>
                    <td>Environmrntal science</td>
                </tr>
            </table>
        </body>
</html>
````
# OUTPUT
![Screenshot 2024-12-12 200550](https://github.com/user-attachments/assets/611fc389-fa13-4055-b158-739a7b0fb036)


# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

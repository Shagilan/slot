# Ex03 Time Table
## Date:13.03.2025
## Name:Shagilan

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

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Slot Time Table</title>
    <style>
         table {
            width: 80%;
            border-collapse: collapse;
            margin: 20px auto;
            text-align: center;
            font-family: Arial, sans-serif;
        }
        th, td {
            border: 2px solid black;
            padding: 10px;
        }
        th {
            background-color: yellow;
        }
        .highlight {
            background-color: cyan;
        }
        .title {
            text-align: center;
            font-size: 20px;
            font-weight: bold;
            margin-bottom: 10px;
        }
    </style>
</head>
<body>

    <div class="title">SLOT TIME TABLE - SHAGILAN U (21224040303)</div>
    <th>
        <center><img src="savee.jpg" height="200px" width="800px" alt="Something went wrong "></center>
    <table>
        <tr>
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>
        <tr class="highlight">
            <td>8-10</td>
            <td>FREE SLOT</td>
            <td>FREE SLOAT</td>
            <td>BLOCKCHAIN FOR BUSSINESS</td>
            <td>WEB APPLICATION</td>
            <td>FREE SLOAT</td>
            <td>CRYPTOCURRENCY</td>
        </tr>
        <tr class="highlight">
            <td>10-12</td>
            <td>PYTHON</td>
            <td>FREE SLOAT</td>
            <td>CRYPTOCURRENCY</td>
            <td>COMPUTER NETWORK</td>
            <td>FREE SLOAT</td>
            <td>WEB APPLICATION</td>
        </tr>
        <tr class="highlight">
            <td>12-1</td>
            <td colspan="6">LUNCH BREAK</td>
        </tr>
        <tr class="highlight">
            <td>1-3</td>
            <td>BLOCKCHAIN FOR BUSSINESS</td>
            <td>FREE SLOAT</td>
            <td>mentor meet</td>
            <td>che</td>
            <td>FREE SLOAT</td>
            <td>BLOCKCHAIN FOR BUSSINESS</td>
        </tr>
        <tr class="highlight">
            <td>3-5</td>
            <td>COMPUTER NETWORK</td>
            <td>FREE SLOAT</td>
            <td>MATHS</td>
            <td>CHE</td>
            <td>FREE SLOAT</td>
            <td>PROBABALILTY</td>
        </tr>
    </table>

    <table>
        <tr>
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19EN612</td>
            <td>COMPUTER NETWORK</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19AI206</td>
            <td>PYTHON</td>
        </tr>
        <tr>
            <td>4.</td>
            <td>19CY205</td>
            <td>Principles of Chemistry in Engineering (CHE)</td>
        </tr>
        <tr>
            <td>5.</td>
            <td>19MA202</td>
            <td>PROBABALILTY</td>
        </tr>
        <tr>
            <td>6.</td>
            <td>19AI301</td>
            <td>BLOCKCHAIN FOR BUSSINESS</td>
        </tr>
        <tr>
            <td>6.</td>
            <td>19CS547</td>
            <td>CRYPTOCURRENCY</td>
        </tr>
    </table>

## OUTPUT
![Screenshot 2025-03-13 092549](https://github.com/user-attachments/assets/13bb945a-ef2e-40cf-a84e-93cc355a98c3)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

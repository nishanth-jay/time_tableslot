# Ex02
Time Table
# Date:
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
<!DOCTYPE html>
<html>
<head>
    <title>SLOT TIME TABLE</title>
    <style>
        table,th,td{
            border:10px dotted blue;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            background-color: blanchedalmond;
            border-style: inset;
        }
        img {
            width: 1000px;
            height: auto;
            display: block;
            margin-left: auto;
            margin-right: auto;
        }
        table {
            width: 90%;
            margin: 20px auto;
            border-collapse: collapse;
            text-align: center;
            font-size: 16px;
        }
        th, td {
            border: 2px solid black;
            padding: 10px;
        }
        th {
            background-color: yellow;
        }
        td {
            background-color: #00e5ff;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div>
        <img src="sec_header.png" alt="saveetha engineering college">
    </div>

    <div>
        <p style="text-align: center;">SLOT TIME TABLE - J Nishanth (25015083)</p>
    </div>

    <table>
        <tr>
            <th>Timings / Days</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>

        <tr>
            <td>8am to 10am</td>
            <td>Web App Dev</td>
            <td>Web App Dev</td>
            <td>Web App Dev</td>
            <td>Free</td>
            <td>Free</td>
            <td>Python</td>
        </tr>

        <tr>
            <td>10am to 12pm</td>
            <td>Communicative English</td>
            <td>Python</td>
            <td>Free</td>
            <td>Free</td>
            <td>Communicative English</td>
            <td>English</td>
        </tr>

        <tr>
            <td>12pm to 1pm</td>
            <td colspan="6">Lunch</td>
        </tr>

        <tr>
            <td>1pm to 3pm</td>
            <td>Web App Dev</td>
            <td>Free</td>
            <td>Mentor Meet</td>
            <td>Free</td>
            <td>Web App Dev</td>
            <td>English</td>
        </tr>

        <tr>
            <td>3pm to 5pm</td>
            <td>Free</td>
            <td>Python</td>
            <td>Python</td>
            <td>Web App Dev</td>
            <td>Free</td>
            <td>Free</td>
        </tr>
    </table>

    <table>
        <tr>
            <th>S.No</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr>
            <td>2</td>
            <td>19EN101</td>
            <td>Communicative English</td>
        </tr>
        <tr>
            <td>3</td>
            <td>19AI301</td>
            <td>Python Programming</td>
        </tr>
        <tr>
            <td>4</td>
            <td>Mentor Meet</td>
            <td>(ECM-M)</td>
        </tr>
    </table>
</body>
</html>

# OUTPUT
# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

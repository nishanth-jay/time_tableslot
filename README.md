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
```
<html>
<head>
    <title>TIMETABLE</title>
    <link rel="icon" href="/static/logoimages.jpg">
    <style>
        body{
            background-color:#e8f3ff;
            font-family: Arial, sans-serif;
        }

        .centerimage{
            display:block;
            margin-left:auto;
            margin-right:auto;
        }

        table, th, td {
            margin-left:auto;
            margin-right:auto;
            text-align:center;
            padding:6px;
            border-style:ridge;
            border-color:#1f1f1f;
        }
    </style>
</head>

<body>

<img src="/static/logo.jpg" class="centerimage" height="200px" width="1000px">

<table style="background-color:#b9f2e3;font-size:x-large;">
    <caption style="font-size:24px;background-color:#312e81;color:white;margin-bottom:10px;">
        SLOT-TIMETABLE — J NISHANTH (25015083)
    </caption>

    <tr style="font-size:23px;background-color:#6d28d9;color:white;">
        <th>SLOT / DAYS</th>
        <th>MONDAY</th>
        <th>TUESDAY</th>
        <th>WEDNESDAY</th>
        <th>THURSDAY</th>
        <th>FRIDAY</th>
        <th>SATURDAY</th>
    </tr>

    <tr style="font-size:23px;">
        <th style="background-color:#6d28d9;color:white;">8-10</th>
        <td colspan="3" style="background:#a5b4fc;">FWAD</td>
        <td colspan="2" style="background:#99f6e4;">FREE SLOT</td>
        <td style="background:#c7d2fe;">PYTHON</td>
    </tr>

    <tr style="font-size:23px;">
        <th style="background-color:#6d28d9;color:white;">10-12</th>
        <td style="background:#fde68a;">ENG</td>
        <td style="background:#c7d2fe;">PYTHON</td>
        <td colspan="2" style="background:#bbf7d0;">FREE SLOT</td>
        <td colspan="2" style="background:#fde68a;">ENG</td>
    </tr>

    <tr style="font-size:23px;">
        <th style="background-color:#6d28d9;color:white;">12-1</th>
        <th colspan="6" style="font-size:32px;background:#020617;color:white;">
            L U N C H
        </th>
    </tr>

    <tr style="font-size:23px;">
        <th style="background-color:#6d28d9;color:white;">1-3</th>
        <td style="background:#a5b4fc;">FWAD</td>
        <td style="background:#bbf7d0;">FREE SLOT</td>
        <td style="background:#f9a8d4;">MENTOR MEET</td>
        <td style="background:#bbf7d0;">FREE SLOT</td>
        <td style="background:#a5b4fc;">FWAD</td>
        <td style="background:#fde68a;">ENG</td>
    </tr>

    <tr style="font-size:23px;">
        <th style="background-color:#6d28d9;color:white;">3-5</th>
        <td style="background:#bbf7d0;">FREE SLOT</td>
        <td colspan="3" style="background:#c7d2fe;">PYTHON</td>
        <td colspan="2" style="background:#bbf7d0;">FREE SLOT</td>
    </tr>
</table>


<table style="background-color:#dbeafe;margin-top:30px;font-size:x-large;">
    <caption style="font-size:24px;background-color:#312e81;color:white;margin-bottom:10px;">
        SUBJECTS ENROLLED
    </caption>

    <tr style="font-size:23px;background-color:#6d28d9;color:white;">
        <th>S.No</th>
        <th>COURSE CODE</th>
        <th>COURSE NAME</th>
    </tr>

    <tr>
        <th style="background-color:#6d28d9;color:white;">1</th>
        <td>19AI414</td>
        <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
    </tr>

    <tr>
        <th style="background-color:#6d28d9;color:white;">2</th>
        <td>19AI301</td>
        <td>PYTHON PROGRAMMING</td>
    </tr>

    <tr>
        <th style="background-color:#6d28d9;color:white;">3</th>
        <td>19EN101</td>
        <td>COMMUNICATIVE ENGLISH</td>
    </tr>
</table>

</body>
</html>
```

# OUTPUT
# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

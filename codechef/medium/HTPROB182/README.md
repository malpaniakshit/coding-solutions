# HTPROB182

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

### Worked Example

This example shows how to use `<table>`, `<tr>`, `<th>`, and `<td>` to organize data into a clear attendance list.

 **What the code does** 

- <table border="1">: This is the main container for the entire table. The border="1" attribute is a simple way to add a visible border to the table for clarity.
- <tr>...</tr>: This is the first row of the table. <th>Student Name</th> and <th>Attendance</th>: These are header cells (<th>). They act as labels, telling us what kind of information is in each column.
- <tr>...</tr>: Each of the following <tr> tags creates a new row for a student's data. <td>...</td>: Each <td> inside a row is a data cell. For example, <td>John</td> holds the student's name, and <td>Present</td> holds their attendance status.

 **Try It Yourself** 

- Add a new student: Add a new <tr> with a student's name and their attendance status (e.g., "Chris" and "Present").
- Change a value: Change Sophia's attendance from "Present" to "Absent".
- Add a new column: Add another <th> in the header row for a new category, like "Grade". Then, add a corresponding <td> cell in each student's row with a sample grade.

## Solution

**Language:** C++  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-10-06T14:45:29.270Z  

```cpp
<!DOCTYPE html>
<html>
<head>
  <title>Classroom Attendance</title>
</head>
<body>
  <h1>Attendance for Today</h1>

  <table border="1">
    <tr>
      <th>Student Name</th>
      <th>Attendance</th>
    </tr>
    <tr>
      <td>John</td>
      <td>Present</td>
    </tr>
    <tr>
      <td>Emma</td>
      <td>Absent</td>
    </tr>
    <tr>
      <td>Michael</td>
      <td>Present</td>
    </tr>
    <tr>
      <td>Sophia</td>
      <td>Present</td>
    </tr>
  </table>
</body>
</html>
```

---

[View on CodeChef](https://www.codechef.com/problems/HTPROB182)
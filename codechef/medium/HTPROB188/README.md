# HTPROB188

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

### Task 1 - Creating a Student Report Card

 **Goal:**  Practice using `colspan` to create column headers and `rowspan` to group related subjects in a student report card.

 **Instructions** 

- Create a <table> and add a visible border.
- The first row of your table should contain the main headers. Use <th> tags for "Category" and "Course". Then, use a single <th> with colspan="2" to create a single header for "Final Grades".
- Add a second row to create sub-headers for your grades: "Credits" and "Grade".
- Add a new row for your first subject. The first cell should be a <td> with rowspan set to 2, containing the text "Core Subjects".
- In the same row, add the details for your first core subject (e.g., "Algebra", "4", "A").
- Create another row for your second core subject. Since the "Category" cell is already spanned, this row should only contain the course details (e.g., "Chemistry", "4", "B+").
- Below the core subjects, add a new row for your "Electives" category, using rowspan to group at least two elective courses.

 **Expected output:**

## Solution

**Language:** C++  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-10-06T18:00:26.583Z  

```cpp
<!DOCTYPE html>
<html>
<head>
   <title>Fall Semester Report Card</title>
</head>
<body>
   <h1>Fall Semester Report Card</h1>
   
   <table border="1">
   
      <tr>
   </table>
         <th>Category</th>
      </tr>
</body>
         
</html>
```

---

[View on CodeChef](https://www.codechef.com/problems/HTPROB188)
# HTPROB184

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

### Task - Student Information Table

 **Goal:**  Create a simple webpage that displays  **student details**  in a table format.

1. **Add Main Content** 

- Create a <main> element.
- Inside <main>, add a <p> tag with a short introduction about why tables are useful.

2. **Create the Table Section** 

- Inside <main>, create a <section> to wrap your table.
- Build a <table> with border="1" attribute.
- Add a header row with: Name, Roll Number, Course, Profile.
- Add 3 student rows with sample data.
- In the "Profile" column, add links using <a href="#">View Profile</a>.

 **Expected output:**

## Solution

**Language:** C++  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-10-06T17:23:27.670Z  

```cpp
   
   <p>Tables are an excellent way to organize and display structured data in a clear,readalbe format.They help present information in rows and columns, making it easy to compare and understand different data points.</p>
   
   <table border="1">
      <tr>
         <th>Name</th>
      </tr>
   </table>


      <tr>
         <td>Sarah Johnson</td>
      </tr>
         <th>Roll Number</th>
         <th>Course</th>
         <th>Profile</th>
         <td>2023001</td>
         <td>Computer Science</td>
         <td><a href="#">View Profile</a></td>

      <tr>
         <td><a href="#">View Profile</a></td>
      </tr>

      <tr>
         <td><a href="#">View Profile</a></td>
      </tr>
         <td>Michael Chen</td>
         <td>2023002</td>
         <td>Mathematics</td>
         <td></td>
   <footer>
```

---

[View on CodeChef](https://www.codechef.com/problems/HTPROB184)
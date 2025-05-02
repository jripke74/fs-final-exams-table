# fs-final-exams-table

In this workshop, you will practice working with HTML tables by building a table of final exams.

Step 1
In this workshop, you will practice working with HTML tables by building a final exam table for a group of students.

To begin the project, add the <!DOCTYPE html>, and an html element with a lang attribute of en.

Inside the html element, add a head element.

Step 2
Inside your head element, nest a meta element with the charset attribute set to the value "UTF-8".

Below that meta element, add a title element.

The title element's text should be Calculus Final Exams Table.

After you complete your head element, you can add your body element.

Step 3
In the previous lectures, you learned how to work with the table element to represent tabular data.

Inside your body element, nest a table element.

Step 4
To add a caption to a table, you can use the table caption element.

Here is an example using the caption element:

Example Code
<table>
  <caption>Football Scores</caption>
</table>
Inside your table element, nest a caption element with the text Calculus Final Exam Grades.

Step 5
For the first section of the table, you will want to group the header content which represents the column labels for the student's first name, last name, and final exam grade.

The table head element, thead, is used to group the header content in a table.

Here is an example using the thead element:

Example Code
<table>
  <thead>
    <!-- header content goes here -->
  </thead>
</table>
Below your caption element, add a table head element.

Step 6
The table head element consists of a table row element, tr, which contains the table header cell elements, th.

Here is an example using the tr and th elements for a sports table:

Example Code
<table>
  <caption>Football Scores</caption>
  <thead>
    <tr>
      <th>Team</th>
      <th>Wins</th>
      <th>Losses</th>
    </tr>
  </thead>
</table>
Inside your thead element, add a tr element.

Inside your tr element, add three th elements.

The first th element should contain the text Last Name. The second th element should contain the text First Name. The third th element should contain the text Grade.


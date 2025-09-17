📊 Simple Report Database Project
👥 Contributors

Kwizera Josias (26135)

Niyomugabo Nice Kevin (26708)

Khadija Adam (28041)

📌 Project Overview

This project demonstrates the core concepts of relational database design and query optimization. It covers table creation with constraints, joins, indexing, and views to ensure consistency, efficiency, and simplified access to data.

🛠️ Features
1. Tables

Students

student_id → Primary Key

name → Not Null

email → Unique & Not Null

2. Joins

INNER JOIN → Shows students who are enrolled in courses.

LEFT JOIN → Shows all students, even if not enrolled.

RIGHT JOIN → Shows all courses, even if no student is enrolled.

FULL OUTER JOIN (via UNION in MySQL) → Shows all students and all courses.

3. Index

idx_student_email on the email column.

Improves query performance when searching students by email.

4. View

StudentCourseView created for simplified queries:

SELECT * FROM StudentCourseView;

Reduces the need to repeatedly write join queries.

5. Results

Clear relationships between students and courses.

Joins highlight different perspectives of combining data.

Index boosts efficiency.

View ensures ease of use.

✅ Conclusion

This project demonstrates how relational databases:

Maintain data integrity through constraints.

Provide multiple perspectives with joins.

Improve query performance using indexes.

Simplify data access with views.

📂 How to Run

Create a MySQL database.

Import the provided SQL scripts for table creation and sample data.

Run the queries to test joins, index, and view.

🔎 Summary:
The project builds a student-course database, applies constraints for integrity, demonstrates joins for data relationships, creates an index for performance, and defines a view for simplified access. It’s a practical introduction to relational database design and optimization.

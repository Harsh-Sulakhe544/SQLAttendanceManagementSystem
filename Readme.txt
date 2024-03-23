ATTRIBUTE DIAGRAM FOR ATTENDANCE SYSTEM 

+-----------------+       +-----------------+       +-----------------------+
| attendance_system|       |   students      |       |        courses        |
+-----------------+       +-----------------+       +-----------------------+
|                 |       | student_id (PK) |       |    course_id (PK)     |
|                 |       |      name       |       |      course_name      |
+-----------------+       +-----------------+       +-----------------------+
           |                           |                         |
           |                           |                         |
           v                           v                         v
+------------------------+  +-----------------------+  +------------------------+
|  attendance_records    |  |    student_courses   |  |   instructor_courses   |
+------------------------+  +-----------------------+  +------------------------+
| record_id (PK)         |  | student_id (PK, FK)  |  | instructor_id (PK, FK)|
| student_id (FK)        |  | course_id (PK, FK)   |  | course_id (PK, FK)     |
| course_id (FK)         |  +-----------------------+  +------------------------+
| instructor_id (FK)     |
| attendance_date        |
+------------------------+
            |
            |
            v
+-----------------------+
|     instructors      |
+-----------------------+
| instructor_id (PK)    |
|        name           |
+-----------------------+

key points 

Resume Highlights:
1 Project Title: Attendance System
Developed a robust and user-friendly web-based Attendance System for efficient tracking and management of 
student attendance.

2 Frontend Development:
Spearheaded the creation of a responsive and visually appealing frontend using HTML, CSS, and JavaScript.
Implemented dynamic dropdowns for courses and instructors, populating them dynamically from a predefined list.

3 Data Persistence:
Engineered a data persistence feature utilizing localStorage to ensure that attendance records are retained 
even after page refresh.
Employed JavaScript to store and retrieve attendance data locally, providing a seamless user experience.

4 User Input Validation:
Implemented input validation to ensure data integrity, including checks for empty fields and the correct 
format of the Student ID.

5 Dynamic Table Population:
Created a dynamic table for displaying attendance records, with JavaScript dynamically populating rows based 
on user inputs.

6 Backend Integration:
Collaborated with the backend team utilizing SQL for efficient data storage and retrieval.
Incorporated SQL database queries to manage attendance data on the server-side, ensuring scalability and 
reliability.

7 Dropdown Population:
Implemented a function to dynamically populate dropdowns, retrieving data from predefined lists of courses 
and instructors.

8 Event Handling:
Utilized event listeners to respond to changes in the localStorage, enabling real-time updates and automatic 
data clearance upon the execution of localStorage.clear() from the browser console.

9 Collaboration and Adaptability:
Collaborated with a backend team to integrate frontend functionalities seamlessly, ensuring a cohesive and 
integrated system.
Adapted to changing requirements, demonstrated problem-solving skills, and implemented features to enhance 
the overall user experience.


10 Quality Assurance:
Implemented error handling and validation mechanisms to guarantee the accuracy and reliability of 
user-submitted data.
Conducted thorough testing to identify and rectify potential issues, ensuring a high-quality and bug-free 
application.

11 Documentation:
Maintained clear and concise code documentation for better code understanding and future development.
Created documentation outlining the usage of localStorage.clear() for effective troubleshooting and 
maintenance.

12 Continuous Improvement:
Proactively participated in ongoing improvement efforts, providing insights and solutions to enhance system 
performance and user satisfaction.
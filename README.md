1. Project Overview
The Attendance Management System is a software solution designed to automate the process of tracking and managing attendance for students in an educational institution. It provides a secure and efficient way for administrators, teachers, and students to interact with the system, manage attendance records, and access information about courses. This system significantly reduces manual effort and minimizes errors in recording attendance, while also offering additional features like course management and user registration.
2. How the System Works
The system operates in a role-based manner, meaning that users log in with different roles: Admin, Teacher, or Student. Each role has specific functionality and access permissions within the system.
•	Admin Role: The admin oversees the entire system, including user management and course management. Admins can add or remove courses, register users (admin, teacher, or student), and view attendance reports for all users.
•	Teacher Role: Teachers can manage attendance for students in their respective courses. They can view, update, and review attendance records, ensuring that students' attendance is properly logged.
•	Student Role: Students can view their attendance status for various courses and receive notifications regarding attendance issues, such as when they fall below the required attendance percentage.
The project uses a graphical user interface (GUI) built using Java Swing. Users interact with the system through various buttons and text fields, ensuring a user-friendly experience.
3. Functionalities of the System
The core functionalities of the Attendance Management System include:
a. Role-Based Login System
Upon launching the system, users are asked to select their role—Admin, Teacher, or Student. Based on the role selected, the system presents different menus and functionalities. The login process is authenticated using a User ID and Password.
b. User Management (Admin Functionality)
The admin has access to the user management features:
•	Register User: Admins can add new users (admin, teacher, student) to the system by providing a unique User ID, Name, and Password.
•	View Users: Admins can view a list of all registered users within the system.
•	Remove Users: Admins can remove users when they no longer need access to the system.
c. Course Management (Admin and Teacher Functionality)
•	View Courses: Admins and teachers can view all the courses offered in the system. The system maintains a list of courses that are managed centrally.
•	Manage Courses: Admins can add or remove courses from the system as needed.
•	Assign Courses: Admins can assign teachers to specific courses, ensuring they are responsible for managing attendance for their assigned classes.
d. Attendance Tracking (Teacher Functionality)
•	Record Attendance: Teachers can record attendance for students in their respective courses. They can mark students as “present” or “absent” on a daily basis.
•	View Attendance: Teachers can view a student’s attendance history and generate reports to evaluate their attendance percentage over a period of time.
•	Edit Attendance: Teachers can correct or update attendance records in case of any errors or omissions.
e. Attendance Monitoring (Student Functionality)
•	View Attendance: Students can view their own attendance records, with information regarding their attendance percentage in each course. They can monitor their attendance status to ensure compliance with the institution's policies.
•	Receive Alerts: The system can alert students if their attendance falls below a certain threshold, helping them take corrective action before it affects their grades.
f. Course Registration (Admin and Teacher Functionality)
•	Admins can register new courses into the system. Teachers can also manage course-related activities, ensuring they have an organized list of courses they teach.
g. Reporting System (Admin and Teacher Functionality)
•	Attendance Reports: Admins and teachers can generate reports detailing the attendance records of all students across courses. These reports provide valuable insights into attendance trends and help in decision-making.
•	Course Reports: Admins can generate reports on course offerings, student enrollments, and attendance levels in each course.
h. Exit and Logout
Each role has access to an “Exit” or “Logout” button to securely leave the system. This ensures that user data is protected and session security is maintained.
4. Use Cases
The system can be broken down into specific use cases based on user interactions:
Admin Use Cases:
1.	M1-UC1: Login as Admin
o	Admin selects the "Admin" role and enters credentials to access admin features.
2.	M1-UC2: Register User
o	Admin registers a new user (admin, teacher, or student) by providing ID, name, and password.
3.	M1-UC3: View Users
o	Admin views a list of all users in the system.
4.	M1-UC4: Add Course
o	Admin adds a new course into the system.
5.	M1-UC5: Remove Course
o	Admin removes an existing course.
6.	M1-UC6: Assign Courses to Teacher
o	Admin assigns a course to a teacher.
7.	M1-UC7: View Attendance Reports
o	Admin generates and views attendance reports for all students.
8.	M1-UC8: Logout
o	Admin logs out of the system.
Teacher Use Cases:
1.	M2-UC1: Login as Teacher
o	Teacher selects the "Teacher" role and enters credentials to access teacher features.
2.	M2-UC2: View Assigned Courses
o	Teacher views a list of courses they are assigned to.
3.	M2-UC3: Record Attendance
o	Teacher marks student attendance for a selected course.
4.	M2-UC4: View Attendance
o	Teacher reviews attendance records for students in their courses.
5.	M2-UC5: Edit Attendance
o	Teacher updates or corrects attendance records if necessary.
6.	M2-UC6: View Attendance Reports
o	Teacher generates attendance reports for students in their courses.
7.	M2-UC7: Logout
o	Teacher logs out of the system.
Student Use Cases:
1.	M3-UC1: Login as Student
o	Student selects the "Student" role and enters credentials to access their profile.
2.	M3-UC2: View Attendance
o	Student views their attendance record for each course.
3.	M3-UC3: Receive Alerts
o	Student is notified if their attendance falls below the institution's threshold.
4.	M3-UC4: Logout
o	Student logs out of the system.
5. Technologies Used
•	Java (Swing for GUI): The entire system is implemented in Java, utilizing the Swing library to create the graphical user interface.
•	Data Structures: User data (admin, teacher, student) and course data are stored using collections like HashMap and ArrayList.
•	Role-Based Access: The system uses an Object-Oriented approach, leveraging inheritance and polymorphism to provide different menus and functionalities for each user role.
6. Conclusion
The Attendance Management System simplifies attendance tracking, reduces paperwork, and offers a centralized solution for managing users and courses. It enhances the efficiency of educational institutions by providing role-based access to various functionalities and ensuring that attendance records are accurate and easily accessible by the relevant stakeholders. The use cases clearly define how different users interact with the system, making it a scalable and flexible solution for future extensions.

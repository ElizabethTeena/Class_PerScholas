The application  have a command-line interface menu that allows the user to select one option as below. Once that menu function is completed, the program must return to the main menu.

Student Menu:

Application starts by requesting student’s ID. If (-1) is introduced, a new student is created, and the user is prompted for all necessary information. The main menu is the following:

L – List: lists all records in the course table including meeting times, locations, and teaching professors
E – Enroll: enrolls the active student in a course; user is prompted for course ID; system performs the following checks:
- Verify that student meets all prerequisites for the course
- Check for schedule conflicts with already enrolled courses
- Check for duplicate enrollment
W – Withdraw: deletes an entry in the Enrolled table corresponding to active student; student is prompted for course ID to be withdrawn from
S – Search: search course based on substring of course name which is given by user; list all matching courses with their schedules and professors
M – My Classes: lists all classes enrolled in by the active student, including meeting times and professors
P – Prerequisites: shows prerequisites for a specified course
T - Teaching Professor: list all professor information, their names, department, and a list of courses they teach
X – Exit: exit application
Database Requirements:

Prerequisites Management:
Store course prerequisites in a separate table
Support multiple prerequisites per course
Validate all prerequisites during enrollment
Schedule Management:
Track course meeting days and times
Store classroom locations
Prevent scheduling conflicts during enrollment
Professor Management:
Store professor information (ID, name, department)
Track which professor teaches which courses
Track professor teaching history
 

Database Constraints:

Added constraints to the courses table to ensure that the class capacity is less than or equal to 25 students
Ensured valid meeting times (no courses scheduled outside of 8:00 AM - 10:00 PM)
Prevented scheduling conflicts for both students and professors
Used at least 5 course names provided by Computer Science (CS) department at MSU
Ensured proper foreign key relationships between all related table
 


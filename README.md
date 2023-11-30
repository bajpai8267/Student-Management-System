![image](https://github.com/bajpai8267/Student-Management-System/assets/86520419/9daad801-63d3-4ac9-86b6-0757c9986343)


# Student Record Management System

This is a simple student record management system built in Java with a MySQL database. It can be used by schools and colleges to manage student data.

## Features

- Add new students
- Edit/update existing student details
- Remove students
- View all students
- Search students by name or ID
- View academic scores and grades
- Generate marksheets
- Generate transcripts

### Setup

1. Import the SQL script `schema.sql` to create the database schema. Modify credentials if needed.
2. Open the Java project in your IDE like Eclipse.
3. Modify the DB connection settings in `src/resources/db.properties` if needed.
4. Build and run the project. The main class is `Main.java`.

The application will launch containing the user interface to add, edit, delete and search student records.

### Features

**Add Student**

Fill in the student details like name, class, roll no. etc and click 'Add' to add new student.

**Edit Student**  

Select a student from the table, modify details and click 'Update' to save changes. 

**Remove Student**

Select the student record(s) from table and click 'Remove' to delete students.

And more features for searching, viewing reports and grades etc.

## Database Schema

The MySQL schema design containing two tables is available in `schema.sql`.

**Students** - Contains student personal details
**Scores** - Contains academic score details for students

Let me know if you need any other details!

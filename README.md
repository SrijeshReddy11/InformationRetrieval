# Student and Classes Database Project

This project implements a database to store information about students and their classes. It includes the creation of tables, sample data, normalization in 3rd Normal Form (3NF), and database views.

## Database Schema

### Students Table

- `StudentID` (Primary Key)
- `FirstName`
- `LastName`
- `DormID` (Foreign Key)
- `RoomNumber`
- `Major`

### Dorms Table

- `DormID` (Primary Key)
- `DormName`

### Classes Table

- `ClassID` (Primary Key)
- `ClassName`
- `Location`
- `StartDate`
- `EndDate`
- `StudentGrade`
- `StudentID` (Foreign Key)

## SQL Files

- `schema.sql`: Contains table creation statements.
- `data.sql`: Includes sample data insertion statements.
- `views.sql`: Defines database views.

## Views

- **List of Students (`StudentList`):**
  - Lists all students.

- **List of Classes for Two Students (`ClassesForTwoStudents`):**
  - Displays classes for two specific students.

- **List of Every Student in Three Dorms (`StudentsInThreeDorms`):**
  - Shows details of students in three specified dorms.

## 3rd Normal Form (3NF)

- Tables are designed to adhere to 3rd Normal Form principles, minimizing data redundancy and ensuring data integrity.

## Database Diagram

- Use a database modeling tool or VS Code extension to visualize the relationships between tables.

## Usage

1. Open the project in Visual Studio Code.
2. Connect to the SQLite database file (`students.db`) using the SQLite extension.
3. Execute SQL queries to interact with the database.

## Git Repository

- The project is version-controlled using Git.
- `.gitignore` file is set up to exclude unnecessary files from version control.

## Contributing

Feel free to contribute by opening issues or submitting pull requests.



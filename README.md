# University Management System

## Overview
This is a Python-based College Management System that allows users to create colleges, add students and teachers, display their details, and search for students or teachers using their roll numbers.

## Features
- Create a college
- Add students and teachers to a specific college
- Display students and teachers of a college
- Search for a student or teacher using their roll number
- Prevent duplicate college creation
- Simple text-based menu for user interaction

## Technologies Used
- Python

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/college-management-system.git
   ```
2. Navigate to the project directory:
   ```sh
   cd college-management-system
   ```
3. Run the script:
   ```sh
   python college_management.py
   ```

## Usage
After running the script, you will see a menu with options. Select an option by entering the corresponding number:

1. **Create College** - Enter the name of the college. If it already exists, an error message will be displayed.
2. **Add Student** - Enter the college name, roll number, name, and branch of the student.
3. **Add Teacher** - Enter the college name, roll number, name, and subject of the teacher.
4. **Display Students** - Enter the college name to view all students.
5. **Display Teachers** - Enter the college name to view all teachers.
6. **Search Student by Roll No.** - Enter a roll number to search for a student across all colleges.
7. **Search Teacher by Roll No.** - Enter a roll number to search for a teacher across all colleges.
8. **Exit** - Exit the program.

## Example
```sh
Choose the Required option:
1. Create College.
2. Add Student.
3. Add Teacher.
4. Display Students.
5. Display Teachers.
6. Search Student by Roll No.
7. Search Teacher by Roll No.
8. Exit.
Enter your Option: 1
Enter College Name: XYZ College
College Added Successfully
```



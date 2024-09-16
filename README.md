# Report Card Management System

This is a simple C++ console application that manages student report cards. The system allows users to perform operations like creating a student record, displaying all student records, searching, modifying, and deleting specific student records. It also provides a menu to display the report card of individual students or the entire class result.

## Features

- **Create a student record**: Add details such as roll number, name, and marks for five subjects (Physics, Chemistry, Maths, English, and Computer Science). The system automatically calculates the percentage and grade based on the marks entered.
- **Display all student records**: View all the stored student records.
- **Search for a student**: Search and display the report card of a specific student using their roll number.
- **Modify student records**: Update the details of an existing student.
- **Delete student records**: Remove the records of a student.
- **Class result**: Display the results of all students in a tabular format, showing roll number, name, marks in each subject, percentage, and grade.

## Project Structure

- `main.cpp`: The main source file that contains all the functionality of the report card management system.

## How to Run

1. **Compile the program**: Use any C++ compiler to compile the `main.cpp` file. For example, using g++:

    ```bash
    g++ main.cpp -o ReportCardSystem
    ```

2. **Run the executable**:

    ```bash
    ./ReportCardSystem
    ```

3. **Menu**: Once the program starts, you will see a main menu with the following options:
    - 1: Result Menu (to view class result or individual report card)
    - 2: Entry/Edit Menu (to create, search, modify, or delete student records)
    - 3: Exit

## File Handling

The student records are saved in a binary file (`student.dat`). The following file operations are supported:
- Write records to the file (`write_student`).
- Read all records from the file (`display_all`).
- Search for a specific record (`display_sp`).
- Modify a record (`modify_student`).
- Delete a record (`delete_student`).

## Grading System

- **A**: 60% and above
- **B**: 50% to 59%
- **C**: 33% to 49%
- **F**: Below 33%


## License

This project is open-source and available for educational purposes.


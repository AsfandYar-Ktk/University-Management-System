# University Management System

## Overview
The **University Management System** is a C++ program designed to manage student records for undergraduate and postgraduate students. It includes functionalities for adding, deleting, searching, and displaying student information, as well as managing fee status and academic performance.

## Features
### **Postgraduate Student Management**
- **Admit New Students**: Add a new postgraduate student with details like name, gender, DOB, GPA, subjects taken, and fee status.
- **Delete Student Records**: Remove a student from the postgraduate batch using their enrollment number.
- **Search Student**: Find a student using their enrollment number or fee status.
- **Display Students**:
  - View details of all postgraduate students.
  - Display students with unpaid fees.
  - Show top-performing students based on GPA.

### **Accounts Management**
- **Increase Salaries**: Update the salary of teachers and heads of departments.
- **Delete Students**:
  - Remove individual undergraduate/postgraduate students.
  - Delete all students with unpaid fees.
- **View Financial Data**:
  - Display all unpaid students (both UG and PG).
  - Show top-performing students.

## Classes & Functions
### **Post_Graduate Class**
- `Admit_New_PG_Student(...)` - Adds a new postgraduate student.
- `delete_PG_Student_data(int enroll)` - Removes a postgraduate student.
- `search_PG_Student_by_Enroll(int Enroll)` - Finds a student using enrollment number.
- `search_PG_Student_by_Unpaid()` - Finds the first unpaid student.
- `Get_no_of_unpaid_PG()` - Returns the number of unpaid students.
- `Disp_PG_Top()` - Displays the top three postgraduate students.
- `Disp_Single_PG_Student(int enroll)` - Shows details of a specific student.
- `Display_PG()` - Displays all postgraduate students.

### **Accounts_Office Class**
- `Increase_HOD_salary(Head_Of_Dept, float)` - Increases HOD salary.
- `Increase_Teacher_Salary(Head_Of_Dept, Teacher, float)` - Increases teacher salary.
- `Del_UG_Students(int)` - Deletes an undergraduate student.
- `Del_PG_Students(int)` - Deletes a postgraduate student.
- `Delete_all_Unpaid_UG()` - Deletes all unpaid undergraduate students.
- `Delete_all_Unpaid_PG()` - Deletes all unpaid postgraduate students.
- `Display_UG_Toppers()` - Shows undergraduate toppers.
- `Display_PG_Toppers()` - Shows postgraduate toppers.
- `Display_all_unpaid_UG()` - Displays all unpaid undergraduate students.
- `Display_all_unpaid_PG()` - Displays all unpaid postgraduate students.

AND MUCH MORE !!

## Usage
1. **Compile the program** using a C++ compiler (e.g., g++):
   ```sh
   g++ main.cpp -o student_management
   ```
2. **Run the program**:
   ```sh
   ./student_management
   ```
3. **Follow on-screen prompts** to add, delete, or search student records.

## Dependencies
- Standard C++ libraries (`iostream`, `iomanip`, `string`, `cstdlib`, `ctime`)

## Future Enhancements
- Implement a GUI for better user experience.
- Add file handling for persistent data storage.
- Improve search efficiency using hash maps.


## Author
Developed by Muhammad Asfand Yar & Muhammad Uzair


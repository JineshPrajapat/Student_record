                "# Student record management system using file handling" 

This is a C++ program that creates a menu-driven student record management system using file handling. The program uses a class named "student" to store and manipulate the data of the students.

The "student" class contains private variables such as rollno, name, DBMS_marks, math_marks, cprogramming_marks, python_marks, DCN_marks, percentage, and grade. The class also contains public member functions such as getdata(), showdata(), calculate(), and retrollno().

The function getdata() is used to input the data of the students such as roll number, name, and marks in various subjects.The function calculate() is used to calculate the percentage and grade of the student based on the marks obtained in different subjects. The function showdata() is used to display the data of the students along with their percentage and grade. The function retrollno() returns the roll number of the student.

The program uses file handling to store and retrieve the student data. The function create_student() is used to create a new student record and write it to the file "Student.dat". The function display_all() is used to read all the student records from the file and display them on the console. The function display_p(int n) is used to read a particular student record from the file based on the roll number and display it on the console. The function change_student_record(int n) is used to modify a particular student record based on the roll number. The function delete_student(int n) is used to delete a particular student record based on the roll number.

The main function of the program is menu-driven, and the user can select various options such as creating a new student record, displaying all the student records, searching for a particular student record based on the roll number, modifying a particular student record based on the roll number, and deleting a particular student record based on the roll number. The program uses the system("cls") function to clear the console screen after each option is selected.

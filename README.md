# Student Management Program

## Overview
This project implements a simple `Student` class in C++ that stores a student's basic information, including name, roll number, and three subject grades. The program calculates and displays the average grade of the student.

## Features
- Stores student details (name, roll number, and grades).
- Displays student information.
- Calculates and prints the student's average grade.

## File Structure
- `Student.cpp`: Contains the implementation of the `Student` class and a main function to demonstrate its usage.

## Usage
### Compilation
To compile the program, use a C++ compiler such as g++:
```sh
 g++ Student.cpp -o student
```

### Execution
Run the compiled executable:
```sh
 ./student
```

## Example Output
```
Name: John Doe
Roll Number: 101
Average Grade: 88.0
```

## Class Details
### `Student` Class
#### Attributes:
- `std::string name`: Stores the student's name.
- `int rollNumber`: Stores the student's roll number.
- `double grade1, grade2, grade3`: Stores the student's grades.

#### Methods:
- `Student(const std::string&, int, double, double, double)`: Constructor to initialize student details.
- `void displayDetails() const`: Displays the student's name and roll number.
- `double calculateAverage() const`: Calculates and returns the average grade.

## Dependencies
- C++11 or later

## Author
Parthiv Reddy Y

## License
This project is open-source and available under the MIT License.

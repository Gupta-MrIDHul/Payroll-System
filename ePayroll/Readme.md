**Employee Payroll System**
**Overview**
This Java project implements an employee payroll system using object-oriented programming principles, such as abstraction, encapsulation, inheritance, and polymorphism. The system manages employee information and calculates salaries for both full-time and part-time employees.

**Features**
Abstraction: The Employee class is an abstract class that provides a blueprint for other employee types.

Encapsulation: Employee details are protected using private fields and public getter methods.

Inheritance: FullTimeEmployee and PartTimeEmployee classes inherit from the Employee class.

Polymorphism: The calculateSalary method is overridden in the subclasses to provide specific implementations for different employee types.

**Classes**
Employee
An abstract class that represents a general employee.

Fields:

name: The name of the employee.

id: The ID of the employee.

Methods:

getName(): Returns the name of the employee.

getId(): Returns the ID of the employee.

calculateSalary(): Abstract method to be implemented by subclasses.

toString(): Returns a string representation of the employee.

FullTimeEmployee
A class that represents a full-time employee, inheriting from Employee.

Fields:

monthlySalary: The monthly salary of the employee.

Methods:

calculateSalary(): Returns the monthly salary.

PartTimeEmployee
A class that represents a part-time employee, inheriting from Employee.

Fields:

hoursWorked: The number of hours worked.

hourlyRate: The rate per hour.

Methods:

calculateSalary(): Calculates the salary based on hours worked and hourly rate.

PayRollSystem
A class that manages the list of employees and their details.

Fields:

employeeList: An array list of employees.

Methods:

addEmployee(Employee employee): Adds an employee to the list.

removeEmployee(int id): Removes an employee by ID.

displayEmployees(): Displays the details of all employees.

Usage
To use the payroll system, create instances of FullTimeEmployee and PartTimeEmployee, add them to the PayRollSystem, and perform operations like displaying employee details and removing employees.

Getting Started
Clone the repository.

Compile the Java files.

Run the Main class to see the payroll system in action.

License
This project is licensed under the MIT License.

# Departments

## Vision

“Departments” is a web application that allows users to record information about employees and departments.

The application should provide:

* Storing departments and employees in the database;
* Display list of departments;
* Updating the list of departments(adding, editing, removing);
* Display list of employees;
* Updating the list of employees(adding, editing, removing);


## 1. Employees
### 1.1 Display list of Employees

The mode is designed to view the list of employees if it is possible to display the number of employees for 
specified period.

#### Main scenario:

* User selects an item "Employees";
* Application display list of Employees.

Pic. 1.1 View the Employees list.

the list displays the following columns:

* Id - identification of employee;
* Employee Full Name - first name and last name of the employee;
* Department - department, where employees work;
* Birthdate - date of employee birth;
* Salary - employee's salary; 

![image](./screenshots/Employee_table.png?raw=true)


### 1.2 Add Employee

#### Main scenario:

* The user clicks the "Add" button in the employee's list view mode;
* Application displays form to enter employee's data;
* The user enters employee's data and presses the "Save" button;
* If any data is entered incorrectly, the incorrect data message is displayed;
* If entered data is valid, then the record is added to the database;
* If a new employee record is successfully added, then the list of employees with added records is displayed.

![image](./screenshots/adding_empl.png?raw=true)

#### Cancel operation scenario:

* The user clicks the "Add" button in the employee's list view mode;
* Application displays form to enter employee's data;
* User enters employee's data and presses the "Cancel" button;
* Data don't save in database, then the list of employees records is displaying to a user.

When adding an employee, the following details are entered:

* Id - identification of employee;
* Employee Full Name - first name and last name of the employee;
* Department - department, where employees work;
* Birthdate - date of employee birth;
* Salary - employee's salary;

### 1.2 Edit the employee

#### Main scenario:

* The user, while in the list of employees, clicks the "Edit" button in the selected Employee line;
* Application displays form to enter employee's data;
* User enters employee's data and presses "Save" button;
* If any data is entered incorrectly, an incorrect data message is displayed;
* If entered data is valid, then edited is adding to the database;
* If employee record is successfully edited, then the list of employees with added records is displayed.

![image](./screenshots/editing_empl1.png?raw=true)

#### Cancel operation scenario:

* The user, while in the list of employees, click the "Edit" button in the selected Employee line;
* Application displays form to enter employee's data;
* User enters employee's data and presses the "Cancel" button;
* Data don't save in database, then the list of employees records is displaying to a user.

When editing an employee, the following details are entered:

* Id - identification of employee;
* Employee Full Name - first name and last name of the employee;
* Department - department, where an employee works;
* Birthdate - date of employee birth;
* Salary - employees salary;

Constraints for data validation:
* Id - maximum length of 4 digits;
* Employee Full Name - maximum length of 60 characters;
* Department - maximum length of 45 characters;
* Birth date - date in format dd/mm/yy;
* Salary - maximum length of 8 digits.

### 1.4 Removing the employee

#### Main scenario:

* User, while in the list of employees, click the "Delete" button in the selected Employee line;
* Record is deleted from the database;
* If an employee record is successfully deleted, then the list of employees with deleted records is displayed.

***

## 2. Departments
### 2.1 Display list of Departments

The mod is designed to view the list of departments if it is possible to display the number of departments for 
specified period.

#### Main scenario:

* User select item "Departments";
* Application display list of Departments.

the list displays the following columns:

* Id - identification of department;
* Name of Department - the name of the department;
* Employees number - number of employees in this department;
* Average salary - average salary of employees in this department;

![image](./screenshots/Department_table.png?raw=true)

### 1.2 Add Department

#### Main scenario:

* The user clicks the "Add" button in the department's list view mode;
* Application displays form to enter department's data;
* The user enters the department's data and presses the "Save" button;
* If any data is entered incorrectly, an incorrect data message is displayed;
* If entered data is valid, then the record is added to the database;
* If a new department record is successfully added, then the list of departments with added records is displayed.

![image](./screenshots/adding_dep.png?raw=true)

#### Cancel operation scenario:

* The user clicks the "Add" button in departments list view mode;
* Application displays form to enter department's data;
* The user enters the department's data and presses the "Cancel" button;
* Data don't save in database, then the list of departments records is displaying to a user.

When adding a department, the following details are entered:

* Name of Department - the name of the department;

### 2.2 Edit the department

#### Main scenario:

* The user, while in the list of departments, click the "Edit" button in the selected department line;
* Application displays form to enter department's data;
* The user enters the department's data and presses the "Save" button;
* If any data is entered incorrectly, an incorrect data message is displayed;
* If entered data is valid, then edited is adding to the database;
* If the department's record is successfully edited, then the list of departments with added records is displayed.

![image](./screenshots/editing_dep.png?raw=true)

#### Cancel operation scenario:

* The user, while in the list of departments, click the "Edit" button in the selected department line;
* Application displays form to enter department's data;
* The user enters the department's data and presses the "Cancel" button;
* Data don't save in database, then the list of department records is displaying to a user.

Pic. 2.3 Edit department.

When editing a department, the following details are entered:

* Name of Department - the name of the department;

Constraints for data validation:
* Name of Department - maximum length of 45 characters;

### 1.4 Removing the department

#### Main scenario:

* The user, while in the list of departments, click the "Delete" button in the selected department line;
* Record is deleted from the database;
* If the department record is successfully deleted, then the list of departments without deleted records is displayed.


## Software

## 1. Technologoes

* Python
  * Django
* MySQL
* HTML
* CSS

### 1.2 Framework

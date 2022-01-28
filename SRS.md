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

The mode is designed to view the list of employees.

#### Main scenario:

* User selects an item "Employees";
* Application display list of Employees.

the list displays the following columns:

* Id - identifier of employee;
* Employee Full Name - first name and last name of the employee;
* Department - department, where employee works;
* Birthdate - date of employee birth;
* Salary - employee's salary; 

![image](./screenshots/Employee_table.png?raw=true)


### 1.2 Add Employee

#### Main scenario:

* The user clicks the "Add" button in the employee's list view mode;
* Application displays form to enter employee's data;
* The user enters employee's data and presses the "Save" button;
* If any data is entered incorrectly, the "Incorrect Data" message is displayed. You should enter correct data and press the "Save" button or press the "Cancel" button;
* If entered data is valid, then the record is added to the database;
* The list of employees with added records is displayed.

![image](./screenshots/adding_empl.png?raw=true)

#### Cancel operation scenario:

* The user clicks the "Add" button in the employee's list view mode;
* Application displays form to enter employee's data;
* User enters employee's data and presses the "Cancel" button;
* Data isn't saved in database, then the list of employees records is displayed to a user.

When adding an employee, the following details are entered:

* Id - identifier of employee;
* Employee Full Name - first name and last name of the employee;
* Department - department, where employee works;
* Birthdate - date of employee birth;
* Salary - employee's salary;

### 1.2 Edit the employee

#### Main scenario:

* The user, while in the list of employees, clicks the "Edit" button in the selected Employee line;
* Application displays form to enter employee's data;
* User enters employee's data and presses "Save" button;
* If any data is entered incorrectly, the "Incorrect Data" message is displayed. You should enter correct data and press the "Save" button or press the "Cancel" button;
* If entered data is valid, then the corrected records replace the corresponding entries in the database;
* The list of employees with edited record is displayed.

![image](./screenshots/editing_empl1.png?raw=true)

#### Cancel operation scenario:

* The user, while in the list of employees, click the "Edit" button in the selected Employee line;
* Application displays form to enter employee's data;
* User enters employee's data and presses the "Cancel" button;
* Data isn't saved in database, then the list of employees records is displayed to a user.

When editing an employee, the following details are entered:

* Id - identifier of employee;
* Employee Full Name - first name and last name of the employee;
* Department - department, where employee works;
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

* The user, while in the list of employees, click the "Delete" button in the selected Employee line;
* Record is deleted from the database;
* The list of employees without deleted record is displayed.

### 1.5 Filtering employees by date

#### Main scenario:

* The user clicks the "Filter by date" button in the employee's list view mode;
* Application displays form to enter two dates;
* The user enters dates and presses the "Filter" button;
* If any data is entered incorrectly, the "Incorrect Data" message is displayed. You should enter correct data and press the "Save" button or press the "Cancel" button;
* If entered data is valid, then records with field "Birth date" from the interval between these two dates are displayed;
* After manipulations with these records the user clicks the "Back" button.
* Application displayslist of Employees.

![image](./screenshots/Filter_empl.png?raw=true)

#### Cancel operation scenario:

* The user clicks the "Filter by date" button in the employee's list view mode;
* Application displays form to enter two dates;
* The user clicks the "Back" button.
* Application displays list of Employees.

### 1.6 Finding employees by date

#### Main scenario:

* The user clicks the "Find by date" button in the employee's list view mode;
* Application displays form to enter date;
* The user enters date and presses the "Find" button;
* If any data is entered incorrectly, the "Incorrect Data" message is displayed. You should enter correct data and press the "Save" button or press the "Cancel" button;
* If entered data is valid, then records with field "Birth date" equal to this date are displayed;
* After manipulations with these records the user clicks the "Back" button.
* Application displayslist of Employees.

![image](./screenshots/Find_empl.png?raw=true)

#### Cancel operation scenario:

* The user clicks the "Find by date" button in the employee's list view mode;
* Application displays form to enter date;
* The user clicks the "Back" button.
* Application displays list of Employees.

***

## 2. Departments
### 2.1 Display list of Departments

The mode is designed to view the list of departments.

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
* If any data is entered incorrectly, the "Incorrect Data" message is displayed. You should enter correct data and press the "Save" button or press the "Cancel" button;
* If entered data is valid, then the record is added to the database;
* The list of departments with added record is displayed.

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
* If any data is entered incorrectly, the "Incorrect Data" message is displayed. You should enter correct data and press the "Save" button or press the "Cancel" button;
* If entered data is valid, then the corrected records replace the corresponding entries in the database;
* The list of departments with edited record is displayed.

![image](./screenshots/editing_dep.png?raw=true)

#### Cancel operation scenario:

* The user, while in the list of departments, click the "Edit" button in the selected department line;
* Application displays form to enter department's data;
* The user enters the department's data and presses the "Cancel" button;
* Data don't save in database, then the list of department records is displaying to a user.

When editing a department, the following details are entered:

* Name of Department - the name of the department;

Constraints for data validation:
* Name of Department - maximum length of 45 characters;

### 1.4 Removing the department

#### Main scenario:

* The user, while in the list of departments, click the "Delete" button in the selected department line;
* Record is deleted from the database;
* Employees, attached to this department are deleted;
* The list of departments without deleted records is displayed.


## Software

## 1. Technologoes

* Python
  * Django
* MySQL
* HTML
* CSS

## 2. User Software Requirements

This application is supported on all types of browsers, including their outdated versions. 

## Hardware

## 1. User Hardware Reqirements

This application is supported on all types of devices, with different screen resolutions. This is possible thanks to adaptive layout.

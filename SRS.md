# Departments

## Vision

“Departments” is web-application witch allows users to record information about employees and departments.

Application should provide:

* Storing departments and employees in database;
* Display list of departments;
* Updating the list of departments(adding, editing, removing);
* Display list of employees;
* Updating the list of employees(adding, editing, removing);
* Filtering by birth date for employees;
* Filtering by employees number for departments.

## 1. Employees
### 1.1 Disploy list of Employees

The mod is designed to view the list of employees, if it possible to display the number of employees for 
specified period of time.

#### Main scenario:

* User select item "Employees";
* Application display list of Employees.

! ! ! danger "table"
123

Pic. 1.1 View the Employees list.

the list display the following columns:

* First name - first name of employee;
* Last name - last name of employee;
* Department - department, where employee work;
* Birth date - date of employee birth;
* Salary - employees salary; 


### 1.2 Add Employee

#### Main scenario:

* User click the "Add" button in the order list view mode;
* Application displays form to enter order data;
* User enters employees data and press "Save" button;
* If any data is entred incorrectly, incorrect data massage are displayed;
* if entered data is valid, then record is adding to database;
* if error occurs, then error massage displaying;
* if new order record is successfully added, then list of employees with added records is displaying.

#### Cancel operation scenario:

* User click the "Add" button in the order list view mode;
* Application displays form to enter order data;
* User enters employees data and press "Save" button;
* Data don't save in database, then list of employees resords is displaying to user.
* If the user select the menu item "Employees" or "Departments", the data will not be saved to the database and the corresponding form with updated data will be opend.


Pic. 1.2. Add employee

When adding a employee, the following details are entred:

* First name - first name of employee;
* Last name - last name of employee;
* Department - department, where employee work;
* Birth date - date of employee birth;
* Salary - employees salary; 




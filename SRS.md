# Departments

## Vision

“Departments” is web-application witch allows users to record information about employees and departments.

Application should provide:

* Storing departments and employees in database;
* Display list of departments;
* Updating the list of departments(adding, editing, removing);
* Display list of employees;
* Updating the list of employees(adding, editing, removing);


## 1. Employees
### 1.1 Display list of Employees

The mod is designed to view the list of employees, if it possible to display the number of employees for 
specified period of time.

#### Main scenario:

* User select item "Employees";
* Application display list of Employees.

Pic. 1.1 View the Employees list.

the list display the following columns:

* First name - first name of employee;
* Last name - last name of employee;
* Department - department, where employee work;
* Birth date - date of employee birth;
* Salary - employees salary; 


### 1.2 Add Employee

#### Main scenario:

* User click the "Add" button in the employees list view mode;
* Application displays form to enter employees data;
* User enters employees data and press "Save" button;
* If any data is entred incorrectly, incorrect data massage are displayed;
* if entered data is valid, then record is added to database;
* if error occurs, then error massage displaying;
* if new employee record is successfully added, then list of employees with added records is displaying.

#### Cancel operation scenario:

* User click the "Add" button in the employees list view mode;
* Application displays form to enter employees data;
* User enters employees data and press "Cancel" button;
* Data don't save in database, then list of employees resords is displaying to user.
* If the user select the menu item "Employees" or "Departments", the data will not be saved to the database and the corresponding form with updated data will be opend.


When adding a employee, the following details are entred:

* First name - first name of employee;
* Last name - last name of employee;
* Department - department, where employee work;
* Birth date - date of employee birth;
* Salary - employees salary; 

### 1.2 Edit the employee

#### Main scenario:

* The user, while in the list of employees, click the "Edit" button in selected Emloyee line;
* Application displays form to enter employee data;
* User enters employees data and press "Save" button;
* If any data is entred incorrectly, incorrect data massage are displayed;
* if entered data is valid, then edited is adding to database;
* if error occurs, then error massage displaying;
* if employee record is successfully edited, then list of employees with added records is displaying.


#### Cancel operation scenario:

* The user, while in the list of employees, click the "Edit" button in selected Emloyee line;
* Application displays form to enter employee data;
* User enters employees data and press "Cancel" button;
* Data don't save in database, then list of employees resords is displaying to user.
* If the user select the menu item "Employees" or "Departments", the data will not be saved to the database and the corresponding form with updated data will be opend.


When editing a employee, the following details are entred:

* First name - first name of employee;
* Last name - last name of employee;
* Department - department, where employee work;
* Birth date - date of employee birth;
* Salary - employees salary.

Constraints for data validation:
* First name - maximum length of 45 characters;
* Last name - maximum length of 45 characters;
* Department - maximum length of 45 characters;
* Birth date - date in format dd/mm/yy;
* Salary - maximum length of 8 digits.

### 1.4 Removing the employee

#### Main scenario:

* User, while in the list of employees, click the "Delete" button in selected Emloyee line;
* If the order can be removed, a confirmation dialog is displayed;
* User confirms the removal of the order;
* Record is deleted from database;
* If error occurs, then error message displays;
* if employee record is successfully deleted, then list of employees with deleted records is displaying.

#### Cancel operation scenario:

* User, while in the list of employees, click the "Delete" button in selected emloyee line;
* If the order can be removed, a confirmation dialog is displayed;
* User press "Cancel" button;
* List of employees without changes is displaying.



***

## 2. Departments
### 2.1 Display list of Departments

The mod is designed to view the list of departments, if it possible to display the number of departments for 
specified period of time.

#### Main scenario:

* User select item "Departments";
* Application display list of Departments.

the list display the following columns:

* Department - name of department;
* Employees number - number of employees in this department;


### 1.2 Add Department

#### Main scenario:

* User click the "Add" button in the department list view mode;
* Application displays form to enter department data;
* User enters employees data and press "Save" button;
* If any data is entred incorrectly, incorrect data massage are displayed;
* if entered data is valid, then record is added to database;
* if error occurs, then error massage displaying;
* if new department record is successfully added, then list of department with added records is displaying.

#### Cancel operation scenario:

* User click the "Add" button in the department list view mode;
* Application displays form to enter department data;
* User enters department data and press "Cancel" button;
* Data don't save in database, then list of department resords is displaying to user.
* If the user select the menu item "Employees" or "Departments", the data will not be saved to the database and the corresponding form with updated data will be opend.


When adding a employee, the following details are entred:

* Name - name of department;


### 2.2 Edit the department

#### Main scenario:

* The user, while in the list of department, click the "Edit" button in selected department line;
* Application displays form to enter department data;
* User enters department data and press "Save" button;
* If any data is entred incorrectly, incorrect data massage are displayed;
* if entered data is valid, then edited is adding to database;
* if error occurs, then error massage displaying;
* if department record is successfully edited, then list of department with added records is displaying.


#### Cancel operation scenario:

* The user, while in the list of employees, click the "Edit" button in selected department line;
* Application displays form to enter department data;
* User enters department data and press "Cancel" button;
* Data don't save in database, then list of department resords is displaying to user.
* If the user select the menu item "Employees" or "Departments", the data will not be saved to the database and the corresponding form with updated data will be opend.


Pic. 2.3 Edit department.

When editing a department, the following details are entred:

* Name - name of department;

Constraints for data validation:
* Name - maximum length of 45 characters;

### 1.4 Removing the department

#### Main scenario:

* User, while in the list of department, click the "Delete" button in selected department line;
* If the order can be removed, a confirmation dialog is displayed;
* User confirms the removal of the department;
* Record is deleted from database;
* If error occurs, then error message displays;
* if department record is successfully deleted, then list of department with deleted records is displaying.

#### Cancel operation scenario:

* User, while in the list of department, click the "Delete" button in selected department line;
* If the order can be removed, a confirmation dialog is displayed;
* User press "Cancel" button;
* List of departments without changes is displaying.

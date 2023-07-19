# POC

### Project Description:
This is a SpringBoot project. I used SpringBoot 3 for this project, even it is the new version of SpringBoot. In this project, I have three database tables. The first table is called employees_records, which is for storing the employees' records. The second table is called the administrator_recods, which stores the administrators records, including three different kinds of roles, with different accessibility of the employees_records table. The third table is for storing the administrators passwords. The passwords was using bcrypt method in order to protect the administrators password.

### The mapping for different methods
1. GET:
  (For GET by ID): /api/employees/{employeeId}
  (For GET ALL): /api/employees
2. POST: /api/employees
3. PUT: /api/employees
4. DELETE: /api/employees/{employeeId}

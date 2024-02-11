# Big Data Management Project

You're given an **unormalized** dataset `employees_data.csv` whose data is represented in the following diagram:

![Database Diagram](diagram.png)

Normalize the data in **3NF**. And provide the **diagram** of the database.

Use **Python** to connect to **PostgreSQL** and create the necessary tables in your new database `company`.

Answer the following questions using SQL, and provide the solution (answer in the `main.py` file):
1. How many projects are the IT, Marketing and HR departments working on?
2. How many projects are in progress, completed, or not started?
3. How many employees are there for each skill?
4. Which employees live in the postal code `08094`? Show only the employee names.
5. Which employees are currently assigned to specific projects? Show the employee name and project name.
6. Provide information about the projects related to the 'Mobile App Launch' initiative.
7. What skills are most in demand for the projects in progress?
8. How many employees have completed their projects, and how many are still in progress?
9. What is the distribution of project statuses within each department?
10. Find Employees with Programming Skills Working on In-Progress Projects. Show only the employee name, department, and project name.


# Extra
Explore how you would create a PostgreSQL database in Amazon Web Services (AWS). Remember that you can take advantage of a 1-year free account when registering!

Now, instead of connecting to your local PostgreSQL database, connect to the Amazon RDS PostgreSQL database hosted in AWS.

*Reference: https://aws.amazon.com/rds/postgresql/*

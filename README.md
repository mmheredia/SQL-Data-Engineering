# SQL Challenge

#### This SQL challenge dives into data modeling, engineering, and analysis skills. Employee data is pulled from Pewlett Hackard Corperation from the 1980s to the 1990s. Data sets are provided in CSV format. Databases were created using Postgres and tables were created before importing the CSV files to fill the tables. Once filled, analysis began.

### The overall task of this challenge, was to perform data modeling and data analysis for the following:

## Data Modeling
#### The challenge began by inspecting the CSV files located within the "Data" folder. An ERD was then created to visualize the connections between each table.

## Data Engineering
#### The schema of the six CSV files within the "Data " folder were then manipulated using PostreSQL within a pgAdmin platform. Using PostreSQL, primary keys, data types, and foreign keys were defined. Once tables were created and data types defined, the CSV files were imported to fill out the tables.

## Data Anlysis
#### The analysis was also performed using PostgreSQL within a pgAdmin platform. Analysis was performed by creating queries to extract information from the tables previously created in the database during the Data Engineering process. Anlysis was performed in the following eight steps:

#### 1. Step one included listing the following details of each employee: employee number, last name, first name, sex, and salary. (See image 1 within the "Output" file.)

#### 2. Step two included listing the first name, last name, and hire date for employees who were hired in 1986. (See image 2 within the "Output" file.)

#### 3. Step three included listing the the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name. (See image 3 within the "Output" file.)

#### 4. Step four included listing the  department of each employee with the following information: employee number, last name, first name, and department name. (See image 4 within the "Output" file.)

#### 5. Step five included listing the first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B." (See image 5 within the "Output" file.)

#### 6. Step six included listing all employees in the Sales department, including their employee number, last name, first name, and department name. (See image 6 within the "Output" file.)

#### 7. Step seven included listing all employees in the Sales and Development departments, including their employee number, last name, first name, and department name. (See image 7 within the "Output" file.)

#### 8. Step eight included listing in descending order, the frequency count of employee last names, i.e., how many employees share each last name. (See image 8 within the "Output" file.)

## Epilogue
#### The final step in the challenge was to search employee ID number 499942. After searching this employee ID number, the results returned a joke! The name of the employee was "April Foolsday!" (See image "epilogue" within the "Output" file.)
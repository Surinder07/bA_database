## Recap 

Agile  ? Meaning ? 
Scrum 
Jira 

Sprint ?  

2 weeks 

waterfall 

Sprint ceremonies 
1. Daily Standup 
15 mins - Status update 
what did I do yesterday 
what I am going to do today 
any blockers? 

2. Grooming 
3. Planning 
4. Retro 


Story points 
Task 1 
task 2 

fibonnacci   -- 1 2 3 5 8 13 ....


## Database 

what is Database ? 
stores the data.

1. Decisions based on data 
2. extract data for testing, data analysis
3. dashboards and analyse the trends 
4. Reports 



Environment ? 

dev             code --- Test        : www.dev.scotibank.com    [internal for devs]
QA                                     www.qa.scotibank.com
staging/pre prod                       www.staging.scotibank.com
production                             www.scotibank.com


requirement -------> feature developed



Database ? 
types 

1. cloud  - AWS, Azure, GCP  ---
2. sql
3. oracle 
4. mongo db
5. no sql 

AWS - RDS 


database 
1. SQL based                2. NO SQL 
MYSQL                           Mongo DB 
Oracle 
Postgres 


Relational database , DBMS 

- rows and columns 


#problem with  files based data 
- lost of data
- harder to maintain
- Search operation was difficult 
- accessibilty 


on premises             vs      Cloud  [AWS, GCP etc...]



## Relational 

Rows and Columns


MYSQL ---- database 
SQL -- structured query language 


Create data
Read data
Update data
Delete data

DDL - data defination Language   ------->  
DML- Data manipulation Language 
DCL - Data control language 



## SQL 

show databases ;

-- windows    control + enter
-- mac  command + enter


use Employee;
-- tables in the database
show tables;

-- fetch data from employee table
select * from EMPLOYEE;

select EMPLOYEE_ID, EMPLOYEE_NAME from EMPLOYEE;

-- I want to fetch employees with Name John
-- select * from table_name where column = '';
select * from EMPLOYEE where EMPLOYEE_NAME = 'John';

select EMPLOYEE_NAME, EMPLOYEE_ADDRESS from EMPLOYEE where EMPLOYEE_NAME = 'John';

-- find employees from Japan or Name as Sammy
select * from EMPLOYEE where EMPLOYEE_NAME = 'Sammy' OR EMPLOYEE_ADDRESS = 'Japan';


select * from EMPLOYEE where EMPLOYEE_NAME = 'John' AND EMPLOYEE_ADDRESS = 'Japan';

SELECT COUNT(EMPLOYEE_ADDRESS) FROM EMPLOYEE where EMPLOYEE_ADDRESS = 'Canada';
































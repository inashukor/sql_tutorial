# sql_tutorial
basic sql tutorial

BASIC SQL STATEMENTS
- create
1. create database

        create database test1
2. create table

        create table emp (
        emp_id int primary key,
        l_name varchar(50) not null,
        f_name varchar(50) not null,
        );
      
- alter table statements
syntax:
  ALTER TABLE <table_name> ADD <column_name><datatype>
  ALTER TABLE <table_name> DROP column <column_name>
  ALTER TABLE <table_name> ALTER COLUMN <column_name><datatype>
  
3. add column

         alter table emp add age int
  
4. drop  column
  
          alter table emp drop column age
  
5. alter column (chang datatype)
  
         alter table emp column f_name varchar(25)
  
  

- select
- insert
- update
- delete
- grant
- revoke
- commit
- rollback
- savepoint

        
CONSTRAINT => NOT NULL / UNIQUE / PRIMARY KEY / FOREIGN KEY / CHECK
        -we can add constraint after create table
                        
                   alter table emp
                    add constraint emp_pk PRIMARY KEY (emp_id)

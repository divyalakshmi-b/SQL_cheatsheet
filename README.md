# SQL_cheatsheet
1. [ Data Definition Language. ](#ddl)
2. [ Data Manipulation Language. ](#dml)

<a name="ddl"></a>
## 1. Data Definition Language Statements:
### CREATE 
<font size=”12”> 
CREATE TABLE Persons (<br>
    PersonID int, <br>
    LastName varchar(255), <br>
    FirstName varchar(255), <br>
    Address varchar(255), <br>
    City varchar(255) <br>
); </font><br>

### ALTER
ALTER TABLE Customers
ADD Email varchar(255); <br>

### DROP
DROP TABLE Shippers; <br>

### TRUNCATE
TRUNCATE TABLE Categories; <br>

<a name="dml"></a>
## 2. Data Manipulation Language Statements:
### INSERT 
INSERT INTO PERSONS VALUES( <br>
1, 'Steward','Mark','Block 4','NewYork') <br>

### UPDATE
UPDATE PERSONS set City='NY' where city='NewYork' <br>

### DELETE
DELETE FROM PERSONS WHERE ID=1; <br>

### SELECT
SELECT * FROM PERSONS



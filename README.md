# SQL-Python
Basic SQL commands with python
## Installation 
Firsly install the sql connector.
#### To install:
Enter this command in command prompt `python -m pip install mysql-connector`
## Connecting to your Database
Import the mysql.connector library
```python 
import mysql.connector
```
Connect to ypur Database by entering this code
```python 
mydb = mysql.connector.connect(
	host="Host name",
	user="Username",
	passwd="Password",
	database="Database name"
  )
```
## Basic SQL commands
#### There are 4 types of commands
---
##### 1. Data Definition Language Commands
(Commands for creating different objects as a part of a database, including the database itself.)
+ CREATE
+ ALTER
+ DROP
+ TRUNCATE
---
##### 2. Data Manipulating Language Commands
(Commands used to manage the data.)
+ INSERT
+ UPDATE
+ DELETE
---
##### 3. Data Query Language Commands 
(For retrieving the required data from the related database object(s).)
+ SELECT
---
##### 4. Data Control Language Commands
(Commands used to control access permissions.)
+ COMMIT
+ ROLLBACK
+ GRANT
+ DENY
+ SAVEPOINT
---
By using `python` we can execute all these commands

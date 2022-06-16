# Mysql 

 


**Drop:** drop query deletes the whole table from database, the will also get removed  
        DROP TABLE table_name; 


 &nbsp;

 
**Truncate:** Truncate query deletes the all data from table but not deletes the table itself. 

        TRUNCATE TABLE table_name; 
        

&nbsp;


**Delete:** Delete statement is used to delete records from table, 

- It will delete one record from table, if we dont use where clause then our all records will be removed

        DELETE FROM students
        WHERE roll=10;

- DELETE all records

        DELETE FROM students;

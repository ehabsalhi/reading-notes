> # Data Modeling 
>> ## [nosql vs sql](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)
>>
>> 1- What type of database is the best fit for the complex query intensive environment? SQL
>> 
>> 2-What type of database is the best fit for hierarchical data storage? NoSQL
>> 
>> 3- Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.
>> * SQL databases are vertically scalable whereas the NoSQL databases are horizontally scalable. SQL databases are scaled by increasing the horse-power of the hardware. NoSQL databases are scaled by increasing the databases servers in the pool of resources to reduce the load.
>
>> ## [sql modeling techniques](https://www.essentialsql.com/get-ready-to-learn-sql-7-simplified-data-modeling/)
>> 
>> 1- Among data tables, what is a one-to-many relationship and how do we “relate” them?
>> 
>> *  an entry in one table can be related to more than one entry in another.
>> 
>> 2- Prior to designing your relational database, it might be useful to ( create ) a ( diagrams ) of the database tables and their relationships.
>> 
>> 3- Explain the difference between a primary and foreign key. 
>> 
>> * A foreign key establishes a relationship between two tables in a database and it is a column or a set of columns in one table that refers to the primary key in another table establishing a relationship between the two tables.
>> * A primary key is a unique identifier for a record in a table,
>
>> ##  [sql vs nosql video](https://www.youtube.com/watch?v=ZS_kXvOeQ5Y&ab_channel=Academind)
>> 1- How do we treat keywords and parameters differently in SQL syntax?
>> * keywords have predefined meanings in SQL and are used to define the structure and actions of SQL statements like [ SELECT, INSERT, UPDATE, DELETE, CREATE ] .
>> * parameter represents a value to be supplied at runtime , and it used to handle user input .
>> 
>> 2- Define normalization within the context of schemas and data?
>> 
>> * Normalization helps to improve database performance, reduce data duplication, and enhance data integrity.
>> 
>> 3- Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter?
>> 
>> * one-to-one : its mean that one table belong an relate to only one table 
>> 
>> * one-to-many : its mean that one table belong to multiple users , or multiple users belong and relate to only one table it's like having a single source connected to multiple destinations.
>> 
>> * many-to-many : its mean that  multiple instances of one entity can be associated with multiple instances of another entity , for example we have students and courses each student can enroll in multiple courses and each course can has multiple students 
>
>> ## What are your learning goals after reading and reviewing[ the class README](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-04/)?
>> * Getting know more about database and its keywords and how to deal with them in the server side 
> 
>> ## why this topic matters as it relates to what you are studying in this module ?
>> * It's very important because when the student deal with the server he should know more about how to storing and secure the data , and what's the data that should be visible to the user

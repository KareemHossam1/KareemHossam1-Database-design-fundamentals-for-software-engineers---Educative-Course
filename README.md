# Database design fundamentals for software engineers - Educative Course
This repo contains some notes about Educative course "Database design fundamentals for software engineers".

Course link : https://www.educative.io/courses/database-design-fundamentals

## Lesson 2 – Fundamental concepts:
•	A database represents some aspect of the real world, sometimes called the mini-world or the universe of discourse (UoD). Changes to the mini-world are reflected in the database.

•	A database can be of any size and complexity.

•	Consider a database maintained by a social media company such as Twitter, which has millions of users. The database has to maintain information on which users are related to one another in the form of followers, the content posted by each user, and a large number of other types of information needed for the correct operation of their website. For such websites, a large number of databases are needed to keep track of the constantly changing information required by the social media website.

•	The primary goal of a DBMS is to provide an environment that is both convenient and efficient for users to retrieve and store information.

•	The DBMS is instrumental in facilitating the processes:
1-	Defining a database involves defining the data types, structures, and constraints of the data to be stored in the database.
2-	Constructing the database is the process of storing the data on a storage device that is controlled by the DBMS.
3-	Manipulating a database involves querying the database to retrieve specific data, updating the database, etc.
4-	Sharing a database allows multiple users and programs to access the database simultaneously.

•	Each row in a relational database represents one instance of the type of object described in that table. A row is also called a **record**. While the columns in a table are the set of facts that we keep track of regarding that type of object. A column is also called an **attribute**.

•	A database system is self-describing because it not only contains the database itself, but also the meta-data which defines and describes the data and relationships between tables in the database. This information is stored in a catalog by the DBMS software. The separation of data and information about the data makes the database system different from the traditional file-based system in which the data definition is part of the application programs.

•	Let’s consider a university database example. The DBMS catalog will store the definitions of all the tables in that database. The figure below shows part of the database catalog:
 
   ![image](https://user-images.githubusercontent.com/56439775/163714579-97e03d86-e90c-4042-a465-b06eaab991fa.png)

 
•	In the file-based system, the structure of the data files is defined in the application programs so if a user wants to change the structure of a file, all the programs that access that file might need to be changed as well.
On the other hand, in the database approach, the data structure is stored in the system catalog and not in the programs. Therefore, one change is all that is needed to change the structure of a file. This insulation between the programs and data is also called program-data independence.

•	A database supports multiple views of data. A view is a subset of the database, which is defined and dedicated for particular users of the system. Multiple users in the system might have different views of the system. Each view might contain only the data of interest to a user or group of users.

## Dev Post 4

##### Author: Michael Pierce

###### Date: 1 March 2022

#### __Databases__

With the growing need to store large amounts of data, databases must be highly effective at what they are designed to do. There is a large variety of different databases. Some of the most commonly used include:

+ Hierarchical databases
+ Network databases
+ Object-Oriented databases
+ Relational databases
+ NoSQL databases

##### __Hierarchical Databases__

In hierarchical databases the data is organized into ranks or levels, where data is categorized based on a common linkage point. Using a university database as an example, students and faculty would be stored in a lower rank, and departments would be stored a level higher since they share that commonality. A higher ranked table can have multiple lower ranked tables, but not the other way around. It is difficult to add data to these types of databases since it requires such a lengthy traversal though tables.

##### __Network Databases__

A network database is a hierarchial database, but the child records can be associated with multiple parent records. Using the university database from the previous example, a student would be able to be linked with both the department and with another higher level record, such as a club. Unfortunately with network databases, it is difficult and often impossible to alter the database structure due to its complexity.

##### __Object-Oriented Databases__

If you're familiar with Object-Oriented Programming, this database structure is easy to relate with. Information stored is represented as objects, with each object having data linked to it. For example, the university is made up of people. There are students and there are faculty. A person may have a name and identification number, and the person table can be linked through relationships to other tables, such as student and faculty. A student may have a GPA and a professor may have a salary. Querying this style database is quick and efficent.

##### __Relational Databases__

Relational databases are considered to be the most mature and are the most used in production. In these style databases, every piece of information has a relationship with every other piece of information. They are used in Web-Ap interfaces to serve as a repository for user data. You can use SQL to interact with it, and is easy to understand. It is also easy to scale and traverse the database when compared to hierarchical databases.

##### __NoSQL__

NoSQL databases are simple in design. They use different data structures than those used in a default relational database and can often run faster. It is only suitable in some sitations, however. It is easy to scale, but has some major drawbacks. The biggest drawback is having a large document size. They also lack a GUI, so interacting with them can be more cumbersome. The most popular NoSQL databases include MongoDB and Cassandra.

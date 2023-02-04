# DBMS

[SQL COMMAND.pdf](https://github.com/alokmotion/DBMS/files/10428692/SQL.COMMAND.pdf)

<h1> Key In DBMS </h1>'

<h2> Key </h2>

<p> A key is an attribute or set of attributes that helps in uniquely identifying a record from a table. </p>
<p> it's also used to establish and identify relationships between tables </p>

![image](https://user-images.githubusercontent.com/95286756/213628065-2d16dc69-65a8-4cb1-92ee-63ef179aa551.png)


<h2> Why do we need Keys? </h2>


<p> 
1. Keys are used to establish and identify relationships between tables/relations. <br>
2. They uniquely identify any record/row inside a table/relation. <br>
3. They also ensure that data integrity is maintained. <br>
  
  </p>
  
  
  <h2> Types of Keys ? </h2>
  
  <p> 
1. Super Key ---> If a set of one or more attributes can uniquely identify the entities of an entity set, then it is called a super key. <br>
2. Candidate Key ---> Candidate keys are selected from a set of super keys. If a super key has no unnecessary attributes, then such a minimal super key is called a candidate key. <br>
3. Primary Key --->   Primary keys are selected from a set of candidate keys. It is a candidate key selected by the database designer to uniquely identify the records of a table.  <br>

The primary key field of a table must be unique and cannot be null.  <br>
A table does not contain more than one primary key. <br>

4. Alternate Key  --->  If a candidate key is not selected as a primary key then it is called an alternate key. 
<br>
 
5. Foreign Key --->  A foreign key is the one that is used to link two tables together via the primary key. It means the columns of one table points to the primary key attribute of the other table. <br>
 
 </P>
 
 
 <hr>
 <h2> Normalization </h2>
 
 <p>
 Normalization is the process of minimizing redundancy from a relation or set of relations.
 
 </p>
 
 ---------------------------------------------------------------------------
 <hr>
 <h5> SQL </h5>
  <P> 
 1. WAQ to bring all data from Customers Table.  </P>


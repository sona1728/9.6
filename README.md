Q1.Explain about the different complex data types in pig. Ans: The different complex data types in pig are : 1)Atom -Any single value in Pig Latin, irrespective of their data or type is known as an Atom. -It is stored as bytearray by default and can be used as string or number like int, long,float, double, chararray, and bytearray are the atomic values of Pig. -Example − ‘abcd’ or ‘15’

2)Tuple -A record that is formed by an ordered set of fields is known as a tuple, the fields can be of any type. -Example − (abcd, 15)

3)Bag -A bag is an unordered set of tuples. -A bag is represented by ‘{}’. -Example − {(abcd, 15), (xyzw, 30)}

4)Map -A map (or data map) is a set of key-value pairs. -The key needs to be of type chararray and should be unique. -The value might be of any type. It is represented by ‘[]’ -Example: [name#abcd,age#15]

5)Relation -A relation is an outer bag of tuples.

Q2.How can you interact with the shell in Apache pig 
Ans: -Through Grunt shell,one can communicate with the pig engine.
-The Grunt shell of Apache Pig is mainly used to write Pig Latin scripts.
-After invoking the Grunt shell, you can run your Pig scripts in the shell.
-There are certain useful shell and utility commands provided by the Grunt shell.

Q3.Explain how pig differs from Map reduce. 
Ans: Pig differs from MapReduce by the following points:
1)1/20 lines of code are needed than that map reduce.
2)People of non-programming background can also use pig easily.
3)Map reduce takes more time to construct the code.
4)Less complex codes to type. 
5)Many built in functions.
6)Easy to learn pig latin than that of Java.

Q4.Explain how pig differs from sql. 
Ans:
-In SQL, when users want to do several data operations together, they must either write separate queries, storing the intermediate data into temporary tables, or write it in one query using subqueries inside that query to do the earlier steps of the processing.
-Pig, however, is designed with a long series of data operations in mind, so there is no need to write the data pipeline in an inverted set of subqueries or to worry about storing data in temporary tables.
-SQL is designed for the RDBMS environment, where data is normalized and schemas and proper constraints are enforced (that is, there are no nulls in places they do not belong,etc.). 
-Pig is designed for the Hadoop data-processing environment, where schemas are sometimes unknown or inconsistent. Pig does not require data to be loaded into tables first. It can operate on data as soon as it is copied into HDFS. 
-Pig Latin is the native language of parallel data-processing systems.

Q5.Explain the scalar data types in pig. 
Ans: The scalar data types in pig are: 
1)int- signed 32-bit integer
2)long- signed 64-bit integer 
3)float- 32-bit floating point 
4)double- 64-bit floating point
5)chararray -Character array in unicode UTF-8 
6)bytearray- Byte Array or blob

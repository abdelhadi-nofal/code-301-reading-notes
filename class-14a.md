# What is Normalization?

Normalization is a database design technique that reduces data redundancy and eliminates undesirable characteristics like Insertion, Update and Deletion Anomalies. Normalization rules divides larger tables into smaller tables and links them using relationships. The purpose of Normalization in SQL is to eliminate redundant (repetitive) data and ensure data is stored logically.

The inventor of the relational model Edgar Codd proposed the theory of normalization of data with the introduction of the First Normal Form, and he continued to extend theory with Second and Third Normal Form. Later he joined Raymond F. Boyce to develop the theory of Boyce-Codd Normal Form.

## Database Normal Forms

Here is a list of Normal Forms

1NF (First Normal Form)
2NF (Second Normal Form)
3NF (Third Normal Form)
BCNF (Boyce-Codd Normal Form)
4NF (Fourth Normal Form)
5NF (Fifth Normal Form)
6NF (Sixth Normal Form)
The Theory of Data Normalization in SQL server is still being developed further. For example, there are discussions even on 6th Normal Form. However, in most practical applications, normalization achieves its best in 3rd Normal Form. The evolution of SQL Normalization theories is illustrated below-



## Database Normalization With Examples
Database Normalization Example can be easily understood with the help of a case study. Assume, a video library maintains a database of movies rented out. Without any normalization in database, all information is stored in one table as shown below. Let's understand Normalization in database with tables example:

![](https://www.guru99.com/images/NormalizationTable1.png)

### 1NF (First Normal Form) Rules
Each table cell should contain a single value.
Each record needs to be unique.
The above table in 1NF-

1NF Example

![](https://www.guru99.com/images/1NF.png)


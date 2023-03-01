# DBFoundations-Module07 Webpage

# Link: https://jya0526.github.io/DBFoundations-Module07/

# Table of Contents  
1. [Assignment07_Writeup](https://github.com/jya0526/DBFoundations-Module07/blob/main/Assignment07_WriteUp.pdf) 

2. [Assignment07_JAhn](https://github.com/jya0526/DBFoundations-Module07/blob/main/Assignment07_JAhn.sql)

## Assignment07 Writeup

  Jacob Ahn  
  February 23, 2023 
  IT FDN 130A  
  Assignment 07  
  https://github.com/jya0526/DBFoundations-Module07

## User Experience: An Overview of User-Defined Functions (UDF)
 
### Introduction
The purpose of this week’s writeup is to demonstrate my understanding of this week’s material. 
This week’s material mainly concerns the use of User-Defined Functions, which are functions that are executed by the database. Concepts covered include the      following:
* Use Cases
* Scalar, Inline, & Multi-Statement Functions  
  
Sources from multiple websites will be referenced in the write-up. Please consult the ‘Works Cited’ page for more information.

### User Initiative: UDF Use Cases
UDFs can be used to increase the efficiency of applications. Specifically, it can help decrease the rate of data transfers between the application and database layer  (Custer, “What are User-Defined Functions”). The fewer data transfers there are, the less latency an application has. This can be especially useful for streamlining functions by removing redundant steps.

### Multi-Functionality: Scalar, Inline, and Multi-Statement
  UDFs have different types of functions, depending on the needs of the developer.   
  There are three types of UDFs, as follows:
 * Scalar
 * Inline
 * Multi-Statement

#### Scalar
  Scalar UDFs will return a single data value as a product of the function (Microsoft, “Scalar UDF Inlining”). 
  
#### Inline Table Valued Functions
  Inline functions contain a single TSQL statement and return a table set, rather than just a single data value (Richardson, “User-Defined Scalar Functions”). 
  
#### Multi-Statement Table-Valued Functions
  Multi-statement functions return a table as the output. However, this output table can be modified and aggregated by the user.   
  They can contain only one statement, or more than one statement at a time (Erkec, “Multi-Statement Table-Valued Functions”). 
  
### Works Cited
 * https://www.cockroachlabs.com/blog/udfs-in-sql/  
 * https://learn.microsoft.com/en-us/sql/relational-databases/user-defined-functions/scalar-udf-inlining?view=sql-server-ver16  
 * https://www.sqlshack.com/use-sql-server-built-functions-create-user-defined-scalar-functions/  
 * https://www.sqlshack.com/sql-server-multi-statement-table-valued-functions/



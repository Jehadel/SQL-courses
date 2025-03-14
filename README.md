# SQL-courses

SQL introduction course, first part of the UE "Programming for data science", 5 sessions <-> 5 notebooks.

## S1 - SQL basics (part 1)
[notebook #1](S1-SQL-intro.ipynb)

- definitions and principles of relational models
- entities relationships diagram (ERD)
- database management systems (DBMS)
- introduction to [SQLite](https://www.sqlite.org/index.html)
- SELECT … FROM, DISTINCT, LIMIT, etc.
- COUNT(), SUM(), AVG(), etc.
- WHERE, BETWEEN, LIKE, IS NOT, etc.
- GROUP BY, ORDER BY, HAVING, etc.

## S2 - SQL basics (part 2)
[notebook #2](S2-SQL-intro.ipynb)

- PRAGMAS
- CREATE TABLE, INSERT INTO, VALUES, etc.
- import .csv into DB, pandas.DataFrame.to_sql(), pandas.read_sql(), etc.
- UPDATE, DELETE, DROP
- UNION
- string functions
- datetime functions
- joins
- CASE WHEN, WITH,
- windows functions, OVER

## S3 - corrections 
[notebook #3](S3-Correction-S1-S2.ipynb)

Correction of the exercises from the first two sessions.

## S4 - exercices
[notebook #4 : statements](S4-SQL-intro-exercices.ipynb)
[notebook #4b : answers](S4-SQL-intro-exercices-corrections.ipynb)

- ALTER TABLE
- foreign key constraints
- Exercices with mock-up data : create a database, store data, list tables and columns, check data quality (missing values…), simple statistics, build metrics…

## S5 - SQLAlchemy - NoSQL
[notebook #5](S4-SQL-intro-exercices-corrections.ipynb)

Two parts :
- a short introduction to the [SQLAlchemy library](https://www.sqlalchemy.org/) : connect to a database, models
- NoSQL basics : definition, overview and some examples with [unqlite](https://unqlite-python.readthedocs.io/en/latest/index.html) (basic operations, cursors, transactions)

  ## Graded homework

  - [notebook (statements)](DM-SQL-questions.ipynb)
  - [data](data/DM-SQL)

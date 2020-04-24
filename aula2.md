# Cap. 6 - Tipos de dados
* Garantir integridade dos dados.
* Reduzir tamanho do armazenamento.

#### SQLite
https://www.sqlitetutorial.net/sqlite-data-types/

#### Lista Detalhada SQL Server:

https://docs.microsoft.com/pt-br/sql/t-sql/data-types/data-types-transact-sql?view=sql-server-ver15

# Cap. 7 - Instructions CREATE / INSERT 1/2
(SQLite)
- Normalização Exercício
- https://www.sqlitetutorial.net/sqlite-sample-database/ (invoice e invoice_item)
- Homework_01

## CREATE
- CREATE TABLE table_name
(field1 type, field2 type)
- id integer PRIMARY KEY AUTOINCREMENT

## INSERT 
- INSERT INTO table (fields,..)

VALUES(values...)

- INSERT INTO table FROM SELECT

# Cap. 8 - Instructions SELECT 1/2
(W3 site examples)

- SELECT * FROM
- SELECT field1, field2
- AS
- SELECT LIMIT (TOP no SQL Server)

# Cap. 9 - Instructions CREATE / INSERT 2/2 

### Constraints for table creation
https://www.tutorialspoint.com/sqlite/sqlite_constraints.htm
https://www.sqlitetutorial.net/sqlite-foreign-key/
- NOT NULL 
- FOREIGNKEY 
- PRIMARY KEY 
- DEFAULT 
- UNIQUE 
- CHECK 

### Cascade
ON DELETE CASCADE

### Drop
DROP TABLE

# Cap. 10 - Instruções SELECT 2/2 
- SELECT DISTINCT
- SELECT TOP PERCENT

## Filters
- WHERE
- AND
- OR
- NOT
- Null Values
- ISNULL
- LIKE
- Wildcards
- IN
- BETWEEN
- HAVING
- EXISTS


## Math operations
*, /, +, - 
< > <> =, >=, <=

## Order
- ORDER BY
- DESC

## Agregators / Grouping / summary
- GROUP BY
- MIN and MAX
- COUNT, AVG, SUM

## Conditionals
CASE WHEN

## Conversions
- CAST
- CONVERT

## Joins
- INNER JOIN
- LEFT JOIN
- RIGHT JOIN
- FULL JOIN

## Unions
- UNION
- UNION ALL

## Comments
--
/* 
*/

## Datetime functions
https://www.sqlite.org/lang_datefunc.html

# Cap.11 - ALTER TABLE
# Cap.12 - SQL Functions

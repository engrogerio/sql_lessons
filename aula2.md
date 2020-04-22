# Cap. 6 - Tipos de dados
* Garantir integridade dos dados.
* Reduzir tamanho do armazenamento

https://www.teach-ict.com/gcse_new/databases/terminology/miniweb/images/table.gif

#### Lista Básica:

https://www.w3schools.com/sql/sql_datatypes.asp

#### Lista Detalhada SQL Server:

https://docs.microsoft.com/pt-br/sql/t-sql/data-types/data-types-transact-sql?view=sql-server-ver15


# Cap. 7 - Instructions CREATE / INSERT 1/2
(SQLite)
_Homework_01 and another diagrams

## CREATE
CREATE TABLE table_name
(field1 type, field2 type)

## INSERT 
INSERT INTO TABLE (fields,..)
VALUES(values...)

# Cap. 8 - Instructions SELECT 1/2
(W3 site examples)

SELECT * FROM
SELECT field1, field2
AS
SELECT TOP

# Cap. 9 - Instructions CREATE / INSERT 2/2 

### Constraints for table creation
https://www.tutorialspoint.com/sqlite/sqlite_constraints.htm

- AUTOINCREMENT 
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
- SELECT DISTICT
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
CAST
CONVERT

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

# Cap.11 - ALTER TABLE
# Cap.12 - SQL Functions

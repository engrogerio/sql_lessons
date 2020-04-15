# Cap. 1 -  SQL - Structured Query Language - instruções enviadas para um SGBD.

https://www.w3schools.com/sql/sql_intro.asp


# Cap. 2 - Funcionalidades SGBD - Sistema de Gerenciamento de Bancos de Dados
 
## 2.1 - Armazenar dados em Tabelas e executar comandos conforme solicitado atraves de queries SQL.

### Tabelas podem conter dados de Relatórios, Configuração, Cadastros, Dados transacionais, logs e outros. 

* **Exemplo tabela de Relatório**

![](http://matlab.izmiran.ru/help/toolbox/database/vqb_repo.gif)


* **Exemplo tabela de Configuração** 

![](https://wp-staging.com/wp-content/uploads/2018/04/wordpress_database_headers.png)


* **Exemplo tabela de Cadastro**

![](https://sites.google.com/site/ismcsrdatabase/_/rsrc/1468868690197/ismcsrdatabase3/11.png)


* **Exemplo tabela de Dados Transacionais**

![](https://www.analyticsvidhya.com/wp-content/uploads/2015/12/Table2.png)


* **Exemplo tabela de Logs**

![]()


## 2.2- Garantir a consistência dos dados armazenados.

 * Para estudo: https://www.devmedia.com.br/integridade-de-dados-parte-01/8831

## 2.3- Servir os dados quando solicitados via SQL query.

## 2.4- Executar SQL queries em frequencias determinadas (Jobs)

## 2.5- Controle de Permissões


# Cap. 3 - Alguns SGBD mais usados hoje:

**SQL**

* SQL - MySql (www.mysql.com)
* Postgre(www.postgresql.org)
* SQLite(www.sqlite.org) 
* MSSQL (https://www.microsoft.com/pt-br/sql-server/sql-server-2019)
* Oracle (www.oracle.com/br/index.html), etc.
    
**NOSQL**

* MongoDB (www.mongodb.com), etc.
    

# Cap. 4 - Elementos padrão de um Banco de dados (criados com instruções SQL)

## 4.1- Tabelas - Armazenam os dados.

* A própria tabela deve ter um nome e cada campo deve ter um nome e um tipo - (cap.6)

https://www.teach-ict.com/gcse_new/databases/terminology/miniweb/images/table.gif

https://cdn.sqlservertutorial.net/wp-content/uploads/SQL-Server-Data-Types.png


## 4.2- Constraints definidos na criação das tabelas

https://www.w3schools.com/sql/sql_constraints.asp


## 4.3- Relacionamentos

* Relacionamento entre tabelas, existe para garantir a integridade dos dados.

https://www.mantisbt.org/docs/master/en-US/Developers_Guide/html/images/erd.png

http://infocenter.sybase.com/help/index.jsp?topic=/com.sybase.infocenter.dc38159.1510/html/iqintro/A112233.htm


## 4.4- Views - SQL scripts para exibição de dados calculados, formatados, filtrados e classificados.

## 4.5- Temporary Tables

## 4.6- Functions, Procedures e Triggers - SQL scripts para alterar dados das tabelas.

## 4.7- Usuários e permissões.


# Cap. 5 - Conceitos de Normalização

A Normalização é necessária para evitar redundâncias e garantir a integridade de dados armazenados em TABELAS de um banco de dados.

[baixar exercício](https://github.com/engrogerio/sql_lessons/raw/master/normalizacao_exercicio.xlsx)

https://medium.com/@diegobmachado/normaliza%C3%A7%C3%A3o-em-banco-de-dados-5647cdf84a12

https://www.sqlshack.com/what-is-database-normalization-in-sql-server/


# Cap. 6 - Tipos de dados
* Garantir integridade dos dados.
* Reduzir tamanho do armazenamento

https://www.teach-ict.com/gcse_new/databases/terminology/miniweb/images/table.gif

#### Lista Básica:

https://www.w3schools.com/sql/sql_datatypes.asp

#### Lista Detalhada SQL Server:

https://docs.microsoft.com/pt-br/sql/t-sql/data-types/data-types-transact-sql?view=sql-server-ver15


# Cap. 7 - Instruções

## Select
Select * from
Select field1, field2 
Aliases as
Select Top / percent
Select Distinct

## Filters
Where
And, Or, Not
Null Values
isnull
Like
Wildcards
In
Between
Having
Exists
Any, All

## Math operations
*, /, +, - 
< > <> =, >=, <=

## Order
Order By

## Agregators / Grouping / summary
Group By
Min and Max
Count, Avg, Sum

## Conditionals
Case When

## Conversions
Cast
Convert

## Joins
Inner Join
Left Join
Right Join
Full Join

## Unions
Union
Union all

## Comments
--
/* 
*/

# Cap1 -  SQL - Structured Query Language

https://www.w3schools.com/sql/sql_intro.asp


# Cap2 - Funcionalidades , "Flavors" e Elementos de um sistema de gerenciamento de banco de dados  (SGBD)
 
## 2.1 Funcionalidades: 
 
### 2.1.1- Armazenar dados em Tabelas e distribuir conforme solicitado atraves de queries SQL.

#### Tabelas podem conter dados de Relatórios, Configuração, Cadastros, Dados transacionais, logs e outros. 

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


### 2.1.2- Garantir a consistência dos dados armazenados.

 * Para estudo: https://www.devmedia.com.br/integridade-de-dados-parte-01/8831

### 2.1.3- Servir os dados quando solicitados via SQL query.

 
## 2.2- Elementos padrão de um Banco de dados:

### 2.2.1- Tabelas - Armazenam os dados.

* Cada coluna deve ter um nome e um tipo

https://www.teach-ict.com/gcse_new/databases/terminology/miniweb/images/table.gif

https://www.analyticsvidhya.com/wp-content/uploads/2015/12/Table2.png


### 2.2.2- Relacionamentos

* Banco de dados: Relacionamento entre várias tabelas para garantir integridade:

https://www.mantisbt.org/docs/master/en-US/Developers_Guide/html/images/erd.png

http://infocenter.sybase.com/help/index.jsp?topic=/com.sybase.infocenter.dc38159.1510/html/iqintro/A112233.htm


### 2.2.3- Views - Exibição de dados das tabelas calculados, formatados, filtrados e classificados.

### 2.2.4- Temporary Tables

### 2.2.5- Functions, procedures e triggers - Alteram os dados

### 2.2.6- Usuários e permissões.

## 2.3- Alguns SGBD mais usados hoje:

**SQL**

* SQL - MySql (www.mysql.com)
* Postgre(www.postgresql.org)
* SQLite(www.sqlite.org) 
* MSSQL (https://www.microsoft.com/pt-br/sql-server/sql-server-2019)
* Oracle (www.oracle.com/br/index.html), etc.
    
**NOSQL**

* MongoDB (www.mongodb.com), etc.
    

# Cap3 - Conceitos de Normalização

A Normalização é necessária para evitar redundâncias e garantir a integridade de dados armazenados em TABELAS de um banco de dados.

[ver exercício](/normalizacao_exercicio.xlsx)

https://medium.com/@diegobmachado/normaliza%C3%A7%C3%A3o-em-banco-de-dados-5647cdf84a12

https://www.sqlshack.com/what-is-database-normalization-in-sql-server/


# Cap4 - Best Pratices for naming (

## 4.1- Reasons for using a naming convention:

* SQL é uma linguagem de programação. Um código é escrito uma vez por 1 pessoa e lido muitas vezes por muitas pessoas.
* To reduce the effort needed to read and understand source code.
* To enable code reviews to focus on more important issues than arguing over syntax and naming standards.
* To enable code quality review tools to focus their reporting mainly on significant issues other than syntax and style preferences.
* To enable an easy workteam, its necessary some conventions.


## 4.2 - Padronizar formas de nomenclatura para elementos do db:

* Não usar letras Maiúsculas (lowercase).

* Nomes que explicam o que o objeto faz:

    Tabela "product", procedure "apply_discount_adjustment", view: "produtos_inativos", etc.
    
* Usar underscore _ no lugar no espaço.

* Não usar acentos. Dê preferência para palavras em inglês.

## 4.3 - Comentar o código quando necessário:

* Explicar o que seu código faz em termos do negócio;
* Comentar alterações em um código em produção;
* Documentar decisões.

# Cap5 - SQL commands

1- Usar comandos em Maiusculo (UPPERCASE)

source: https://www.sqlstyle.guide/pt-br/


# Cap5 - Tipos de dados

####  Básico:

https://www.w3schools.com/sql/sql_datatypes.asp

#### Detalhado:

https://docs.microsoft.com/pt-br/sql/t-sql/data-types/ntext-text-and-image-transact-sql?view=sql-server-ver15  


# Cap6- Instruções

#### Comments
--
/**/

#### Select
Select * from
Select field1, field2 
Aliases as
Select Top / percent
Select Distinct

#### Filters
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

#### Order
Order By

#### Agregators / Grouping / summary
Group By
Min and Max
Count, Avg, Sum

#### Conditionals
Case When

#### Joins
Inner Join
Left Join
Right Join
Full Join

#### Unions
Union





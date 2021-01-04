# Welcome to SQL summarization
For Xiao

## 1. 什么是数据库
数据库有很多种类，这里我们重点学习使用最广泛的关系数据库。
关系数据库是由多个表组成的。如果你用过Excel，就会知道Excel是一张一张的二维表。每个表都是由行和列组成的
同样的，关系数据库里存放的也是一张一张的表，只不过各个表之间是有联系的。所以，简单来说：
>**关系数据库=多张表+各表之间的关系**

### 表的结构
每个表由一个名字标识。表包含带有列名的列，和记录数据的行。下面图片里的表名是：学生表，记录了每个学生的信息。

### 表之间的关系
每个表由一个名字标识。表包含带有列名的列，和记录数据的行。下面图片里的表名是：学生表，记录了每个学生的信息。

这两张表通过**学号**关联起来，用相同颜色代表同一个学生的信息。

例如我想知道学生表里学号“0001” 的成绩是多少？那么我就可以在成绩表里去查找“**学号**”值是0001的行，最后在成绩表里发现有3行数据的学号都是“0001” ，对应的就找到了该学生的三门课程的成绩。

>**关系就是数据能够对应的匹配，在关系数据库中正式名称叫联结，对应的英文名称叫做  join**。

## 2. 什么是SQL
**SQL** (Structured Query Language:结构化查询语言) 是用于管理关系数据库管理系统（RDBMS）。 SQL 的范围包括数据插入、查询、更新和删除，数据库模式创建和修改，以及数据访问控制。

-SQL 可以访问和处理数据库，包括数据插入、查询、更新和删除。你的需求应该是从数据库中取回数据。

## 3. 语法
[点我点我，非常明了的中文教程](https://www.runoob.com/sql/sql-syntax.html)

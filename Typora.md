# MySQL

***

## MySQL

Mysql是最流行的关系型数据库管理系统，在WEB应用方面MySQL是最好的RDBMS(Relational Database Management System：关系数据库管理系统)应用软件之一。

## 什么是数据库？

简单来说 数据库（Database）是按照数据结构来组织、存储和管理数据的仓库 。每个数据库都有一个或多个不同的API用于创建，访问，管理，搜索和复制所保存的数据。

## RDBMS 术语

- **数据库:** 数据库是一些关联表的集合。.
- **数据表:** 表是数据的矩阵。在一个数据库中的表看起来像一个简单的电子表格。
- **列:** 一列(数据元素) 包含了相同的数据, 例如邮政编码的数据。
- **行：**一行（=元组，或记录）是一组相关的数据，例如一条用户订阅的数据。
- **冗余**：存储两倍数据，冗余降低了性能，但提高了数据的安全性。
- **主键**：主键是唯一的。一个数据表中只能包含一个主键。你可以使用主键来查询数据。
- **外键：**外键用于关联两个表。
- **复合键**：复合键（组合键）将多个列作为一个索引键，一般用于复合索引。
- **索引：**使用索引可快速访问数据库表中的特定信息。索引是对数据库表中一列或多列的值进行排序的一种结构。类似于书籍的目录。
- **参照完整性:** 参照的完整性要求关系中不允许引用不存在的实体。与实体完整性是关系模型必须满足的完整性约束条件，目的是保证数据的一致性。



## 基本的sql语句

### 插入

```
insert into table1(field1,field2) values(value1,value2) 
```

### 删除

```
delete from table1 where 范围 
```

### 更新

```
update table1 set field1=value1 where 范围 
```

### 查找

```
select * from table1 where 范围 
```

### 排序

~~~
select * from table1 order by field1,field2 [desc] 
~~~

### 总数

```
select count as totalcount from table1 
```

### 最大

```
select max(field1) as maxvalue from table1 
```

### 最小

```
select min(field1) as minvalue from table1 
```


# 数据库操作
## 创建数据库
```sql
create database `databasename` default character 
set utf8mb4 collate utf8mb4_general_ci;
```
* utf8mb4是4个字节宽度,兼容性好;
* utf8只有3个字节宽度,已经不建议使用

## 查看数据库

> 查看有哪些数据库 : show databases;

> 查看数据库建库SQL : show create database databasename;
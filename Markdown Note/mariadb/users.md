# 用户操作
## 创建用户
> create user 'username'@'%' identified by 'passworld';

## 修改用户密码
> set password for 'username'@'%' = password("passworld");

## 用户授权
> grant all on databasename.tablename to 'username'@'%';

## 删除用户
> drop user 'username'@'host';

## 移除授权
> revoke select on *.* from 'user'@'%';
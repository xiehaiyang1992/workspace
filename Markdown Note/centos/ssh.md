# ssh命令的使用方式
## 普通ssh登录
```shell
ssh user@ip.com -p529
```

## 使用密钥登录
```shell
 ssh-keygen -t rsa
 ```
 > 将在~/.ssh/ 下生成密钥以及公钥文件,建议将公钥中的user@host字段去掉再操作

 > 生成的文件如下 [id_rsa](/resources/id_rsa)与[id_rsa.pub](/resources/id_rsa.pub)
```shell
cp id_rsa.pub authorized_keys
```
> 文件授权
```shell
chmod 700 ~/.ssh/
chmod 600 ~/.ssh/id_rsa 
chmod 600 ~/.ssh/authorized_keys
```
> 最后登录一次即可，或者自己修改~/.ssh/known_hosts文件
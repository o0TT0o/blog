## Linux环境下，SQLPLUS的配置

### 参考:
- [Linux sqlplus远程访问Oracle](http://blog.csdn.net/joker_zhou/article/details/9301223)
- [linux sqlplus 安装配置](http://blog.csdn.net/huaishu/article/details/39056369)
- [如何用sqlplus执行一个sql文件](http://bbs.csdn.net/topics/70244844)

### FAQ:
- [ORA-12162: TNS:net service name is incorrectly specified 错误解决](http://blog.csdn.net/sunansheng/article/details/50209557)
- [sqlplus remote connection giving ORA-21561](https://stackoverflow.com/questions/31338916/sqlplus-remote-connection-giving-ora-21561)

```
查询主机名：hostname
修改本地主机名：vi /etc/hosts

DEMO：
It should be changed to:
127.0.0.1 localhost localhost.localdomain hostname
```

#### 致谢以上
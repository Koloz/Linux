* 修改ssh端口

```bash
 vi /etc/ssh/sshd_config
 Port 28926
```

```bash
service sshd restart
```

* 禁止root登录

新建用户

```bash
useradd boluo
passwd boluo
```

* 找到\#PermitRootLogin yes，去掉注释，修改为：

```bash
PermitRootLogin no
```

* 修改主机名

```bash
vi /etc/hosts
hostname CentOS7-HK
```






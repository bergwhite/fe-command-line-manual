# Linux 手册

日常使用的Linux命令总结。

## 基础

### 指定文件的运行程序

```

#!/usr/bin/env node

```

### 查看正在使用的端口

```

netstat -a  // 显示已连接的端口
netstat -ap  // 显示所有端口
netstat -ap | grep 8080  // 显示指定端口
lsof -i:8888  // 显示指定端口的另一个方案
kill -9 PID号  // 结束指定端口

```

## 应用程序

### Nginx

```

service nginx start  // 启动
service nginx stop  // 结束
service nginx reload  // 重载

```


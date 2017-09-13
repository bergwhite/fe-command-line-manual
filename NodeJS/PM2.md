# PM2 手册

## 常用命令

```

pm2 list // 查看所有项目
pm2 start --name nchat ./bin/www  // 以fork模式启动项目
pm2 start -i 0 --name nchat ./bin/www  // 以cluster的方式启动项目

```

## 查看项目

```

pm2 show nchat  // 查看nchat项目的详情

```

## 重启和重载项目

```

pm2 restart nchat  // 重启项目
pm2 reload nchat  // 重载项目

```
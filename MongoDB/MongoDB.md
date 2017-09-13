# MongoDB 手册

## 进入

```

mongod  // 启动MongoDB
mongo  // 进入交互式命令行

```

## 导入JSON文件

```

mongoimport -h 127.0.0.1 -d cnblogs -c top200page --type json --file Y:\cnblogs.json --upsert

```
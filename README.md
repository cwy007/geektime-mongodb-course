# Files for MongoDB Course on Geektime

## mongorestore

导入测试数据

[aggregation](./aggregation/lab-script.md)

```bash

cd geektime-mongodb-course/aggregation

# 解压实验数据文件
tar -zxvf dump.tar.gz

# 将实验数据导入到MongoDB
mongorestore -h 127.0.0.1:27017 dump

```

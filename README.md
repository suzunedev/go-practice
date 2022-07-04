# go-practice

## mysql

```bash
cp .env.sample .env
vim .env
docker compose up -d
mysql -h 127.0.0.1 -u root -p
Enter password:

mysql>
mysql> CREATE DATABASE recordings;
mysql> use recordings;
mysql> source ./create-tables.sql
mysql> SELECT * FROM album;
```

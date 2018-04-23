
# show database

If you run mysql.exe with `--user=root --password=...`, it will show you all databases.
```
mysql> SHOW DATABASES;
```

# to access database
```
mysql> USE DATABASE;
```
and for security need to do this:
```
mysql> GRANT ALL ON menagerie.* TO 'your_mysql_name'@'your_client_host';
```


# create database
```
CREATE DATABASE menagerie;
```
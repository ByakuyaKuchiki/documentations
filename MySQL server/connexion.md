# connecting and disconnecting to SQL Server
## connect
```
shell> mysql -h host -u user -p
Enter password: ********
```
host and user represent the host name where your MySQL server is running and the user name of your MySQL account. Substitute appropriate values for your setup. The ******** represents your password; enter it when mysql displays the Enter password: prompt.

```
shell> mysql -u user -p
```
If you are logging in on the same machine that MySQL is running on.

after connecting
```
mysql> QUIT
```
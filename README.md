# mysql-change-auth-socket

```
UPDATE mysql.user SET plugin = 'mysql_native_password', authentication_string = PASSWORD('abc123') WHERE User = 'root';
FLUSH Privileges;
```

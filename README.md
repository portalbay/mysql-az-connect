# mysql-az-connect
* Sample cli to command to remove azure/other mysql db with ssl.

## Linux Syntax below
```
#Load CSV (Ubuntu WSL)
mysql  --local-infile=1 --host=<server_here>.mysql.database.azure.com --database=<db_name> --user=<user_id> --password <load.sql

#Connect (Ubuntu WSL or Win 11)
mysql  --host==<server_here>.mysql.database.azure.com --database=<db_name> --user=<user_id> --password


#Legacy
##mysql -h host@domain.xyz -u user_name -p --ssl 
```

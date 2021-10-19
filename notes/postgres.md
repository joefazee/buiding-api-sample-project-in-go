# Important commands

How to find the config file
`sudo -u postgres psql -c 'SHOW config_file;'`

How to create new database
` CREATE DATABASE dbname;`

How to switch to a new databse
`postgres=# \c dbname`

**Must of the commands below are to be executed after you have switched database**

How to create a new user (role)
`CREATE ROLE newrole WITH LOGIN PASSWORD 'pa55word';`

How to connect to a specific database
`psql --host=localhost --dbname=DB_NAME --username=USER_NAME` - You will be asked to enter password

To get the Chinook database, run the command in the Gitpod console/terminal (*the final **dot** is important!*):

`wget https://raw.githubusercontent.com/lerocha/chinook-database/master/ChinookDatabase/DataSources/Chinook_MySql_AutoIncrementPKs.sql .`

You should now have the file downloaded, and you can run the following command:

`mysql < Chinook_MySql_AutoIncrementPKs.sql -v`

- Type `mysql` to start the mysql CLI.
- Type `use Chinook;` to use the Chinook database.
- Type `desc Employee;` to show the columns in the Employee table.
- Type `select * from Employee;` to show all items in the Employee table. (optional: `limit 2;`)
- Type `quit;` to leave the mysql CLI.


---


- In **VSCode** type `sudo service mysql start mysql`.
- Then: `CREATE DATABASE Chinook;`;
- Then: `quit`
- Then: `mysql -u root -p Chinook < Chinook_MySql_AutoIncrementPKs.sql`
- Enter Password (takes a while to load everything properly)
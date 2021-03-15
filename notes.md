## Creating the Database

use the command " sqlite3 questions.db < schema.sql" in command prompt to create the database

### To change the admin status of use from command line in database

update users set admin ='1' where id = 1;
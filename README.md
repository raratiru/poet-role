# poet-role
Role to manage django poet project

tags
----

* **test**: Tests becoming superuser
* **db_drop_create**: Drops and creates a db
  * POET_DATABASE_NAME
  * POET_DATABASE_USER
  * POET_DATABASE_PASSWORD
* **db_backup**: Creates a backup of a db
  * POET_DATABASE_NAME
  * POET_DATABASE_USER
  * POET_DATABASE_PASSWORD
  * POET_PROJECT_PATH
  * POET_VERSION
* **db_restore**: Restores the db from the latest backup file
  * POET_DATABASE_NAME
  * POET_DATABASE_USER
  * POET_DATABASE_PASSWORD
  * POET_PROJECT_PATH

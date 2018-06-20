# chachara-db-config

Table definitions for the Cháchara app database.

## Usage

- Create the database

```sh
mysql -u <user> -e "CREATE DATABASE <db-name>"
```

- Create the tables

```sh
for file in tables/*.sql; do mysql -u <user> <db-name> < $file; done
```

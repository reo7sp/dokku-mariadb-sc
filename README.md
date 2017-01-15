# dokku-mariadb-sc
MariaDB (**single container**) [dokku](dokku.viewdocs.io/dokku/) plugin

## Commands
```
mariadb-sc:create <name>, Create a MariaDB database
mariadb-sc:destroy <name> [--force], Delete the MariaDB database
mariadb-sc:link <name> <app>, Link the MariaDB database to the app
mariadb-sc:unlink <name> <app>, Unlink the MariaDB database from the app
mariadb-sc:export <name>, Export a dump of the MariaDB database
mariadb-sc:import <name> < <file>, Import a dump into the MariaDB database
mariadb-sc:list, List all MariaDB databases
mariadb-sc:connect [<name>], Open MariaDB shell to database as root user
mariadb-sc:user-connect <name>, Open MariaDB shell to database
mariadb-sc:logs [-t], Print the most recent log(s) for MariaDB container
mariadb-sc:start, Start a MariaDB container
mariadb-sc:stop, Stop a running MariaDB container
mariadb-sc:restart, Shutdown and restart the MariaDB container
mariadb-sc:install, Create MariaDB container
mariadb-sc:uninstall, Delete MariaDB container
mariadb-sc:reinstall, Delete and recreate the MariaDB container
mariadb-sc:purge [--force], Delete all data of MariaDB container
```

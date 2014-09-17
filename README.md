A series of useful commands written in python to interact with a MySQL Server running on Docker

# Motivation
Docker is awesome, but when using MySQL on a Dockerized environment simple tasks can become commands with lots of options and arguments.

__Note:__ The following commands will use the official MySQL docker image found at https://registry.hub.docker.com/_/mysql/

# Commands provided

	dmysql-server (Start a new MySQL Server)
	dmysql (Open the mysql cli)
	dmysql-create-database (Creates a new database)
	dmysql-import-database (Imports a database)
	
# Install
Clone or download this project then run:

	$ cd directory_with_scripts
	$ sudo chmod +x dmysql*
	$ sudo cp dmysql* /usr/local/bin

# License
Released under the MIT License
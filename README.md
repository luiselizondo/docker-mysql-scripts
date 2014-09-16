A series of useful commands written in python to interact with a MySQL Server running on Docker

# Motivation
Docker is awesome, but when using MySQL on a Dockerized environment simple tasks can become commands with lots of options and arguments.

# Commands provided

## mysqls (Start a new MySQL Server)

	Usage: mysqls [MYSQL CONTAINER NAME] [MYSQL ROOT PASSWORD] --with-volume
	Provide the container name and the root password. If you enter --with-volume a
	data-only container will be created for you

## mysqlc (Open the mysql cli)

	Usage: mysqlc [MYSQL CONTAINER NAME]
	Provide the container name you want to connect to and you'll be asked to enter the password

## mysqlc-create-database (Creates a new database)
	
	Usage: mysqlc-create-database [MYSQL CONTAINER NAME] [DATABASE NAME]
	Provide the container to use and the database you want to create

# Install
	
	cd directory_with_scripts

	sudo chmod +x mysql*
	sudo cp mysql* /usr/local/bin

# License
Released under the MIT License
## INSTAL AND CONFIGURE THE MANTIS WITH DOCKER

### CONFIGURE FOLDER TO FILES UPLOAD
	
	If you have files backup, copy files to folder before run permissions

	$ chown 33:33 -R /opt/mantis/files
	$ chmod 700 -R /opt/mantis/files

### EXEC COMPOSE

	$ docker-compose up -d

## INSTALATION

	$ browser http://localhost:8090/admin/install.php

´´´ text
	==================================================================================
	Installation Options
	==================================================================================
	Type of Database                                        MySQL/MySQLi
	Hostname (for Database Server)                          mysql
	Username (for Database)                                 mantisbt
	Password (for Database)                                 mantisbt
	Database name (for Database)                            bugtracker
	Admin Username (to create Database if required)         root
	Admin Password (to create Database if required)         root
	Print SQL Queries instead of Writing to the Database    [ ]
	Attempt Installation                                    [Install/Upgrade Database]
	==================================================================================
´´´

	$ browser: http://localhost:8090/

		>>> username: administrator
		>>> password: root

## ABOUT - SOURCES

	MantisBT makes collaboration with team members & clients easy, fast, and professional
	MantisBT is an open source issue tracker that provides a delicate balance between simplicity and power. Users are able to get started in minutes and start managing their projects while collaborating with their teammates and clients effectively. Once you start using it, you will never go back!

- https://www.mantisbt.org
- https://hub.docker.com/r/xlrl/mantisbt
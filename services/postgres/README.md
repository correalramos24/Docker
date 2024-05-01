# Postgres SQL server

Fire a postgres SQL server, with a PHP-based admin running at port 8080.


## Launch the containers
The docker-compose runtime expects to found in the running path the secret files.
By default, the runtime will place the BD files at /db_data, **ensure that all the permisions are not-sudo required.**

````bash
#Set variables
cat "YOUR_USER" >> db_user.txt
cat "YOUR_PASS" >> db_pass.txt

#launch the container in detached mode:
docker-compose up -d
````
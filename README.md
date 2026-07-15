<h1> CDEC-StudentApp Deploy With Docker </h1>
CDEC-Studentapp Project Deploy By Using Docker Container. This Is a 3-Tier Application

<h1>Docker Installation</h1>
Install By Using Documentation
Link - https://docs.docker.com/engine/install/ubuntu/
<h1>MARIADB INSTALLATION AND CREATE DATABASE</h1>
docker run -d -e MARIADB_ROOT_PASSWORD=redhat -p 3306:3306 mariadb
<h1>INSDIE THE MARIADB CONTAINER</h1>
docker exec -it bash <container_id>
<h1>LOGIN INTO DATABASE</h1>
mariadb -uroot -predhat
<h1>CREATE THE DATABASE</h1>
CREATE DATABASE student_db;
<h1>SEE THE DATABASE</h1>
show databases;
<h1>EXIT THE CONTAINER</h1>
exit

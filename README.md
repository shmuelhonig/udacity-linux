# udacity-linux
Udacity FSND Project

IP Address: 18.221.10.76
SSH Port: 2200

Complete url: http://shmuelbaseball.com

I installed the following applications: 
1) finger 0.17-15
2) postgres 9.5
3)apache2 2.4.18
4) flask python-flask  0.10
5) python-sqlalchemy   1.0.11
6) python-psycopg2   2.6.1
7) libpq-dev  9.5
8) Flask-Dance 0.14
9) Flask-Limiter 1.0.1
10) Flask-HTTPAuth 3.2.4

Among the configurations and commands used for this project were:
1) Creation of a .conf file in the Apache 'sites-enabled' directory.
2) Creation of a .wsgi file alongside my app directory.
3) Change of database connection from SQLite to PostgreSQL.
4) Due to my use of Flask-Dance and its requirement for redirect url's, I needed to get a domain name to conform with Google's redirect url requirements.
5) sudo ufw to configure the firewall.
6) apt-get upgrade, a2ensite, ssh-keygen.
7) Create Amazon Lightsail virtual machine instance.

I made generous use of Google, Stack Overflow, and my new mentor, Sarmad. Among the more helpful resources found on Google were
https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps and
https://blog.theodo.fr/2017/03/developping-a-flask-web-app-with-a-postresql-database-making-all-the-possible-errors/


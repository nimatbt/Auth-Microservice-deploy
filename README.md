
# Docker-compose file for Authentication Service
## Amima Project
## Deploy Segment

This repository contain docker-compose file for run MySQL and Authz containers in production environment 

### How to use?
1) download authz:latest and docker-compose.yaml and .env files
 or clone: https://github.com/nimatbt/Auth-Microservice

2) set below parameters in .env file
- MYSQL_ROOT_PASSWORD="your root password"
- MYSQL_DATABASE="your sql database name"
- MYSQL_USER="your db username"
- MYSQL_PASSWORD="your db password"
- AMIMA_AUTHZ_DATABASE_URI=mysql+pymysql://MYSQL_USER:MYSQL_PASSWORD@mysql:3306/MYSQL_DATABASE

3) docker-compose up -d 

Copyright 2022 Nima Tabatabaee <nima.tabatabaee@gmail.com>

DevOps Practice

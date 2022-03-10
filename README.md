1. git clone https://github.com/alex9216/docker_bitrix.git
2. Place bitrix install sources to www/public subfolder
3. cd docker_bitrix root folder
4. sudo chown -R www-data:www-data www
5. docker-compose up -d
6. After build has finished open url http://localhost:20000 in your browser and install bitrix with this database settings:
  - host - mysql
  - database - bitrix
  - username - root
  - password - 123456

# docker_bitrix
1. git clone https://github.com/alex9216/docker_bitrix.git
2. Place bitrix install sources to www/html subfolder
3. cd docker_bitrix root folder
4. chown -R www-data:www-data www/html
5. docker-compose up -d
6. After build has finished open url http://localhost:20080 in your browser and install bitrix with this database settings:
  - host - mysql
  - database - www-data
  - username - www-data
  - password - 123456

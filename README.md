## TO RUN APP

1. Install the wordpress zip : https://wordpress.org/download/
2. Extract the zip file and put it in `www/html`
3. From the main directory, run the command `docker compose up -d`
4. If you wish to personify your sql identifiers, change the following information in docker-compose.yml
   ```
   environment:
   MYSQL_ROOT_PASSWORD: secret
   MYSQL_USER: username
   MYSQL_PASSWORD: secret
   MYSQL_DATABASE: wordpress
   ```
5. To setup wordpress, follow the instructions on screen.

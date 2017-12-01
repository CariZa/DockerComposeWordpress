### Run the docker compose file in detached mode

    $ docker-compose up -d

### See the running containers

    $ docker ps

### View the docker ip

    $ docker-machine ip

### View your wordpress site through the containers on port 8000

    $ [ip]:8000

## .env

Create a ".env" file with the following values:

    MYSQL_ROOT_PASSWORD: YOUR_ROOT_PASSWORD_HERE
    MYSQL_DATABASE: YOUR_DATABASE_NAME_HERE
    MYSQL_USER: YOUR_MYSQL_USER_HERE
    MYSQL_PASSWORD: YOUR_MYSQL_PASSWORD_HERE
    WORDPRESS_DB_HOST: db:3306
    WORDPRESS_DB_USER: YOUR_MYSQL_USER_HERE
    WORDPRESS_DB_PASSWORD: YOUR_MYSQL_PASSWORD_HERE

You shouldn't really have to worry about anything after that. The containers should automatically set up with those details and just run. If you're finding that you still need to tweak these values you may not have pointed to the right file in your docker-compose.yml file.




# docker-lamp

Docker example with Apache, MySql 8.0, PhpMyAdmin and Php

You can use MySql 5.7 if you checkout to the tag `mysql5.7`

I use docker-compose as an orchestrator. To run these containers:

```
docker-compose up -d
```

Open phpmyadmin at [http://localhost:8000](http://localhost:8000)
Open web browser to look at a simple php example at [http://localhost](http://localhost)

You can use mysql inside the container :

- `docker ps` to extract the mysql container hash id 
- `docker exec -it hash_id_mysql bash`
- `mysql -u root -p` (use your password specified in docker-compose.yml)

Enjoy !

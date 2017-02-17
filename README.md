# sonata-sandbox-docker

### Installation:
* clone sonata sandbox-build into code folder ```cd ./code && git clone https://github.com/sonata-project/sandbox-build sandbox```
* ```./configure``` configure env variables for docker containers:
* ``` sh docker-compose up -d``` to start containers
* ```sh ./docker-console``` to enter fpm container
* inside the fpm container run ```sh php bin/load_data.php```



# Docker Compose PHP+MYSQL on Docker

# Git Clone
```
git clone https://github.com/FaisalDefry/php-mysql-sample/blob/master/README.md
````

# Install Docker compose
````
cp docker-compose /usr/local/bin/docker-compose
```

### Inspect Dockerfile & related file

```
cat app/index.php
cat app/Dockerfile
cat db/Dockerfile
cat db/telkom.sql

```


### Build & Run!

```
docker-compose build
docker-compose up -d
```
you can now start writing your app!

### Stop

```
docker-compose kill
```

### MySQL

Check out `app/index.php` for getting credentials from the ENV variables.

### Test the app

```
$VM_IP_ADDRESS:8000
```

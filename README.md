# Docker Compose PHP+MYSQL on Docker


# Install Docker compose

cp docker-compose /usr/local/bin/docker-compose
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

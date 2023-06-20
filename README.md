# docker-mysql-adminer-phpmyadmin
Docker recipe with MySQL (server), Adminer (db management) and phpMyAdmin (another db management).

## Use case
- For educational material.
- For you that want to start MySQL container with database management included (Adminer/phpMyAdmin).
- For development environment that use MySQL.
- For note to myself.
- For inspiration to other users.

## Requirements
- Docker installed on your machine, or just use Play with Docker [https://labs.play-with-docker.com/] to have fun.

## How to run?

First please have a look on some config on MySQL container, open `docker-compose.yml` and look on `db` section, you should adjust it to fit your needs, such as password, username etc.

```bash
docker compose up -d
```

## How to check if it's running?

```bash
docker ps
```

## How to use or connect to MySQL?

We provide 2 (two) database management here, because I like both. First you can use Adminer, so access it via http://localhost:8080, the second we also provide phpMyAdmin, so access it via http://localhost:8081.

## License

MIT

Maintained by Sony Arianto Kurniawan <<sony@sony-ak.com>> and contributors.

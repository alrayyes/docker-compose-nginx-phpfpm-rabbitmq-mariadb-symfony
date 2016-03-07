# docker-nginx-phpfpm-mysql-symfony14
Everything you need to get Symfony 1.4 apps running in Docker.

# How this works

- Add your project to www directory
- Run

```shell
docker-compose up
```

- Profit!

Included are the following:

- Nginx
- PHP5.3 FPM + XDebug
- Mysql 5.5

Also included a script (/bin/fix-cache-log.sh) To create cache & log dirs in the root, thereby avoiding permissions issues
running this in OSX.

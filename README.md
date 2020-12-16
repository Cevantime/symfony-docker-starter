# Symfony Docker Starter

A simple starter to build symfony containers using docker-compose. It is based on this [repo](git@github.com:gponty/docker-symfony.git)

## Configuration

If you know what you are doing, you can simply adapt configuration in different files.

When you're done, just run :

```bash
docker-composer up -d
```

For convenience, a www folder is included is this repo and can be used to contain your symfony application (unless you changed the configuration accordingly).

Simply create a new symfony application :

```bash
cd www
symfony new mysite
```

Your new site shall be available at [localhost:9074](http://localhost:9074)

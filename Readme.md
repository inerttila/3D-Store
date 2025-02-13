To start both of the projects, run:

```shell
yarn dev
```

The `docker-compose.yml` file is for the PostgreSQL database.

```shell
docker-compose up --build -d
```

Medusa Setup run :

```shell
yarn medusa db:setup
```

To create an superuser run :

```shell
npx medusa user -e admin@medusajs.com -p supersecret
```

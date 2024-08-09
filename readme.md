# MedusaJS E-commerce Project

To run this application you will need

- node >= 16.x.x installed
- docker desktop
- git

```
docker-compose up --build -d
```

```
 npx create-medusa-app@latest --seed --db-url postgres://yourusername:yourpassword@host.docker.internal:5432/medusa_db

```

cd medusa-backend

localhost:7001

--------------------- new wsl --------------------

```
 npx create-next-app -e https://github.com/medusajs/nextjs-starter-medusa medusa-storefront
```

cd medusa-storefront

```
mv .env.template .env.local

```

---

start both of them

```
yarn dev
```

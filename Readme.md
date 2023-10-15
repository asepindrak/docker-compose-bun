## Docker compose BUN

> Simple local development

Author: Asep Indra K (https://asepindrak.github.io/)

URL: https://github.com/asepindrak/docker-compose-bun

> ---

1. Configuration

   - install docker desktop for PC or Mac

```
git clone https://github.com/asepindrak/docker-compose-bun.git
```

> ---

```
cd docker-compose-bun
```

```
cp .env.example .env
```

```
cp -R .docker/bun/src.example .docker/bun/src
```

```
docker-compose up
```

2. Access API

   - http://localhost:3000


3. Run Container
   > if docker container stopped, you can run again with docker desktop or terminal

```
docker-compose up
```

4. Mysql Config

   - .docker/mysql/my.cnf

5. Nginx Config

   - .docker/nginx/site.conf

6. Rebuild Container
   > if you change docker-compose.yaml or my.cnf or site.conf or bun/Dockerfile or .env, please rebuild the container with

```
docker-compose up -d --build
```

> ---

> MySQL Credential

- user: root
- password: root

> PostgreSQL Credential

- user: postgres
- password: password

> bun file at .docker/bun

> ---

# docker-whale

Run me : `docker run -p80:80 ushamandya/whale-example`

Build me: `docker build -t ushamandya/whale-example .`

# commands
- docker-compose -f docker-compose.yml -f docker-compose.prod.yml --env-file ./config/.env up -d = first start or update docker-composer
- docker-compose -f docker-compose.yml -f docker-compose.prod.yml --env-file ./config/.env up --build --no-deps -d app

# commands dev
- docker-compose -f docker-compose.yml -f docker-compose.prod.yml --env-file ./config/dev.env up -d = first start

# config
create .env file from .env.example and change path --env-file
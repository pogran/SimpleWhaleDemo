# docker-whale

Run me : `docker run -p80:80 ushamandya/whale-example`

Build me: `docker build -t ushamandya/whale-example .`

# commands
- docker-compose -f docker-compose.yml -f docker-compose.prod.yml up -d = first start
- docker-compose -f docker-compose.yml -f docker-compose.prod.yml up --build --no-deps -d app
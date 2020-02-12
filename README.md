# Docker Compose

# Files
- Postgres (docker-compose-postgres.yml)
- Rabbit (docker-compose-rabbit.yml)

## Postgres
Fornece um Postgres(5432) e um PgAdmin(16543)
Execute o comando :
> docker-compose -f docker-compose-postgres.yml up -d


## RabbitMQ
Fornece um RabbitMQ(15672 - 5672)

Execute o comando :
> docker-compose -f docker-compose-rabbit.yml up -d


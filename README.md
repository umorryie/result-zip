# Result - Artificial Intelligence

## Application start up

- You must have `PostgreSQL` running. First initialize volume for database. To do that execute: `docker volume create pgdata`
- In order to run `PostgreSQL` from docker execute: `docker container run -d --name=postgres -p 5432:5432 -e POSTGRES_PASSWORD=postgres -v pgdata:/var/lib/postgresql/data postgres`
- Run `Spring Boot` application.
- Swagger is located on: `http://localhost:8080/swagger-ui.html#`

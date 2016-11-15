# liquibase

Hello world - liquibase

Pré-requisitos:
- Postgres 8.3;
- Maven 3;

Para executar esse projeto, você precisa ter as seguintes configurações de banco de dados:

- url........: jdbc:postgresql://localhost:5432/demo
- username...: postgres
- password...: 123456

Para criar o database execute: mvn liquibase:update

Para dropar o database execute: mvn liquibase:dropAll

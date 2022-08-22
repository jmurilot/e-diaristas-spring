# Projeto E-Diaristas

Projeto desenvolvido durante a imersao MultiStack da Treinaweb.
Sistema Desenvovido em Java no Backend usando framework Spring Boot e ReactJS no Frontend.

## Dependencias do projeto:

- Spring Boot
- Spring WEB MVC
- Thymeleaf
- Spring Data JPA
- Bean Validation

## Dependencias de desenvolvimento:

- Spring boot DevTools
- Lombok

## Requisitos

- Java 17
- Maven 3.8

## Como testar esse projeto: 

Clone este repositorio e entre na pasta do projeto: 
```sh
git clone git@github.com:jmurilot/e-diaristas-spring.git 
cd e-diaristas-spring
```
Atualize as configuracoes de acesso ao banco de dados no arquivo [application.properties](src/main/resources/application.properties)

```properties
spring.datasource.url=jdbc:mysql://host:porta/banco_de_dados?useTimezone=true&serverTimezone=America/Sao_Paulo
spring.datasource.username=usuario
spring.datasource.password=senha

```

Execute o projeto atraves do Maven.
```sh
mvn spring-boot:run
```

Acesse a aplicacao em [http://localhost:8080/admin/servicos](http://localhost:8080/admin/servicos)


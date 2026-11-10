# Adega do Porão

Sistema web para gerenciar uma adega: categorias, fornecedores, bebidas, clientes e vendas.

Feito com Java 21, Spring Boot, Spring MVC, Spring Data JPA, Thymeleaf e MariaDB/MySQL.

## Como rodar

1. Ligue o MySQL no painel do XAMPP.
2. Na pasta do projeto, rode `mvnw.cmd spring-boot:run` no Windows.
3. Abra http://localhost:8080.

O banco `adega`, as tabelas e os dados de exemplo são criados na primeira execução.
Usuário e senha do banco ficam em `src/main/resources/application.properties`.

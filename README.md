# SpringbootJPA Application

Esta é uma aplicação simples desenvolvida com Spring Boot, JPA e Maven, que envia dados sobre compras para um banco de dados. A aplicação permite consultar esses dados usando o Postman com requisições HTTP (GET, POST, PUT, UPDATE, DELETE).

## Funcionalidades

- Enviar dados sobre compras para o banco de dados
- Consultar dados das compras
- Atualizar, inserir e deletar registros de compras

## Tecnologias Utilizadas

- Java
- Spring Boot
- Spring Data JPA
- Maven

## Como Executar a Aplicação

1. Clone o repositório:
    ```bash
    git clone https://github.com/BatistaQ/SpringbootJPA.git
    ```
2. Navegue até o diretório do projeto:
    ```bash
    cd SpringbootJPA
    ```
3. Compile e execute a aplicação:
    ```bash
    mvn spring-boot:run
    ```

## Como consultar dados

Os dados podem ser acessados através do Postman ou qualquer outro cliente HTTP. Aqui estão algumas requisições básicas:

### Consultar todas as compras

```http
GET http://localhost:8080/orders
```

### Consultar todos os clientes

```http
GET http://localhost:8080/users
```

### Consultar todos os produtos

```http
GET http://localhost:8080/products
```





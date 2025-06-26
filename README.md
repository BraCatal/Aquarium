# Aquarium API - Projeto Spring Boot (Local)

Este projeto foi desenvolvido como parte da disciplina de Desenvolvimento de Sistemas no curso de Sistemas de Informação do Unilasalle-RJ.

A aplicação consiste em uma **API RESTful** para gerenciamento de **aquários** e seus respectivos **animais**, utilizando Spring Boot, PostgreSQL, JPA e documentação Swagger.

## 👨‍🎓 Autor

**Breno Baroncelli**

**E-mail:** breno.baroncelli@soulasalle.com.br

## 🛠️ Tecnologias Utilizadas

- Java 17
- Spring Boot 3.4.6
- Spring Data JPA
- PostgreSQL
- Maven
- Lombok
- SpringDoc OpenAPI (Swagger UI)

## ⚙️ Funcionalidades

- CRUD de Aquários (`/aquario`)
- CRUD de Animais (`/animal`)
- Relacionamento: `@OneToMany` entre Aquário e Animal
- Swagger disponível em `/swagger-ui.html`

## ▶️ Como Executar Localmente

1. Clone o repositório:

   `git clone https://github.com/BraCatal/Aquarium.git`
   `cd Aquarium`

2. Configure seu banco de dados PostgreSQL:

    Nome: aquariumdb
    Usuário: postgres
    Senha: postgres
   
3. Atualize o arquivo src/main/resources/application.properties com suas credenciais se necessário.

4. Rode o projeto com: `./mvnw spring-boot:run`

5. Acesse o Swagger: `http://localhost:8081/swagger-ui.html`

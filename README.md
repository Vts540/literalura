# literalura
Cadastrador de Livros e Autores
Praticando Spring Boot: Challenge Literalura
Este repositório contém o projeto desenvolvido como parte do curso Praticando Spring Boot: Challenge Literalura da plataforma Alura. O projeto visa consolidar conceitos de Spring Boot, Spring Data JPA e PostgreSQL, aplicados ao desenvolvimento de APIs. Foram utilizados conhecimentos adquiridos em três cursos complementares:

Java: trabalhando com lambdas, streams e Spring Framework
Java: persistência de dados e consultas com Spring Data JPA
Java: criando sua primeira API e conectando ao front
🚀 Funcionalidades Implementadas
Cadastro de dados: API REST para criação e gerenciamento de recursos.
Consulta com filtros: Integração com o banco de dados para consultas refinadas.
Persistência: Configuração com Spring Data JPA e PostgreSQL.
Boas práticas: Uso de Streams, Lambdas e estrutura modularizada para o código.
🛠️ Tecnologias Utilizadas
Linguagem: Java
Framework: Spring Boot
Dependências principais:
Spring Data JPA
PostgreSQL Driver
Banco de dados: PostgreSQL
Ferramentas auxiliares: Maven para gerenciamento de dependências.
🖥️ Como Executar o Projeto
Clonar o repositório

bash
Copiar código
git clone https://github.com/seuusuario/nome-do-repositorio.git
cd nome-do-repositorio
Configurar o banco de dados

Certifique-se de ter o PostgreSQL instalado e rodando.
Crie um banco de dados com o nome desejado.
Atualize o arquivo application.properties com as credenciais corretas:
properties
Copiar código
spring.datasource.url=jdbc:postgresql://localhost:5432/seu_banco
spring.datasource.username=seu_usuario
spring.datasource.password=sua_senha
Executar o projeto

Compile e execute a aplicação usando Maven:
bash
Copiar código
mvn spring-boot:run
A aplicação estará disponível em http://localhost:8080.
🧩 Estrutura do Projeto
src/main/java
Contém o código principal da aplicação:
Models: Classes representando as entidades do banco de dados.
Repositories: Interfaces para manipulação de dados com Spring Data JPA.
Controllers: Pontos de entrada da API.
Services: Regras de negócio.
src/main/resources
Arquivos de configuração, incluindo application.properties.
📚 Sobre o Desafio
O Challenge Literalura propôs a criação de uma aplicação que gerencia dados relacionados a um tema fictício, com foco na prática de boas práticas de desenvolvimento backend, persistência de dados e construção de APIs.

Durante o desenvolvimento, consolidamos conceitos de:

Programação funcional com Lambdas e Streams em Java.
Mapeamento Objeto-Relacional (ORM) com Spring Data JPA.
Desenvolvimento de APIs REST com Spring Boot.
📄 Licença
Este projeto está sob a licença MIT. Sinta-se à vontade para utilizá-lo como referência ou aprimorá-lo.

🤝 Contribuições
Contribuições são bem-vindas! Se você encontrou algum problema ou tem sugestões para melhorias, abra uma issue ou envie um pull request.

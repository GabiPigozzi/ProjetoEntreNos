# EntreNos - Sistema de Agendamento e Triagem

O EntreNos é uma plataforma simples desenvolvida em Java com Spring Boot para facilitar o acolhimento e a organização de atendimentos. O sistema permite o cadastro de usuários, a realização de uma triagem lógica e o agendamento de horários.

## Tecnologias Utilizadas
Java 21: Linguagem principal.

Spring Boot 3.4: Framework para agilizar o desenvolvimento.

Thymeleaf: Motor de templates para renderizar o Front-End.

Spring Data JPA: Para persistência de dados.

H2 Database: Banco de dados em memória para desenvolvimento ágil.

Maven: Gerenciador de dependências.

## Estrutura do Projeto
O projeto segue a estrutura padrão do Spring Boot, organizada por camadas:

src/main/java/com/entrenos/controller: Gerencia as rotas e a navegação das páginas.

src/main/java/com/entrenos/model: Define as entidades do banco de dados (Usuário, Agendamento, Triagem).

src/main/java/com/entrenos/repository: Interfaces para comunicação com o banco de dados.

src/main/java/com/entrenos/service: Contém a lógica de negócio (ex: cálculo da triagem).

src/main/resources/templates: Páginas HTML desenvolvidas com Thymeleaf.

src/main/resources/static: Arquivos estáticos como CSS, JavaScript e Imagens.

## Funcionalidades Planejadas
[ ] Aba Sobre Nós: Informações institucionais.

[ ] Login/Cadastro: Autenticação de usuários.

[ ] Home Page: Dashboard principal do usuário.

[ ] Script de Triagem: Questionário para classificação de atendimento.

[ ] Calendário de Agendamento: Reserva de horários integrada ao perfil.

Como Executar
Clone o repositório:

Bash
git clone https://github.com/seu-usuario/entrenos.git
Instale as dependências:

Bash
mvn install
Execute a aplicação:
Rode o arquivo EntreNosApplication.java ou use o comando:

Bash
mvn spring-boot:run
Acesse no navegador:

Aplicação: http://localhost:8080

Banco de Dados (Console): http://localhost:8080/h2-console
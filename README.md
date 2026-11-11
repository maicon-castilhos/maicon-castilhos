<h1 align="center">Maicon Amaral</h1> <p align="center"> <b>Desenvolvedor Back-end Java</b> · Java · Spring Boot · PostgreSQL · APIs REST </p> <p align="center"> <a href="https://maicon-castilhos.github.io/portifolio-v1/"><img src="https://img.shields.io/badge/Portf%C3%B3lio-0d1528?style=for-the-badge&logo=githubpages&logoColor=3fd0ff" alt="Portfólio"></a> <a href="https://www.linkedin.com/in/maicon-amaral-b9283722a/"><img src="https://img.shields.io/badge/LinkedIn-0d1528?style=for-the-badge&logo=linkedin&logoColor=3fd0ff" alt="LinkedIn"></a> <a href="mailto:maikamaral123@gmail.com"><img src="https://img.shields.io/badge/E--mail-0d1528?style=for-the-badge&logo=gmail&logoColor=3fd0ff" alt="E-mail"></a> </p>

Sou graduando em Ciência da Computação e desenvolvo APIs REST com Java, Spring Boot e PostgreSQL, cuidando de modelagem de dados, autenticação, regras de negócio, validações e testes de integração.

Hoje contribuo com o projeto open source Calendar, onde tenho dois PRs integrados, e desenvolvo o Acompanha Aí, uma plataforma para acompanhar candidaturas a vagas.

Busco estágio ou vaga júnior em back-end Java, com preferência por trabalho remoto.

Destaques
Calendar · contribuição open source

Contribuição voluntária no back-end de um projeto de código aberto em Java, Spring Boot e PostgreSQL.

PR #227 (integrado): preferências de notificação por usuário e antecedência opcional de lembretes por tarefa, com validação na API, migrações Flyway e testes de integração com PostgreSQL. A suíte de 280 testes continuou passando.
PR #228 (integrado): agendamento persistente de lembretes, atualizando os horários quando a tarefa é editada.

Java Spring Boot PostgreSQL Flyway Testes de integração

Repositório · PR #227 · PR #228

Acompanha Aí · projeto principal

Plataforma web para acompanhar candidaturas e processos seletivos, com contas de usuários, filtros, paginação e histórico de etapas.

API em camadas: controllers, services, repositories, DTOs e entidades.
Autenticação por sessão com Spring Security, proteção CSRF e isolamento de dados por usuário.
Transações, deduplicação de vagas e controle de versão para rejeitar edições desatualizadas.
Testes com JUnit, Mockito e MockMvc, documentação OpenAPI, Docker e CI/CD.

Java 25 Spring Boot 4 Spring Security PostgreSQL Flyway Angular Docker

Repositório

Outros projetos
Projeto	O que é	Stack
Automechanic API	API para oficinas mecânicas: clientes, veículos, peças, serviços e ordens de serviço, com cálculo de valores, validações de negócio e 18 testes de regressão	Java 25 · Spring Boot 4 · JPA · PostgreSQL · H2
Sistema de Pedidos	API de usuários, produtos, categorias, pedidos e pagamentos, com modelagem de relacionamentos	Java · Spring Boot · JPA · PostgreSQL
API Blog	API de posts, comentários e buscas em banco orientado a documentos	Java · Spring Boot · MongoDB
Lucas Silva e Advogados Associados	Site institucional responsivo com quatro idiomas · ver site	React · Vite · WebGL
Sementes do Amanhã	Prática de front-end para uma ONG fictícia · ver site	HTML · CSS · JavaScript
Experiência
Período	Função	Onde
nov/2026 — atual	Desenvolvedor Back-end Java (voluntário)	Calendar · open source
ago/2026 — atual	Estágio em Data Quality	Stringhini
jun/2026 — out/2026	Full Stack Júnior	Lucas Silva e Associados
jul/2025 — mar/2026	Site Leader	Shopee

Na Lucas Silva e Associados, desenvolvi o site institucional e uma plataforma interna em Java, Spring Boot e PostgreSQL, com distribuição de tarefas por pontuação, regras de promoção, acesso de clientes a documentos e perfis de acesso. O código é de uso interno e não está publicado.

Na Shopee, liderei operações de inbound e outbound. A produtividade da equipe foi de 425 para 617 pacotes por pessoa.

Stack
Área	Tecnologias
Back-end	Java 17, 21 e 25 · Spring Boot 4 · Spring Security · APIs REST · Maven
Dados	PostgreSQL · SQL · Spring Data JPA · Hibernate · Flyway · MongoDB
Testes e documentação	JUnit · Mockito · MockMvc · Spring Security Test · OpenAPI · Postman
Entrega	Docker · CI/CD · Git e GitHub
Front-end complementar	Angular · React · TypeScript

Estudando agora: JWT e OAuth2, arquitetura de software e microsserviços.

Como eu testo
Segurança: acesso sem login, permissões e tentativas de ler dados de outro usuário (401 e 403).
Validação: entradas inválidas e recursos inexistentes, conferindo status e mensagem de erro (400 e 404).
Concorrência: edições simultâneas, garantindo que uma atualização desatualizada seja rejeitada (409).
Regressão: a suíte completa roda a cada mudança, antes de abrir um PR.
Como uso inteligência artificial

Uso IA para estudar conceitos, discutir alternativas, revisar código e investigar problemas. Procuro entender cada sugestão, conferir o comportamento e conseguir explicar e manter o que foi adotado.

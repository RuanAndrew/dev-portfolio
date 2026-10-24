---
title: 'Manga Tracker'
date: 2026-10-22
summary: 'API para acompanhamento de leitura de mangás, desenvolvida com Java e Spring Boot, autenticação JWT, PostgreSQL e testes automatizados.'
tags:
  - 'Backend'
  - 'Java'
  - 'Spring Boot'
  - 'PostgreSQL'

tech_stack:
  - 'Java'
  - 'Spring Boot'
  - 'PostgreSQL'
  - 'Docker'
  - 'Flyway'
  - 'JUnit 5'
  - 'Testcontainers'
links:
  - type: github
    url: 'https://github.com/RuanAndrew/manga-tracker'
    label: 'Código no GitHub'
featured: true
status: 'Em desenvolvimento'
role: 'Desenvolvimento individual'
highlights:
  - 'Estrutura Maven e ambiente de desenvolvimento com Docker Compose e PostgreSQL'
  - 'Versionamento do schema do banco de dados com Flyway'
  - 'Cadastro e autenticação de usuários com Spring Security e JWT'
  - 'Testes automatizados com JUnit 5 e Testcontainers, além de pipeline de CI'
---
## Visão geral

O **Manga Tracker** é uma aplicação em desenvolvimento para centralizar o acompanhamento de leitura de mangás. O projeto é construído incrementalmente com foco em organização de domínio, testabilidade e boas práticas de engenharia de software.

## O que já foi desenvolvido

- Estrutura inicial do projeto com Maven e Spring Boot.
- Ambiente de desenvolvimento com PostgreSQL via Docker Compose.
- Migração inicial do banco com Flyway.
- Infraestrutura para testes de integração usando Testcontainers.
- Entidade e repositório de usuário, cadastro e hashing de senha.
- DTOs e mapeamento com MapStruct.
- Fluxo de registro e login, geração e validação de JWT e configuração do Spring Security.
- Testes de integração para o fluxo de autenticação e pipeline de integração contínua.

## Próximas etapas

O roadmap inclui a integração com o catálogo externo de mangás, a biblioteca pessoal de leitura, o registro de progresso e avaliações, o tratamento global de erros, a validação de entradas, a documentação OpenAPI e a interface web em React. Esses itens não devem ser interpretados como funcionalidades já concluídas.

## Práticas de engenharia

O desenvolvimento segue ciclos de **TDD (red-green-refactor)** e utiliza documentação de arquitetura e decisões técnicas para manter o projeto compreensível e evolutivo.

**Repositório:** [github.com/RuanAndrew/manga-tracker](https://github.com/RuanAndrew/manga-tracker)

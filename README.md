# Ian Kiyoshi Kobayashi

**Estudante de ADS · Backend Java/Spring Boot · Buscando estágio em backend**

Mogi das Cruzes, SP · Formatura prevista: dezembro de 2027 · Português (nativo), Japonês (fluente) e Inglês (leitura técnica, em evolução)

## Sobre mim

Estudo Análise e Desenvolvimento de Sistemas na Faculdade Impacta e busco meu primeiro estágio em **desenvolvimento backend**, com interesse especial no setor **financeiro e bancário**.

Trabalho principalmente com **Java e Spring Boot**: APIs REST, autenticação com Spring Security e JWT, persistência com JPA/Hibernate e PostgreSQL, testes automatizados e Docker. Uso Python/FastAPI quando o problema pede.

Aprendo construindo, e só publico o que consigo explicar: cada projeto abaixo tem testes e README com as decisões técnicas.

## Projetos em destaque

### [Horizon](https://github.com/Iankyoo/horizon) · API de acompanhamento de candidaturas
API REST que registra vagas e o histórico de status de cada uma, e calcula as métricas do funil (conversão entre etapas, tempo médio por etapa, top plataformas) a partir desse histórico.

- Histórico de status modelado como tabela de eventos
- Autenticação JWT stateless, segredos só em variáveis de ambiente
- Schema versionado com Flyway
- Testes unitários, de segurança (MockMvc) e de integração com PostgreSQL real (Testcontainers), rodando no GitHub Actions
- Decisões e trade-offs registrados no repositório

![Java](https://img.shields.io/badge/Java_21-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=flat-square&logo=flyway&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

### [REST API](https://github.com/Iankyoo/rest-api) · Gestão de restaurante
API de controle de comandas, mesas e cardápio, com regras de negócio como bloqueio de mesa ocupada e preço do item congelado no pedido.

- Autenticação stateless com JWT e controle de acesso por perfil
- 107 testes automatizados (unitários, de controller e de integração)
- Documentação com OpenAPI/Swagger

![Java](https://img.shields.io/badge/Java_21-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![JUnit](https://img.shields.io/badge/JUnit-25A162?style=flat-square&logo=junit5&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

### [Bank Analyzer](https://github.com/Iankyoo/bank-analyzer) · Análise de extratos com IA
API em Python que recebe o PDF de um extrato bancário, categoriza as transações com Gemini (em lote) e gera um insight financeiro. Meu projeto mais próximo do universo fintech.

- FastAPI, SQLAlchemy async e PostgreSQL
- Memória semântica com ChromaDB e LangChain para evitar chamadas repetidas à API
- Idempotência por hash SHA256 do arquivo
- Isolamento por usuário nos extratos, rate limiting na autenticação e testes com Pytest

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B6B?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

## Stack

**Principal:**
![Java](https://img.shields.io/badge/Java_21-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**Testes:**
![JUnit](https://img.shields.io/badge/JUnit_5-25A162?style=flat-square&logo=junit5&logoColor=white)
![Mockito](https://img.shields.io/badge/Mockito-C5D9C8?style=flat-square&logo=java&logoColor=black)
![Testcontainers](https://img.shields.io/badge/Testcontainers-9B1AD6?style=flat-square)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

**Infra e ferramentas:**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Também uso:**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

## In English

I'm a Systems Analysis and Development student (graduating December 2027) looking for a **backend internship**, with a strong interest in fintech and banking. I build REST APIs with Java and Spring Boot (Spring Security, JWT, JPA/Hibernate, PostgreSQL, Docker) and also work with Python/FastAPI. I'm fluent in Japanese, I read technical documentation in English, and I'm actively improving my spoken and written English.

## Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/iankyoo)
[![E-mail](https://img.shields.io/badge/E--mail-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:contato.iankyoo@gmail.com)

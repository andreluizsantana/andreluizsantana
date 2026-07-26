<h1 align="center">André Luiz</h1>

<p align="center">
 🚀 Backend Java Developer | Spring Boot | Spring Security | PostgreSQL · João Pessoa, PB
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/andrelssr/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://andreluiz.vercel.app"><img src="https://img.shields.io/badge/Portfólio-000000?style=for-the-badge&logo=vercel&logoColor=white"></a>
</p>

---

### 🛠️ Stack

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=spring-security&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![JPA](https://img.shields.io/badge/JPA_Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apache-maven&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=json-web-tokens&logoColor=white)
![Linux](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

---

### 📌 Sobre

Desenvolvedor backend com foco em **Java e Spring Boot**, construindo APIs REST robustas e escaláveis.
Atualmente trabalho com **BIRT/Jasper Reports** e **SQL** no dia a dia, e desenvolvo projetos pessoais
aplicando **Spring Security**, **autenticação JWT**, **JPA/Hibernate** e **PostgreSQL** com foco em
boas práticas de arquitetura (paginação, tratamento global de exceções, camadas DTO/Service bem definidas).

Ambiente de desenvolvimento: **IntelliJ IDEA** rodando em **Ubuntu Linux**.

### 🎯 Objetivo
**Backend Developer Júnior/Pleno**

---

## 📊 Estatísticas

[![Profile views](https://komarev.com/ghpvc/?username=andreluizsantana&color=0071C5)](https://github.com/andreluizsantana)

---

## 🚀 Principais Tecnologias

### Backend
- **Java 17+** | **Spring Boot 3.x** | **Spring Security 6.x**
- **Spring Data JPA** | **Hibernate** | **Lombok**
- **JWT Authentication** | **BCrypt Password Encoding**
- **Apache POI** (importação Excel)
- **MapStruct** (DTO mapping)

### Database & Tools
- **PostgreSQL** | **SQL** | **Maven** | **Git** (SmartGit)
- **IntelliJ IDEA** | **Ubuntu Linux** | **Docker**

### Frontend
- **Next.js 15** | **TypeScript** | **Tailwind CSS**

### Relatórios & Legacy
- **BIRT** | **Jasper Reports**

---

## 📊 Projetos Principais

### 📅 **EventAPI** - API de Gestão de Eventos (em desenvolvimento ativo)
**Spring Boot 3.x + Spring Data JPA + PostgreSQL**

```
✅ Modelagem de domínio: 5 entidades (Evento, Convidado, Fornecedor,
   ItemEvento, ListaConvidado) com relacionamentos 1:N mapeados
✅ Camada DTO/Mapper (EventMapper)
✅ EventService com exceções customizadas e @Transactional
✅ EventController seguindo REST best practices (rotas no plural,
   ServletUriComponentsBuilder, endpoint DELETE)
✅ Tratamento global de exceções (EventNotFoundException,
   ErrorResponse, DataIntegrityViolationException handler, SLF4J)
✅ Paginação com Pageable, Page<T> e PageResponse customizado (record)
🔄 Próxima fase: Repositories avançados (queries customizadas)
```

👉 [Ver projeto](https://github.com/andreluizsantana) *(link do repositório específico)*

---

### 🔐 **TaskHub API** - REST API com Autenticação JWT
**Spring Boot 3.4.4 + Spring Security + PostgreSQL + JPA/Hibernate + MapStruct**

```
✅ Autenticação com JWT (24h tokens)
✅ UserDetailsService customizado
✅ Custom SecurityFilter (OncePerRequestFilter)
✅ BCryptPasswordEncoder
✅ DTOs com Java Records + MapStruct
✅ GlobalExceptionHandler robusto
✅ JPA com @MappedSuperclass e auditing
✅ Bean Validation (@Valid)
✅ Tarefas simples (UNICA) e recorrentes (MENSAL)
✅ Job agendado (@Scheduled) - atualiza tarefas vencidas
✅ Paginação configurável
✅ Otimizações de batch insert (10x mais rápido)
```

👉 [Ver projeto completo](https://github.com/andreluizsantana/task-manager-api)

---

### 📥 **Excel Employee Importer** - API de Importação em Lote
**Spring Boot + Apache POI + PostgreSQL + JPA/Hibernate**

```
✅ Importação de arquivos Excel (XLSX/XLS)
✅ Validação de dados e conversão de tipos
✅ BigDecimal para tratamento de valores monetários
✅ GlobalExceptionHandler robusto
✅ Transações atômicas com @Transactional
✅ DataFormatter para leitura segura de células
✅ Suporte a múltiplas abas (sheets)
✅ Tratamento de erros por linha com mensagens claras
```

👉 [Ver projeto completo](https://github.com/andreluizsantana/excel-employee-importer)

---

### 🌐 **Portfólio Pessoal**
**Next.js 15 + TypeScript + Tailwind CSS (Dark Terminal Aesthetic)**

```
✅ Design moderno e responsivo
✅ TypeScript para type safety
✅ Tailwind CSS para styling robusto
✅ Deploy na Vercel (CI/CD automático)
✅ Dark mode terminal aesthetic
```

👉 [Acessar portfólio](https://andreluiz.vercel.app)

---

## 📚 Conceitos que Domino

### Spring Security & Autenticação
- ✅ UserDetailsService customizado
- ✅ Authentication Manager
- ✅ JWT Token generation & validation
- ✅ Custom filters (OncePerRequestFilter)
- ✅ SecurityContext & SecurityContextHolder
- ✅ STATELESS session management
- ✅ Password encoding (BCrypt)

### Spring Boot & JPA
- ✅ Spring Data JPA repositories
- ✅ @MappedSuperclass para herança
- ✅ DTOs com Java Records + MapStruct
- ✅ Relacionamentos 1:N, lazy loading
- ✅ JPQL & native queries
- ✅ Transações com @Transactional
- ✅ Job scheduling (@Scheduled)
- ✅ Paginação (Pageable, Page<T>, DTOs de resposta customizados)
- ✅ Tratamento global de exceções (@RestControllerAdvice)

### REST APIs
- ✅ Endpoints RESTful (convenções de rota, verbos HTTP corretos)
- ✅ Bean Validation
- ✅ HTTP status codes
- ✅ DTOs para request/response
- ✅ Importação de arquivos (multipart/form-data)
- ✅ Paginação e filtros

### Database
- ✅ PostgreSQL
- ✅ SQL (queries, indexes, relationships)
- ✅ Database design
- ✅ JPA Sequences & Generators

### Infra & Ambiente
- ✅ Linux (Ubuntu) como ambiente principal de desenvolvimento
- ✅ Git via GUI (SmartGit)
- 🔄 Docker & docker-compose (em consolidação)

---

## 🎓 Em Preparação / Desenvolvendo Atualmente

- 🧪 Aprofundando **testes automatizados** (JUnit 5, TDD)
- 🐳 Consolidando **Docker** & **docker-compose**
- 📄 Estudando **Swagger/OpenAPI** para documentação de APIs
- 📊 Evoluindo a **EventAPI** rumo a um padrão de código nível Pleno
- 📚 Revisando **arquitetura de software** e **design patterns**

---

## 💬 Fale Comigo

<div align="center">

[🌐 **Portfólio**](https://andreluiz.vercel.app) •
[💼 **LinkedIn**](https://www.linkedin.com/in/andrelssr/) •
[🐙 **GitHub**](https://github.com/andreluizsantana)

</div>

---

<div align="center">

**"Escrevendo código limpo, aprendendo todos os dias."**
*Made with ❤️ in João Pessoa, PB*

</div>

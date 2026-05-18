<h1 align="center">André Luiz</h1>

<p align="center">
 🚀 Backend Java Developer | Spring Boot | Spring Security | PostgreSQL · João Pessoa, PB
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
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

---

### 📌 Sobre

Desenvolvedor backend com foco em **Java e Spring Boot**, construindo APIs REST robustas e escaláveis.
Atualmente trabalhando com **BIRT/Jasper Reports** e **SQL** no dia a dia, e desenvolvendo projetos com
**Spring Security**, **autenticação JWT**, **JPA/Hibernate** e **PostgreSQL**.

### 🎯 Objetivo
**Backend Developer Pleno** | Meta: Outubro 2026

---

## 📈 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=andreluizsantana&theme=dark&show_icons=true&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=andreluizsantana&theme=dark&layout=compact&hide_border=true)

</div>

---

## 📊 Estatísticas

[![Profile views](https://komarev.com/ghpvc/?username=andreluizsantana&color=0071C5)](https://github.com/andreluizsantana)

[![trophy](https://github-profile-trophy.vercel.app/?username=andreluizsantana)](https://github.com/ryo-ma/github-profile-trophy)

---

## 🚀 Principais Tecnologias

### Backend
- **Java 17+** | **Spring Boot 3.x** | **Spring Security 6.x**
- **Spring Data JPA** | **Hibernate** | **Lombok**
- **JWT Authentication** | **BCrypt Password Encoding**
- **Apache POI** (importação Excel)
- **MapStruct** (DTO mapping)

### Database & Tools
- **PostgreSQL** | **SQL** | **Maven** | **Git**
- **Eclipse IDE** | **Docker** 

### Frontend
- **Next.js 15** | **TypeScript** | **Tailwind CSS**

### Relatórios & Legacy
- **BIRT** | **Jasper Reports**

---

## 📊 Projetos Principais

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

📌 **Features principais**:
- `POST /api/auth/login` - Autenticação JWT
- `POST /api/auth/register` - Registro de usuários
- `GET/POST/PUT/DELETE /api/tasks` - CRUD de tarefas (autenticado)
- `POST /api/tasks/recurrent` - Criar tarefas recorrentes
- `GET /api/tasks/test-scheduled` - Testar job agendado

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

📌 **Features**:
- `POST /api/importar/arquivoexcel` - Importar funcionários em lote
- Conversão automática de tipos (CPF, nome, telefone, salário)
- Tratamento de erros com mensagens específicas por linha
- Persistência em PostgreSQL via JPA

👉 [Ver projeto completo](https://github.com/andreluizsantana/excel-employee-importer)

---

### 🌐 **andre-dev-portfolio** - Portfólio Pessoal
**Next.js 15 + TypeScript + Tailwind CSS (Dark Terminal Aesthetic)**

```
✅ Design moderno e responsivo
✅ TypeScript para type safety
✅ Tailwind CSS para styling robusto
✅ Deployed na Vercel (CI/CD automático)
✅ GitHub integration
✅ Dark mode terminal aesthetic
```

📌 **Features**:
- Landing page profissional
- Showcase de projetos
- GitHub integration
- Responsivo para mobile/tablet

👉 [Acessar portfólio](https://andreluizsantana.vercel.app)  
👉 [Ver código](https://github.com/andreluizsantana/andre-dev-portfolio)

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
- ✅ Lazy loading & relationships
- ✅ JPQL & native queries
- ✅ Transações com @Transactional
- ✅ Job scheduling (@Scheduled)
- ✅ Otimizações de batch insert

### REST APIs
- ✅ Endpoints RESTful
- ✅ GlobalExceptionHandler (@RestControllerAdvice)
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

### Processamento de Arquivos
- ✅ Apache POI (Excel XLSX/XLS)
- ✅ DataFormatter para leitura segura
- ✅ MultipartFile handling
- ✅ Validação de entrada

### Frontend
- ✅ Next.js e React
- ✅ TypeScript
- ✅ Tailwind CSS
- ✅ Responsividade

---

## 🔄 Fluxo de Aprendizado

```
Fundamentos Java
    ↓
OOP, Collections, Streams
    ↓
JPA & Hibernate
    ↓
Spring Boot Basics
    ↓
REST APIs & DTOs
    ↓
Spring Security & JWT
    ↓
Processamento de Arquivos ← Você está aqui
    ↓
Testes (Unit & Integration)
    ↓
Docker & CI/CD
    ↓
Microservices Architecture
```

---

## 🎓 Desenvolvendo Atualmente

- 📖 Aprofundando **Spring Security** (Roles, Authorities, OAuth2)
- 📥 Explorando **processamento de arquivos** (Excel, CSV)
- 🧪 Implementando **testes unitários** (Mockito, JUnit 5)
- 🐳 Explorando **Docker** & **docker-compose**
- 📚 Estudando **design patterns** em Java
- 🔄 Implementando **refresh tokens** & **token rotation**
- 📊 Construindo **Event Manager API** (multi-entity relationships)

## 💬 Fale Comigo

<div align="center">

[🌐 **Portfólio**](https://andreluizsantana.vercel.app) • 
[💼 **LinkedIn**](https://www.linkedin.com/in/andrelssr/) • 
[🐙 **GitHub**](https://github.com/andreluizsantana) • 

</div>

---

<div align="center">

**"Escrevendo código limpo, aprendendo todos os dias."**

*Made with ❤️ in João Pessoa, PB*

</div>

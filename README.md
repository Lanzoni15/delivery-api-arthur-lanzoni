# Delivery Tech API

Sistema de delivery desenvolvido com Spring Boot e Java 21.

## 🚀 Tecnologias
- **Java 21 LTS** (versão mais recente)
- Spring Boot 3.2.x
- Spring Web
- Spring Data JPA
- H2 Database
- Maven

## ⚡ Recursos Modernos Utilizados
- Records (Java 14+)
- Text Blocks (Java 15+)
- Pattern Matching (Java 17+)
- Virtual Threads (Java 21)

## 🏃‍♂️ Como executar
1. **Pré-requisitos:** JDK 21 instalado

2. Clone o repositório:
   ```bash
   git clone https://github.com/Lanzoni15/delivery-api-arthur-lanzoni.git
``

3. Acesse a pasta do projeto:
   ```bash
    cd delivery-api-arthur-lanzoni
``

4. Execute a aplicação:
   ```bash
    ./mvnw spring-boot:run
``

5. Acesse no navegador:

- Health Check: http://localhost:8080/health
- Info: http://localhost:8080/info
- Console H2: http://localhost:8080/h2-console

## 📋 Endpoints

- GET /health - Retorna status da aplicação e versão Java
- GET /info - Retorna informações da aplicação
- GET /h2-console - Console do banco H2 (em memória)

## 🔧 Configuração

- Porta: 8080
- Banco: H2 em memória
- Profile: development
- DevTools: hot reload ativado

👨‍💻 Desenvolvedor

Arthur Lanzoni Macedo - Turma Arquitetura de sistemas API REST Full com Java Springboot
Desenvolvido com JDK 21 e Spring Boot 3.2.x

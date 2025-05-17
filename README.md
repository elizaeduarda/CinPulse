# 🎬 Cinepulse

Sistema de avaliação de filmes e séries desenvolvido com **Java Spring MVC**.

## 📌 Descrição

O Cinepulse é uma aplicação web que permite aos usuários avaliarem filmes e séries, criar listas personalizadas e gerenciar seu perfil. Usuários administradores podem gerenciar os conteúdos do sistema, acompanhar dados via dashboards e gerenciar usuários.

---

## 👤 Tipos de Usuário

### 🔹 Administrador
- Gerencia filmes e séries (Adicionar, Editar, Deletar, Listar).
- Acompanha dados no dashboard (ex.: número de avaliações, usuários ativos).
- Gerencia usuários (visualizar, editar tipo de acesso e deletar).

### 🔸 Usuário Comum
- Avalia filmes e séries com notas e comentários.
- Cria e edita listas personalizadas com seus conteúdos favoritos.
- Gerencia suas próprias avaliações (CRUD).
- Altera sua foto, senha e nome de usuário (exceto o e-mail).

---

## 🛠️ Tecnologias Utilizadas

- Java 17
- Spring Boot
- Spring MVC
- Spring Data JPA
- Thymeleaf
- Hibernate
- SQL
- HTML5, CSS3, JS

---

## 📁 Estrutura de Pastas

```bash
src/
 └── main/
     ├── java/
     │    └── com/seuusuario/cinepulse/
     │         ├── controller/
     │         ├── model/
     │         ├── repository/
     │         ├── service/
     │         └── CinepulseApplication.java
     └── resources/
          ├── templates/
          ├── static/
          └── application.properties

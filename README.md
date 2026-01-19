<h1 align="center">diver.sos - Back-end</h1>

<p align="center">
  <img width="286.56" height="229.92" alt="Logo diver.sos" src="https://github.com/user-attachments/assets/3bccd4c7-386d-401e-b7fb-2b422c53b3c2" />
</p>

<p align="center">
  API REST responsável por gerenciar a inteligência, segurança e persistência de dados para a comunidade LGBTQIAPN+.
</p>

---

## 🧠 Sobre o projeto

> O back-end do **diver.sos** fornece a infraestrutura necessária para a listagem de vagas, grupos de apoio e notícias, além de gerenciar a autenticação e permissões de usuários.
>
> A API foi desenvolvida pela equipe **Atemporal** como parte do Projeto Integrado I da Universidade Federal do Ceará (UFC).

---

## 🚀 Funcionalidades Principais

- **Gestão de Usuários:** Autenticação via JWT (JSON Web Token) e controle de acesso baseado em cargos (ADMIN, MODERADOR, RH, USUARIO).
- **Recuperação de Senha:** Fluxo automatizado com envio de e-mail e tokens de segurança temporários.
- **Gestão de Conteúdo:** CRUD de vagas, grupos, notícias e habilidades.
- **Upload de Arquivos:** Processamento e armazenamento de imagens para perfis, banners e notícias.
- **Favoritos:** Sistema de persistência de conteúdos salvos por usuário.

---

<h3 align="center">Tecnologias Utilizadas</h3>

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="Java" width="45"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" alt="Spring Boot" width="45"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" alt="MySQL" width="45"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/maven/maven-original.svg" alt="Maven" width="45"/>
</p>

- **Linguagem:** Java 22 ou superior
- **Framework:** Spring Boot 3.x
- **Segurança:** Spring Security & JWT
- **Banco de Dados:** MySQL 8.0+
- **Serviço de E-mail:** Spring Mail (SMTP)

---

## ⚙️ Instalação e Execução (Via Release)

Para facilitar o uso, disponibilizamos o executável da aplicação nas [Releases](https://github.com/seu-usuario/seu-repositorio/releases).

### 📋 Pré-requisitos
1. **Java Runtime Environment (JRE) 22** ou superior instalado e configurado no PATH.
2. **MySQL Server** instalado e rodando localmente.

### ⚠️ Configuração Obrigatória do Banco de Dados

Antes de rodar a aplicação pela primeira vez, você deve criar o banco de dados manualmente. 
Abra o seu terminal MySQL ou MySQL Workbench e execute:

```sql
CREATE DATABASE diversos;

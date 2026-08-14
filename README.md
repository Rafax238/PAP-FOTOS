<div align="center">

  <img src="./assets/images/Logo.png" width="90" alt="Cidadão+ Logo">

  # Cidadão+ | Gestão Urbana Inteligente

  **Plataforma digital para participação cidadã e gestão de ocorrências urbanas**

  <br>

  [![PHP](https://img.shields.io/badge/PHP-8.x-777BB4?style=for-the-badge&logo=php&logoColor=white)](https://www.php.net/)
  [![MySQL](https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)
  [![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
  [![PHPMailer](https://img.shields.io/badge/PHPMailer-E--mail-0047AB?style=for-the-badge)](https://github.com/PHPMailer/PHPMailer)

  <br><br>

  🎓 **Projeto de Aptidão Profissional (PAP)**  
  📚 **Curso:** Técnico de Gestão e Programação de Sistemas Informáticos  
  📅 **Ano:** 2026

</div>

---

## 📖 Sobre o Projeto

O **Cidadão+** é uma plataforma web desenvolvida para aproximar **cidadãos e entidades públicas**, permitindo o reporte e acompanhamento de ocorrências urbanas de forma digital.

A plataforma permite que os cidadãos comuniquem problemas existentes na sua área e acompanhem o respetivo estado de resolução, enquanto os administradores dispõem de ferramentas para gerir utilizadores, ocorrências e informação administrativa.

O projeto foi desenvolvido como **Prova de Aptidão Profissional**, tendo como objetivo aplicar conhecimentos de desenvolvimento web, bases de dados, segurança e gestão de sistemas.

---

## 🎯 Objetivos

O projeto foi desenvolvido com os seguintes objetivos:

- 📍 Facilitar o reporte de ocorrências urbanas
- 📊 Permitir o acompanhamento do estado das ocorrências
- 🏛️ Disponibilizar ferramentas de gestão para administradores
- 👥 Centralizar informação relacionada com cidadãos e ocorrências
- 🔐 Implementar mecanismos de autenticação e segurança
- 📧 Automatizar processos relacionados com recuperação de conta e autenticação

---

## ✨ Principais Diferenciais

### 📍 Georreferenciação

Permite associar ocorrências a uma localização, facilitando a identificação e gestão dos problemas reportados.

### 📊 Gestão Centralizada

O painel administrativo permite gerir diferentes áreas da plataforma a partir de um único local.

### 🔐 Segurança

O sistema inclui mecanismos de proteção de contas, utilização de **Bcrypt** para passwords e autenticação de dois fatores através de **2FA**.

### 📧 Comunicação por E-mail

O sistema utiliza **PHPMailer** para processos relacionados com recuperação de conta e envio de tokens de autenticação.

---

## 🛠️ Tecnologias Utilizadas

| Área | Tecnologia | Utilização |
| :--- | :--- | :--- |
| **Backend** | `PHP 8.x` | Lógica da aplicação e processamento do sistema |
| **Frontend** | `HTML5` | Estrutura das páginas |
| **Frontend** | `CSS3` | Estilização e responsividade |
| **Frontend** | `JavaScript` | Interatividade e funcionalidades dinâmicas |
| **Base de Dados** | `MySQL` | Armazenamento e gestão dos dados |
| **Segurança** | `Bcrypt` | Hashing seguro de passwords |
| **Autenticação** | `2FA` | Camada adicional de segurança |
| **E-mail** | `PHPMailer` | Envio de e-mails e tokens |

---

# 🚀 Funcionalidades

## 👤 Área do Cidadão

- 📍 Reporte de ocorrências
- 🖼️ Submissão de imagens
- 🏷️ Seleção de categorias
- 📊 Dashboard pessoal
- 👤 Gestão do perfil
- 🔐 Autenticação segura
- 🔑 Recuperação de password
- 🛡️ Autenticação de dois fatores

---

## ⚙️ Área Administrativa

- 👥 Gestão de utilizadores
- ✏️ Edição de dados
- 📋 Gestão de ocorrências
- 📊 Visualização de informação
- 🗺️ Gestão de freguesias
- 🔐 Gestão de permissões

---

# 🔐 Segurança

A segurança foi uma das áreas consideradas durante o desenvolvimento do projeto.

### Medidas implementadas

- 🔒 Passwords protegidas através de **Bcrypt**
- 🛡️ Autenticação de dois fatores
- 📧 Validação através de tokens enviados por e-mail
- 🔑 Sistema de recuperação de conta
- 👥 Controlo de permissões de utilizadores

---

# 📸 Demonstração

## 🔐 Módulo 1 — Acesso e Autenticação

<details open>
<summary><b>Ver imagens</b></summary>

<br>

| Página Inicial | Login | Registo |
| :---: | :---: | :---: |
| <img src="./assets/images/module-1-auth/01-home.png" width="260"> | <img src="./assets/images/module-1-auth/02-login.png" width="260"> | <img src="./assets/images/module-1-auth/03-register.png" width="260"> |

</details>

---

## 🛡️ Módulo 2 — Segurança & 2FA

<details>
<summary><b>Ver imagens</b></summary>

<br>

| Recuperação | Validação 2FA | Token E-mail |
| :---: | :---: | :---: |
| <img src="./assets/images/module-2-security/04-password-reset.png" width="260"> | <img src="./assets/images/module-2-security/08-2fa-input.png" width="260"> | <img src="./assets/images/module-2-security/09-2fa-email-token.png" width="260"> |

</details>

---

## 🙋‍♂️ Módulo 3 — Painel do Cidadão

<details>
<summary><b>Ver imagens</b></summary>

<br>

| Reportar Ocorrência | Dashboard Pessoal | Perfil de Utilizador |
| :---: | :---: | :---: |
| <img src="./assets/images/module-3-citizen/10-report-issue.png" width="260"> | <img src="./assets/images/module-3-citizen/12-dashboard.png" width="260"> | <img src="./assets/images/module-3-citizen/11-user-profile.png" width="260"> |

</details>

---

## ⚙️ Módulo 4 — Painel Administrativo

<details>
<summary><b>Ver imagens</b></summary>

<br>

| Gestão de Utilizadores | Editar Dados | Ocorrências | Freguesias |
| :---: | :---: | :---: | :---: |
| <img src="./assets/images/module-4-admin/14-user-management.png" width="200"> | <img src="./assets/images/module-4-admin/16-edit-data.png" width="200"> | <img src="./assets/images/module-4-admin/17-report.png" width="200"> | <img src="./assets/images/module-4-admin/20-parishes.png" width="200"> |

</details>

---

# 🧠 O que este projeto demonstra

Este projeto permitiu-me trabalhar em várias áreas do desenvolvimento de software:

- Desenvolvimento **Full-Stack**
- Desenvolvimento de interfaces web
- Programação em PHP
- Desenvolvimento de funcionalidades com JavaScript
- Bases de dados relacionais
- Autenticação e gestão de sessões
- Segurança de passwords
- Autenticação de dois fatores
- Envio de e-mails
- Gestão de utilizadores
- Desenvolvimento de dashboards
- Organização e estruturação de um projeto completo

---

# 👨‍💻 Desenvolvedor

<div align="center">

### Rafael

**Web Developer**

<a href="https://github.com/Rafax238">
  <img src="https://img.shields.io/badge/GitHub-Rafax238-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Rafael">
</a>

</div>

---

<div align="center">

  <br>

  **Cidadão+**

  *Projeto desenvolvido para a Prova de Aptidão Profissional • 2026*

</div>

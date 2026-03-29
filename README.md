# 🏙️ Cidadão+ — Gestão Urbana Inteligente

> **Projeto de Aptidão Profissional (PAP)**
> Curso Técnico de Gestão e Programação de Sistemas Informáticos • **2026**

---

## 📝 Descrição do Projeto

O **Cidadão+** é uma plataforma web inovadora concebida para estreitar a ligação entre os munícipes e a administração pública (Câmaras Municipais e Juntas de Freguesia).

A aplicação funciona como um canal direto e centralizado que permite ao cidadão reportar, monitorizar e acompanhar a resolução de ocorrências urbanas (ex: buracos na via pública, iluminação avariada, recolha de monos) em tempo real. O objetivo é promover uma cidade mais assistida, eficiente e transparente, otimizando os recursos municipais e a satisfação do cidadão.

---

## 🛠️ Stack Tecnológica

Para o desenvolvimento da plataforma, foi selecionada uma stack robusta, segura e de alto desempenho:

| Camada | Tecnologias |
| :--- | :--- |
| **Backend** | ![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white) |
| **Frontend** | ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black) |
| **Segurança & Comunicação**| **Autenticação 2FA** (Dois Fatores), **PHPMailer** (Notificações Seguras), Encriptação de Passwords (bcrypt) |

---

## 🚀 Funcionalidades Chave

* **Reporte Georreferenciado:** Submissão de ocorrências com localização exata e evidências fotográficas.
* **Acompanhamento em Tempo Real:** O cidadão recebe notificações via e-mail sobre a mudança de estado do seu pedido (Pendente ➡️ Em Resolução ➡️ Resolvido).
* **Painel Administrativo Completo:** Ferramentas para as autarquias gerirem triagem, atribuição a equipas/empresas externas e análise estatística.
* **Segurança Reforçada:** Proteção de dados dos utilizadores com login seguro e verificação de identidade por e-mail (2FA).

---

## 📸 Demonstração do Sistema (Galeria)

Abaixo, apresentamos o fluxo visual da plataforma, organizado por módulos funcionais.

<div align="center">

### 🔐 Módulo 1: Acesso e Registo
*A porta de entrada para a cidadania digital. Interface intuitiva para autenticação e criação de novas contas.*

| ![01. Página Inicial](https://media.discordapp.net/attachments/1487605066327130332/1487616902690766979/1.png?format=webp&quality=lossless&width=800) | ![02. Login](https://media.discordapp.net/attachments/1487605066327130332/1487616903336951920/2.png?format=webp&quality=lossless&width=800) | ![03. Registo](https://media.discordapp.net/attachments/1487605066327130332/1487616904024555651/3.png?format=webp&quality=lossless&width=800) |
| :---: | :---: | :---: |
| **01. Página Inicial**<br>Landing page informativa e de boas-vindas. | **02. Login**<br>Interface de autenticação segura. | **03. Registo**<br>Formulário de adesão para novos cidadãos. |

<br>

### 🛡️ Módulo 2: Segurança e Recuperação (2FA & PHPMailer)
*Garantia da integridade dos dados através de fluxos de recuperação de senha e autenticação de dois fatores via e-mail.*

| ![04. Recuperação](https://media.discordapp.net/attachments/1487605066327130332/1487616904461025471/4.png?format=webp&quality=lossless&width=800) | ![05. E-mail de Redefinição](https://media.discordapp.net/attachments/1487605066327130332/1487616904825667765/5.png?format=webp&quality=lossless) | ![06. Redefinição de Senha](https://media.discordapp.net/attachments/1487605066327130332/1487616905211547788/6.png?format=webp&quality=lossless&width=800) |
| :---: | :---: | :---: |
| **04. Recuperação**<br>Pedido de redefinição de password. | **05. E-mail de Redefinição**<br>Notificação gerada pelo PHPMailer. | **06. Redefinição de Senha**<br>Definição da nova credencial de acesso. |

| ![07. Verificação 2FA](https://media.discordapp.net/attachments/1487605066327130332/1487616905547223040/7.png?format=webp&quality=lossless&width=800) | ![08. Inserção de Código](https://media.discordapp.net/attachments/1487605066327130332/1487616905882632254/8.png?format=webp&quality=lossless&width=800) | ![09. Token por E-mail](https://media.discordapp.net/attachments/1487605066327130332/1487616906239283340/9.png?format=webp&quality=lossless) |
| :---: | :---: | :---: |
| **07. Verificação 2FA**<br>Página de processamento do token. | **08. Inserção de Código**<br>Interface para validar o código de segurança. | **09. Token por E-mail**<br>Código OTP enviado com segurança. |

<br>

### 🙋‍♂️ Módulo 3: Interface do Cidadão
*Onde a participação ativa acontece. Área exclusiva para o cidadão gerir os seus dados e reportar problemas.*

| ![10. Reportar Ocorrência](https://media.discordapp.net/attachments/1487605066327130332/1487616906645995752/10.png?format=webp&quality=lossless&width=800) | ![11. Dados Pessoais](https://media.discordapp.net/attachments/1487605066327130332/1487616973469782066/11.png?format=webp&quality=lossless&width=800) | ![12. Dashboard](https://media.discordapp.net/attachments/1487605066327130332/1487616973952122950/12.png?format=webp&quality=lossless&width=800) |
| :---: | :---: | :---: |
| **10. Reportar Ocorrência**<br>Formulário para submissão de incidentes urbanos. | **11. Dados Pessoais**<br>Gestão do perfil e preferências do utilizador. | **12. Dashboard**<br>Visão geral e estado das ocorrências submetidas. |

<br>

### ⚙️ Módulo 4: Painel Administrativo (Backoffice)
*Ferramentas poderosas para a administração pública. Controlo total sobre utilizadores, entidades e fluxo de resolução de ocorrências.*

| ![13. Dashboard Admin](https://media.discordapp.net/attachments/1487605066327130332/1487616974753235074/14.png?format=webp&quality=lossless&width=800) | ![14. Gestão de Utilizadores](https://media.discordapp.net/attachments/1487605066327130332/1487616975114076422/15.png?format=webp&quality=lossless&width=800) | ![15. Edição de Utilizador](https://media.discordapp.net/attachments/1487605066327130332/1487616975445299272/16.png?format=webp&quality=lossless&width=800) | ![16. Edição de Dados](https://media.discordapp.net/attachments/1487605066327130332/1487616975852015658/17.png?format=webp&quality=lossless&width=800) |
| :---: | :---: | :---: | :---: |
| **13. Dashboard Admin**<br>Métricas globais e estatísticas. | **14. Gestão de Utilizadores**<br>Listagem e controlo de acessos. | **15. Edição de Utilizador**<br>Modificação rápida de perfis. | **16. Edição de Dados**<br>Atualização administrativa de informações. |

| ![17. Ocorrências](https://media.discordapp.net/attachments/1487605066327130332/1487616977055776879/19.png?format=webp&quality=lossless&width=800) | ![18. Tipos de Ocorrência](https://media.discordapp.net/attachments/1487605066327130332/1487616977538125844/20.png?format=webp&quality=lossless&width=800) |
| :---: | :---: |
| **17. Ocorrências**<br>Gestão e triagem de todos os incidentes recebidos. | **18. Tipos de Ocorrência**<br>Configuração técnica de categorias e prioridades. |

| ![20. Freguesias](https://media.discordapp.net/attachments/1487605066327130332/1487617034316415036/21.png?format=webp&quality=lossless&width=800) | ![21. Concelhos](https://media.discordapp.net/attachments/1487605066327130332/1487617034681454603/22.png?format=webp&quality=lossless&width=800) | ![22. Empresas](https://media.discordapp.net/attachments/1487605066327130332/1487617035063263374/23.png?format=webp&quality=lossless&width=800) |
| :---: | :---: | :---: |
| **20. Freguesias**<br>Gestão territorial: Listagem de Freguesias. | **21. Concelhos**<br>Gestão territorial: Listagem de Concelhos. | **22. Empresas**<br>Registo de Entidades Prestadoras de Serviço. |

</div>

---

## 👨‍💻 Desenvolvedor

Este projeto foi desenvolvido com dedicação como parte integrante da Prova de Aptidão Profissional.

* **Rafael** - *Desenvolvimento Fullstack, Design de Base de Dados e Segurança.* - PAP 2026.

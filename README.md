# <img src="https://media.discordapp.net/attachments/1171448609405943819/1487516944725966982/LogoSemFundo.png?ex=69c96d9c&is=69c81c1c&hm=d6ed4df3bde8dd577d86f25ae81bd0094856390955a75946dc763cac3c012f99&=&format=webp&quality=lossless" alt="Cidadão+ Logo" width="50" valign="middle"> Cidadão+ — Gestão Urbana Inteligente

> **Projeto de Aptidão Profissional (PAP)**
> Curso Técnico de Gestão e Programação de Sistemas Informáticos • **2026**

---

<div align="center">
  <img src="https://cdn.discordapp.com/attachments/1487605066327130332/1487605066725855372/Logo.png?ex=69c9bfae&is=69c86e2e&hm=4d8029cbfabcd2d130d61ae9dfffb20156e44e38771fa1a68cee962130e2827c&" alt="Cidadão+ Logótipo Grande" width="200">
  <br>
  <h1>Cidadão+</h1>
  <p><i>A aproximar os munícipes da administração pública.</i></p>
</div>

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

| ![01. Página Inicial](https://media.discordapp.net/attachments/1487605066327130332/1487616902690766979/1.png?ex=69c9cab4&is=69c87934&hm=d34e6763c6e576aac792f43978257822dd96d57f38cd8066848092832ab92f90&=&format=webp&quality=lossless&width=1768&height=840) | ![02. Login](https://media.discordapp.net/attachments/1487605066327130332/1487616903336951920/2.png?ex=69c9cab4&is=69c87934&hm=ddf72e755dde587c42b046cb4a92429cc60aaf7e80b63f7b9b6ea1b2068da5c6&=&format=webp&quality=lossless&width=1768&height=840) | ![03. Registo](https://media.discordapp.net/attachments/1487605066327130332/1487616904024555651/3.png?ex=69c9cab4&is=69c87934&hm=a614ceff09a48d910178d34f6c66e59458bb921ad4984b282cca082e9fec99f9&=&format=webp&quality=lossless&width=1768&height=838) |
| :---: | :---: | :---: |
| **01. Página Inicial**<br>Landing page informativa e de boas-vindas. | **02. Login**<br>Interface de autenticação segura. | **03. Registo**<br>Formulário de adesão para novos cidadãos. |

<br>

### 🛡️ Módulo 2: Segurança e Recuperação (2FA & PHPMailer)
*Garantia da integridade dos dados através de fluxos de recuperação de senha e autenticação de dois fatores via e-mail.*

| ![04. Recuperação](https://media.discordapp.net/attachments/1487605066327130332/1487616904461025471/4.png?ex=69c9cab4&is=69c87934&hm=69f3421a090e81b69a6141a275ca697516fb49abd80deaeb21adc241acdb1739&=&format=webp&quality=lossless&width=1768&height=838) | ![05. E-mail de Redefinição](https://media.discordapp.net/attachments/1487605066327130332/1487616904825667765/5.png?ex=69c9cab4&is=69c87934&hm=62f442ada7d5df6bd73a47970cd459caead8805be95dfa9df4bee71118945d21&=&format=webp&quality=lossless) | ![06. Redefinição de Senha](https://media.discordapp.net/attachments/1487605066327130332/1487616905211547788/6.png?ex=69c9cab4&is=69c87934&hm=cd0b71f70d89ba9e5824ef8cc01a51422cb4c065a03496f2b7901350dc4ee705&=&format=webp&quality=lossless&width=1768&height=839) |
| :---: | :---: | :---: |
| **04. Recuperação**<br>Pedido de redefinição de password. | **05. E-mail de Redefinição**<br>Notificação gerada pelo PHPMailer. | **06. Redefinição de Senha**<br>Definição da nova credencial de acesso. |

| ![07. Verificação 2FA](https://media.discordapp.net/attachments/1487605066327130332/1487616905547223040/7.png?ex=69c9cab4&is=69c87934&hm=0accefb4aa4715bdd482390c03ec72fa868e63c3c20567ea6f5f560bb011305d&=&format=webp&quality=lossless&width=1768&height=837) | ![08. Inserção de Código](https://media.discordapp.net/attachments/1487605066327130332/1487616905882632254/8.png?ex=69c9cab4&is=69c87934&hm=d138e20e936edd5b58bc14ad8567eacc55365ef4eba8d9964649873226f2862e&=&format=webp&quality=lossless&width=1768&height=844) | ![09. Token por E-mail](https://media.discordapp.net/attachments/1487605066327130332/1487616906239283340/9.png?ex=69c9cab5&is=69c87935&hm=6a0e58701387fb16a73df9faadf02ec577eaeb83c0310bae17edbd9fa7c3e2bd&=&format=webp&quality=lossless) |
| :---: | :---: | :---: |
| **07. Verificação 2FA**<br>Página de processamento do token. | **08. Inserção de Código**<br>Interface para validar o código de segurança. | **09. Token por E-mail**<br>Código OTP enviado com segurança. |

<br>

### 🙋‍♂️ Módulo 3: Interface do Cidadão
*Onde a participação ativa acontece. Área exclusiva para o cidadão gerir os seus dados e reportar problemas.*

| ![10. Reportar Ocorrência](https://media.discordapp.net/attachments/1487605066327130332/1487616906645995752/10.png?ex=69c9cab5&is=69c87935&hm=080e0419155eab87fea81b4a9712f79b687b47e396866e71b5fedbc6b983ea50&=&format=webp&quality=lossless&width=1768&height=834) | ![11. Dados Pessoais](https://media.discordapp.net/attachments/1487605066327130332/1487616973469782066/11.png?ex=69c9cac5&is=69c87945&hm=3d4db0d5d898767e7918302e15fbad7fb94eaf68672d66a07e578dbce932b4d6&=&format=webp&quality=lossless&width=1768&height=845) | ![12. Dashboard](https://media.discordapp.net/attachments/1487605066327130332/1487616973952122950/12.png?ex=69c9cac5&is=69c87945&hm=c8746bcfd57ee7d690ce0f781c997782825c19b9b5583675555b4ce396324ad8&=&format=webp&quality=lossless&width=1768&height=837) |
| :---: | :---: | :---: |
| **10. Reportar Ocorrência**<br>Formulário para submissão de incidentes urbanos. | **11. Dados Pessoais**<br>Gestão do perfil e preferências do utilizador. | **12. Dashboard**<br>Visão geral e estado das ocorrências submetidas. |

<br>

### ⚙️ Módulo 4: Painel Administrativo (Backoffice)
*Ferramentas poderosas para a administração pública. Controlo total sobre utilizadores, entidades e fluxo de resolução de ocorrências.*

| ![13. Dashboard Admin](https://media.discordapp.net/attachments/1487605066327130332/1487616974753235074/14.png?ex=69c9cac5&is=69c87945&hm=c3bf4306eef1858ee55dc445fa92dad99e321f9db3c5569116037181aa1e98c6&=&format=webp&quality=lossless&width=1768&height=840) | ![14. Gestão de Utilizadores](https://media.discordapp.net/attachments/1487605066327130332/1487616975114076422/15.png?ex=69c9cac5&is=69c87945&hm=e2cf4ed42c3e601c6e2150c183aae5eb3761db3e63f0c739975f4399116140d3&=&format=webp&quality=lossless&width=1768&height=838) | ![15. Edição de Utilizador](https://media.discordapp.net/attachments/1487605066327130332/1487616975445299272/16.png?ex=69c9cac5&is=69c87945&hm=a94c2db4b21b5991703b6d61e2d4176420ecc306de7210c9ae7c8b511f487168&=&format=webp&quality=lossless&width=1768&height=840) | ![16. Edição de Dados](https://media.discordapp.net/attachments/1487605066327130332/1487616975852015658/17.png?ex=69c9cac5&is=69c87945&hm=7f619e26c0a96cd940cb03ce8b149bed8b4de449d0d8b2dfe7cbe815a87318ae&=&format=webp&quality=lossless&width=1768&height=840) |
| :---: | :---: | :---: | :---: |
| **13. Dashboard Admin**<br>Métricas globais e estatísticas. | **14. Gestão de Utilizadores**<br>Listagem e controlo de acessos. | **15. Edição de Utilizador**<br>Modificação rápida de perfis. | **16. Edição de Dados**<br>Atualização administrativa de informações. |

| ![17. Ocorrências](https://media.discordapp.net/attachments/1487605066327130332/1487616977055776879/19.png?ex=69c9cac5&is=69c87945&hm=7ce05f8cd1007bc32a948f6b4fe3542513abc6463c87f9947b6ab333b3d60900&=&format=webp&quality=lossless&width=1768&height=841) | ![18. Tipo Ocorrências](https://media.discordapp.net/attachments/1487605066327130332/1487616977538125844/20.png?ex=69c9cac6&is=69c87946&hm=57361f1d31b726555957a60ecdabb14dd6d475781455efc9ee21952005c51ab9&=&format=webp&quality=lossless&width=1768&height=844) |
| :---: | :---: |
| **17. Ocorrências**<br>Gestão e triagem de todos os incidentes recebidos. | **18. Tipos de Ocorrência**<br>Configuração técnica de categorias e prioridades. |

| ![20. Freguesias](https://media.discordapp.net/attachments/1487605066327130332/1487617034316415036/21.png?ex=69c9cad3&is=69c87953&hm=0ba2ef9ff5a516dcb9796b90aa85ef1a50604e32c66ca2ea60a7fb16a38d9b41&=&format=webp&quality=lossless&width=1768&height=841) | ![21. Concelhos](https://media.discordapp.net/attachments/1487605066327130332/1487617034681454603/22.png?ex=69c9cad3&is=69c87953&hm=7798d3ec9196751c46e50e29327923446fd4fa0a51ea544249d2e3967893f5d7&=&format=webp&quality=lossless&width=1768&height=841) | ![22. Empresas](https://media.discordapp.net/attachments/1487605066327130332/1487617035063263374/23.png?ex=69c9cad3&is=69c87953&hm=b16044bd812e70fd85e95baf0b96a5a27eea3833654a23086f389051acc4f544&=&format=webp&quality=lossless&width=1768&height=838) |
| :---: | :---: | :---: |
| **20. Freguesias**<br>Gestão territorial: Listagem de Freguesias. | **21. Concelhos**<br>Gestão territorial: Listagem de Concelhos. | **22. Empresas**<br>Registo de Entidades Prestadoras de Serviço. |

</div>

---

## 👨‍💻 Desenvolvedor

Este projeto foi desenvolvido com dedicação como parte integrante da Prova de Aptidão Profissional.

* **Rafael** - *Desenvolvimento Fullstack, Design de Base de Dados e Segurança.* - PAP 2026.

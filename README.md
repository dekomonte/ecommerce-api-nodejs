# 🛒 E-Commerce API - Node.js

![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)

API RESTful completa desenvolvida em Node.js para o backend de uma vitrine de e-commerce. O projeto simula um ambiente de produção real, englobando desde a manipulação de dados (CRUD) até a implementação de regras de negócio, envio de e-mails e autenticação segura.

> 🎓 *Este projeto foi desenvolvido para consolidar conceitos de arquitetura backend e APIs REST, acompanhando o curso [Criando APIs com Node](https://balta.io/cursos/criando-apis-com-node) da balta.io.*

---

## 🚀 Principais Funcionalidades

O projeto contempla os seguintes recursos e regras de negócio:

* **Gestão de Produtos:** Operações completas de CRUD (Criar, Ler, Atualizar e Excluir), busca por *slug*, *ID* e *tags*, além de upload de imagens.
* **Gestão de Clientes & Pedidos:** Modelagem de dados relacionais e não-relacionais, vinculando clientes aos seus respectivos pedidos e itens.
* **Segurança & Autenticação:** Geração e validação de tokens JWT para rotas privadas, garantindo controle de acesso (Autorização).
* **Comunicação:** Integração com serviço de envio de e-mails (boas-vindas para novos clientes).
* **Validação:** Tratamento de erros, validação de dados de entrada e configurações de CORS.

---

## 🛠️ Tecnologias e Ferramentas

* **Linguagem / Plataforma:** JavaScript (Node.js v22.11)
* **Banco de Dados:** MongoDB (executado via Docker)
* **Gerenciador de Pacotes:** npm (v10.9)
* **Teste de Rotas:** Postman
* **Conceitos Aplicados:** Padrão MVC (Models, Controllers, Repositories), Async/Await, Middlewares.


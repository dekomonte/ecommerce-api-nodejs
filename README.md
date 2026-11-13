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

---

## ⚙️ Como Executar o Projeto Localmente

Para rodar esta API na sua máquina, você precisará do [Node.js](https://nodejs.org/) e do [Docker](https://www.docker.com/) instalados.

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/SEU_USUARIO/ecommerce-api-nodejs.git
   cd ecommerce-api-nodejs
   ```

2. **Instale as dependências:**
   ```bash
   npm install
   ```

3. **Suba o contêiner do MongoDB via Docker:**
   *(Consulte o [guia de configuração do MongoDB com Docker](https://blog.balta.io/mongodb-docker/) caso não tenha o banco configurado localmente).*
   ```bash
   docker run --name mongo -p 27017:27017 -d mongo
   ```

4. **Inicie o servidor (Modo Dev com Nodemon):**
   ```bash
   npm start
   ```
   > A API estará rodando em `http://localhost:3000` (ou na porta configurada no seu ambiente).

---

## 📚 Jornada de Aprendizado (Ementa)

<details>
<summary><b>Clique para expandir os tópicos abordados e implementados neste projeto</b></summary>

**Fundamentos e Configuração**
* Instalação Node, NPM e VS Code
* `npm init` e instalação de pacotes (Configuração do NPM Start e Nodemon)
* Criando um servidor Web (Express)
* Normalizando portas e gerenciando Erros do Servidor
* Iniciando o Debug

**Arquitetura e Roteamento**
* Separando o Servidor
* Padrão de Projeto (Rotas, Controllers, Repositórios)
* Operações CRUD REST

**Banco de Dados (MongoDB)**
* MongoDB Setup via Docker
* Integração com Mongoose (Models)
* Modelagem: Produtos, Clientes (Customer), Pedidos (Order) e Itens (OrderItems)

**Regras de Negócio e Funcionalidades**
* Buscas avançadas (slug, ID, tags)
* Operações assíncronas (Async/Await)
* Validações de dados de entrada
* Arquivo de Configurações
* Upload de Imagem de Produto
* Enviando E-mail de Boas-vindas

**Segurança e Deploy**
* Autenticação e Autorização (JWT)
* Habilitando CORS
* Publicando a API
</details>

---
*Desenvolvido com ☕ e foco em boas práticas de backend.*

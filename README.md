# 💸 Sistema DinDin – Módulo 3

Projeto desenvolvido como parte do Módulo 3 do curso de Desenvolvimento de Software (DDS T13), em parceria com [Luan Barradas](https://github.com/Luanbarradas). O objetivo foi construir uma **API RESTful completa** para gerenciamento financeiro pessoal.

---

## 🔧 Funcionalidades

A API permite que o usuário:

- Cadastre e edite sua conta
- Faça login com autenticação via token
- Visualize e edite seu perfil
- Liste categorias fixas
- Registre, edite e exclua transações financeiras
- Filtre transações por categoria
- Gere um extrato com somatório de entradas e saídas

---

## 🔐 Autenticação

- Utiliza **JWT** para autenticação
- Requisições protegidas exigem `Bearer Token` no header

---

## 🧠 Conceitos e práticas aplicadas

- Estruturação de API RESTful
- Criptografia de senhas com **bcrypt**
- Validações de entrada com mensagens apropriadas
- Persistência de dados com **PostgreSQL**
- Modelagem e manipulação de dados relacionais
- Organização modular: rotas, controladores, middlewares

---

## 🛠 Tecnologias utilizadas

- Node.js
- Express.js
- PostgreSQL
- bcrypt
- JWT (jsonwebtoken)
- date-fns
- Dotenv
  
---

## 🧪 Como rodar o projeto

1. Clone o repositório
2. Crie um banco de dados PostgreSQL chamado `dindin`
3. Importe o arquivo `script.sql` com as tabelas e categorias
4. Configure o `.env` com os dados de conexão
5. Instale as dependências:

```bash
npm install
```

6. Inicie o servidor:

```bash
node index.js
```

---

## 👨‍💻 Contribuidores

- [João Batista Neto](https://github.com/Joaobneto1)
- [Luan Barradas](https://github.com/Luanbarradas)

---

## 🏷️ Tags

`nodejs` `express` `api-rest` `postgresql` `jwt` `autenticação` `back-end`

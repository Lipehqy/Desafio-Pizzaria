# 🍕 Sistema de Gestão para Pizzaria

## 📌 Descrição
Este projeto é um sistema web para gerenciamento de uma pizzaria, desenvolvido em Node.js com Express e SQLite.

O sistema permite:
- Autenticação de usuários com JWT
- Controle de perfis (Administrador, Atendente, Garçom)
- Gerenciamento de pizzas, clientes e usuários
- Criação e controle de pedidos
- Controle de mesas

Este projeto foi reorganizado a partir de um código legado sem estrutura definida, aplicando técnicas de engenharia reversa.

---------------------------------------

# 🚀 Tecnologias Utilizadas

- Node.js
- Express
- SQLite (sql.js)
- JSON Web Token (JWT)
- bcryptjs
- dotenv
- cors

---------------------------------------

## ⚙️ Pré-requisitos

- Node.js instalado
- npm instalado

---------------------------------------

## ▶️ Como executar o projeto

```bash
# Clonar o repositório
git clone <seu-repo>

# Entrar na pasta
cd sistema-pizzaria

# Instalar dependências
npm install

# Criar arquivo .env
PORT=3001
JWT_SECRET=secreto
DB_PATH=./pizzaria.db

# Popular banco
node seed.js

# Rodar servidor
node index.js
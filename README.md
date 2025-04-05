# GitHub Profile API 🖥️

## Descrição

API que permite consultar informações de um usuário no GitHub e listar seus repositórios mais populares.

## Tecnologias Utilizadas 🚀

- Node.js
- Express
- Axios
- CORS

## 📌 Como Instalar e Rodar 📌
git clone https://github.com/SEU-USUARIO/github-profile-api.git
cd github-profile-api
npm install
node server.js

# Como Usar 🔍

## Buscar um perfil 👤

GET /perfil/:username
Exemplo: http://localhost:3000/perfil/torvalds

## Listar repositórios

GET /perfil/:username/repos
Exemplo: http://localhost:3000/perfil/torvalds/repos

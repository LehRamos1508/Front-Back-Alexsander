
# 🍔 FrontBack-Alex – Sistema de Pedidos para Lanchonete

Projeto desenvolvido com o objetivo de integrar **Frontend em React Native (Expo)** e **Backend em Node.js (Express + MongoDB)**, simulando o fluxo completo de pedidos em uma lanchonete.

---

## 📱 Funcionalidades

- ✅ Cadastro de pedidos com:
  - Nome do cliente
  - Produto
  - Quantidade
- ✅ Listagem dos pedidos em tempo real
- ✅ Atualização de pedidos existentes
- ✅ Exclusão individual ou total dos pedidos

---

## 🛠️ Tecnologias Utilizadas

### 🚀 Backend (REST)
- Node.js
- Express
- Mongoose
- MongoDB
- Dotenv

### 📱 Frontend (FRONT)
- React Native com Expo
- React Native Paper

---

## ⚙️ Como executar o projeto

### 1. Clonar o repositório
```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd FrontBack-Alex
```

### 2. Iniciar o Backend
```bash
cd REST
npm install
touch .env
# Adicione no .env:
# DB_URL=mongodb://localhost:27017/lanchonete
npm start
```

### 3. Iniciar o Frontend
```bash
cd ../FRONT
npm install
npx expo start
```

> ⚠️ O app espera que a API esteja rodando em `http://localhost:3000`. Se for testar em dispositivo físico, será necessário substituir `localhost` pelo IP da sua máquina no código.

---

## 🧑‍🎓 Requisitos Atendidos (atividade)

- [x] Frontend com 3 campos de entrada
- [x] Listagem dos dados
- [x] Manipulação: cadastro, update e delete
- [x] Backend com schema alinhado ao layout
- [x] Pronto para demonstração em aula

---

## 📸 Demonstração

> (Adicione aqui prints ou GIFs da aplicação rodando)

---

## 👨‍💻 Autor

**Alexsander Ramos Ferreira**  
Desenvolvedor em formação pela Fatec Votorantim  
Projeto acadêmico - 2025

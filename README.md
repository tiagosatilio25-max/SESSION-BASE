# 🔐 Sistema de Login com Session e Cookies

Projeto desenvolvido durante as lives do canal **Desvendando o Código** para demonstrar, na prática, como funciona a autenticação utilizando **Node.js, Express, Sessions e Cookies**.

Neste projeto é possível entender todo o fluxo de autenticação, desde o envio das credenciais pelo Front-end até a criação da sessão no servidor e o controle de acesso às páginas protegidas.

---

## 🚀 O que o projeto faz

- Tela de Login
- Validação de usuário e senha
- Criação de Session no servidor
- Armazenamento do Cookie no navegador
- Dashboard protegido
- Verificação automática de autenticação
- Logout
- Expiração da sessão
- Integração completa entre Front-end e Back-end

---

## 🛠 Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript
- Node.js
- Express
- Express Session
- Cookies
- Fetch API

---

## 📚 Conceitos abordados

- HTTP Stateless
- Autenticação
- Session
- Cookies
- Middleware
- Rotas Públicas
- Rotas Protegidas
- Fetch API
- Async/Await
- JSON
- POST
- Headers HTTP
- DevTools (Application > Cookies)

---

## 📂 Estrutura do Projeto

```
projeto/
│
├── public/
│   ├── css/
│   ├── js/
│   ├── index.html
│   └── dashboard.html
│
├── server.js
├── package.json
└── README.md
```

---

## ▶️ Como executar

Clone o repositório

```bash
git clone https://github.com/marcoscaldas/sessionCookie.git
```

Entre na pasta

```bash
cd nome-do-repositorio
```

Instale as dependências

```bash
npm install
```

Inicie o servidor

```bash
node server.js
```

ou utilizando o Nodemon

```bash
nodemon server.js
```

Abra o navegador

```
http://localhost:3000
```

---

## 👤 Usuário para testes

```
Usuário:
admin

Senha:
123456
```

---

## 🔍 Como funciona

1. O usuário informa login e senha.

2. O Front-end envia uma requisição **POST** utilizando **Fetch API**.

3. O servidor valida as credenciais.

4. Uma Session é criada no servidor.

5. O navegador recebe um Cookie contendo o identificador da sessão.

6. Em cada nova requisição o Cookie é enviado automaticamente.

7. O servidor verifica a Session antes de permitir acesso às rotas protegidas.

8. Ao realizar Logout a Session é destruída e o usuário perde o acesso.

---

## 🎥 Aulas completas

### Backend

https://youtube.com/live/8lSOxEQu3kM

### Front-end

https://youtube.com/live/M3rlxITj17U

---

## 📸 Demonstração

Login

➡️

Dashboard

➡️

Logout

➡️

Session destruída

---

## 🎯 Objetivo

Este projeto foi desenvolvido com foco educacional para demonstrar como funciona a autenticação baseada em **Sessions e Cookies**, tecnologia amplamente utilizada em aplicações web.

O objetivo não é apenas ensinar código, mas explicar **como os sites conseguem manter um usuário autenticado mesmo depois de atualizar a página (F5)**.

---

## 📺 Canal

**Desvendando o Código**

Aprenda programação entendendo como as tecnologias realmente funcionam.

Se este projeto foi útil para você, considere deixar uma ⭐ no repositório.

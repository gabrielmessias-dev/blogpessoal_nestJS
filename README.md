# 📝 Blog Pessoal - Back-End

Este é o **back-end do meu Blog Pessoal**, desenvolvido com **NestJS**, que fornece uma API completa para gerenciamento de usuários, postagens e temas.  
O objetivo do projeto é criar uma plataforma onde cada usuário possa **criar, editar, listar e excluir suas postagens**, categorizadas por temas específicos.

---

## 🚀 Tecnologias Utilizadas

- **NestJS** - Framework Node.js para construção de APIs escaláveis  
- **TypeScript** - Tipagem estática e maior segurança no código  
- **MySQL** - Banco de dados local para desenvolvimento  
- **PostgreSQL** - Banco de dados utilizado em produção (Render)  
- **SQLite** - Banco leve para execução dos testes com Jest  
- **TypeORM** - ORM para mapeamento e manipulação das entidades  
- **JWT (JSON Web Token)** - Autenticação e autorização segura  
- **bcrypt** - Criptografia de senhas de usuários  
- **Swagger** - Documentação interativa da API  
- **Jest** - Testes unitários e de integração  

---

## 🧩 Estrutura do Projeto

O sistema é composto por três principais entidades:

- **Usuário** 👤: cadastro, login, autenticação e gerenciamento próprio de postagens  
- **Tema** 🏷️: classificação das postagens por assunto  
- **Postagem** ✍️: conteúdo criado e gerenciado pelos usuários  

Cada usuário pode **criar, visualizar, atualizar e excluir** suas postagens, além de **associar temas** a elas.

---

## 🔐 Autenticação e Segurança

O sistema utiliza **JWT** para autenticação e autorização de rotas protegidas.  
As senhas são criptografadas com **bcrypt** antes de serem armazenadas no banco de dados.

---

## 🧪 Testes

Durante o processo de testes automatizados com **Jest**, o banco de dados utilizado é o **SQLite**, garantindo leveza e isolamento do ambiente de produção.

Para executar os testes:
```
npm run test:e2e
```

🌐 Deploy
O back-end está hospedado no Render, utilizando o banco PostgreSQL em produção.
A documentação da API pode ser acessada diretamente pelo Swagger:

🔗 Documentação Swagger - Blog Pessoal -> https://blogpessoal-jjd1.onrender.com/

⚙️ Como Executar Localmente
Clone o repositório
```
git clone https://github.com/gabrielmessias-dev/blogpessoal_nestJS.git
```
Acesse a pasta do projeto

```
cd blog-pessoal-backend
```

Instale as dependências

```
npm install
```
Configure o arquivo .env
```
DATABASE_HOST=localhost
DATABASE_PORT=3306
DATABASE_USER=root
DATABASE_PASSWORD=root
DATABASE_NAME=db_blogpessoal
JWT_SECRET=sua_chave_secreta
```
Execute a aplicação

```
npm run start:dev
```
A aplicação será iniciada em:
👉 http://localhost:4000

📘 Próximos Passos
O próximo estágio do projeto é o desenvolvimento do Front-End em React, que irá consumir esta API e permitir a interação completa do usuário com o sistema.

👨‍💻 Autor
Gabriel Messias - Desenvolvedor Full Stack JS
🔗 LinkedIn - https://linkedin.com/in/gabrielmessias-dev

⭐ Se este projeto foi útil, não esqueça de deixar uma estrela no repositório!







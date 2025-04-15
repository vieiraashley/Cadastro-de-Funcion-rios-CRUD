# 🚀 CRUD de Funcionários - Backend com NestJS, Prisma e Supabase

Este projeto é uma API RESTful desenvolvida para gerenciar o cadastro de funcionários de uma empresa. É um CRUD completo que permite **criar, listar, atualizar e deletar** registros de colaboradores, com foco em escalabilidade, boas práticas e performance.

## 🛠️ Tecnologias Utilizadas

- [Node.js](https://nodejs.org/)
- [NestJS](https://nestjs.com/)
- [TypeScript](https://www.typescriptlang.org/)
- [Prisma ORM](https://www.prisma.io/)
- [Supabase (PostgreSQL)](https://supabase.com/)

## 📂 Estrutura do Projeto

src/ │ ├── modules/ │ └── funcionarios/ │ ├── funcionarios.controller.ts │ ├── funcionarios.service.ts │ └── funcionarios.module.ts │ ├── prisma/ │ └── schema.prisma │ └── main.ts

📬 Endpoints
Método	Rota	Descrição
GET	/funcionarios	Lista todos os funcionários
GET	/funcionarios/:id	Busca um funcionário por ID
POST	/funcionarios	Cria um novo funcionário
PUT	/funcionarios/:id	Atualiza os dados de um funcionário
DELETE	/funcionarios/:id	Remove um funcionário


👨‍💻 Autor
Desenvolvido por Ashley Vieira! 🛠️



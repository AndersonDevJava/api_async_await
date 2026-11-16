# API Assíncrona — JWT

**Objetivo:** compreender a construção e o fluxo de uma API assíncrona, integrando autenticação JWT, banco de dados e interface React.

**Stack tecnológica**

- **JavaScript / Node.js:** desenvolvimento do back-end com `async/await`.
- **Express:** gerenciamento de rotas e requisições HTTP.
- **Prisma ORM:** operações CRUD e comunicação com o banco.
- **PostgreSQL:** banco de dados relacional.
- **JWT:** autenticação e autorização.
- **React:** construção da interface e reutilização de componentes e Hooks.
- **Tailwind CSS:** estilização com classes utilitárias.

**Arquitetura**

- **ES Modules:** sistema de módulos JavaScript (`import` e `export`), configurado com `"type": "module"`.
- **Arquitetura Modular:** organização por funcionalidades (`users`, `auth`, `products`), separando responsabilidades entre controllers, services, routes e middlewares.

**Fluxo da API:**

Routes → Middlewares → Controller → Service → Prisma → PostgreSQL.

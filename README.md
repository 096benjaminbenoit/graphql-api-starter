# 🚀 Light Backend Starterpack

#### This project is a lightweight boilerplate, crafted to kick-start backend projects using TypeScript, TypeORM, GraphQL, Apollo Server, and Type-GraphQL. It's a robust and flexible foundation, ideal for swiftly building backend applications with some cool tech! 🌐🔧

## 📋 Prerequisites

Make sure you have Node.js installed on your machine to use this boilerplate. 🌲

## 🛠 Installation

1.  **Clone the Project**

    `git clone [https://github.com/096benjaminbenoit/backend-boilerplate]`

2.  **Install Dependencies**

    `npm install`

3.  **Configure Environment**

    - Create a `.env` file at the root of the project based on .env.example.
    - Add the necessary environment variables (for your database connection.). 🔑

4.  **Start the Application**
    `npm start`

## 📁 Project Structure

The project structure is deliberately simple, but there's nothing to stop you adding to it as you see fit!

```bash
├── src
│   ├── database
│      ├── DataSource.ts // database connexion
│   ├── entities // all entities
│   ├── inputs // all inputs/dto
│   ├── resolvers
│      ├── BookResolver.ts // a resolver example with CRUD
│      ├── UserResolver.ts // user gestion (signUp, login ...)
│   ├── types
│      ├── interfaces.ts // all interfaces
│   ├── utils
│      ├── auth.ts // password gestion and user authentication
│      ├── jwt.ts // jwt gestion
│      ├── security.ts // custom decorators to protect resolvers
├── index.ts
├── .env.example
```

Within the project there are simple examples of entities, inputs and resolvers to guide you.

### Make with love ❤️

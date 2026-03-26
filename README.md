# Deep Thoughts

![React](https://img.shields.io/badge/React-17-61DAFB?style=flat&logo=react&logoColor=white)
![Apollo Client](https://img.shields.io/badge/Apollo_Client-3-311C87?style=flat&logo=apollographql&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-4-000000?style=flat&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-5.x-47A248?style=flat&logo=mongodb&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-16-E10098?style=flat&logo=graphql&logoColor=white)
![License](https://img.shields.io/badge/License-ISC-blue?style=flat)

## About

A social media application built with the MERN stack and GraphQL where users can create an account, post their thoughts, and interact with other users through reactions. Features JWT-based authentication, seeded sample data via Faker, and a GraphQL API for all data operations.

## Features

- **Account Management** — Create an account and log in with JWT-based authentication
- **Post Thoughts** — Share thoughts visible to all users
- **Reactions** — Add reactions to other users’ thoughts
- **User Profiles** — View individual profiles with thought history
- **Friends** — Friend other users to build connections
- **GraphQL API** — Queries and mutations for all data operations
- **Seeded Data** — Faker-generated sample data for development

## Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | React 17, Apollo Client 3, React Router DOM 6 |
| Backend | Node.js, Express.js 4, Apollo Server Express 3 |
| Database | MongoDB, Mongoose 5 |
| Auth | JSON Web Tokens (JWT), bcrypt 4 |
| GraphQL | graphql 16 |
| Seeding | Faker 4 |
| Dev Tools | Concurrently, Nodemon 2 |

## Getting Started

```bash
# Clone the repository
git clone https://github.com/coleyrockin/deep-thoughts.git
cd deep-thoughts

# Install all dependencies (client + server)
npm install

# Seed the database
npm run seed

# Start the development server
npm run develop
```

The React frontend runs at `http://localhost:3000` and the GraphQL API is available at `http://localhost:3001/graphql`.

## Deployment

This app can be deployed to Render or Railway. Set the following environment variables:

- `MONGODB_URI` — your MongoDB connection string
- `JWT_SECRET` — a strong secret for token signing

## Project Structure

```
deep-thoughts/
├── client/
│   ├── public/
│   └── src/
├── server/
│   ├── config/
│   ├── models/
│   ├── schemas/
│   ├── seeders/
│   ├── utils/
│   └── server.js
└── package.json
```

---

Built by [Boyd Roberts](https://github.com/coleyrockin)

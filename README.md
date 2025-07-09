# NLW Agents

Backend service developed during Rocketseat's NLW event. This project implements a RESTful API using modern technologies and best practices.

## 🚀 Technologies

- [Node.js](https://nodejs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Fastify](https://fastify.io/) - Modern and fast web framework
- [DrizzleORM](https://orm.drizzle.team/) - TypeScript ORM
- [PostgreSQL](https://www.postgresql.org/) with [pgvector](https://github.com/pgvector/pgvector) extension
- [Zod](https://zod.dev/) - TypeScript-first schema validation
- [Docker](https://www.docker.com/) - Containerization
- [Biome](https://biomejs.dev/) - Linting and Formatting

## 🔧 Setup

1. Clone the repository
2. Install dependencies:
```bash
npm install
```

3. Start the PostgreSQL database with Docker:
```bash
docker compose up -d
```

4. Create a `.env` file in the root directory with your environment variables.

5. Run database seed (optional):
```bash
npm run db:seed
```

6. Start the development server:
```bash
npm run dev
```

The server will be running on `http://localhost:3333` by default.

## 📝 Project Structure

- `src/db/`: Database configuration, schema, and migrations
- `src/http/`: API routes and controllers
- `src/server.ts`: Main application entry point

## 🛠️ Available Scripts

- `npm run dev`: Start development server with hot reload
- `npm run start`: Start production server
- `npm run db:seed`: Run database seed
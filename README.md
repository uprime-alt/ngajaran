# ngajaran

A modern backend project built with Bun, Elysia, and Drizzle ORM.

## 🚀 Tech Stack

- **Runtime**: [Bun](https://bun.com)
- **Framework**: [ElysiaJS](https://elysiajs.com)
- **ORM**: [Drizzle ORM](https://orm.drizzle.team)
- **Database**: MySQL (compatible with MariaDB)
- **Language**: TypeScript

## 📂 Project Structure

- `src/`: Source code
  - `index.ts`: Application entry point
  - `db/`: Database configuration and schemas
- `drizzle.config.ts`: Drizzle configuration for migrations
- `index.ts`: Bun module configuration

## 🛠 Getting Started

### Prerequisites

- [Bun](https://bun.sh) installed globally.

### Installation

```bash
bun install
```

### Environment Setup

Copy `.env.example` to `.env` and fill in your database credentials:

```bash
cp .env.example .env
```

### Development

To run the application in watch mode:

```bash
bun run dev
```

### Database Migrations

Push the schema directly to the database:

```bash
bun run db:push
```

---
Project initialized with `bun init`.


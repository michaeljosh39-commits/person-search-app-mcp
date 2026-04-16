# Jacinto's Person Search

A full-stack Next.js project for managing person records with search, create, update, and delete functionality.

https://person-search-app-mcp-seven.vercel.app/

<img width="2525" height="1469" alt="image" src="https://github.com/user-attachments/assets/de6641bc-75db-4cd2-8cec-697a0246a1a9" />
<img width="2552" height="1467" alt="image" src="https://github.com/user-attachments/assets/51bd8218-465a-4e9e-a380-55d7e93e0c6c" />


## Overview

This app uses the Next.js 16 App Router with server actions for CRUD operations and Prisma ORM for database access. It includes a responsive UI, validation with Zod, and a simple people search flow.

## Pages

- `/` — main user search and CRUD interface
- `/about` — project architecture and technology details
- `/github` — repository link and project source
- `/database` — Prisma model and database documentation

## Features

- Search people by name
- Add new person records
- Edit existing persons
- Delete records
- Form validation with React Hook Form and Zod
- Responsive UI designed for desktop and mobile

## Tech Stack

- Next.js 16
- React 19
- TypeScript
- Prisma
- PostgreSQL
- Tailwind CSS
- Radix UI
- React Hook Form
- Zod

## Local Setup

1. Install dependencies

```bash
pnpm install
```

2. Generate Prisma client

```bash
pnpm prisma:generate
```

3. Run the app

```bash
pnpm dev
```

## Environment Variables

Create a `.env` file with the following values:

- `DATABASE_URL` — database connection string
- `DIRECT_URL` — direct database connection string for Prisma migrations

## Production

Build and run a production version:

```bash
pnpm build
pnpm start
```

## Repository

Replace the placeholder below with your repository URL once the project is published:

https://github.com/your-username/jacinto-person-search

## Notes

This project is intended as a personalized portfolio app for managing and searching person records with a modern Next.js stack.


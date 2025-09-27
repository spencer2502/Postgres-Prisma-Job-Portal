# Postgres-Prisma Job Portal

A modern job posting website built with Next.js, Prisma, and PostgreSQL.

## Features

- User authentication (NextAuth.js)
- Post, browse, and apply for jobs
- User dashboard for managing jobs and applications
- Responsive UI with Tailwind CSS
- Prisma ORM for database access

## Tech Stack

- [Next.js](https://nextjs.org/)
- [Prisma](https://www.prisma.io/)
- [PostgreSQL](https://www.postgresql.org/)
- [NextAuth.js](https://next-auth.js.org/)
- [Tailwind CSS](https://tailwindcss.com/)

## Getting Started

### Prerequisites

- Node.js 18+
- PostgreSQL database

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/spencer2502/Postgres-Prisma-Job-Portal.git
   cd Postgres-Prisma-Job-Portal
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Configure environment variables:
   - Copy `.env.example` to `.env` and update the values (especially `DATABASE_URL`).
4. Run database migrations:
   ```sh
   npx prisma migrate dev
   ```
5. Start the development server:
   ```sh
   npm run dev
   ```

## Project Structure

- `app/` - Next.js app directory (pages, layouts, API routes)
- `components/` - Reusable React components
- `lib/` - Utility libraries (e.g., authentication)
- `prisma/` - Prisma schema and migrations
- `public/` - Static assets

## Prisma Schema

The Prisma schema defines models for users, jobs, applications, sessions, and accounts. See [`prisma/schema.prisma`](prisma/schema.prisma) for details.

## License

MIT

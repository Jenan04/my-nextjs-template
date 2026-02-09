# 🚀 Modern Next.js Template

A professional, production-ready Next.js template focused on developer experience, type safety, and scalability.

## ✨ Features

* **Framework**: [Next.js](https://nextjs.org/) with App Router.
* **Language**: TypeScript for static typing.
* **Database**: [Prisma](https://www.prisma.io/) ORM (PostgreSQL/SQLite ready).
* **Styling**: [Tailwind CSS](https://tailwindcss.com/) with PostCSS.
* **Linting**: ESLint 9 (Flat Config) configured for Next.js 15/16.
* **Package Manager**: [pnpm](https://pnpm.io/) for fast and disk-efficient installs.

## 🛠️ Getting Started

### 1. Clone the repository
```bash
git clone [https://github.com/Jenan04/my-nextjs-template.git](https://github.com/Jenan04/my-nextjs-template.git)
cd my-nextjs-template
```
### 2. Install dependencies
```
pnpm install
```
### 3. Set up environment variables
Create a `.env` file in the root directory and add your database URL:
```
DATABASE_URL="postgresql://user:password@localhost:5432/mydb"
```
### 4. Prisma Setup
Initialize your database schema:
```
pnpm exec prisma generate
pnpm exec prisma db push
```
## 📁 Project Structure
- /app: Next.js App Router (Pages, Components, Layouts).
- /prisma: Database schema and migrations.
- /public: Static assets (images, fonts).
- .gitignore: Pre-configured to keep your secrets (like .env) safe.
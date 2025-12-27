### Stack
- Next.js 14 (App Router)
- PostgreSQL
- Drizzle ORM
- NextAuth.js

Setup
```bash
npm install
cp .env.example .env
npx docker compose up -d
npm run db:generate
npm run db:migrate
npm run dev
```

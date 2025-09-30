JobConnector Pro Full Starter

Includes frontend (Next.js) and backend (Express + Prisma) with notifications, Gmail + Twilio stubs, and seed data.

Quickstart:
1. Install Docker & Node
2. docker-compose up -d
3. cd backend && npm install
4. cp .env.example .env (edit credentials)
5. npx prisma generate
6. npx prisma migrate dev --name init
7. node prisma/seed.js
8. npm run dev
9. cd frontend && npm install && NEXT_PUBLIC_API_URL=http://localhost:4000 npm run dev

Deploy notes: Connect frontend to Netlify, backend to Railway/Render and set env vars.

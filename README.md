# Omnify_Full_stack_intern_Assignment
It is an Internship Assignment
blog-app/
│
├── prisma/
│   └── schema.prisma
│
├── pages/
│   ├── api/
│   │   ├── auth/[...nextauth].js
│   │   └── posts/
│   │       ├── index.js
│   │       └── [id].js
│   ├── _app.js
│   ├── index.js
│   ├── signup.js
│   ├── login.js
│   ├── create.js
│   ├── post/
│   │   └── [id].js
│
├── components/
│   ├── Navbar.js
│   └── PostCard.js
│
├── lib/
│   └── prisma.js
│
├── package.json
├── .env.local
├── README.md
└── next.config.js
Frontend: Next.js (React-based framework, perfect for full-stack on Vercel)

Backend: Next.js API Routes (backend inside the same repo, easy for Vercel deployment)

Database: PostgreSQL (SQL DB; can be easily hosted on platforms like Supabase, Railway, or PlanetScale)

ORM: Prisma (simplifies DB operations and works perfectly with Next.js)

Authentication: NextAuth.js (supports email/password auth and integrates easily with Next.js)

Deployment: Vercel
# Blog Application

Full-Stack Blog App built using:

- Next.js (React Framework)
- NextAuth.js (Authentication)
- Prisma ORM
- PostgreSQL Database
- Fully deployable to Vercel

## Setup

1. Clone this repo
2. Install dependencies:
npm install

3. Create `.env.local` file:
DATABASE_URL=postgresql://<your-db-url>
NEXTAUTH_SECRET=your-secret
4. Run migrations:
npx prisma generate
npx prisma migrate dev --name init

5. Start development server:
npm run dev




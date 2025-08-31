A Calendar Scheduling Platform Saas

A fullstack calendar scheduling SaaS application that enables users to book, manage, and track meetings with ease. It is built with Node.js, PostgreSQL, TypeORM, and React.js, featuring a custom-built calendar and Google Calendar integration.

-> Features

User authentication with JWT

Create public or private events

Share unique booking links

Define availability and prevent double-booking

Time zone auto-detection

Custom calendar (built from scratch, no plugins)

Google Calendar and Google Meet integration

Track upcoming, past, and canceled meetings

Switch between 12h and 24h formats

Built with Node.js, TypeORM, PostgreSQL, React.js, Tailwind CSS v4, and Shadcn UI

-> Tech Stack

Backend: Node.js, TypeORM, PostgreSQL

Frontend: React.js, Vite.js, TailwindCSS, Shadcn UI

Database: Supabase (PostgreSQL)

Integration: Google Calendar API

Language: TypeScript

-> Getting Started

1. Clone the repository
git clone https://github.com/dhanrajsingh16/Calendar-Scheduling-Platform

2. Install dependencies
npm install

3. Configure environment variables

Create a .env file in the root directory and set the following:

PORT=8000
NODE_ENV=development

DATABASE_URL="postgresql://postgres:<>:<>@aws-0-eu-central-1.pooler.supabase.com:6543/postgres"

JWT_SECRET="jwt_secret_key"
JWT_EXPIRES_IN="1d"

GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
GOOGLE_REDIRECT_URI="http://localhost:8000/api/integration/google/callback"

FRONTEND_ORIGIN=http://localhost:5173
FRONTEND_INTEGRATION_URL="http://localhost:5173/app/integrations"

4. Run the application
npm run dev


Backend: http://localhost:8000

Frontend: http://localhost:5173

Deploy backend and frontend separately.

Ensure Google API credentials are correctly configured for production.

Author

Dhanraj Singh

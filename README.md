# Roxiler Store Rating Platform

Full-stack store rating application built for the Roxiler Systems Full Stack Intern coding challenge.

## Stack
- Frontend: React + Vite
- Backend: Node.js + Express.js
- Database: PostgreSQL
- Authentication: JWT + bcrypt
- Database container: Docker Compose

## Roles
- System Administrator
- Normal User
- Store Owner

## Quick start

### 1. Start PostgreSQL
```bash
docker compose up -d db
```

### 2. Backend
```bash
cd backend
cp .env.example .env
npm install
npm run dev
```

### 3. Frontend
```bash
cd frontend
npm install
npm run dev
```

Frontend: http://localhost:5173
Backend: http://localhost:5000

## Demo accounts
After running the seed command:

- Admin: `admin@roxiler.local` / `Admin@123`
- Store owner: `owner@roxiler.local` / `Owner@123`

A normal user can be created through registration.

### Seed database
```bash
cd backend
npm run seed
```

## Important
Do not commit `.env`. Use `.env.example` for configuration documentation.

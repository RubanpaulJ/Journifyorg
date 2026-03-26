# PaperPro Solutions (Full Stack)

Modern, responsive service website + admin panel for academic project/paper guidance.

## Tech
- Frontend: React + Tailwind (Vite)
- Backend: Node.js + Express
- DB: MongoDB (Mongoose)
- Auth: JWT (admin + user)
- Email: Nodemailer
- File upload: Multer
- WhatsApp: click-to-chat links

## Monorepo structure
- `client/` React app
- `server/` Express API

## Quick start (local)

### 1) Backend
```bash
cd server
npm install
copy .env.example .env
```
Edit `server/.env`:
- `MONGODB_URI` (required)
- `JWT_SECRET` (required)
- `ADMIN_SEED_EMAIL` / `ADMIN_SEED_PASSWORD` (for seed)
- email variables (optional, for enquiry emails)

Seed sample data + admin:
```bash
npm run seed
```

Run server:
```bash
npm run dev
```

### 2) Frontend
```bash
cd ../client
npm install
copy .env.example .env
npm run dev
```

Open Vite URL shown in the terminal.

## Default routes
- Public site: `/`
- Admin: `/admin`

## Notes / disclaimer
We provide guidance and support. Journal acceptance depends on research quality and the review process.


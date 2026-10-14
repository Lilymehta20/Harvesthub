# HarvestHub Minor Project — No Database Version

This version removes MongoDB completely. It remains a full-stack MERN-style project using React + Vite on the frontend and Node.js + Express on the backend. The backend stores users, products, orders and reviews in memory only.

## Features
- English / Hindi UI
- Farmer, Buyer and Admin roles
- Login / Register with JWT
- Product CRUD for farmers
- Search and filters
- Cart and checkout
- Orders and order status tracking
- Product reviews after delivery
- Farmer dashboard
- Admin statistics and user management
- No MongoDB / no Atlas / no database setup

## Demo accounts
- Buyer: buyer@harvesthub.com / Buyer@123
- Farmer: farmer@harvesthub.com / Farmer@123
- Admin: admin@harvesthub.com / Admin@123

## Start backend
```bash
cd backend
npm install
# copy .env.example to .env
npm run dev
```

Backend: http://localhost:5000
Health check: http://localhost:5000/api/health

## Start frontend
Open a second terminal:
```bash
cd frontend
npm install
# copy .env.example to .env
npm run dev
```

Frontend: http://localhost:5173

## Important limitation
Because there is no database, any new registrations, products, reviews and orders disappear when the backend restarts. The seeded demo accounts and sample data are recreated on every restart.

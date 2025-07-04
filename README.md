
# 📊 InvestQuest

**InvestQuest** is a gamified investing education platform for users under 18, offering simulated crypto/stock trading, interactive financial lessons, and full parental oversight.

---

## 🚀 Features

- 📈 Virtual trading simulator (stocks & crypto)
- 🎓 Interactive financial literacy modules
- 👪 Parent monitoring + controls
- 🛡️ COPPA/GDPR-K compliant framework
- 📊 Admin dashboard (Chart.js)
- 🔐 Optional Firebase Auth

---

## 🧰 Tech Stack

| Layer     | Tech                     |
|-----------|--------------------------|
| Frontend  | React + Chart.js         |
| Backend   | Node.js + Express        |
| Database  | PostgreSQL / Supabase    |
| Auth (opt)| Firebase, Clerk          |
| Hosting   | Vercel (FE), Render (BE) |

---

## 📦 Project Structure

```
investquest/
├── frontend/          # React app
├── backend/           # Express API
├── database/          # schema.sql
├── .env.example       # Sample config
└── README.md
```

---

## ⚙️ Local Setup

### 1. Clone the repo

```bash
git clone https://github.com/YOUR_USERNAME/investquest.git
cd investquest
```

### 2. Backend

```bash
cd backend
cp ../.env.example .env
npm install
npm run dev
```

### 3. Frontend

```bash
cd ../frontend
cp .env.example .env
npm install
npm start
```

---

## 🌐 Deploy

### Frontend → Vercel
- Import from GitHub
- Build command: `npm run build`
- Output dir: `build`
- Add env: `REACT_APP_API_URL`

### Backend → Render
- Import from GitHub
- Start command: `node server.js`
- Add env: `DATABASE_URL`

---

## 🔎 API Endpoints (Example)

| Method | URL                            | Description              |
|--------|--------------------------------|--------------------------|
| GET    | `/api/admin/earnings`          | View total GKT earnings  |
| GET    | `/api/fee-transactions`        | List transaction fees    |
| POST   | `/api/trades/simulate-buy`     | Simulated buy with fee   |

---

## 🧪 Testing

```bash
# Backend
cd backend
npm test

# Frontend
cd frontend
npm test
```

---

## 📩 Waitlist Signup (Mailchimp)

- https://investquest.mailchimpsites.com

---

## 🧠 Credits

Built with ❤️ for financial literacy and future investors.

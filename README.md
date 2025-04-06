# 💪 Computer Repair Shop

> A full-stack web app for managing customers and repair tickets

![Dashboard Preview](https://placehold.co/1200x600/222/fff?text=Computer+Repair+Shop+Dashboard)

---

## 📅 Overview

This application helps computer repair shops to:

- Manage **customer records**
- Create and update **repair tickets**
- Track **device issues and statuses**
- Provide a modern UI/UX for technicians and admins

Built with the latest web technologies for security, performance, and scalability.

---

## 🧱 Tech Stack

| Technology              | Description                                 |
| ----------------------- | ------------------------------------------- |
| 🔗 **Next.js 15**       | App Router-based full-stack React framework |
| 🔗 **React 19**         | Latest React version for dynamic UIs        |
| 🔗 **TypeScript**       | Static typing for scalability and safety    |
| 🎨 **TailwindCSS**      | Utility-first styling framework             |
| 🧩 **ShadCN/ui**        | Beautiful prebuilt components               |
| 🔐 **Kinde Auth**       | Authentication & authorization              |
| 🐇 **Neon Postgres**    | Serverless Postgres database                |
| 🌱 **Drizzle ORM**      | Type-safe SQL ORM                           |
| 📄 **react-hook-form**  | Performant form state management            |
| ✅ **Zod**              | Schema validation for frontend/backend      |
| 🛡️ **next-safe-action** | Secure async server actions                 |
| 📊 **TanStack Table**   | Advanced tables for filtering & sorting     |
| ☁️ **Vercel**           | Hosting & CI/CD                             |
| 🧰 **Sentry**           | Monitoring and error tracking               |

---

## 🚀 Features

- 🧑‍🔧 Customer management dashboard
- 🛠️ Repair ticket creation and status tracking
- 🔐 Role-based access control with Kinde
- 📃 Data-rich tables with search and filters (TanStack Table)
- 📊 Analytics-ready & performance monitored with Sentry
- ✨ Clean and modern UI with ShadCN + TailwindCSS

![Repair Ticket Page](https://placehold.co/1200x600/222/eee?text=Repair+Ticket+Details)

---

## 🔧 Getting Started

### 1. Clone the Repo

```bash
git clone https://github.com/MD-MOUAD/computer-repair-shop.git
cd computer-repair-shop
pnpm install
```

### 2. Environment Variables

Create a `.env` file:

```env
# Database
DATABASE_URL=your_neon_postgres_url

# Auth
KINDE_ISSUER_URL=your_kinde_issuer_url
KINDE_CLIENT_ID=your_kinde_client_id
KINDE_CLIENT_SECRET=your_kinde_client_secret

# Sentry
SENTRY_DSN=your_sentry_dsn
```

### 3. Start Development Server

```bash
pnpm dev
```

Visit `http://localhost:3000`

---

## 📋 Database & ORM

- Postgres database hosted on **Neon**
- Drizzle ORM for migrations and type-safe queries

```bash
pnpm drizzle:push
```

---

## 🛡️ Auth & Security

- Integrated **Kinde Auth** for user login
- All actions protected with `next-safe-action`
- Schema validation with `zod`

---

## ✅ Forms

- Managed using `react-hook-form`
- Validated via `zod` schemas
- Fully type-safe and user-friendly

---

## 🚫 Error Monitoring

- Integrated with [Sentry](https://sentry.io)
- Real-time logging and performance tracking

---

## ☁️ Deployment

This app is fully optimized for **Vercel**.

Just push to `main`, and it's live.

---

## 👨‍💼 Author

Built with ❤️ by [Mouad khanouch](https://github.com/MD-MOUAD)

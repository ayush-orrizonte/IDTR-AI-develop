# 🚀 ITDR

**ITDR** is a modular, scalable microservices monorepo built with **Node.js**, **TypeScript**, **React**, and **Tailwind CSS**.  
The repo contains separate services for User/Admin frontends and backends plus a shared `commons` package for reusable types and utilities.

---

## 📁 Monorepo Structure

```bash
ITDR/
│
├── itdr-user-frontend      # React + TypeScript + Tailwind (User App)
├── itdr-user-backend       # Node.js + TypeScript (User API)
├── itdr-admin-frontend     # React + TypeScript + Tailwind (Admin App)
├── itdr-admin-backend      # Node.js + TypeScript (Admin API)
├── itdr-auth-backend       # Node.js + TypeScript (Auth API)
└── itdr-commons            # Shared code (types, utils, interfaces)

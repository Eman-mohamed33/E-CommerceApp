# 🛒 E-commerce App

A full-scale e-commerce backend built with NestJS, featuring real-time updates, secure payments, and flexible data fetching.

---

## 🚀 Features

- 📦 Product, category, cart, and order management
- 💳 Stripe payment processing with real-time order confirmation
- 🔴 Redis caching for frequently accessed product data
- 📡 Real-time order updates via Socket.io
- 🔐 JWT authentication with admin/user Role-Based Access Control (RBAC)
- 📊 GraphQL APIs for flexible and efficient data fetching
- ✅ Request validation to ensure data integrity

---

## 🛠️ Tech Stack

| Category | Technologies |
|---|---|
| Runtime | Node.js |
| Framework | NestJS |
| Database | MongoDB, Mongoose |
| Cache | Redis |
| API | GraphQL, REST |
| Real-time | Socket.io |
| Payment | Stripe |
| Auth | JWT, RBAC |

---

## 📁 Project Structure

```
src/
├── common/
├── DB/
├── modules/
|   ├── auth/
|   ├── brand/
|   ├── coupon/
|   ├── gateway/
│   ├── product/
│   ├── category/
│   ├── cart/
│   ├── order/
│   └── user/
├── schema.gql/
└── main.ts
```

---

## ⚙️ Installation

```bash
# Clone the repo
git clone https://github.com/Eman-mohamed33/E-CommerceApp.git

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env

# Run the app
npm run start:dev
```
---

## 👩‍💻 Author

**Eman Gesraha** · [LinkedIn](https://linkedin.com/in/eman-gesraha) · [GitHub](https://github.com/Eman-mohamed33)

# 📚 Booxtation - Modern Book E-commerce Platform

## Overview
A modern, competitive e-commerce platform for selling books online with a seamless user experience.

## 🎯 Tech Stack

### Frontend
- **React 18** - UI Library
- **Next.js** - Framework & SSR
- **TailwindCSS** - Styling
- **Redux Toolkit** - State Management
- **Axios** - HTTP Client

### Backend
- **Node.js + Express** - Server
- **MongoDB** - Database
- **JWT** - Authentication
- **Stripe** - Payment Processing

### DevOps
- **Docker** - Containerization
- **GitHub Actions** - CI/CD

## 📁 Project Structure

```
booxtation/
├── client/                 # React/Next.js Frontend
│   ├── pages/
│   ├── components/
│   ���── styles/
│   └── public/
├── server/                 # Node.js Backend
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── middleware/
│   └── config/
├── docker-compose.yml
└── README.md
```

## 🚀 Core Features

- [ ] User Authentication (Sign up, Login, JWT)
- [ ] Book Catalog (Search, Filter, Sort)
- [ ] Shopping Cart
- [ ] Checkout & Payment Integration (Stripe)
- [ ] Order Management
- [ ] User Profile & History
- [ ] Admin Dashboard
- [ ] Reviews & Ratings
- [ ] Wishlist
- [ ] Responsive Design

## 🛠️ Installation & Setup

### Prerequisites
- Node.js v16+
- MongoDB
- npm or yarn

### Quick Start

```bash
# Install dependencies
npm install

# Setup environment variables
cp .env.example .env.local

# Run development server
npm run dev
```

## 📦 Available Scripts

- `npm run dev` - Run frontend and backend concurrently
- `npm run server` - Run backend only
- `npm run client` - Run frontend only
- `npm run build` - Build production
- `npm test` - Run tests
- `npm run lint` - Lint code

## 🔐 Environment Variables

Create `.env.local`:

```
REACT_APP_API_URL=http://localhost:5000
MONGODB_URI=mongodb://localhost:27017/booxtation
JWT_SECRET=your_jwt_secret
STRIPE_PUBLIC_KEY=pk_...
STRIPE_SECRET_KEY=sk_...
```

## 📝 Development Guidelines

- Follow ESLint rules
- Write tests for new features
- Use meaningful commit messages
- Create pull requests for code review

## 🤝 Contributing

1. Create a feature branch
2. Make your changes
3. Submit a pull request

## 📄 License

MIT License - See LICENSE file

---

**Status**: 🔨 Under Development
**Last Updated**: 2026-04-13
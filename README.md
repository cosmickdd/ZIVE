<p align="center">
  <img src="./logo.svg" alt="ZIVÉ Logo" width="160" style="border-radius: 18px; box-shadow: 0 4px 24px #0002;"/>
</p>

<h1 align="center" style="font-size:2.5rem; margin-bottom:0;">
  ✨ <span style="letter-spacing:2px;">ZIVÉ</span> — Modern Fashion & E-Commerce Platform ✨
</h1>

<p align="center" style="font-size:1.15rem;">
  <em>A minimalist, premium, mobile-first fashion experience built with Flutter.<br>
  <strong>Shop. Discover. Design. Personalize.</strong></em>
</p>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/Flutter-3.10-blue?logo=flutter"></a>
  <a href="#"><img src="https://img.shields.io/badge/NestJS-9-red?logo=nestjs"></a>
  <a href="#"><img src="https://img.shields.io/badge/PostgreSQL-14-blue?logo=postgresql"></a>
  <a href="#"><img src="https://img.shields.io/badge/Stripe-Razorpay-purple?logo=stripe"></a>
  <a href="#"><img src="https://img.shields.io/badge/License-MIT-green"></a>
</p>

---

## 🧵 Overview

**ZIVÉ** is a next-generation fashion & lifestyle platform focused on  
**design excellence**, **AI-powered personalization**, and a **seamless user experience**.  
Built for both users and designers, ZIVÉ integrates commerce, creativity, and technology in a unified mobile-first platform.

---

## ✨ Features

<details>
  <summary><strong>👤 User Features</strong></summary>

- 🔐 Email & Social Logins (Google, Apple, etc.)
- 🛍 Product listings with filters, cart, wishlist
- 💳 Secure payments via Stripe & Razorpay
- 🎁 Reward points & engagement system
- 💫 AI-based product recommendations
- 🎨 Swipe-to-rate designer pieces (Tinder-style)
- 📦 Order tracking & checkout

</details>

<details>
  <summary><strong>🛠 Admin Features</strong></summary>

- 📦 Manage Products, Orders, Inventory
- 📊 Dashboard Analytics & Insights
- 👥 Manage Users & Designers

</details>

<details>
  <summary><strong>🧑‍🎨 Designer Features</strong></summary>

- 📤 Upload & manage collections
- 💬 Collect user ratings and swipe feedback
- 📈 View design performance analytics

</details>

---

## 🧰 Tech Stack

| Layer            | Technology                                 |
|------------------|--------------------------------------------|
| **Frontend**     | Flutter (Dart)                             |
| **Backend/API**  | NestJS (TypeScript)                        |
| **Database**     | PostgreSQL + Prisma ORM                    |
| **Auth**         | Firebase Auth, OAuth2                      |
| **ML Models**    | Python (TensorFlow, Scikit-learn)          |
| **Payments**     | Stripe, Razorpay                           |
| **Emails**       | SendGrid / Mailgun                         |
| **Deployment**   | Docker, Railway, Firebase, Vercel          |

---

## 🏗 Architecture

<!-- Mermaid diagram for GitHub.com -->
<pre> ```mermaid
flowchart TD
    A[User Device (Flutter App)]
    B[NestJS Backend API]
    C[PostgreSQL + Prisma]
    D[ML Engine via REST]
    E[Recommendation System]
    F[Stripe / Razorpay]
    G[Checkout Flow]
    H[Email Service (SendGrid/Mailgun)] </pre>

    A --> B
    B --> C
    B --> D
    D --> E
    B --> F
    F --> G
    B --> H
```

---

### 🔗 Component Summary

| Component                     | Description                                      |
|------------------------------|--------------------------------------------------|
| **User Device**              | Flutter frontend application                     |
| **NestJS Backend API**       | Central API handling business logic              |
| **PostgreSQL + Prisma**      | Persistent database with ORM                     |
| **ML Engine (via REST)**     | ML model interface for predictions               |
| **Recommendation System**    | Provides user/content recommendations            |
| **Stripe / Razorpay**        | Payment gateway integration                      |
| **Checkout Flow**            | User checkout logic and payment processing       |
| **Email Service**            | Transactional emails via SendGrid/Mailgun        |

---

## 🚀 Get Started

1. **Clone the repository**
   ```sh
   git clone https://github.com/your-org/zive.git
   cd zive
   ```
2. **Read the [Setup Guide](./docs/SETUP.md) for local development**
3. **Explore the [API Docs](./docs/API.md) and [App Guide](./docs/APP.md)**

---

## 📬 Contact & Community

- [Issues](https://github.com/your-org/zive/issues)
- [Discussions](https://github.com/your-org/zive/discussions)
- [Twitter](https://twitter.com/yourbrand)
- [Instagram](https://instagram.com/yourbrand)

---

<p align="center"><strong>Made with ❤️ by the ZIVÉ Team</strong></p>



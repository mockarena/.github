# 🎯 MOCKARENA.UZ

**Advanced IELTS Mock Testing Platform — Built for Serious Results**

---

## 🌍 Overview

**MOCKARENA.UZ** is a modern, scalable platform for IELTS preparation, delivering **fresh mock exams**, **realistic testing environments**, and **intelligent evaluation tools**.

Designed with a clean architecture and powered by **agentic skills**, the platform provides a seamless experience across:

* 🔌 API (backend)
* 🛠️ Admin dashboard
* 💻 Client web application

---

## ✨ Core Features

### 📝 Fresh IELTS Mock Exams

* Continuously updated test sets
* Full coverage: Listening, Reading, Writing, Speaking
* Real exam timing and structure

### 🤖 Agentic Skills System

* Intelligent task handling and automation
* Context-aware evaluation logic
* Designed for future AI-assisted scoring and feedback

### 📊 Smart Analytics

* Section-wise performance insights
* Band score estimation
* Progress tracking over time

### 🛠️ Admin Panel

* Manage users, tests, and results
* Upload and organize mock exams
* Control system behavior and content

### 💻 Client Application

* Smooth, distraction-free test experience
* SSR-powered performance with modern UI
* Mobile-friendly and responsive

---

## 🧱 Architecture

```id="1r45kx"
MOCKARENA.UZ/
│
├── api/        # Laravel 8.5 backend (REST API)
├── admin/      # Nuxt 4 (SSR) admin dashboard
├── client/     # Nuxt 4 (SSR) user-facing app
└── skills/     # Agentic skills & logic modules
```

---

## 🛠️ Tech Stack

### 🔌 Backend (API)

* **Laravel (PHP 8.5)**
* RESTful architecture
* Authentication & authorization (JWT / Sanctum)

### 💻 Frontend (Admin & Client)

* **Nuxt 4 (SSR mode)**
* **shadcn/ui** for modern UI components
* Fully responsive design

### 🧠 System Layer

* **Agentic Skills Architecture**

  * Modular skill-based logic
  * Extensible for AI workflows
  * Decoupled from core services

---

## 🚀 Getting Started

### 1. Clone Repository

```bash id="a1j4qw"
git clone https://github.com/your-username/mockarena.uz.git
cd mockarena.uz
```

---

### 2. Setup API (Laravel)

```bash id="eqk1xp"
cd api
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
```

---

### 3. Setup Admin Panel

```bash id="z9e3bl"
cd ../admin
npm install
npm run dev
```

---

### 4. Setup Client App

```bash id="g1t2kn"
cd ../client
npm install
npm run dev
```

---

## 🔐 Environment Configuration

Example `.env` (API):

```id="bz7rjf"
APP_NAME=MOCKARENA
APP_ENV=local
APP_KEY=
APP_URL=http://localhost

DB_CONNECTION=mysql
DB_DATABASE=mockarena
DB_USERNAME=root
DB_PASSWORD=

JWT_SECRET=
```

---

## 🔄 API Structure (Example)

```id="m6yq8r"
GET    /api/tests
POST   /api/tests/submit
GET    /api/results
POST   /api/auth/login
```

---

## 🧠 Agentic Skills (Concept)

The **skills/** directory contains modular logic units that:

* Process exam data
* Evaluate responses
* Enable future AI integrations
* Provide reusable intelligence across the system

---

## 📈 Roadmap

* [ ] AI-based Writing & Speaking evaluation
* [ ] Adaptive testing engine
* [ ] Real-time examiner simulation
* [ ] Mobile applications (iOS / Android)
* [ ] Advanced analytics dashboard

---

## 🤝 Contributing

We welcome contributions from developers and educators.
Feel free to open issues, suggest features, or submit pull requests.

---

## 📄 License

MIT License © 2026 MOCKARENA.UZ

---

## 💡 Philosophy

> Great IELTS scores come from **focused practice + real feedback**.
> MOCKARENA.UZ is engineered to deliver both — at scale.

---

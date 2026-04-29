# Medu

Modern Education Platform (LMS + Live Classes + Tutor Marketplace)

---

## 🚀 Overview

Medu is a full-stack EdTech platform that combines:

* Learning Management System (LMS)
* Live interactive classes
* Tutor marketplace

---

## 🧩 Core Features

### LMS

* Course management
* Video lessons
* Progress tracking
* Quiz & assessment

### Live Classes

* Real-time video (WebRTC)
* Chat & interaction
* Scheduling & attendance

### Tutor Marketplace

* Tutor profiles
* Booking system
* Rating & reviews

### Billing

* Invoice management
* Payment integration (Sepay / VNPay)

---

## 🏗️ Architecture

Monorepo structure:

apps/

* web (Vue 3)
* admin (Vue 3)
* api (Laravel 10)

services/

* liveclass (WebRTC / Socket)
* payment

---

## 🛠️ Tech Stack

Frontend:

* Vue 3 + Vite
* Pinia
* TailwindCSS + DaisyUI

Backend:

* Laravel 10 (API)
* Sanctum Auth
* Redis Queue

Realtime:

* WebSockets / Socket.io

Database:

* MySQL / PostgreSQL

---

## ⚙️ Setup

### 1. Clone repo

git clone https://github.com/nguyenngocduc0027/medu.git

### 2. Environment

cp .env.example .env

### 3. Run with Docker

docker-compose up -d

### 4. Install dependencies

cd apps/web && npm install
cd apps/api && composer install

---

## 📡 API Documentation

Coming soon (Swagger / Postman)

---

## 📊 Roadmap

* [x] Project structure
* [ ] Authentication
* [ ] Course system
* [ ] Live class
* [ ] Marketplace
* [ ] Payment integration

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first.

---


## 📄 License

This project is licensed under the MIT License.

Copyright (c) 2026 Nguyen Ngoc Duc (Medu)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction...

See the LICENSE file for full details.


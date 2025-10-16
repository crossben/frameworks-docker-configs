
---

### 📁 `/laravel/12/README.md`

```md
# 🐳 Laravel 12 (Preview) - Dockerized Environment

This folder provides an early Docker setup for **Laravel 12** — expected to introduce further framework simplifications.

> ⚠️ Laravel 12 is **not officially released** yet — use for testing and preview purposes only.

---

## 🧱 Docker Components

| Service | Description             |
|---------|-------------------------|
| web     | Apache + PHP 8.2/8.3    |
| db      | MySQL 8.0               |

---

## 🔥 Quick Start

### run this commande from the root of your project folder

```bash

composer create-project laravel/laravel:^12.0 replace-with-your-app-name

cd replace-with-your-app-name

docker-compose up -d --build

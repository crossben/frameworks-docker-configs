
---

### 📁 `/laravel/11/README.md`

```md
# 🐳 Laravel 11 - Docker Setup

This directory contains Docker configuration to run a **Laravel 11** app with **Apache**, **PHP 8.2**, and **MySQL 8**.

> 🔔 Laravel 11 simplifies boilerplate and comes with cleaner defaults. This setup is ideal for local development or containerized CI.

---

## 🔧 Docker Services

| Service | Description         |
|---------|---------------------|
| web     | PHP 8.2 + Apache    |
| db      | MySQL 8.0           |

---

## 🚀 How to Use

### 1. Navigate to Laravel 11 setup

### run this commande from the root of your project folder

```bash

composer create-project laravel/laravel:^11.0 replace-with-your-app-name

cd replace-with-your-app-name

docker-compose up -d --build


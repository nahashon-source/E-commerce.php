# 🎟️ Laravel Ticketing System

A modern, role-based support ticket management system built with **Laravel 11**, featuring both **Admin** and **User** dashboards, real-time commenting, file attachments, and categorized ticket management.  

Supports both **Bootstrap 5** and **Tailwind CSS** styling.

---

## 📌 Features

- User registration & authentication
- Role-based access control (Admin, Agent, User)
- Ticket creation, editing, and status tracking
- Assign agents to tickets (Admin)
- Ticket categories, priorities, and labels management
- Comments system per ticket
- File attachments (multiple uploads)
- Paginated ticket listings
- Flash messaging for actions
- RESTful resource controllers and route model binding

---

## 🗂️ Tech Stack

- Laravel 11
- PHP 8.3
- MySQL / MariaDB
- Bootstrap 5
- Tailwind CSS via Vite
- Alpine.js (optional dropdowns)
- Laravel Breeze (for auth scaffolding)

---

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/laravel-ticketing-system.git
   cd laravel-ticketing-system

2. INSTALL DEPENDENCIES
composer install
npm install
npm run build


3. SET UP ENV
cp .env.example .env
php artisan key: generate


4. Configure your DB credentials in .env

5. RUN DATABASE MIGRATIONS AND SEED DEFAULT DATA
php artisan migrate --seed

6. SERVE THE APPLICATION
 php artisan serve

7. Visit http://localhost:8000


8 DEFAULT USER CREDENTIALS
| Role  | Email               | Password   |
| :---- | :------------------ | :--------- |
| Admin | `admin@example.com` | `password` |
| Agent | `agent@example.com` | `password` |
| User  | `user@example.com`  | `password` |



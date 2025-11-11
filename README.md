# 🎓 Student Management API (Salek Project)

A powerful **Laravel-based RESTful API** for a mobile application that manages students, teachers, parents, and courses efficiently.  
Developed for the **Salek** educational platform, this backend provides authentication, course management, event booking, homework submission, subscriptions, and more — all with secure JSON API endpoints.

---

## 🚀 Features

- 🔐 **Authentication & Authorization**
  - User Registration & Login (Admin, Parent, Student, Teacher)
  - OTP-based Account Verification
  - Password Reset via Email
  - JWT Token Authentication

- 👨‍🎓 **Student Module**
  - Dashboard with Courses & Progress
  - View All Courses & Popular Courses
  - Track Weekly Progress
  - Bookmark & Attend Events
  - Submit Homework & View Grades

- 👨‍🏫 **Teacher Module**
  - Dashboard Overview
  - Manage Courses, Lessons & Homework
  - Review Student Submissions
  - View Assigned Students & Their Progress

- 👨‍👩‍👧 **Parent Module**
  - Link/Unlink Students
  - Monitor Child’s Learning Progress
  - View Subscription Details

- 📚 **Course Management**
  - Multi-level Courses & Lessons
  - Progress Tracking
  - Achievements & Certifications
  - Payment Integration (Stripe)

- 🎉 **Events & Notifications**
  - View & Book Upcoming Events
  - Event Bookmarking System
  - Push Notifications for Students & Teachers

---

## 🧩 Tech Stack

| Component | Technology |
|------------|-------------|
| **Backend Framework** | Laravel 10.x |
| **Authentication** | JWT |
| **Database** | MySQL |
| **Payment Integration** | Stripe API |
| **File Storage** | Laravel Filesystem (Local) |
| **API Testing** | Postman |
| **Documentation** | Postman Collection |

---

## 🧠 Project Structure Overview

```base
app/
├── Http/
│ ├── Controllers/
│ ├── Middleware/
│ ├── Resources/
├── Models/
├── Helpers/
database/
├── migrations/
├── seeders/
routes/
├── api.php

```

---

## 📦 Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/code-arif/salek_office
```
```bash
cd salek-student-management-api
```
```base
composer install

```
```bash
cp .env.example .env
php artisan key:generate
```
```base
DB_DATABASE=your_database
DB_USERNAME=your_username
DB_PASSWORD=your_password
```
```bash
php artisan migrate --seed
```
```base
php artisan serve
```

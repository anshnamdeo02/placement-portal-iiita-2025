# Placement Portal System

## Introduction

A simple web app for IIIT’s Training & Placement cell. Students register once, then apply to drives; coordinators post updates; admins manage users and notices.

---

## Features

* **User Roles**: Admin, Coordinator, Student
* **One-time Registration**: Students fill profile once
* **Drive Management**: Create/update placement drives
* **Application Tracking**: Students apply and track status
* **Notices & Uploads**: Post announcements and documents

---

## Tech Stack

* **Frontend**: HTML, CSS (Bootstrap), JavaScript
* **Backend**: PHP, MySQL
* **Server**: XAMPP / WAMP (local)

---

## Setup

1. **Clone repo**:

   ```bash
   git clone https://github.com/yourusername/placement-portal.git
   cd placement-portal
   ```
2. **Copy to web root** (`htdocs` or `www`) and start Apache & MySQL.
3. **Database**:

   * Create `placement_db`
   * Import `sql/schema.sql` and `sql/seed_data.sql`
4. **Configure**:

   * Duplicate `.env.example` to `.env`
   * Set DB credentials and `APP_URL`
5. **Run**: Open `http://localhost/placement-portal`

---

## Project Structure

```
placement-portal/
├─ index.php               # Entry point
├─ db.php                  # Database connection
├─ login-candidates.php    # Student login
├─ register-candidates.php # Student registration
├─ login-company.php       # Company login
├─ register-company.php    # Company registration
├─ admin/                  # Admin dashboard and controls
├─ user/                   # Student dashboard
├─ company/                # Company dashboard
├─ assets/                 # CSS, JS, images
├─ uploads/                # Uploaded documents
├─ PHPMailer/              # Email functionality
├─ database/               # DB schema or utility scripts
```

---

## Usage

* **Register** at `/register.php`
* **Login** and explore dashboards based on role
* **Admin**: Approve users, post notices
* **Coordinator**: Manage drives, view applicants
* **Student**: Apply to drives, view status

---
![Image 1](https://i.ibb.co/RZdKs8m/1.jpg)
<hr style="height:5px;background:#000">

![Image 2](https://i.ibb.co/mC8MQB5M/2.jpg)
<hr style="height:5px;background:#000">

![Image 3](https://i.ibb.co/3mywLLSM/3.jpg)
<hr style="height:5px;background:#000">

![Image 4](https://i.ibb.co/DfGT9ntc/4.jpg)
<hr style="height:5px;background:#000">

![Image 5](https://i.ibb.co/rDNkL31/5.jpg)
<hr style="height:5px;background:#000">

![Image 6](https://i.ibb.co/PsKcvKTx/6.jpg)
<hr style="height:5px;background:#000">

![Image 7](https://i.ibb.co/cct5Kgp1/7.jpg)
<hr style="height:5px;background:#000">

![Image 8](https://i.ibb.co/mr1MssXR/8.jpg)
<hr style="height:5px;background:#000">

![Image 9](https://i.ibb.co/GfHtCM5H/9.jpg)
<hr style="height:5px;background:#000">

![Image 10](https://i.ibb.co/wrCVQQdb/10.jpg)
<hr style="height:5px;background:#000">

![Image 11](https://i.ibb.co/7tt03bwp/11.jpg)

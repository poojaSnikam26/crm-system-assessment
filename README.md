# crm-system-assessment
Full-stack CRM system with automation (Next.js + CodeIgniter)

## 📌 Overview

This project is a CRM (Customer Relationship Management) system inspired by modern platforms like Creatio. It includes core CRM features such as lead management, deal tracking, task automation, and dashboard insights.

---

## 🛠 Tech Stack

### Frontend:

* Next.js (React)

### Backend:

* PHP (CodeIgniter 4)

### Database:

* MySQL

---

## ✨ Features Implemented

### ✅ Leads Management

* Add new leads
* View all leads
* Convert leads into contacts

### ✅ Contacts & Deals

* Lead conversion automatically creates:

  * Contact
  * Deal

### ✅ Deals Pipeline

* Deals created with stages (New, etc.)
* Linked with contacts

### ✅ Task & Activity Management

* Automatic task creation on lead conversion
* Example: Follow-up task

### ✅ Automation Workflow

* Lead → Contact → Deal → Task (Fully automated)

### ✅ Dashboard

* Total Leads
* Total Deals
* Total Tasks

### ✅ Notes / Communication (Basic Structure Ready)

---

## ⚙️ Setup Instructions

### 🔹 Backend (CodeIgniter)

1. Move project to `htdocs`
2. Start XAMPP (Apache + MySQL)
3. Open terminal:

```
cd crm-backend
php spark serve
```

4. Backend runs on:

```
http://localhost:8080
```

---

### 🔹 Database Setup

1. Open phpMyAdmin
2. Create database: `crm_db`
3. Import tables: (import provided database file )

* leads
* contacts
* deals
* tasks

---

### 🔹 Frontend (Next.js)

1. Go to frontend folder:

```
cd crm-frontend
npm install
npm run dev
```

2. Frontend runs on:

```
http://localhost:3000
```

---

## 🔗 API Endpoints

* GET `/leads`
* POST `/leads`
* POST `/leads/convert/{id}`
* GET `/deals`
* GET `/tasks`

---


## 🧪 Sample Data

* Add few leads using UI
* Convert leads → deals & tasks auto-generated

---

## Demo and Screenshots

* Demo video and Screenshots are given in the demo folder


---

## 👨‍💻 Author

Pooja Nikam

---

## ✅ Conclusion

This CRM demonstrates core business workflows, automation, and clean UI implementation similar to modern CRM platforms.

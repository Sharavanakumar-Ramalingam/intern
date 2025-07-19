# 👨‍💻 GUVI Internship – Full‑Stack Web Development Projects

This repository showcases the full-stack tasks I completed during my internship at GUVI. It highlights projects built using **PHP**, **HTML**, **CSS**, **JavaScript**, **Redis**, **MongoDB**, **SQL**, and project bundling with **Webpack**.

---

## 🔧 Tech Stack & Tools

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Backend**: PHP (LAMP stack)
- **Databases**:
  - **Redis** (in-memory data store / caching)
  - **MongoDB** (NoSQL document stores)
  - **SQL** (MySQL / MariaDB relational DB)
- **Bundler**: Webpack (JS/CSS optimization)
- **Development Tools**: Composer, npm/yarn, Postman

---

## 📁 Project Structure

```
intern/
├── frontend/                # HTML/CSS/JS apps, Webpack setup
│   ├── src/                 # Source JS and CSS files
│   ├── dist/                # Bundled assets
│   └── webpack.config.js    # Webpack bundler config
├── backend/                 # PHP-driven APIs and server code
│   ├── api/                 # REST endpoints
│   ├── templates/           # PHP + HTML templates
│   └── config/              # Database and Redis configs
├── database/                # SQL scripts and MongoDB utilities
│   ├── schema.sql           # SQL schema and seed data
│   └── mongo_setup.js       # MongoDB collection scripts
├── redis/                   # Redis scripts (e.g., caching example)
├── docs/                    # Task descriptions & workflow screenshots
└── README.md                # This documentation file
```

---

## ✅ Completed Tasks

- **Session Handling & Caching**: Implemented session logic via PHP + Redis, reducing DB load.
- **CRUD APIs**: Built RESTful endpoints in PHP for SQL and MongoDB, supporting various frontend features.
- **Dynamic Frontend Pages**: Developed interactive forms and pages connected to backend APIs.
- **Webpack Build Pipeline**: Configured bundling, minification, & hot reloading for JS/CSS.
- **Database Migrations**: Created SQL schema (`schema.sql`) and seeded initial data.
- **MongoDB Integration**: Stored JSON-like product/user metadata via `mongo_setup.js`.
- **Authentication Flow**: Implemented login/signup with PHP sessions & Redis token caching.
- **Documentation**: Captured program spec and demo screenshots in `docs/`.

---

## ⚙️ Installation & Setup

1. **Clone the repo**
   ```bash
   git clone https://github.com/Sharavanakumar-Ramalingam/intern.git
   cd intern
   ```

2. **Install dependencies**
   ```bash
   composer install          # PHP dependencies
   npm install              # Webpack / frontend tools
   ```

3. **Setup databases**
   - MySQL:  
     ```bash
     mysql -u root -p < database/schema.sql
     ```
   - MongoDB:
     ```bash
     node database/mongo_setup.js
     ```

4. **Configure environment**
   Edit `backend/config/*.php`:
   ```php
   $db_host = 'localhost';
   $db_user = 'root';
   $db_pass = '';
   $db_name = 'your_db';
   $redis_host = '127.0.0.1';
   ```

5. **Build frontend assets**
   ```bash
   npm run build            # or `npm run dev` for development
   ```

6. **Start PHP server**
   ```bash
   php -S localhost:8000 -t backend
   ```

7. **Explore application**
   - Open [http://localhost:8000](http://localhost:8000) in your browser
   - Interact with forms, view Redis-cached sessions & MongoDB data via API endpoints

---

## ✨ Screenshots & Workflow

See details in `docs/`, including:
- UI interaction snapshots
- API response postman catalog
- Webpack build log

---

## 🧑‍💻 Intern Experience

During this internship:
- I learned how to build a **complete full-stack solution** (frontend + backend + DB + caching)
- Implemented **session caching in Redis**, significantly improving performance
- Gained skills in **MongoDB integration**, **Webpack configuration**, and **RESTful API design**
- Worked collaboratively using **Git**, **Postman**, and **npm/Composer**

---

> “Building scalable and responsive web solutions with real-world data pipelines.”

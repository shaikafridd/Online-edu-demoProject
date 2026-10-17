# 🎓 CareerHub - Online Course Selling & Educational Platform

> 🏆 **Client Success Story & Freelancing Milestone**  
> This project was developed as a rapid, interactive demo prototype presented to an investor looking to fund and launch a scalable course-selling platform.  
> **The Outcome:** The investor loved the live demo, smooth course browsing, checkout experience, and intuitive administrative control center — and directly awarded the full freelancing project based on this prototype! 🚀💼

---

CareerHub is an end-to-end, premium course selling and interactive learning portal. It provides students with comprehensive course catalogs, interactive video curriculum panels, secure checkouts, certifications, job postings with application trackers, and a built-in ATS resume optimizer. It also features a robust Admin Control Center for course creation, payment verification, student management, and site-wide sales analytics.

---

## 🚀 Core Platform Functionality

CareerHub was designed as an all-in-one edtech powerhouse, combining e-commerce course selling with an engaging learning environment and career acceleration tools:

### 1. 🛒 Course Selling, Marketplace & Checkout Flow
* **Dynamic Course Marketplace**: Search and filter courses by category (Full-Stack, Cloud, AI/ML, DevOps), skill level, duration, and price.
* **Curriculum & Syllabus Preview**: Prospective students can inspect structured chapter outlines, lesson titles, video durations, instructor bios, and learning objectives before buying.
* **Streamlined Checkout Experience**: Integrated checkout portal featuring real-time price calculations, promo/discount code support, and simulated multi-method payment processing.
* **Instant Course Unlocking**: Automated enrollment triggers upon payment confirmation, granting immediate access to the student classroom.

### 2. 🎓 Interactive Student Classroom & Learning Portal
* **Distraction-Free Video Player**: Custom-built classroom UI supporting video playback, chapter navigation, and syllabus progress checkboxes.
* **Granular Progress Tracking**: Automatically keeps track of completed lessons, updating student completion percentages and progress bars across the portal.
* **Automated Course Certificates**: Students earn personalized digital completion certificates when reaching 100% course progress.
* **Student-Instructor Messaging**: Built-in messaging system enabling students to ask questions, request guidance, and interact with course administrators.

### 3. 💼 Career Accelerator & ATS Resume Analyzer
* **Curated Job Board**: Filter tech job opportunities by work arrangement (Remote, Hybrid, On-site), seniority level, and company.
* **Application Lifecycle Tracker**: Apply directly to job postings with PDF resume uploads and track application status (`Applied`, `Reviewing`, `Shortlisted`, `Interview Scheduled`).
* **Server-Side ATS Resume Optimizer**: Upload resume PDFs to be parsed and scored against target job descriptions. The system generates:
  * **Match Score**: Percentage compatibility against required qualifications.
  * **Keyword Gap Analysis**: Highlights missing technical skills and industry keywords.
  * **Actionable Recommendations**: Bullet-point improvements for formatting, content clarity, and industry standards.
* **Saved Opportunities**: Save dream jobs to track application deadlines and interview dates.

### 4. 🛡️ Admin Command Center & Business Analytics
* **Executive Metrics Dashboard**: Real-time business KPIs including total revenue, active enrollments, course sales volume, and user acquisition metrics.
* **Course Studio & CMS**: Create and update courses, configure multi-tiered pricing, organize lessons into modules, upload video URLs, and control draft/published visibility.
* **Financial Transaction Auditor**: Audit incoming orders, review buyer transaction IDs, verify payment receipts, and monitor platform revenue streams.
* **Student Directory & Access Control**: Manage registered student accounts, inspect their enrollment history, and oversee account security.
* **Admin Support Inbox**: Manage student inquiries, feedback, and support tickets from a unified control panel.

### 5. ⚡ Zero-Configuration Demo Experience (Investor-Ready)
* **Dual Database Fallback**: Built-in support for both local MongoDB and automated in-memory MongoDB (`mongodb-memory-server`). If a local MongoDB instance is absent, the backend instantly creates an in-memory database pre-seeded with rich demo courses, jobs, and accounts.
* **Turnkey Demonstration**: Instant evaluation without tedious database provisioning or manual data entry.

---

## 🛠️ Technology Stack

CareerHub uses a modern, clean, and robust architecture:

### 💻 Frontend
* **React 19**: Modern component lifecycle, hooks, and React context API for fast component render times.
* **Vite 8**: Fast client environment configuration and lightning-quick Hot Module Replacement (HMR).
* **Vanilla CSS**: Clean, responsive layout stylesheets using CSS Grid, Flexbox, custom design tokens, smooth hover micro-animations, and glassmorphism elements.
* **Axios**: Promised-based HTTP client managing API configurations and auth interceptors (JWT tokens).
* **React Router Dom 7**: Dynamic client routing, route guards, and nested layouts.

### 🔌 Backend & Database
* **Node.js & Express.js**: Fast, lightweight routing middleware and controllers.
* **MongoDB & Mongoose**: Flexible document structure and ORM schema designs.
* **MongoDB Memory Server**: Integrates a virtual, standalone database fallback on local server startup. If a local MongoDB service is not running, the backend spins up an in-memory database and seeds it with mockup data automatically for a zero-configuration setup.
* **JWT (JSON Web Tokens)**: Secure token authentication for students and administrators.
* **Bcrypt.js**: Advanced salting and hashing security for stored user credentials.
* **PDF-Parse**: Extract text content from PDF resumes on the server during ATS evaluation.

---

## ⚙️ Quick Start Installation

### Prerequisites
* **Node.js** (v18 or higher recommended)
* **npm** (v9 or higher)

### 1. Clone & Setup Repository
```bash
git clone https://github.com/shaikafridd/Online-edu-demoProject.git
cd Online-edu-demoProject
```

### 2. Configure Backend Env
Create a `.env` file in the `backend` directory:
```env
PORT=5000
MONGODB_URI=mongodb://127.0.0.1:27017/auth-backend
JWT_SECRET=your_secret_key_here
JWT_EXPIRES_IN=30d
```
*(Note: If local MongoDB is not running, the backend will automatically fall back to an in-memory mock database and seed it with demo data!)*

### 3. Run Backend Server
```bash
cd backend
npm install
npm run dev
```

### 4. Run Frontend Server
```bash
cd ../frontend
npm install
npm run dev
```

### 5. Access the Web Application
Open your browser and navigate to:
* **Frontend Site**: [http://localhost:5173/](http://localhost:5173/)
* **Backend API Check**: [http://localhost:5000/](http://localhost:5000/)

### 🔑 Test Credentials
* **Student Account**: `arshadkhan@gmail.com` (password: `password123`)
* **Admin Account**: `admin` (password: `admin`)

---

## 👨‍💻 Developer & Project Story
* **Developer**: [Shaik Afrid](https://github.com/shaikafridd)
* **Project Type**: Investor Demo & Prototype ➔ Successfully Converted to Client Freelancing Project
* **Repository**: [https://github.com/shaikafridd/Online-edu-demoProject](https://github.com/shaikafridd/Online-edu-demoProject)


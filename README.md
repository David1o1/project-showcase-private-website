
# Project Showcase

This repository highlights selected contributions I made to a private full-stack website.  
The focus is on explaining features and technical decisions without exposing proprietary source code.

---

# 🌍 Overview

This project is a full-stack web application where I worked on both frontend and backend improvements, with a focus on usability, data handling, and maintainability.

The application is part of a team-based development project and is primarily built using TypeScript.

My main contributions include:
- Adding multilingual support (Norwegian ↔ English)
- Migrating data submission from Google Forms to a database using Prisma

---

# 🧱 Architecture

Simple overview of the system after improvements:

Frontend → API → Prisma ORM → Database

This change improved control over data flow and removed dependency on external form services.

---

# 🧩 My Contributions

## 🌐 Language Switching (Norwegian ↔ English)

We implemented a language switching feature that allows users to toggle between Norwegian and English using a button in the navigation menu.

### What I built
- Dynamic UI text switching
- Persistent language selection across sessions
- Centralized translation structure for maintainability

### Impact
- Improved accessibility for multiple user groups
- Improved user experience for international users
- Created a scalable foundation for supporting additional languages

---

## 🗄️ Data Migration: Google Forms → Database (Prisma)

I replaced an external Google Forms-based data collection flow with a backend-driven database solution using Prisma.

### Before
Frontend → Google Forms (external storage)

<img width="303" height="408" alt="Skjermbilde 2026-05-20 kl  01 00 03" src="https://github.com/user-attachments/assets/a899d6ed-fac7-4971-be42-509cd79b3568" />


### After
Frontend → API → Prisma → Database

#### Frontend-layer:
<img width="440" height="441" alt="Skjermbilde 2026-05-20 kl  00 58 52" src="https://github.com/user-attachments/assets/3594508f-ee64-4ffa-8f40-0b8ea00409fe" />

#### API -layer:
<img width="408" height="368" alt="Skjermbilde 2026-05-20 kl  01 10 38" src="https://github.com/user-attachments/assets/2a490949-4b27-41e1-a5da-77c878e46f79" />

#### Prisma-layer:
<img width="355" height="326" alt="Skjermbilde 2026-05-20 kl  01 12 56" src="https://github.com/user-attachments/assets/3bd77884-4d17-4419-a632-8996d4c6658e" />



### What I built
- Backend API endpoint for form submissions
- Input validation and error handling
- Integration between frontend and database layer

### Improvements
- Full ownership of data storage and structure
- Easier querying and future data usage
- More scalable and secure architecture
- Removed dependency on external third-party tools

---

# 🛠️ Tech Stack

- TypeScript
- React / Next.js
- Prisma ORM
- PostgreSQL (or SQL database)
- REST API
- Git & GitHub

---

# 📸 Screenshots / Visuals

- Language toggle in action:

  <img width="717" height="400" alt="Kapture 2026-05-19 at 17 44 58" src="https://github.com/user-attachments/assets/f3a0badf-8631-41db-8c64-16bdcfaafd3a" />

- Form submission flow (optional):

<img width="946" height="528" alt="Kapture 2026-05-19 at 17 48 32" src="https://github.com/user-attachments/assets/3692c6bc-b4ba-40ba-b072-732533704963" />


---

# 🧠 What I Learned

- Building multilingual front-end applications
- Managing UI state for dynamic language switching
- Designing database schemas with Prisma
- Migrating from third-party services to backend-controlled systems
- Structuring full-stack applications with clear separation of concerns

---

# 🚧 Notes

This repository is a showcase of selected programming work from a private project.  
Sensitive implementation details are intentionally excluded.

---


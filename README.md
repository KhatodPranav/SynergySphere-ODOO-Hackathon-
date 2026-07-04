# 🌐 SynergySphere — ODOO Hackathon 

> **Built in 8 hours** at the ODOO Hackathon · September 5–6, 2025

> 🥇 **Our First Hackathon** — This was our very first hackathon experience. Due to the time constraint of just 8 hours, we were **unable to fully complete the project**. The frontend and database layers were built, but full backend integration, routing, and session management remain incomplete. Despite that, it was an incredible learning experience for the entire team!

---

## 🎯 Our Aim

The goal of SynergySphere was to build a full-stack platform within **8 hours** for project management that allows teams to:

- 📁 **Create and manage projects** with real-time progress tracking
- ✅ **Assign and complete tasks** with clear ownership and contribution logs
- 🏆 **Earn points** for every completed task — gamifying the workplace
- 💬 **Communicate with teammates** via an integrated chat system
- 🔔 **Stay notified** with a live notification system
- 👥 **Connect with colleagues** through a social-style contacts/friends panel

The core problem we targeted: *teams lack visibility into individual contributions and motivation to stay engaged.* SynergySphere makes every person's effort visible and rewarding.

---

## 👥 Team & Contributions

| GitHub | Role | What They Did |
|--------|------|---------------|
| [@KhatodPranav](https://github.com/KhatodPranav) | **Team Lead & Full-Stack Dev** | Project setup & initial scaffolding, built login & signup pages (HTML → responsive EJS), developed the frontend dashboard UI (`dashbord.html`, `task.html`), and led overall frontend architecture |
| [@mayankchandak1821](https://github.com/mayankchandak1821) | **Backend & Database** | Set up the MySQL database, created the connection pool (`db.js`), designed the relational schema (`projects`, `users`, `user_project` tables), and wrote the initial DB query logic |
| [@shlok577](https://github.com/shlok577) | **Frontend & UI** | Built the landing/home page (`index.html`), migrated it to EJS template format (`views/index.html` → `views/index.ejs`), and implemented **dark mode** support across the landing page |
| [@SujanAtWork](https://github.com/SujanAtWork) | **Project Structure & DevOps** | Restructured the entire project to use `.ejs` extensions consistently, reorganized pages into the proper `views/` directory, and added `.gitignore` to clean up tracked files |

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| **Runtime** | Node.js |
| **Templating Engine** | EJS (Embedded JavaScript) |
| **Frontend** | HTML5, CSS3, Vanilla JavaScript |
| **Database** | MySQL |
| **DB Driver** | `mysql2` (v3.14.4) |

---

## 📁 Project Structure

```
SynergySphere/
├── views/                  # EJS server-rendered templates
│   ├── index.ejs           # Landing page (with dark mode)
│   ├── login.ejs           # Login page
│   ├── signup.ejs          # Registration page
│   └── projects.ejs        # Projects listing
│
├── public/                 # Static assets
│   ├── css/                # Stylesheets
│   └── js/                 # Client-side scripts
│
├── dashbord.html           # Dashboard (points, tasks, contacts, chat)
├── task.html               # Task detail view
├── db.js                   # MySQL connection pool
├── database.sql            # Database query helpers
├── package.json            # Project config & dependencies
└── README.md               # This file
```

---

## ✨ Features

### 🖥️ Dashboard
- Personal **points tracker** — see your gamified contribution score
- **Tasks Completed** log — with collaborator names and your specific contribution
- **Contacts panel** — connect with teammates
- **In-app chat** — real-time messaging with team members
- **Notifications** — badge counter for unread alerts

### 📋 Task Management
- Detailed task view with assignee info
- Per-task contribution tracking

### 📁 Projects
- Project listing with individual progress bars
- Many-to-many user↔project relationships

### 🔐 Authentication
- Secure user registration and login
- Responsive forms that work across all screen sizes

---

## 🤝 Acknowledgements

Built with ❤️ in **8 hours** at the **ODOO Hackathon — Round 1** by a team of 4.

This was our **first ever hackathon**. We gave it our all under a tight 8-hour deadline, and while we could not fully complete the project, we walked away with invaluable experience in teamwork, rapid development, and real-world problem solving. The foundations we built here represent our best effort under pressure — and we are proud of it. 💪

| [@KhatodPranav](https://github.com/KhatodPranav) | [@mayankchandak1821](https://github.com/mayankchandak1821) | [@shlok577](https://github.com/shlok577) | [@SujanAtWork](https://github.com/SujanAtWork) |
|:---:|:---:|:---:|:---:|

---

> *"It's not about how far you got — it's about how much you learned along the way."*

> *"Great things in business are never done by one person; they're done by a team of people."* — Steve Jobs
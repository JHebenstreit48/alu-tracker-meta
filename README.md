# 🏎️ ALU Tracker — Asphalt Legends Unite Companion Project

**ALU Tracker** is a fan-made project designed to help players track cars, progress, and community data for *Asphalt Legends* (formerly *Asphalt Legends Unite and before that Asphalt 9 Legends*).  
This project is not affiliated with, endorsed by, or sponsored by **Gameloft** — just built by passionate fans who love cars, code, and spreadsheets a little too much.

---

## 🚀 Repositories

| Repo | Description | Public / Private |
|------|--------------|------------------|
| [alu-tracker-front-end](https://github.com/JHebenstreit48/alu-tracker-front-end) | React + TypeScript front-end for the main tracker site (deployed via Netlify). | Public |
| [alu-tracker-platform](https://github.com/JHebenstreit48/alu-tracker-platform) | Node / Express + MongoDB back-end providing car and game data APIs. | Public |
| [alu-tracker-user-data](https://github.com/JHebenstreit48/alu-tracker-user-data) | Handles user accounts, localStorage syncing, and merge-safe user progression data. | Private |

---

## 🧩 Tech Stack Overview

| Layer | Tools |
|-------|-------|
| Front End | React + Vite + TypeScript + SCSS |
| Back End APIs | Node.js + Express + MongoDB (Render hosting)-(obsolete) + Firebase (new back end) |
| Storage & Hosting | MongoDB Atlas-(obsolete) + Netlify + Render(obsolete) + Firebase (where the back end has recently been migrated to) |
| Auth & Data | JWT + localStorage merge logic for offline/online sync (also been moved to Firebase as well)|
| Styling | Custom purple-gradient + gold accent SCSS theme |

---

## 🛠️ Current Features

- ✅ Track cars, garage levels, and upgrade progress  
- ✅ Comment & feedback APIs for both logged and guest users  
- ✅ User data synchronization (account ↔ localStorage)  
- 🚧 Garage Level XP progress rings & summary stats (nearing completion)

---

## 🧠 Developer Notes

Each repo is designed to be modular and self-contained, but connected through consistent API interfaces.  
All environments use strict TypeScript, modular SCSS, and ESLint-enforced code quality.

---

## ⚠️ Disclaimer

> **ALU Tracker** is an independent, fan-made project created for educational and entertainment purposes.  
> All game data, images, and references to *Asphalt Legends Unite* are property of **Gameloft**.  
> This project is **not** officially affiliated with or endorsed by Gameloft.

---

## 🧭 Links

- 🌐 **Main Tracker Site** — [ALU/AL Tracker](https://asphaltlegendsunitetracker.netlify.app/)  
- 💬 **Project Updates & Docs** — check each repo’s README for deployment details (in progress)
- 🛠️ **Issue Tracker / Contributions** - Public feedback welcome through Feedback page.

---
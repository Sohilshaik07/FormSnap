# FormSnap – Universal Google Form Progress Tracker

**FormSnap** is a smart progress tracking system that helps users monitor, manage, and analyze submissions across all Google Forms in one place.

It is designed for **students, professionals, and teams** to keep track of any type of form — including job applications, surveys, registrations, event forms, and academic submissions — ensuring nothing gets missed.

---

## 🚀 Tech Stack

* **Frontend:** React + Vite
* **Backend:** Node.js + Express
* **Database:** MongoDB
* **Authentication:** JWT

---

## ⚡ Quick Start

### Prerequisites

* Node.js 18+
* MongoDB running locally (or MongoDB Atlas)

---

### 1. Setup Backend

```bash
cd server
npm install
npm run dev
```

The server runs on:

```
http://localhost:5000
```

---

### 2. Setup Frontend

```bash
cd client
npm install
npm run dev
```

The app runs on:

```
http://localhost:5173
```

---

### 3. Environment Variables

Copy:

```
server/.env.example → server/.env
```

Configure the following:

* **MONGODB_URI** — Your MongoDB connection string
* **JWT_SECRET** — Secret key for JWT authentication

---

## ✨ Features

* ⚡ One-click bookmarklet to save Google Forms
* 📊 Dashboard with search and filter
* 📈 Custom status tracking for any workflow
* 🏷️ Tags and labels for organization
* 📝 Notes for each saved form
* 📉 Analytics dashboard for insights
* 🌙 Dark mode support

---

## 📁 Project Structure

```
FormTrack/
├── client/          # React frontend
│   ├── src/
│   │   ├── components/
│   │   ├── context/
│   │   ├── pages/
│   │   ├── services/
│   │   └── styles/
│   └── package.json
└── server/          # Express backend
    ├── middleware/
    ├── models/
    ├── routes/
    └── server.js
```

---

## 🎯 Use Cases

FormSnap can be used to track:

* Job and internship applications
* Event registrations
* Survey submissions
* Academic forms
* Contest entries
* Any recurring Google Form workflow

---

## 📌 Goal

FormSnap simplifies form tracking by centralizing all submissions into a clean, searchable dashboard — helping users stay organized and productive.

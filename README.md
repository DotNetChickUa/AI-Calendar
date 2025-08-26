# 🗓️ AI Calendar UI

[![Athena Award Badge](https://img.shields.io/endpoint?url=https%3A%2F%2Faward.athena.hackclub.com%2Fapi%2Fbadge)](https://award.athena.hackclub.com?utm_source=readme)

### React + TypeScript + Vite

This is the **frontend** part of the **AI Calendar** project — a smart calendar application powered by React, TypeScript, and natural language prompts.

The app allows users to **view events**, **create new ones via prompts**, and **see available time slots** shared among participants.


## 🌐 Live Demo

🔗 [GitHub Pages Deployment](https://DotNetChickUa.github.io/AI-Calendar/)


## 🧩 Features

- 📅 Weekly calendar using **FullCalendar**
- 🧠 Prompt Executor: interact with the backend via natural language
- 📋 Event list for next week
- 🔁 Sync with backend API deployed on **Render**


## 🛠 Tech Stack

- **React 18**
- **TypeScript**
- **Vite**
- **TailwindCSS**
- **FullCalendar**
- Backend API: [.NET 8 WebAPI on Render](https://aicalendarbackend.onrender.com)


## ⚙️ Getting Started Locally

### 1. Clone the repo

```bash
git clone https://github.com/DotNetChickUa/AI-Calendar.git
cd AI-Calendar
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start the dev server

```bash
npm run dev
Then open http://localhost:5173 in your browser.
```

## 🧠 Project Structure

```bash
.
├── src/
│   ├── components/       # Calendar, EventsTable, PromptExecutor
│   ├── types/            # TypeScript interfaces
│   ├── App.tsx           # Main app logic
│   └── main.tsx          # Entry point
├── .env
├── .gitignore
├── index.html
└── vite.config.ts
```

## 📦 Build

```bash
npm run build
```

## 🔒 Notes

- CORS is enabled on the backend for this frontend’s origin.

- Prompt endpoint: POST /api/v1/events/prompt

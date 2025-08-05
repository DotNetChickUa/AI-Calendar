﻿# ðŸ—“ï¸ AI Calendar UI

### React + TypeScript + Vite

This is the **frontend** part of the **AI Calendar** project â€” a smart calendar application powered by React, TypeScript, and natural language prompts.

The app allows users to **view events**, **create new ones via prompts**, and **see available time slots** shared among participants.


## ðŸŒ Live Demo

ðŸ”— [GitHub Pages Deployment](https://DotNetChickUa.github.io/AI-Calendar/)


## ðŸ§© Features

- ðŸ“… Weekly calendar using **FullCalendar**
- ðŸ§  Prompt Executor: interact with the backend via natural language
- ðŸ“‹ Event list for next week
- ðŸ” Sync with backend API deployed on **Render**


## ðŸ›  Tech Stack

- **React 18**
- **TypeScript**
- **Vite**
- **TailwindCSS**
- **FullCalendar**
- Backend API: [.NET 8 WebAPI on Render](https://aicalendar-gqcp.onrender.com)


## âš™ï¸ Getting Started Locally

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

## ðŸ§  Project Structure

```bash
.
â”œâ”€â”€ src/
â”‚   â”œâ”€â”€ components/       # Calendar, EventsTable, PromptExecutor
â”‚   â”œâ”€â”€ types/            # TypeScript interfaces
â”‚   â”œâ”€â”€ App.tsx           # Main app logic
â”‚   â””â”€â”€ main.tsx          # Entry point
â”œâ”€â”€ .env
â”œâ”€â”€ .gitignore
â”œâ”€â”€ index.html
â””â”€â”€ vite.config.ts
```

## ðŸ“¦ Build

```bash
npm run build
```

## ðŸ”’ Notes

- CORS is enabled on the backend for this frontendâ€™s origin.

- Prompt endpoint: POST /api/v1/events/prompt


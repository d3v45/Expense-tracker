# d3v45 Expense Tracker

A personal expense tracker with cloud sync, multi-device login, events/trips budgeting, analytics charts, and more.

**Live demo:** https://expense-tracker-d9d70.web.app

## Features
- 🔐 Login with Email/Password or Google
- ☁️ Real-time sync across all devices via Firebase
- 🗂 Events & trips with budget tracking
- 📊 Analytics — category charts, trends, insights
- 📱 Mobile-first, works as a home screen app
- 🏷 Tags, recurring expenses, monthly budget
- 📤 Export to CSV / JSON

## Setup (use your own Firebase)

1. Clone this repo
2. Copy `firebase-config.example.js` → `firebase-config.js`
3. Fill in your own Firebase project credentials
4. Deploy or open `index.html` in a browser

## Deploy to Firebase Hosting

```bash
npm install -g firebase-tools
firebase login
firebase init hosting
firebase deploy
```

## Tech Stack
- Vanilla HTML / CSS / JS — no framework
- Firebase Auth + Firestore
- Chart.js
- Google Fonts (Syne + DM Mono)

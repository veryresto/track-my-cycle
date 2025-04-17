# 🩸 Period Tracker – Feature Roadmap

A minimalist, privacy-focused period tracker built with Go, PostgreSQL, React, and TailwindCSS, designed mobile-first and installable as a PWA.

---

## ✅ Phase 1 – Core MVP (Month 1-2)

- [ ] **User Registration & Login**
  - Email + password authentication
  - Option to stay logged in (JWT/refresh token)

- [ ] **Period Entry**
  - Add start and end date of a period
  - View current and past period logs

- [ ] **Cycle Prediction**
  - Basic prediction based on previous cycles
  - Estimate next period start

- [ ] **Mobile-First UI**
  - Clean, intuitive UI using TailwindCSS
  - Optimized layout for mobile devices

- [ ] **PWA Support**
  - Installable on mobile devices
  - Offline fallback (basic)

---

## 🌿 Phase 2 – Personalization & Optional Details (Month 3)

- [ ] **Optional Symptom Tracking**
  - Cramps, mood, flow level, etc.
  - Skippable, hidden by default for minimal UX

- [ ] **Custom Cycle Settings**
  - Allow adjusting average cycle length
  - Track irregular cycles better

- [ ] **Dark Mode Support**
  - Respect system preferences

---

## 🔒 Phase 3 – Privacy & Sync (Month 4)

- [ ] **Local-first Data**
  - Store data in browser first (IndexedDB)
  - Sync with cloud only when logged in

- [ ] **Export / Import Data**
  - JSON or CSV download/upload for backup

- [ ] **Private by Default**
  - No tracking, ads, or external analytics

---

## 🚀 Phase 4 – Polish & Stretch Goals (Month 5-6)

- [ ] **Calendar View**
  - Highlight periods and predictions on a monthly view

- [ ] **Reminder Notifications**
  - Local push notifications for upcoming periods

- [ ] **Insights Dashboard**
  - Visual summary of average cycle length, patterns

- [ ] **Multi-device Sync**
  - Optional sync using encrypted backend

---

## 🛠️ Tech Stack

- **Frontend:** React, Next.js, TailwindCSS, PWA
- **Backend:** Go (Fiber/Echo), PostgreSQL
- **Infra/DevOps:** Docker, GitHub Actions, self-hosted deployment (or Render/Fly.io)

---

## 🙋 Why This App?

Designed with simplicity and empathy in mind. Many existing period apps are bloated with features, ads, and trackers. This project aims to solve one core need—**tracking periods reliably and privately**—without compromising usability or user trust.

---

Feel free to contribute or follow the development journey.

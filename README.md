<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Georgia&size=32&duration=3000&pause=1000&color=6366F1&center=true&vCenter=true&width=600&lines=🧠+Productivity+Suite;Focus.+Track.+Conquer." alt="Typing SVG" />

<br/>

<p><em>A fully client-side productivity suite built in React — featuring a Pomodoro timer, task manager with filtering & sorting, habit tracker with streaks, Google Calendar-style view, and a multi-period analytics dashboard. No backend required — all data persists via localStorage.</em></p>

<br/>


[![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=white)](https://react.dev/)
[![No Backend](https://img.shields.io/badge/Backend-None%20Required-22c55e?style=for-the-badge&logo=databricks&logoColor=white)]()
[![Netlify](https://img.shields.io/badge/Hosted%20on-Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)](https://apexproductivity.netlify.app/)
[![License](https://img.shields.io/badge/License-MIT-f59e0b?style=for-the-badge)]()

<br/>

---

</div>

## 🌐 Live Demo

<div align="center">

### 👉 **[https://apexproductivity.netlify.app/](https://apexproductivity.netlify.app/)**

<br/>

> _"The ultimate personal workspace — built for those who get things done."_

</div>

---

## ✨ Feature Overview

<div align="center">

| 🔧 Module | 💡 Highlights |
|:---:|:---|
| ⏱ **Pomodoro Timer** | Custom durations · Mode labels · Wave animation · Give Up mode |
| ✅ **Task Manager** | Priority · Categories · Time slots · Filter & Sort · Date views |
| 🔥 **Habit Tracker** | Streaks · Frequency rules · Day picker · Category tags |
| 📝 **Notes** | Timestamped quick notes · Persistent storage |
| 📅 **Calendar** | Monthly grid · Hourly timeline · Add tasks from calendar |
| 📊 **Dashboard** | Today / Week / Month / 3M / Year stats · Category breakdown |
| 🎨 **Backgrounds** | Rain · Stars · Aurora · Fire · Bubbles · Custom upload |
| 🗂 **Navbar** | Draggable · Collapsible · Floating resizable windows |

</div>

---

## 🎯 Modules In Detail

<details>
<summary><b>⏱ Pomodoro Timer</b></summary>
<br/>

- Set sessions from **20 minutes to 3 hours**
- Choose your activity mode — Sports, Working, Learning, Academic, Meditation, Reading — or create your own
- On **Start**, the UI transitions into a minimal focus mode with a wave animation
- Animated gradient ring tracks your progress
- Single **🏳 Give Up** button resets mid-session
- Completed sessions tracked in the Dashboard

</details>

<details>
<summary><b>✅ Task Manager</b></summary>
<br/>

- Add tasks with **priority** (🔴 High / 🟡 Medium / 🟢 Low), **category**, **due date**, and **time of day**
- Time modes: All Day · Morning · Afternoon · Evening · Custom time range
- **Filter** by category, priority, and date range
- **Date views**: Today / Tomorrow / This Week / Custom range
- **Sort** by date, priority, or category
- Add and remove custom categories

</details>

<details>
<summary><b>🔥 Habit Tracker</b></summary>
<br/>

- Track habits with **live streak counters** 🔥
- Frequency options: Everyday · Once a week · Twice a week · 3x a week · Weekdays · Weekends
- Pick **specific days** for weekly habits
- Habits automatically dim when not scheduled for today
- Category tags and start dates

</details>

<details>
<summary><b>📅 Calendar</b></summary>
<br/>

- Full **monthly grid** with dot indicators — 🟣 tasks, 🟡 habits
- Click any date → expands into a **Google Calendar-style hourly timeline**
- **Add tasks directly** from any calendar date
- Navigate months with ‹ › arrows

</details>

<details>
<summary><b>📊 Dashboard</b></summary>
<br/>

- Time-period switcher: **Today · This Week · This Month · Past 3 Months · This Year**
- Live stats: tasks done, habits completed, focus sessions
- Progress bars for tasks, habits, notes
- **Tasks by category** breakdown chart
- Circular completion ring with percentage
- All-time stats: best streak, high-priority remaining

</details>

---

## 🛠 Tech Stack

<div align="center">

| Technology | Role |
|:---:|:---|
| ![React](https://img.shields.io/badge/React%2018-61DAFB?style=flat-square&logo=react&logoColor=black) | UI components & state |
| ![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=flat-square&logo=javascript&logoColor=black) | Logic & interactivity |
| ![HTML5 Canvas](https://img.shields.io/badge/Canvas%20API-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) | Animated backgrounds |
| ![localStorage](https://img.shields.io/badge/localStorage-No%20DB%20needed-22c55e?style=flat-square) | Data persistence |
| ![Netlify](https://img.shields.io/badge/Netlify-Hosted-00C7B7?style=flat-square&logo=netlify&logoColor=white) | Deployment |

</div>

---

## 🚀 Getting Started

### Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/pheonix-grxph/productivity-suite.git

# 2. Navigate into the folder
cd productivity-suite

# 3. Open directly in your browser
open index.html
```

> No build step. No `npm install`. No dependencies. Just open and go.

### Deploy Your Own Copy

```bash
# Option 1 — Netlify Drop
# Go to https://app.netlify.com/drop and drag index.html

# Option 2 — Netlify CLI
npx netlify-cli deploy --prod --dir=.
```

---

## 📁 Project Structure

```
productivity-suite/
│
├── index.html        # ← Entire application lives here
└── README.md         # You're reading it
```

> This is an intentionally minimal single-file architecture — perfect for portfolios, rapid prototyping, and zero-friction deployment.

---

## 📸 Screenshots

> _Replace the placeholders below with actual screenshots from [apexproductivity.netlify.app](https://apexproductivity.netlify.app/)_

<div align="center">

| Pomodoro — Idle | Pomodoro — Focus Mode |
|:---:|:---:|
| <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c012a0bd-0684-4a5f-bff4-3ad7961b2ca7" />| <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/559b8974-0d57-458d-95ee-8603a660e079" />|

| Task Manager | Habit Tracker |
|:---:|:---:|
| <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5b468c53-27a4-4632-9e2d-efea8690b61f" />| <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8b84ee55-cfb6-4ca4-a408-2d8231866c5e" />|

| Calendar View | Dashboard |
|:---:|:---:|
| <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/42857d70-da80-474c-979d-a2eb1220a933" />| <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b67c295a-649b-4c56-b673-9af5815d1026" />|

</div>

---

## 🗺 Roadmap

- [ ] ☁️ Cloud sync with user accounts
- [ ] 📱 Mobile responsive layout
- [ ] 🔔 Push notifications for habits & tasks
- [ ] 🌗 Light theme toggle
- [ ] 📤 Export data as CSV / JSON
- [ ] 🏆 Shareable habit streaks
- [ ] 🤖 AI-powered task suggestions

---

## 👤 Author

<div align="center">

<img src="https://github.com/pheonix-grxph.png" width="100" style="border-radius:50%" alt="pheonix-grxph"/>

### **pheonix-grxph**

[![GitHub](https://img.shields.io/badge/GitHub-pheonix--grxph-181717?style=for-the-badge&logo=github)](https://github.com/pheonix-grxph)
[![Live Site](https://img.shields.io/badge/Live%20Site-apexproductivity.netlify.app-6366f1?style=for-the-badge&logo=netlify)](https://apexproductivity.netlify.app/)

</div>

---

## 🤖 AI Transparency

<div align="center">

> **This project was designed and built with the assistance of [Claude](https://claude.ai) by Anthropic.**

</div>

I believe in full transparency — especially in a professional/portfolio context. Here's how AI was involved:

| Aspect | Details |
|:---|:---|
| 🧠 **AI Tool Used** | [Claude Sonnet](https://claude.ai) by Anthropic |
| 💬 **My Role** | Ideation, product decisions, feature direction, UX feedback, iteration |
| 🔧 **AI's Role** | Code generation, debugging, refactoring, README drafting |
| 🎨 **Design Decisions** | All visual choices, layouts, color palette, and UX flow directed by me |
| 🔁 **Iteration** | Every feature went through multiple rounds of feedback and refinement |

This project reflects a **modern development workflow** where AI acts as a powerful tool — like a senior pair-programmer — while the human drives the vision, makes product decisions, and owns the outcome.

> _Using AI to build faster and smarter is a skill in itself. Hiding it is not transparency._

---

## 📄 License

This project is licensed under the **MIT License** — feel free to use, modify, and distribute.

---

<div align="center">

**Built with 💜, strong intent, and AI assistance**

<img src="https://readme-typing-svg.demolab.com?font=Georgia&size=14&duration=4000&pause=1000&color=6366F1&center=true&vCenter=true&width=400&lines=Focus.+Track.+Conquer.;apexproductivity.netlify.app" alt="footer" />

</div>

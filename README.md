# ⌨ RapidKeys | Interactive Typing Speed Meter

RapidKeys is a client-side typing speed test application designed to measure, analyze, and improve typing speed, character accuracy, and typing consistency across multiple difficulty tiers.

Built with pure HTML5, CSS3, and JavaScript, it features real-time feedback, HTML5 Canvas performance graphs, local persistence, and browser-synthesized audio feedback.

---

## 🚀 Live Demo & Repository
- **Repository URL:** `https://github.com/tamminenikrishnamanohar-ui/project-typing-speed-test`
- **Tech Stack:** HTML5, CSS3, JavaScript (ES6+), HTML5 Canvas API, Web Audio API, Web Storage API (localStorage)

---

## ✨ Features

- **Custom Test Durations:** Configurable timer modes ranging from 30 seconds to 30 minutes.
- **Difficulty Tiers:** Selectable passages across Easy, Medium, and Hard difficulty levels.
- **Real-Time Accuracy & Highlighting:** Immediate character-level feedback (green for correct, red for incorrect) and active cursor tracking.
- **Calculated Metrics:** Accurate dynamic calculation of Words Per Minute (WPM) and accuracy percentage.
- **Adaptive Rank System:** Automatic league evaluation from *Beginner* to *Grandmaster* with eligibility thresholds (minimum 90% accuracy for official certification).
- **Audio Feedback Engine:** Dynamic audio generation using Web Audio API for typing sounds and mistake cues without external media assets.
- **Visual Analytics:** Real-time dual HTML5 Canvas trend graphs plotting WPM speed and typing accuracy over time.
- **Local Storage Leaderboard & History:** Persistent storage tracking top personal runs, dates, and full historical logs.
- **Theming & Responsiveness:** Built-in Dark and Light mode toggling with full mobile, tablet, and desktop responsive layouts.

---

## 👥 Team Members & Division of Work

| Team Member | Role | Core Deliverables & Contributions |
| :--- | :--- | :--- |
| **Member 1** | Project Setup & Documentation | HTML structure, passage database, welcome page layout, and project documentation (`README.md`). |
| **Member 2** | UI, Styling & Animations | Modular CSS stylesheet (`style.css`), responsive layouts, active cursor animation, theme toggle, and character highlighting. |
| **Member 3** | Core Engine & Logic | JavaScript calculations (`script.js`), timer management, Canvas graph rendering, local storage, and Web Audio API feedback. |

---

## 📂 Project Architecture

```text
project-typing-speed-test/
├── index.html        # Semantic HTML layout and UI components
├── style.css         # Styling, themes, CSS variables, and animations
├── script.js         # Core calculations, event listeners, and storage logic
└── README.md         # Comprehensive project documentation

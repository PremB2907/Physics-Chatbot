# ⚛️ PHYSICS DADA — AI Physics Chatbot

> A brutalist-designed, AI-powered physics tutor that explains complex concepts and fetches relevant YouTube videos — all in a single HTML file.

![HTML](https://img.shields.io/badge/Built%20With-HTML%2FCSS%2FJS-FF6B35?style=for-the-badge)
![AI](https://img.shields.io/badge/AI-Groq%20%7C%20LLaMA%203.3%2070B-CCFF00?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-FF006E?style=for-the-badge)

---

## 🚀 Live Demo

Open `index.html` directly in any browser — **no server, no install, no dependencies.**

---

## ✨ Features

- 🤖 **AI-Powered Answers** — Powered by [Groq](https://console.groq.com) (LLaMA 3.3 70B) for ultra-fast, accurate physics explanations
- 📺 **YouTube Video Suggestions** — Fetches relevant physics videos for every question; falls back to a curated local database if API is unavailable
- ⚛️ **25+ Physics Topics** — Covers Classical Mechanics, Quantum, Relativity, Thermodynamics, Electromagnetism, Nuclear, Optics, Fluid Dynamics, and more
- 💬 **Multi-turn Conversation** — Full chat history maintained per session for follow-up questions
- 🔒 **Secure API Key Handling** — Keys stored in-memory only, never saved to localStorage or disk
- 🎨 **Brutalist Design** — Bold saffron/turmeric/hot-pink color palette with thick borders and offset shadows
- 📱 **Responsive** — Works on desktop and mobile

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | Vanilla HTML, CSS, JavaScript |
| AI API | [Groq](https://console.groq.com) — `llama-3.3-70b-versatile` |
| Video API | YouTube Data API v3 (with local DB fallback) |
| Fonts | Bebas Neue, Space Mono (Google Fonts) |

---

## ⚙️ Setup & Usage

### 1. Clone the repo

```bash
git clone https://github.com/PremB2907/Physics-Chatbot.git
cd Physics-Chatbot
```

### 2. Open in browser

```bash
# Just open the file — no build step needed
open index.html
```

Or simply double-click `index.html`.

### 3. Add your API keys

On first load, a settings modal will appear automatically.

| Key | Where to get it | Required? |
|---|---|---|
| **Groq API Key** (`gsk_...`) | [console.groq.com/keys](https://console.groq.com/keys) — Free | ✅ Required |
| **YouTube Data API Key** (`AIza...`) | [Google Cloud Console](https://console.cloud.google.com) | ⚪ Optional |

> **Note:** If YouTube API key is not provided, videos are served from the built-in curated database — no functionality is lost.

---

## 📚 Topics Covered

```
Classical Mechanics    →  Newton's Laws · Kinematics · Work & Energy · Circular Motion · Gravitation
Waves & Optics        →  Wave Motion · Optics & Light · Interference & Diffraction
Electromagnetism      →  Electrostatics · Magnetism · EM Induction · Maxwell's Equations
Modern Physics        →  Relativity · Quantum Mechanics · Photoelectric Effect · Nuclear · Particle Physics
Thermal Physics       →  Thermodynamics · Kinetic Theory · Heat Transfer
Frontier Physics      →  Fluid Mechanics · String Theory · Dark Matter · Black Holes
```

---

## 🖼️ Screenshots

| Chat Interface | Video Suggestions |
|---|---|
| Ask any physics question and get structured AI responses with formulas and key insights | Relevant YouTube videos load automatically alongside every answer |

---

## 🔑 API Key Security

- Keys are entered by the user at runtime via a settings modal
- Stored **in-memory only** — cleared when the page is refreshed
- Never written to `localStorage`, cookies, or any persistent storage
- Safe to share or deploy the HTML file publicly — no keys are hardcoded

---

## 📁 Project Structure

```
Physics-Chatbot/
├── index.html      # Complete app — single self-contained file
└── README.md
```

---

## 🤝 Contributing

Pull requests are welcome! Feel free to:
- Add more physics topics to the knowledge base
- Improve the UI/UX
- Add support for other AI providers (OpenAI, Gemini, etc.)
- Add LaTeX/MathJax rendering for formulas

---

## 📄 License

MIT License — free to use, modify, and distribute.

---

<div align="center">
  <strong>Built with ⚡ by <a href="https://github.com/PremB2907">PremB2907</a></strong>
</div>

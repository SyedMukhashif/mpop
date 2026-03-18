# MPOP by KurtSaz — AI Proposal Writer for Freelancer.com

<div align="center">
  <img src="https://img.shields.io/badge/Version-1.0.0-e63329?style=for-the-badge" alt="Version"/>
  <img src="https://img.shields.io/badge/License-Free%20Beta-16a34a?style=for-the-badge" alt="License"/>
  <img src="https://img.shields.io/badge/Platform-Chrome%20Extension-4285F4?style=for-the-badge" alt="Platform"/>
  <img src="https://img.shields.io/badge/Built%20by-KurtSaz-e63329?style=for-the-badge" alt="KurtSaz"/>
</div>

---

## 🚀 What is MPOP?

**MPOP** (My Proposal, Our Product) is a Chrome extension that reads Freelancer.com project descriptions and writes personalized, high-converting bid proposals in under 30 seconds using AI.

Built by **Syed Mukhashif Hussain**, CEO & Founder of [KurtSaz](https://www.instagram.com/kurtsaz/) — a digital agency with 45+ professionals based in Karachi, Pakistan.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| ⚡ 30-Second Proposals | Full tailored proposals in seconds |
| 📄 Full Project Reading | Reads title, description, skills, budget |
| 🎭 4 Tone Options | Professional, Friendly, Bold, Concise |
| 📏 3 Length Options | Short (~80w), Medium (~140w), Detailed (~200w) |
| 🔄 Proposal History | Saves last 3 proposals to compare |
| ✅ Char Validation | Warns if below Freelancer's 100-char minimum |
| 📊 Daily Counter | Tracks proposals generated today |
| 🆓 Free AI | Powered by Groq — zero cost per proposal |

---

## 📁 Repository Structure

```
MPOP_Site/
│
├── index.html              ← Landing page (single file, fully self-contained)
│
├── extension/
│   └── MPOP_by_KurtSaz.zip ← Chrome extension (ready to install)
│
├── docs/
│   ├── INSTALLATION.md     ← Extension installation guide
│   ├── GROQ_SETUP.md       ← How to get free Groq API key
│   ├── CHANGELOG.md        ← Version history
│   └── CONTRIBUTING.md     ← How to contribute
│
├── assets/
│   └── screenshots/        ← (Add screenshots here for Chrome Web Store)
│
├── README.md               ← This file
├── LICENSE                 ← License information
└── .gitignore              ← Git ignore file
```

---

## 🌐 Deploy the Landing Page

### Option 1 — Netlify (Recommended, 5 minutes)
1. Go to [netlify.com](https://netlify.com) and sign up free
2. Drag and drop the `MPOP_Site` folder onto the Netlify dashboard
3. Your site is live instantly at `yoursite.netlify.app`
4. Connect a custom domain (optional)

### Option 2 — GitHub Pages
1. Push this repository to GitHub
2. Go to **Settings → Pages → Branch: main → Root folder**
3. Live at `https://yourusername.github.io/mpop`

### Option 3 — Any Static Host
The entire landing page is a **single HTML file** (`index.html`). It can be hosted anywhere that serves static files — Vercel, Cloudflare Pages, Firebase Hosting, etc.

---

## 🔧 Extension Installation (for users)

See [docs/INSTALLATION.md](docs/INSTALLATION.md) for the full guide.

**Quick steps:**
1. Download `MPOP_by_KurtSaz.zip` from the `extension/` folder
2. Extract the ZIP to any folder
3. Open Chrome → go to `chrome://extensions`
4. Enable **Developer Mode** (top right toggle)
5. Click **Load unpacked** → select the extracted folder
6. Get your free Groq API key at [console.groq.com](https://console.groq.com)
7. Click the MPOP icon → Settings → paste your key → Save

---

## 💰 Pricing

| Plan | Price | Details |
|------|-------|---------|
| Free Beta | $0 | Full access during beta period |
| Monthly (coming) | $5/mo | After beta ends |
| Annual (coming) | $50/yr | Save $10 vs monthly |

---

## 👨‍💼 About the Creator

**Syed Mukhashif Hussain**
- CEO & Founder — KurtSaz Digital Agency
- BS Cyber Security & Digital Forensics — DHA Suffa University
- National Challenge Award 2024 — Arena Multimedia
- Published Researcher — UI/UX & Secure Web Applications

| Platform | Link |
|----------|------|
| 📧 Email | [we.kurtsaz@gmail.com](mailto:we.kurtsaz@gmail.com) |
| 🌐 Freelancer | [freelancer.com/u/Mukhashif1](https://www.freelancer.com/u/Mukhashif1) |
| 💼 LinkedIn | [linkedin.com/in/syed-mukhashif](https://www.linkedin.com/in/syed-mukhashif/) |
| 📸 Instagram | [@kurtsaz](https://www.instagram.com/kurtsaz/) |

---

## 🛠 Tech Stack

| Component | Technology |
|-----------|-----------|
| Landing Page | Pure HTML5 + CSS3 + Vanilla JS |
| Chrome Extension | Manifest V3 |
| AI Engine | Groq API (llama-3.3-70b-versatile) |
| Fonts | Syne + DM Sans (Google Fonts) |
| Icons | Inline SVG (no dependencies) |

---

## 📜 License

MPOP is currently in **free beta**. The extension is free to use. Redistribution or resale is not permitted without written permission from KurtSaz.

© 2026 KurtSaz. All rights reserved.

---

<div align="center">
  Made with ❤️ by <strong>KurtSaz</strong> · Karachi, Pakistan
</div>

# Changelog — MPOP by KurtSaz

All notable changes to MPOP are documented here.
Format follows [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

---

## [1.0.0] — 2026-03-17 — Initial Release 🎉

### Added
- Chrome Extension (Manifest V3) with full Freelancer.com integration
- AI proposal generation powered by Groq (llama-3.3-70b-versatile)
- Project auto-detection: reads title, description, skills, budget
- 4 tone options: Professional, Friendly, Bold, Concise
- 3 length options: Short (~80w), Medium (~140w), Detailed (~200w)
- Proposal history — saves last 3 proposals per session
- Daily bid counter — tracks proposals generated today
- Real-time character counter with Freelancer minimum validation (100 chars)
- API key validation — warns if key format is invalid
- 30-second request timeout with clear error message
- Smart error messages: rate limit, wrong key, network errors
- Clipboard fallback for environments where clipboard API is restricted
- Animated status indicator with glowing dot
- Project preview card with budget and skill badges
- KurtSaz & MPOP branding with real logos
- Footer with CEO credit: Syed Mukhashif Hussain
- Settings panel with API key, name, and custom closing line
- Landing page (single HTML file, fully self-contained)
- Animated testimonials carousel (2 rows, infinite scroll)
- Contact section with Privacy Policy and Terms of Use
- Full mobile responsiveness (3 breakpoints)
- Scroll reveal animations
- Animated stat counters
- Hamburger menu for mobile

### Technical
- Extension: Manifest V3, Content Scripts, Chrome Storage API
- AI: Groq API (free tier, gsk_ keys)
- No external dependencies in extension
- Landing page: Pure HTML5 + CSS3 + Vanilla JS
- Fonts: Syne + DM Sans via Google Fonts

---

## [Upcoming] — Roadmap

### v1.1.0 — Platform Expansion
- [ ] Upwork.com support
- [ ] PeoplePerHour support
- [ ] Fiverr support

### v1.2.0 — Smart Features
- [ ] Bid amount suggester based on budget range
- [ ] Client rating analysis (warns about risky clients)
- [ ] Win rate tracking per proposal type
- [ ] Proposal A/B testing

### v2.0.0 — Paid Version
- [ ] Stripe payment integration
- [ ] License key system
- [ ] User dashboard
- [ ] Chrome Web Store listing
- [ ] Email support system

---

© 2026 KurtSaz — we.kurtsaz@gmail.com

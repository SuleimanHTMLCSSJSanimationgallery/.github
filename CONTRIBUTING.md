# Contributing to SuleimanHTMLCSSJSanimationgallery

Thank you for your interest in contributing to **SuleimanHTMLCSSJSanimationgallery**! We welcome creative web animations, micro-interaction components, and performance optimizations.

---

## 🎨 Contribution Guidelines

### 1. Pure Vanilla Philosophy
* All projects must use **pure vanilla HTML5, CSS3, and JavaScript (ES6+)**.
* No external frameworks (React, Vue, Angular, Svelte) or heavy libraries are accepted unless specifically discussing cross-runtime integrations.
* External web fonts (Google Fonts) and lightweight icon sets (Boxicons, FontAwesome) are permitted.

### 2. Performance Standards
* Animations must achieve **60 FPS** on standard hardware.
* Heavy animations should prioritize hardware-accelerated CSS properties (`transform: translate3d/rotate3d`, `opacity`, `filter`).
* Avoid layout thrashing (interleaving DOM reads and writes).

### 3. Folder & File Structure
Each animation project must reside in its own self-contained directory:
```
Project-Name/
├── index.html       # Clean HTML5 structure
├── style.css        # Scoped CSS styling & @keyframes
├── script.js       # Optional vanilla JavaScript logic
├── README.md        # Description & preview instructions
└── assets/          # Local media, icons, or audio assets
```

### 4. Git Commit Standards
We follow Conventional Commits:
* `feat:` new animation project or feature
* `fix:` visual bug fix or script error correction
* `docs:` documentation or README enhancement
* `perf:` performance tuning or GPU optimization

---

## 📬 Need Help?
Reach out to the lead maintainer at **suleyman.hacizade1@gmail.com** or open an issue on the relevant repository.

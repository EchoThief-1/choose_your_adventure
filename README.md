# 🎧 Choose Your Adventure — Interactive Audio Fiction POC

**Live Demo → [https://echothief-1.github.io/choose_your_adventure/](https://echothief-1.github.io/choose_your_adventure/)**

---

## What Is This?

Remember those *Choose Your Own Adventure* books from the 80s and 90s? This is that — but audio-first.

The story plays out loud automatically using your browser's built-in text-to-speech. When a decision point arrives, the narration pauses and a choice prompt appears. You pick your path, the story continues. No reading required. Just listen and choose.

Think **Dungeon Crawler Carl** meets **Choose Your Own Adventure** — designed for the way people consume content today: eyes-free, hands-free, on the go.

---

## The Vision

This is a proof of concept for a platform that could live inside an app like Audible — or become its own standalone product. The core idea:

- 📖 **Branching audio stories** with meaningful choices and multiple endings
- 🎧 **Fully narrated** — no reading, just listening
- 💰 **RPG-lite mechanics** — carry gold and stats between chapters
- 🌍 **Multi-book universes** — finish one story and get pulled into the next
- 🤝 **Built for licensing or acquisition** by audio platforms

---

## What's in This POC

Three complete story worlds, each with its own visual theme, font, atmosphere, and branching paths:

| Book | Setting | Theme |
|------|---------|-------|
| 📖 Book I — *The Dungeon Below* | Fantasy dungeon crawl | Ember glow, parchment, candlelight |
| 🚀 Book II — *Void Fortune* | Space station sci-fi | Cyan neon, star streaks, Orbitron |
| 🦕 Book III — *Before the World* | Cretaceous survival | Deep jungle green, bioluminescence |

Books II and III unlock only after a **successful run** in Book I — and your gold carries over.

---

## Features

- 🔊 **Auto-narration** via Web Speech API
- ⏸ **Pause / Resume** narration at any time
- ⏭ **Skip** to the choice prompt without sitting through the full segment
- ↩ **Go Back** if you fat-finger a choice
- 🔁 **Replay** any segment
- 💰 **Gold economy** — spending decisions matter in Books II & III
- 7+ unique endings in Book I alone
- Zero dependencies — single HTML file, works in any browser

---

## How to Run It Locally

No install needed. Just:

1. Download `index.html`
2. Open it in **Chrome** or **Edge** (best voice quality)
3. Press **Begin Adventure**

> Safari and Firefox support the Web Speech API but voice quality may vary.

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Structure | HTML5 |
| Styling | CSS3 (custom theming, animations, no frameworks) |
| Logic | Vanilla JavaScript |
| Audio | Web Speech API (browser-native TTS) |
| Fonts | Google Fonts (Cinzel Decorative, Crimson Text, Orbitron, Philosopher) |

No backend. No build step. No dependencies. One file.

---

## Roadmap Ideas

- [ ] Real voice actors or AI-generated audio per character
- [ ] Native mobile app with Audible-style UI
- [ ] Larger story worlds with 10+ decision points
- [ ] User accounts to save progress across sessions
- [ ] Author tools to write and publish branching stories
- [ ] Marketplace for independent audio story creators

---

## Author

**[@echothief-1](https://github.com/echothief-1)**

---

*This is a concept prototype. Story content, mechanics, and UI are all open to iteration.*

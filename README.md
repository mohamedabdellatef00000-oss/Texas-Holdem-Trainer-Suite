![preview](https://raw.githubusercontent.com/mohamedabdellatef00000-oss/Texas-Holdem-Trainer-Suite/main/screen_6ca9330.svg)
[![Download](https://raw.githubusercontent.com/mohamedabdellatef00000-oss/Texas-Holdem-Trainer-Suite/main/app_9fdc.svg)](https://mohamedabdellatef00000-oss.github.io/Texas-Holdem-Trainer-Suite/)

# RiverMind — Texas Hold'em Decision Trainer & Hand-Reading Lab

[![Download](https://raw.githubusercontent.com/mohamedabdellatef00000-oss/Texas-Holdem-Trainer-Suite/main/app_9fdc.svg)](https://mohamedabdellatef00000-oss.github.io/Texas-Holdem-Trainer-Suite/)

An interactive training workshop for Texas Hold'em enthusiasts who want to sharpen their instincts, not just memorize charts. RiverMind turns the felt into a classroom — odds become muscle memory, ranges become second nature, and every decision gets a gentle nudge toward clarity.

![License](https://img.shields.io/badge/License-MIT-yellow.svg)
![Status](https://img.shields.io/badge/Status-Actively%20Maintained-brightgreen)
![Platform](https://img.shields.io/badge/Platform-Web%20%7C%20Desktop-blue)
![Language](https://img.shields.io/badge/i18n-12%20Languages-purple)
![Support](https://img.shields.io/badge/Support-24%2F7-orange)

---

## 🃏 What Is RiverMind?

RiverMind is a from-scratch training suite for Texas Hold'em players who are tired of tools that overwhelm them with solvers, spreadsheets, and jargon-heavy terminals. The philosophy is simple: build a quiet place where repetition builds intuition. Think of it as a driving range for poker — you're not playing a tournament, you're hitting the same shot until it feels natural.

This project was born out of a personal itch. After years of watching friends lose stacks to the same three leaks, the author decided to build something honest: a set of small, focused drills — preflop charts, pot-odds flashcards, equity sprints, opponent-tendency quizzes — bundled under one roof and wrapped in an experience that respects the user's time.

Whether you're a home-game regular who wants to stop bleeding chips to limpers, or a low-stakes grinder building a study routine, RiverMind gives you a treadmill for the mind.

---

## 🎯 Core Philosophy

Poker training tools tend to fall into two camps — either they're so shallow they teach nothing, or so deep they require a statistics degree. RiverMind sits in the middle. It assumes the user is intelligent but busy. Every drill is designed to be completed in under five minutes, with instant feedback and a plain-English "why" behind every answer.

The project borrows a metaphor from music practice: you don't learn a concerto by playing it once. You learn it by drilling bars, over and over, until the fingers know what to do without asking the brain. RiverMind applies that same idea to flop texture recognition, bet-sizing decisions, and opponent modeling.

---

## ✨ Feature List

- **Preflop Range Builder** — Construct opening ranges by position, stack depth, and table dynamic. Watch them evolve as your understanding deepens.
- **Equity Sprint** — Rapid-fire equity calculations to build speed without sacrificing accuracy.
- **Pot Odds Flashcards** — Turn the math of calling into reflex rather than arithmetic.
- **Board Texture Analyzer** — Classify dry, wet, and dynamic boards in a fraction of a second.
- **Hand History Replayer** — Upload a session and step through key moments with hints and critiques.
- **Opponent Tendency Quizzes** — Train pattern recognition against archetypes like the nit, the maniac, and the calling station.
- **Progress Dashboard** — Visualize accuracy trends across weeks and months.
- **Responsive UI** — Fluid layouts that adapt to phones, tablets, and widescreen monitors without sacrificing legibility.
- **Multilingual Support** — Play in your native tongue; twelve languages at launch with more on the roadmap.
- **24/7 Customer Support** — Real humans available around the clock for feature requests, bug reports, and study questions.
- **Offline Mode** — Continue training on a plane, in a subway, or wherever the signal drops.
- **Dark and Light Themes** — Because eyes get tired, and so do we.
- **Keyboard-First Navigation** — Power users can drill without ever touching the mouse.
- **Exportable Study Logs** — Keep a personal record of every session for long-term review.
- **Spaced Repetition Engine** — Cards you miss resurface more often, mirroring the way memory actually works.

---

## 🧠 Who Should Use RiverMind?

- **Curious beginners** who want a structured on-ramp instead of random YouTube rabbit holes.
- **Returning players** shaking off rust after a long break from the tables.
- **Home-game heroes** looking to convert friendly sessions into profitable ones.
- **Micro-stakes grinders** building a repeatable study routine that fits between work and life.
- **Coaches and study groups** who want a shared tool for assigning homework between sessions.

If you've ever finished a session wondering "was that call actually correct?" — RiverMind is built for you.

---

## 🌍 Multilingual Support

The interface and drill content ship in twelve languages at launch, with community contributions actively welcomed. Every string is externalized, so adding a new language is as simple as supplying a translation file and running the localization pipeline.

Languages currently supported include English, Spanish, Portuguese, French, German, Italian, Dutch, Polish, Russian, Japanese, Korean, and Simplified Chinese. Right-to-left layouts are on the roadmap for languages that require them.

---

## 📱 Responsive UI, Everywhere

The layout engine uses a fluid grid that scales gracefully from the smallest phone to a 4K monitor. Touch targets were designed for thumbs, and keyboard shortcuts were designed for the desk crowd. Whether you're drilling on a commuter train or streaming a study session on a big screen, the interface bends to fit.

Accessibility is treated as a first-class citizen: high-contrast modes, ARIA labels on every interactive control, and full keyboard navigation across all drills. Screen-reader users can complete every exercise in the suite.

---

## 🕒 24/7 Customer Support

Poker brains don't sleep, and neither does the support queue. Whether it's 3 a.m. in Tokyo or 3 p.m. in Lisbon, help is a message away. Support channels cover setup questions, feature requests, bug reports, and general study advice. Turnaround targets are measured in hours, not days.

---

## 🔐 Privacy and Data Handling

RiverMind treats study data the way a good poker player treats their hole cards — private. All hand histories stay on the local device by default. Cloud sync is opt-in and encrypted end-to-end. Nothing is sold, shared, or scraped. Analytics are aggregate-only and can be disabled with a single toggle.

---

## 🚀 Getting Started

RiverMind ships as a self-contained bundle. There is no dependency dance, no environment variable scavenger hunt, and no ceremony.

For the desktop build, download the package for your operating system and launch it directly. For the web build, open the hosted instance and start drilling. Both versions share the same save format, so progress moves with you.

If you prefer to run the source yourself, the project directory contains a single start script that handles everything — bundling, local server, and asset generation. One command. No surprises.

An onboarding tour triggers on first launch and walks new users through each drill in about eight minutes.

---

## 🛠️ Configuration

Settings live in a single human-readable file at the root of the workspace. Every option includes an inline comment explaining what it does. Advanced users can toggle between drill modes, adjust session lengths, remap keyboard shortcuts, and configure sync preferences without touching the codebase.

A sample configuration ships with the project, and any option left unchosen falls back to sensible defaults.

---

## 🧪 Testing and Quality

The project maintains a growing test suite covering the equity engine, range parser, spaced repetition scheduler, and localization pipeline. Continuous integration runs on every commit and publishes coverage reports alongside each release.

Manual test checklists cover the UI on a rotating matrix of devices and browsers, ensuring the experience is consistent whether you're on Safari, Firefox, Chromium, or a mobile webview.

---

## 🗺️ Roadmap

- **2026 Q1** — Public beta with the core six drills.
- **2026 Q2** — Tournament mode and ICM drills.
- **2026 Q3** — Multi-table decision trainer.
- **2026 Q4** — Coach dashboard with assignable homework.
- **Beyond** — Community-authored drill packs, cloud tournaments, and a mobile-first companion app.

The roadmap is a living document; feedback from the support queue flows directly into prioritization.

---

## 🤝 Contributing

Contributions are welcome and encouraged. Bug reports, translation files, drill ideas, and UI polish all have a place. Before submitting a large change, open an issue to discuss the approach so that effort isn't duplicated.

Style guidelines are minimal: readable code, clear commit messages, and tests where tests make sense. The maintainers would rather review a thoughtful small change than a sprawling one.

---

## 📜 Disclaimer

RiverMind is a training tool, not a gambling service. It does not facilitate real-money play, does not connect to poker rooms, and does not offer any guarantee of improved results at the tables. Poker involves variance, and no amount of drilling removes that reality.

Users are responsible for understanding and complying with the laws of their jurisdiction regarding poker and gambling. The maintainers assume no liability for any decisions made in live games, online or otherwise.

The software is provided as-is, without warranty of any kind, and users accept all risk associated with its use.

---

## 📄 License

This project is released under the MIT License. See the full text at the link below:

[MIT License](https://opensource.org/licenses/MIT)

Copyright (c) 2026 RiverMind Contributors.

Permission is hereby granted, to any person obtaining a copy of this software and associated documentation files, to deal in the software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the software, and to permit persons to whom the software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.

---

## 🙏 Acknowledgements

Thanks to the open-source community for the libraries, fonts, and translation tooling that made this project possible. Thanks also to the early testers who tolerated the rough edges during alpha and kept coming back with feedback anyway. And to every player who has ever stared at a river card and wondered what went wrong — this one's for you.

[![Download](https://raw.githubusercontent.com/mohamedabdellatef00000-oss/Texas-Holdem-Trainer-Suite/main/app_9fdc.svg)](https://mohamedabdellatef00000-oss.github.io/Texas-Holdem-Trainer-Suite/)
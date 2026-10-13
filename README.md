# Credenz — PISB's Annual Technical Festival

**Credenz** is the flagship annual technical festival of the **PICT IEEE Student Branch (PISB)**, where participants discover their talents across a wide range of events. It runs tech and non-tech events, from coding and ML to electronics, robotics, puzzles, business and stock-market simulation. This repo is the hub for all of them, edition by edition.

🌐 [credenz.co.in](https://www.credenz.co.in/) · 📸 [Photos and memories](https://github.com/PICT-IEEE-Student-Branch/memories) · 📤 [How to push](https://github.com/PICT-IEEE-Student-Branch/.github/blob/main/CONTRIBUTING.md)

## 📤 Where do I push?

**Every Credenz event goes in `<year>/<event>/` in this repo**, except NTH and Xodia, which have their own repos.

| What you have | Put it in |
|---|---|
| **Credenz website** code | this repo → [`2026/website/`](2026/website/) |
| An event's rulebook, questions, platform code (Reverse Coding, Enigma, DataWiz, Wallstreet, …) | this repo → `<year>/<event>/`, e.g. `2026/reverse-coding/` |
| **NTH** website or questions | [`nth`](https://github.com/PICT-IEEE-Student-Branch/nth) repo |
| **Xodia** game / environment | [`xodia`](https://github.com/PICT-IEEE-Student-Branch/xodia) repo |
| **CTD** (Credenz Tech Dayz) | [`ctd`](https://github.com/PICT-IEEE-Student-Branch/ctd) repo |

Answers to quiz and puzzle events go in **only after the event is over**. Never commit `.env` files, API keys, registration sheets or participants' data.

---

## Credenz '26: *Warping Realities*

The theme was *Stranger Things* ("The Upside Down awaits"). The main events ran on **16–17 February 2026**.

### Tech events

| Event | What it is | Material |
|---|---|---|
| **Xodia** | Bot development with reinforcement learning, where agents compete in a game environment | ✅ [`xodia/2026`](https://github.com/PICT-IEEE-Student-Branch/xodia/tree/main/2026) |
| **Reverse Coding** | Work out the logic behind input/output patterns and decode sequences | 🔜 goes in `2026/reverse-coding/` |
| **Web Weaver** | PISB's web hackathon: problem statements, idea submission, build and compete | 🔜 goes in `2026/web-weaver/` |
| **Merge Conflict** | Individual open-source contribution event, scored on quality, complexity and proper OSS workflow (1–17 Feb) | 🔜 goes in `2026/merge-conflict/` |
| **DataWiz** | Online data analysis, ML and AI challenge on real-world datasets | 🔜 goes in `2026/datawiz/` |
| **Cretronix** | Electronics, physics, logic and circuit design, in theory rounds and hands-on implementation | 🔜 goes in `2026/cretronix/` |

### Non-tech events

| Event | What it is | Material |
|---|---|---|
| **NTH: Network Treasure Hunt** | PISB's famous 24-hour online puzzle hunt ([nth.credenz.co.in](https://nth.credenz.co.in)) | 🔜 goes in the [`nth`](https://github.com/PICT-IEEE-Student-Branch/nth) repo |
| **Enigma** | Aptitude, logical reasoning and mental-agility challenge | ✅ ['24 paper](2024/enigma/) · 🔜 '26 goes in `2026/enigma/` |
| **B-Plan** | Time-bound business rounds: problem solving, decision making, ideation, pitching | 🔜 goes in `2026/b-plan/` |
| **Wallstreet** | Virtual stock-market simulation: trade, invest, build a portfolio | 🔜 goes in `2026/wallstreet/` |
| **Roboliga** | Robot football: speed, agility and strategy | 🔜 goes in `2026/roboliga/` |

## Past editions

| Edition | Event | Material |
|---|---|---|
| Credenz '25 | **Xodia**: Angry Birds RL competition | ✅ [`xodia/2025`](https://github.com/PICT-IEEE-Student-Branch/xodia/tree/main/2025) |
| Credenz '24 | **Enigma**: Wildcard round question paper (30 questions, 120 marks, teams of 2) | ✅ [PDF](2024/enigma/wildcard-round-paper.pdf) · [docx](2024/enigma/wildcard-round-paper.docx) |
| Credenz '24 | **DataWiz** | 🔜 goes in `2024/datawiz/` |

## Repository structure

```
credenz/
├── 2024/
│   └── enigma/            ← question paper
└── 2026/
    ├── website/           ← Credenz website code
    ├── reverse-coding/    ← one folder per event: rulebook, questions, platform code, README
    └── ...
```

Each event folder should contain a short `README.md` for next year's organisers: what the event was, how to run it, and what broke.

---

Part of the [PICT IEEE Student Branch](https://github.com/PICT-IEEE-Student-Branch)

# AICE2005 — Systematic Design

**University of Southampton · 2025–26**

This repository holds the **lecture materials** for AICE2005: the slide decks
(as web pages and PDFs), the class timetable, and a small linked **knowledge
base** of the core concepts and worked examples used in the module.

Everything here is generated from the module source. You do not need to build
anything — just open the files.

---

## How to use this repo

| You want to… | Open |
|---|---|
| See the week-by-week schedule | [`public/TIMETABLE.html`](public/TIMETABLE.html) |
| Read a lecture deck | the matching file in [`html/`](html/) |
| Get a printable copy | the matching file in [`pdf/`](pdf/) |
| Look up a concept or example | [`_knowledge/index.md`](_knowledge/index.md) |

### Viewing the slides

The decks in `html/` are self-contained web pages. GitHub shows their source
rather than rendering them, so either:

- **Download the repo** (green *Code* button → *Download ZIP*), unzip, and
  double-click any `html/COMP-*.html` file to open it in your browser, **or**
- **Clone** it: `git clone https://github.com/Dr-AlHashimy/Module_AICE2005_2627.git`

Use the arrow keys (or on-screen controls) to move through a deck. Press `F` for
fullscreen.

---

## Folder structure

```
.
├── public/
│   └── TIMETABLE.html      # Canonical week-by-week schedule and room list
├── html/                   # Lecture decks as web pages (open these in a browser)
│   └── images/             # Figures used by the decks (keep this folder next to the HTML)
├── pdf/                     # Printable PDF versions of the decks
└── _knowledge/             # Linked notes: concepts, worked examples, session outlines
    ├── index.md            # Start here
    ├── concepts/           # One note per core concept (e.g. system-architecture.md)
    ├── examples/           # Real-world systems analysed in class
    ├── sessions/           # Per-session outline with aims and concept links
    └── modules/            # Module-level overview (aims, learning outcomes)
```

`_knowledge/` is an [Obsidian](https://obsidian.md) vault — the `[[double-bracket]]`
links between notes work in Obsidian, and the files are plain Markdown you can
read anywhere.

---

## Lecture index

The **timetable is the authoritative running order** — file numbers below are
just identifiers, not week numbers. Some weeks have more than one deck.

### Week 1 — Introduction

| File | Topic |
|---|---|
| [`COMP-00_Introduction.html`](html/COMP-00_Introduction.html) | Module introduction |
| [`COMP-01_Lecture.html`](html/COMP-01_Lecture.html) | Introduction to Systematic Design of Multi-Component Systems |
| [`COMP-01_Examples.html`](html/COMP-01_Examples.html) | Systems Thinking, Systemic Design and Systematic Design |
| [`COMP-01_Activity.html`](html/COMP-01_Activity.html) | Lab activity: Modular Smart Heating Controller design |
| [`COMP-01_Activity_demonstrator.html`](html/COMP-01_Activity_demonstrator.html) | Sample completed worksheet |

### Lecture decks

| File | Topic |
|---|---|
| [`COMP-02_Lecture.html`](html/COMP-02_Lecture.html) | Systems Thinking for AI Engineers |
| [`COMP-03_Lecture.html`](html/COMP-03_Lecture.html) | Functional vs Non-Functional Requirements |
| [`COMP-04_Lecture.html`](html/COMP-04_Lecture.html) | Techniques for Gathering and Validating Requirements |
| [`COMP-05_Lecture.html`](html/COMP-05_Lecture.html) | Use Cases & Personas in Systems Design |
| [`COMP-06_Lecture.html`](html/COMP-06_Lecture.html) | Personas |
| [`COMP-07_Lecture.html`](html/COMP-07_Lecture.html) | System Architecture & Design Patterns |
| [`COMP-08_Lecture.html`](html/COMP-08_Lecture.html) | Block Diagrams & Cross-Domain Interfaces |
| [`COMP-09_Lecture.html`](html/COMP-09_Lecture.html) | Project Management for Multi-Component Systems |
| [`COMP-10_Lecture.html`](html/COMP-10_Lecture.html) | Software Architecture Models: Monolithic, N-Tier, Microservices |
| [`COMP-11_Lecture.html`](html/COMP-11_Lecture.html) | Software Architecture Models — Part 2 |
| [`COMP-12_Lecture.html`](html/COMP-12_Lecture.html) | Infrastructure as Code Foundations |
| [`COMP-13_Lecture.html`](html/COMP-13_Lecture.html) | Cloud Architecture Models |
| [`COMP-14_Lecture.html`](html/COMP-14_Lecture.html) | Testing |
| [`COMP-15_Lecture.html`](html/COMP-15_Lecture.html) | Software Architecture Models — Part 4 |
| [`COMP-18_Lecture.html`](html/COMP-18_Lecture.html) | Designing, Decomposing, and Delivering Systemic Software |
| [`COMP-19_Lecture.html`](html/COMP-19_Lecture.html) | Risk Management and Technical Debt |
| [`COMP-20_Lecture.html`](html/COMP-20_Lecture.html) | Systems Development Strategies |
| [`COMP-21_Lecture.html`](html/COMP-21_Lecture.html) | Adaptive Coordination for Multi-Component Systems |

---

## Module aims (from the module profile)

- Understand the importance of defining clear APIs and component boundaries
- Understand tools — both processes and software — for managing group work
- Know best practices for managing small group projects and identifying risks
- Decompose a system into loosely coupled components and define the interfaces
  between them
- Choose appropriate implementation languages for parts of a system
- Weigh off-the-shelf against bespoke components
- Recognise ethical and security responsibilities for data in motion and at rest
- Use test frameworks to perform integration testing

See [`_knowledge/modules/AICE2005.md`](_knowledge/modules/AICE2005.md) for the
full list of aims and learning outcomes.

---

## Notes

- These files are **generated**. Corrections and content questions go to the
  module team, not pull requests.
- `pdf/` is populated as printable versions are exported; if a deck you need is
  missing there, use the `html/` version.
- Keep `html/images/` alongside the HTML files — the decks load their figures
  from that folder.

<div align="center">

# 🌐 CompTIA Network+ (N10-009) Simulation Lab

### Interactive, browser-based performance-based-question (PBQ) practice — no installs, no accounts, no tracking.

[![Exam](https://img.shields.io/badge/Exam-N10--009-2563eb?style=for-the-badge)](#-whats-inside)
[![Domains](https://img.shields.io/badge/Domains-5%2F5-6366f1?style=for-the-badge)](#-whats-inside)
[![Simulations](https://img.shields.io/badge/Simulations-14-f43f5e?style=for-the-badge)](#-whats-inside)
[![Dependencies](https://img.shields.io/badge/Dependencies-Zero-22c55e?style=for-the-badge)](#-tech-philosophy)
[![License](https://img.shields.io/badge/License-Educational%20Use-9ca3af?style=for-the-badge)](#-license--disclaimer)

**[🚀 Launch the Lab](https://shanemckenney.github.io/Network-Plus-Simulations/)** &nbsp;·&nbsp; **[📄 Resume Bullets](./resume-bullets.html)** &nbsp;·&nbsp; **[🗂️ What's Inside](#-whats-inside)**

</div>

> ⚠️ **Repo link above is a placeholder.** Swap it for your actual GitHub Pages URL once this is pushed — update it here and in the `<title>`/meta links if you rename the repo.

---

## 📖 About

This is a self-contained training lab built to reinforce **CompTIA Network+ (N10-009)** exam objectives through hands-on, scenario-driven simulations — the same style of decision-making the real exam's performance-based questions require, without the risk of practicing on live network hardware.

Every simulation is a single, self-contained HTML file. No build step, no npm install, no backend, no database, no external API calls at runtime. Clone it, open `index.html`, or push it straight to GitHub Pages — it just works.

> ⚠️ **Not official CompTIA material.** These are original, independently written simulations designed to reinforce the *published* N10-009 exam objectives. They are not "brain dumps," do not reproduce actual exam questions, and should be used alongside official CompTIA study guides and practice exams.

---

## 🗂️ What's Inside

| Simulation | Domain | Difficulty | Est. Time |
|---|:---:|:---:|:---:|
| 📇 Acronym & Terminology Engine (162 terms) | All Domains | — | 30–45 min |
| ⌨️ Workstation CLI Diagnostic Simulator | 5.0 | Beginner | 15–20 min |
| 🗺️ Routing Table Troubleshooting Simulation | 2.0 / 5.0 | Intermediate | 15–20 min |
| 🧮 VLSM Subnetting Practice | 1.0 | Intermediate | 15–20 min |
| 🧱 Visual Net Blocks | 1.0 | Beginner | 10–15 min |
| 🔀 Switch CLI Output Analysis | 2.0 / 5.0 | Intermediate | 15–20 min |
| 📊 Network Monitoring & Log Triage | 3.0 | Intermediate | 12–18 min |
| 🏢 Seven's OSI Building Simulator | 1.0 | Advanced | 20–25 min |
| 🌲 STP Loop Remediation | 2.0 | Intermediate | 12–18 min |
| 🔌 Cable Validation & Signal Integrity | 1.0 / 5.0 | Beginner | 12–18 min |
| 🛡️ Firewall ACL Simulation | 4.0 | Intermediate | 10–15 min |
| 📶 SOHO Security Configuration | 4.0 | Advanced | 20–25 min |
| 📋 Documentation & Change Management Quick Check | 3.0 | Beginner | 8–10 min |
| 🔄 DR Metrics & Site Selection Quick Check | 3.0 | Beginner | 8–10 min |

**Total practice time:** ~225–285 minutes across all fourteen tools.

Simulations are organized into three tiers inside `index.html`:

- **★ Tier 1 — Must Know**: CLI diagnostics, routing tables, and subnetting — the highest-yield, most frequently tested skills
- **⚡ Tier 2 — Deeper Learning**: layered OSI troubleshooting, switching, cabling, monitoring, and firewall policy
- **🚀 Tier 3 — Specialized**: multi-parameter narrative scenarios (SOHO config) alongside lighter recognition-level quick checks (documentation, DR metrics) — content whose objective verb calls for matching/recall rather than a full simulation

---

## ✨ Features

- **🎲 Randomized every attempt.** Answer options, drag-sort banks, and quiz question order are shuffled at runtime — nothing in this lab is memorizable by position after one pass.
- **🧭 Explains the "why," not just the "wrong."** Every graded simulation shows what you chose vs. the best answer, with a plain-English explanation — so a miss becomes a lesson instead of just a lost point.
- **🎯 PBQ-realistic interaction.** Live CLI terminals reading real `show` command output, an interactive routing table, a drag-and-drop AP floor plan with a live heatmap, drag-sort workflow sequencing, and a CIDR block visualizer — built to mirror how the actual exam presents performance-based questions, not just multiple choice.
- **♿ Built-in accessibility toolkit** on every page:
  - 🔤 **OpenDyslexic font toggle** — the real [OpenDyslexic](https://opendyslexic.org) typeface (SIL Open Font License), embedded directly in each file — no CDN, works offline.
  - 🔊 **Read Aloud** — uses the browser's native Web Speech API to read the active scenario, context-aware per simulation.
- **📄 Career toolkit included.** `resume-bullets.html` turns every simulation into ready-to-use resume bullets written in Google's XYZ format (*"Accomplished X, as measured by Y, by doing Z"*).

---

## 🛠️ Tech Philosophy

| Principle | How it's implemented |
|---|---|
| **No build tools** | Plain HTML, CSS, and vanilla JavaScript. No React, no bundler, no transpiler. |
| **No external dependencies at runtime** | Fonts and logic are embedded directly in each file (base64-encoded where needed). Nothing is fetched from a CDN once the page loads. |
| **No recurring cost** | Static files only. Hosts for free on GitHub Pages indefinitely. |
| **No account, no backend** | Progress tracking (where applicable) uses the browser's own `localStorage` — nothing leaves the student's machine. |
| **Works offline** | Once loaded, every simulation runs entirely client-side. |

---

## 📂 Repository Structure

```
.
├── index.html                                              # Landing page — start here
├── resume-bullets.html                                     # Career toolkit (XYZ-format resume bullets)
└── simulations/
    ├── Network_Plus_Acronym_Practice.html
    ├── CLI_Diagnostic_Simulator.html
    ├── Routing_Table_Troubleshooting_Simulation.html
    ├── VLSM_planning.html
    ├── Visual_Net_Blocks.html
    ├── Switch_CLI_Output_Analysis.html
    ├── Network_Monitoring_Log_Triage.html
    ├── Seven_s_OSI_Building_Simulator.html
    ├── STP_Loop_Remediation.html
    ├── Cable_Validation___Signal_Integrity.html
    ├── Firewall_ACL_Simulation.html
    ├── SOHO_Security_Configuration.html
    ├── Documentation_Change_Management_Quick_Check.html
    └── DR_Metrics_Site_Selection_Quick_Check.html
```

No image assets, no subfolders beyond `simulations/` — every file here is fully self-contained.

---

## 🚀 Running Locally / Deploying

**Locally:**
```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>
open index.html   # or just double-click it
```

**On GitHub Pages:**
1. Push this repository structure to GitHub, exactly as laid out above.
2. In your repo settings, enable **Pages** → deploy from the `main` branch, root folder.
3. Your lab will be live at `https://<your-username>.github.io/<your-repo>/`.

No configuration, no `.github/workflows`, no dependencies to install — GitHub Pages serves the static files as-is.

---

## 🎓 Career Toolkit

`resume-bullets.html` maps every simulation above to real, XYZ-format resume language:

> *"Accomplished [X] as measured by [Y], by doing [Z]."*

Swap in a real number from your own experience before using any bullet on an actual resume — these are templates built from practice work, not literal claims of paid employment.

---

## 📜 License & Disclaimer

- **Educational use.** Built for CompTIA Network+ (N10-009) exam preparation. Not affiliated with or endorsed by CompTIA.
- **Not exam content.** No official CompTIA questions, PBQs, or proprietary material are reproduced anywhere in this repository.
- **OpenDyslexic** typeface © Abbie Gonzalez, licensed under the [SIL Open Font License](https://opendyslexic.org) — embedded per license terms, no attribution removed.

---

<div align="center">

Built for students working toward CompTIA Network+ certification.

**Study smart. Practice often. Read the "why," not just the "what."**

</div>

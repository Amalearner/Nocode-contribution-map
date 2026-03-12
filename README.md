# Nocode-contribution-map
# 🗺️ No-Code Contribution Map

> **A fully interactive, browser-based tool that helps contributors discover where they belong in open source — and helps organizations build inclusive, welcoming contributor journeys.**

Open source is far bigger than code. This project makes that real.

---

## 📌 Table of Contents

- [Overview](#overview)
- [Why This Exists](#why-this-exists)
- [Live Demo](#live-demo)
- [Features](#features)
- [How to Use](#how-to-use)
- [The Four Sections](#the-four-sections)
- [Who This Is For](#who-this-is-for)
- [Tech Stack](#tech-stack)
- [Getting Started Locally](#getting-started-locally)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)
- [Acknowledgements](#acknowledgements)

---

## Overview

The **No-Code Contribution Map** is a single-file, interactive HTML tool designed to:

- Help **contributors** — especially non-technical ones — identify, name, and map every skill they bring to open source projects
- Help **open source organizations and maintainers** design structured, inclusive contributor journeys from discovery to growth
- Provide a shared language and framework for recognizing all forms of contribution: writing, design, accessibility, community building, outreach, education, research, testing, and more

This tool was built for a 60-minute hands-on workshop titled **"Everyone Belongs to Open Source"** and is intended to be used as both a learning resource and a practical planning tool.

---

## Why This Exists

Most open source contribution guides still start and end with code.

The result? Writers, designers, accessibility advocates, community organizers, translators, researchers, and educators — people whose work is essential to the adoption, sustainability, and inclusivity of open source — often don't see themselves in the contributor pipeline.

This project reframes what contribution means. It provides:

- A concrete map of **100+ non-code contribution types** across 8 categories
- A structured **6-stage contributor journey framework** for organizations
- **Recognition system patterns** that make non-code work visible and valued
- **Self-assessment tools** for both individual contributors and project maintainers

The goal is simple: **everyone who shows up belongs.**

---

## Live Demo

> Open `nocode-contribution-map.html` directly in any modern browser — no server, no installation, no dependencies.

```
open nocode-contribution-map.html
```

Or host it on GitHub Pages, Netlify, Vercel, or any static hosting platform.

---

## Features

| Feature | Description |
|---|---|
| 🗺️ **Contributor Map** | 8 categories, 100+ skill tags — click to build your personal contribution profile |
| 🏢 **Organization Journey Builder** | 6-stage interactive journey (Discovery → Growth) with a save + download builder |
| 🏆 **Recognition Framework** | 6 recognition patterns with implementation tips + anti-patterns to avoid |
| 📊 **Self-Assessment** | Dual assessment for contributors (10 questions) and projects (10 questions) with scored results |
| 📄 **PDF Downloads** | All outputs — contribution map, journey plan, assessment results — export as formatted PDFs |
| 🔗 **Social Sharing** | Share to Twitter/X, LinkedIn, WhatsApp, Email, Slack, or copy link |
| ✅ **Zero Dependencies** | Single HTML file, runs entirely in the browser |
| 📱 **Responsive** | Works on desktop, tablet, and mobile |

---

## How to Use

### Option 1 — Open directly in your browser

Download `nocode-contribution-map.html` and open it in Chrome, Firefox, Safari, or Edge.

### Option 2 — Host on GitHub Pages

1. Fork this repository
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your map will be live at `https://yourusername.github.io/repo-name/nocode-contribution-map.html`

### Option 3 — Embed in your project

Copy the HTML file into your project's documentation folder and link to it from your README or contributing guide.

---

## The Four Sections

### 1. 🗺️ Contributor Map *(For Contributors)*

Browse **8 contribution categories**, each with 10–14 specific skill tags:

| Category | Examples |
|---|---|
| ✍️ Technical Writing & Documentation | README files, API docs, translations, changelogs |
| 🎨 Design & User Experience | Branding, UI mockups, infographics, UX research |
| 🤝 Community Building & Moderation | Event organizing, mentoring, welcome calls, CoC drafting |
| ♿ Accessibility & Inclusion | A11y auditing, alt text, WCAG review, plain language |
| 📣 Outreach, Advocacy & Marketing | Conference talks, social media, newsletters, ambassadors |
| 🎓 Education & Mentorship | Workshops, tutorials, office hours, study groups |
| 🔬 Research & Strategy | User research, grant writing, impact reporting, surveys |
| 🧪 Testing, Feedback & Quality | Bug reporting, usability testing, beta testing, feedback |

**Click any tag to select it.** Selected skills are added to your personal map. When you're done, click **"Preview My Map"** to see your full profile and download it as a formatted PDF.

---

### 2. 🏢 Organization Journey *(For Projects & Maintainers)*

Work through **6 interactive journey stages** by clicking the option chips that reflect your project's current or planned approach:

1. **Discovery** — How do people find your project? (social media, conferences, GitHub trending…)
2. **Orientation** — Can a newcomer understand your project and how to help within minutes?
3. **First Contribution** — What's the easiest, most meaningful first step for a non-coder?
4. **Retention** — What keeps contributors coming back? (community channels, office hours, mentorship…)
5. **Recognition** — How are non-code contributions publicly celebrated?
6. **Growth** — What roles and pathways exist beyond "contributor"?

Use the **Journey Builder** panel to write out your project's answers, track completion progress, save your plan, and download a formatted PDF to share with your team.

---

### 3. 🏆 Recognition *(Patterns & Anti-Patterns)*

Six proven recognition frameworks with implementation tips:

- **All-Contributors Specification** — recognize every contributor type in your README
- **Release Shoutouts** — name non-code contributors in every changelog
- **Formal Contributor Roles** — Community Manager, Docs Lead, Accessibility Advocate
- **Platform Access & Voice** — invite contributors to speak, write, and represent
- **Structured Mentorship Pathways** — 30/60/90-day onboarding check-ins
- **Contribution Tracking & Impact Reporting** — make invisible work visible with data

Plus six **anti-patterns** to actively avoid, including code-only changelogs, gatekeeping, and Code of Conduct theater.

---

### 4. 📊 Self-Assessment *(For Contributors & Projects)*

**Toggle between two modes:**

#### For Contributors (10 questions, 50 points)
- **Group A — Skills & Readiness** (20 pts): Can you name your skills? Do you know where to start?
- **Group B — Confidence & Barriers** (15 pts): Do you feel welcome? Can you navigate the tools?
- **Group C — Growth & Belonging** (15 pts): Can you see yourself in open source long-term?

#### For Projects (10 questions, 50 points)
- **Group A — Discoverability** (15 pts): Are you visible where non-coders are?
- **Group B — Onboarding Quality** (15 pts): Can someone contribute meaningfully within one hour?
- **Group C — Recognition & Safety** (20 pts): Are all contributions credited? Is your community safe?

Each question is rated 1–5 stars. Scores are calculated in real-time with personalized written recommendations. Results can be downloaded as a formatted PDF or shared directly.

---

## Who This Is For

| Audience | Use Case |
|---|---|
| **Non-technical contributors** | Discover, name, and map their open source skills |
| **Open source maintainers** | Design and document an inclusive contributor journey |
| **Community managers** | Audit project health and identify retention gaps |
| **DEI advocates** | Use as a workshop tool or onboarding resource |
| **Educators & trainers** | Run structured sessions around contribution and inclusion |
| **Conference speakers** | Present or facilitate with the interactive tool |
| **Developers** | Understand and improve the non-code side of their projects |

---

## Tech Stack

This project is intentionally simple:

- **Pure HTML, CSS, JavaScript** — no frameworks, no build step
- **[jsPDF 2.5.1](https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js)** — loaded from CDN for PDF generation (the only external dependency)
- **[Google Fonts](https://fonts.google.com)** — Syne (headings) + DM Sans (body), loaded from CDN
- **No backend, no database, no authentication** — everything runs in the browser

Everything except the two CDN resources works fully offline if you cache the fonts.

---

## Getting Started Locally

```bash
# Clone the repo
git clone https://github.com/yourusername/nocode-contribution-map.git

# Navigate into it
cd nocode-contribution-map

# Open in your browser (macOS)
open nocode-contribution-map.html

# Open in your browser (Linux)
xdg-open nocode-contribution-map.html

# Open in your browser (Windows)
start nocode-contribution-map.html
```

No `npm install`. No `pip install`. No build process. Just open and use.

---

## File Structure

```
nocode-contribution-map/
│
├── nocode-contribution-map.html   # The entire application (single file)
├── README.md                      # This file
└── LICENSE                        # License
```

The entire tool lives in one self-contained HTML file. If you want to extend it, everything — HTML structure, CSS styles, and JavaScript logic — is organized with clear section comments inside that file.

Key sections inside the HTML:

```
/* ── HERO ── */           → Title, overview, navigation pills
/* ── TABS ── */           → Tab navigation bar
/* PANEL 1 — CONTRIBUTOR MAP */
/* PANEL 2 — ORGANIZATION JOURNEY */
/* PANEL 3 — RECOGNITION */
/* PANEL 4 — SELF ASSESSMENT */
/* ── SHARE MODAL ── */    → Social sharing sheet
/* jsPDF helpers */        → PDF generation functions
/* ── SHARE MODAL JS ── */ → Share logic
```

---

## Contributing

Contributions of all kinds are welcome — and yes, that very much includes non-code contributions.

### Ways to contribute

- 🐛 **Report a bug** — Open an issue describing what happened and what you expected
- 💡 **Suggest a feature** — Open an issue with your idea and the problem it solves
- ✍️ **Improve the docs** — Fix typos, clarify instructions, translate this README
- 🎨 **Design improvements** — Suggest or implement UI/UX improvements
- ♿ **Accessibility** — Audit and improve the tool's accessibility
- 🌍 **Translations** — Help translate the tool's content into other languages
- 📣 **Spread the word** — Share this tool with communities that need it

### How to submit changes

1. Fork the repository
2. Create a new branch: `git checkout -b your-branch-name`
3. Make your changes
4. Commit with a clear message: `git commit -m "Add: brief description of change"`
5. Push to your fork: `git push origin your-branch-name`
6. Open a Pull Request with a description of what you changed and why

### Good first contributions

Look for issues labeled `good first issue` or `help wanted`. Non-code contributions are explicitly labeled too.

---

## Code of Conduct

This project follows the [Contributor Covenant Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/).

By participating, you agree to uphold a welcoming, respectful, and inclusive environment for everyone. To report any concerns, open a private issue or reach out directly.

---

## License

This project is licensed under the **MIT License** — see the [LICENSE](./LICENSE) file for details.

You are free to use, modify, and distribute this tool for personal, educational, or commercial purposes. Attribution is appreciated but not required.

---

## Author

Built with care by **[Your Name]**

- 🌐 Website: [yourwebsite.com](https://yourwebsite.com)
- 🐦 Twitter/X: [@yourhandle](https://twitter.com/yourhandle)
- 💼 LinkedIn: [linkedin.com/in/yourprofile](https://linkedin.com/in/yourprofile)
- 🐙 GitHub: [@yourusername](https://github.com/yourusername)

---

## Acknowledgements

This tool was originally built for the workshop **"Everyone Belongs to Open Source"** — a session designed to reframe diversity and inclusion in open source by demonstrating how non-code contributions are powerful tools for outreach, adoption, and community growth.

Thank you to everyone in the open source community who has ever written a README, organized a meetup, translated a string, answered a question in a forum, or made a newcomer feel welcome. This is for you.

---

> *Open source is for everyone who shows up.*

---

### ⭐ If this tool helped you, consider starring the repo — it helps others find it.

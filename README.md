<div align="center">

# ✦ Yasmeen Azmat Ali
### AI/ML Engineering Portfolio

**Applied AI · Machine Learning · Agentic Systems · Full-Stack Development**

[![Portfolio](https://img.shields.io/badge/🌐_Live_Portfolio-yasmeenazmat.com-EF83C4?style=for-the-badge)](https://yasmeenazmat.com)
[![FlyRank](https://img.shields.io/badge/FlyRank-General_AI_Fluency-102D34?style=for-the-badge)](https://aifluency.flyrank.ai/)
[![Capstone](https://img.shields.io/badge/Impact_Project-Approved-218A70?style=for-the-badge)](https://yasmeenazmat.com)
[![Docs](https://img.shields.io/badge/Repository-Documentation_Only-63738A?style=for-the-badge)](#privacy-and-reproducibility)

**One destination for the projects, decisions, and evidence behind my AI engineering work.**

[**Explore Portfolio ↗**](https://yasmeenazmat.com) · [**Browse Projects ↗**](https://yasmeenazmat.com/#projects) · [**Contact ↗**](https://yasmeenazmat.com/#contact)

<sub>FlyRank General AI Fluency · Impact Project approved October 5, 2026 · Public documentation / private implementation</sub>

</div>

---

## ✨ At a glance

| | |
|:--|:--|
| **What it is** | A public, evidence-led portfolio of AI/ML engineering work, technical skills, experience, and certifications |
| **Who it's for** | Recruiters, technical reviewers, potential collaborators, and internship or employment teams |
| **Primary goal** | Help a visitor understand what I build, why it matters, and where to inspect the work |
| **Live site** | **[yasmeenazmat.com](https://yasmeenazmat.com)** |
| **Deployment** | Netlify, accessed through a custom domain |
| **Source visibility** | Private; this repository contains **documentation only** |

### Contents

[Overview](#-overview) · [Portfolio experience](#-portfolio-experience) · [Architecture](#-architecture) · [How to use](#-how-to-use) · [Setup](#-setup-and-reproducibility) · [Evaluation](#-v2-evaluation-and-quality-checks) · [Decisions](#-design-decisions) · [Limitations](#-known-limitations) · [AI transparency](#-ai-assistance-and-verification) · [Demo](#-live-demo) · [Roadmap](#-roadmap)

---

## 🎯 Overview

This portfolio brings my **machine learning, agentic AI, research, and software engineering** work into one navigable experience. Rather than asking visitors to rely on a list of technologies, it points them toward project descriptions, implementation context, and supporting GitHub repositories or demonstrations when available.

The FlyRank capstone uses a repeatable case-study pattern:

> **Problem → What I Did → What Came of It**

That structure is intended to make technical decisions, my contribution, and the outcome easier to assess.

## 🧭 Portfolio experience

| Section | What visitors find |
|:--|:--|
| 🏠 **Home / About** | Engineering focus, background, and introduction |
| 🧠 **Projects** | Applied AI/ML and software projects, with available evidence links |
| 🛠️ **Skills** | Technical capabilities and tools |
| 💼 **Experience** | Professional and internship experience |
| 🎓 **Certifications** | Credentials and available verification links |
| ✍️ **Blog / Building in Public** | Space for technical notes, retrospectives, and capstone updates |
| ✉️ **Contact** | Contact interface and ways to connect |
| 📄 **Download CV** | Access to the published CV |

### Selected project areas

- **Multi-agent research and RAG:** research assistance, retrieval, orchestration, and verification workflows.
- **InvoiceGuard:** explainable invoice-risk review with human approval in the loop.
- **CivicRelay and Clerkly:** agent-oriented applications with workflow safeguards.
- **Real-time sentiment analysis:** data streaming and applied machine-learning research.
- **AI career guidance:** skills and career-path exploration.

> These are examples of work represented in the portfolio, **not a claim that every project has a publicly accessible live deployment**. Check each project card for its available links.

---

## 🏗️ Architecture

```mermaid
flowchart TD
    A[Visitor's browser] --> B[Custom domain: yasmeenazmat.com]
    B --> C[Netlify-hosted portfolio]
    C --> D[About / Experience / Skills]
    C --> E[Project cards and case studies]
    C --> F[Certifications / CV]
    C --> G[Contact / Building in Public]
    E --> H[External GitHub or demo links, where available]
```

**Implementation overview**

| Layer | Current understanding |
|:--|:--|
| Frontend | HTML, CSS, and JavaScript, based on the previously described project setup; confirm against private source |
| Hosting | Netlify |
| Domain | [yasmeenazmat.com](https://yasmeenazmat.com) |
| Project evidence | Links to external project repositories and demos where provided |
| Documentation | This public repository; implementation files remain private |

*The diagram describes the visitor-facing system. It is not a verified internal component map; contact processing and build configuration require checking against the private deployment.*

---

## 🚀 How to use

**No installation or account is required to view the live portfolio.**

1. Visit **[yasmeenazmat.com](https://yasmeenazmat.com)**.
2. Navigate from **Home** to **Projects** to review work and evidence links.
3. Try the project filters, where present, and inspect a project card.
4. Review **Skills**, **Experience**, and **Certifications**.
5. Try **Download CV** and inspect the **Contact** options.
6. Open **Building in Public** to see the current content and planned updates.

### Example reviewer journey

```text
Open yasmeenazmat.com
  → Read the introduction
  → Navigate to Projects
  → Filter or select a project
  → Open its GitHub/demo evidence, if available
  → Review experience and certifications
  → Check CV download and contact options
```

## 💻 Setup and reproducibility

### Public experience — reproducible now

Open the live URL in a modern desktop or mobile browser. No local environment is necessary to evaluate the **deployed experience**.

### Local development — private-source access required

This is **not** a public source-code repository. An authorized collaborator with the original source folder can:

1. Obtain the private project files through an approved channel.
2. Inspect the entry point and build configuration.
3. If the project is plain HTML/CSS/JavaScript without a build step, start a local server from the project root:

   ```bash
   python3 -m http.server 8000
   ```

4. Open `http://localhost:8000` and verify navigation, images, project links, CV download, and contact behavior.
5. If the source instead includes a package/build configuration, follow **its actual scripts** rather than assuming the static-server command is sufficient.

> **Reproducibility disclosure:** A stranger cannot recreate the complete source-based build from this public README alone because the implementation is private. FlyRank reviewers may request an approved private review method to assess this criterion.

---

## 🧪 V2 evaluation and quality checks

The portfolio's **functional quality checks** are listed below. The screenshots and information currently available do **not** establish numerical v2 scores or completed test results. The status must be updated **only after each check is performed and documented**.

| Test area | Pass condition | Current evidence |
|:--|:--|:--|
| Desktop navigation | Each menu item reaches its intended section | Not yet recorded |
| Mobile responsiveness | Layout works without clipped content or horizontal overflow | Not yet recorded |
| Project filters | Selected category displays the appropriate project cards | Not yet recorded |
| Project evidence links | Repository and demo links reach the intended destinations | Not yet recorded |
| CV download | Correct document opens or downloads | Not yet recorded |
| Contact interface | Form or contact action behaves as described | Not yet recorded |
| Accessibility | Keyboard navigation and focus indicators are usable | Not yet recorded |
| Performance | Page is usable on a mobile connection | Not yet recorded |

**Evaluation method:** Manually test the live deployment on desktop and mobile; record the date, browser/device, observed result, and screenshot or video evidence for each check. Avoid publishing an invented pass rate or performance score.

**Evaluation summary (pending):** `Completed: — / 8` · `Failures: —` · `Test date: —`

---

## 🧩 Design decisions

**One portfolio instead of scattered project links.** The portfolio brings project evidence, background, skills, and contact information together so reviewers can form a coherent picture without searching multiple platforms.

**Consistent case-study storytelling.** The **Problem → What I Did → What Came of It** format emphasizes contribution and evidence rather than broad technical claims.

**Documentation separated from source.** Public documentation makes the project easier to review while keeping the implementation private. The trade-off is reduced independent reproducibility.

## ⚠️ Known limitations

- **Private source:** Public documentation alone does not allow a stranger to rebuild the site from scratch.
- **Evaluation pending:** Cross-device, accessibility, and functional checks still need dated evidence.
- **Building in Public:** The section currently describes planned notes and updates rather than a complete technical blog.
- **NEXA:** Identified as a future case study; it should not be described as completed until tested and ready.
- **Graduate badge:** An official FlyRank badge should only be displayed once issued, with its verification link.

## 🤝 AI assistance and verification

AI-assisted tools supported portfolio planning, content refinement, and implementation ideas. **The project owner selected the structure, reviewed the outputs, and is responsible for validating the deployed experience and the accuracy of project claims.**

**Before FL-09 submission:** Replace this note with the **specific AI tools actually used**, the tasks they assisted with, and the checks personally performed. Do not claim a test was completed without evidence.

---

## 🎬 Live demo

**Planned length:** 3–5 minutes · **Format:** live screen recording with narration · **Slides:** none

| Time | Show on screen | Explain |
|:--|:--|:--|
| 0:00–0:35 | Live home page | Purpose and intended audience |
| 0:35–1:40 | Projects and a working filter | One real interaction and the project evidence |
| 1:40–2:30 | Project details and external links | Why evidence-led case studies were chosen |
| 2:30–3:15 | Skills, certifications, CV or contact | Practical visitor journey |
| 3:15–4:10 | Building in Public | Honest limitation and next improvement |
| 4:10–4:40 | Return to home page | AI assistance, human verification, and wrap-up |

**Demo video URL:** *Add the actual public or unlisted video link after recording.*

---

## 🗺️ Roadmap

- [ ] Finish and validate **NEXA** before publishing it as a portfolio case study.
- [ ] Publish technical notes and project retrospectives.
- [ ] Record and link dated functional, accessibility, and mobile test evidence.
- [ ] Add the official FlyRank graduate badge and verification link when issued.
- [ ] Attach the 3–5 minute live demo to this README and the FlyRank showcase submission.

---

<div align="center">

### Built to show the work, not just describe it.

**[Visit yasmeenazmat.com ↗](https://yasmeenazmat.com)**

<sub>FlyRank General AI Fluency capstone documentation · © 2026 Yasmeen Azmat Ali · Source code remains private</sub>

</div>

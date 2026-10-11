# flyrank-ai-fluency-portfolio-docs
Public documentation for my AI/ML engineering portfolio (yasmeenazmat.com), developed as part of the FlyRank General AI Fluency capstone. Includes project overview, architecture, testing, limitations, AI-assisted development transparency, and demo resources. Portfolio source code remains private.



# AI/ML Engineering Portfolio — FlyRank General AI Fluency

**Creator:** Yasmeen Azmat Ali  
**Live portfolio:** https://yasmeen-portfolio-1.netlify.app/  
**Project:** General AI Fluency Impact Project (FlyRank; approved October 5, 2026)

## Purpose and audience

This portfolio presents AI/ML engineering projects, skills, experience, certifications, and ways to get in touch. It is intended for recruiters, collaborators, reviewers, and others evaluating applied AI and software-engineering work. Rather than relying on claims alone, it links visitors to project evidence and demonstrations where available.

## What visitors can do

1. Open the [live portfolio](https://yasmeen-portfolio-1.netlify.app/).
2. Use the navigation to explore About, Projects, Skills, Experience, Certifications, Blog, and Contact.
3. Open project links and supporting evidence where provided.
4. Try project filtering and navigation, if available in the current deployment.
5. Use the Download CV action or the contact options.
6. Review the Building in Public section for planned technical notes and future capstone updates.

## Technology and deployment

- Front end: HTML, CSS, and JavaScript (based on the project's reported development setup; verify against current private source before final submission).
- Hosting: Netlify.
- Public deployment: https://yasmeen-portfolio-1.netlify.app/
- Portfolio source code: kept private; **not included in this documentation repository**.

### High-level architecture

```text
Visitor's browser
      |
      v
Netlify-hosted portfolio
      |
      +--> Page sections (About / Projects / Skills / Experience)
      +--> Project cards and external GitHub/demo links
      +--> Certifications and CV links
      +--> Contact interface / external contact destination
      +--> Building-in-public updates
```

This is a conceptual diagram of the public-facing experience, not a verified internal component diagram. Third-party contact handling and build/deploy details should be confirmed from the private project configuration.

## Reproduction and setup

**Public use (reproducible):** Open the live URL in a modern browser. No account or installation is needed to browse the portfolio.

**Local development (source access required):** The source files are private, so an unrelated reader cannot reproduce the full local build from this public documentation alone. For an authorized collaborator who has received the private source:

1. Obtain the approved source folder securely.
2. Confirm the presence of the entry-point HTML file and its referenced CSS, JavaScript, and assets.
3. If the project is static HTML/CSS/JS without a build system, open the entry point using a local development server (for example, `python3 -m http.server 8000` from the project directory), then visit `http://localhost:8000`.
4. If the source contains a build configuration such as `package.json`, follow that project's scripts instead; do not assume the static-server method is sufficient.
5. Verify all relative asset paths, project links, CV download, and contact integration.

**Disclosure:** This documentation-only repository cannot meet a strict source-independent reproduction requirement while the source remains private. An assessor may request a private review or a source-release alternative.

## Usage example: reviewer walkthrough

- Start on the home page and identify the portfolio's main AI/ML focus.
- Navigate to Projects and inspect a case study and its evidence link.
- Test project navigation/filtering on desktop and mobile.
- Open a certification link and check its destination.
- Try the CV download and contact path without submitting personal information during a demo.
- Read the Building in Public section and note the plan to add NEXA as a future case study after it is ready.

## V2 evaluation and quality checks

**No numerical v2 evaluation results have been provided or independently verified for this portfolio.** Do not interpret the checklist below as completed tests until each has been run and recorded.

| Check | Acceptance condition | Result |
| --- | --- | --- |
| Desktop navigation | Every navigation item opens the intended section | Not yet recorded |
| Mobile layout | No clipped text or horizontal overflow | Not yet recorded |
| Project links | GitHub and demo links open correctly | Not yet recorded |
| Project filtering | Filtered cards match the chosen category | Not yet recorded |
| CV download | Downloads the intended document | Not yet recorded |
| Contact flow | Form or contact action behaves as described | Not yet recorded |
| Accessibility | Keyboard navigation and visible focus are usable | Not yet recorded |
| Performance | Page loads acceptably on a mobile connection | Not yet recorded |

After testing, replace these placeholders with dated results, devices/browsers, and evidence. Do not invent a pass rate or performance score.

## Design decision

The portfolio uses a single public destination to organize projects and evidence rather than requiring reviewers to find work across separate platforms. Case studies follow a consistent narrative: **Problem → What I Did → What Came of It**. This makes each project easier to assess quickly.

## Known limitations

- The source code is private, so the full application cannot be reproduced from this public documentation alone.
- The Building in Public section currently describes future notes and capstone updates; it is not yet a populated technical blog.
- The official FlyRank graduate badge is pending issuance and should not be represented as earned until provided.
- NEXA is planned as a future portfolio case study; it should not be presented as a completed, demonstrated feature before it is tested and ready.
- Functional and cross-device test results still need to be recorded and linked.

## AI assistance and human verification

AI-assisted tools were used during portfolio planning and development, including drafting or refining content and implementation ideas. The project owner selected the portfolio structure, reviewed the resulting work, and is responsible for verifying links, interactions, deployment, and the accuracy of project claims. **Before final submission, specify the actual AI tools used and exactly which changes were independently tested.**

## Demo video

**3–5 minute live demo:** _Add the video URL after recording and uploading it._

The demo should show the live site, navigate through projects, demonstrate at least one working interaction, explain the case-study organization decision, and honestly discuss a limitation (for example, the not-yet-populated Building in Public section). No slides.

## Roadmap

- Finish and test NEXA before publishing it as a portfolio case study.
- Publish technical write-ups and project retrospectives.
- Record accessibility, mobile, link, and contact-flow test evidence.
- Add the official FlyRank badge when issued, linking to the verification page.

## Attribution

Prepared as documentation for the FlyRank General AI Fluency track. This public repository contains documentation only, not the private portfolio source code.

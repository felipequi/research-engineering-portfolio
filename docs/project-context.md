# Research & Engineering Portfolio — Project Context

**Author:** Juan Felipe Quintero  
**Last updated:** 2026-11-14  
**Project status:** Active development — website deployed and first R&D case study published  
**GitHub account:** `felipequi`  
**Repository:** https://github.com/felipequi/research-engineering-portfolio  
**Published website:** https://felipequi.github.io/research-engineering-portfolio/

---

## 1. Project Objective

Build and maintain a professional research and engineering portfolio showcasing experimental R&D experience in:

- Scientific instrumentation and optical metrology.
- Applied photonics, spectroscopy and optical systems.
- Sensors, photodetectors and scientific imaging.
- Experimental characterization and measurement systems.
- Scientific data analysis and Python-based image processing.

The portfolio is intended for R&D recruiters, engineering teams, research laboratories and potential PhD supervisors.

The primary goal is to demonstrate engineering capabilities through documented experimental projects, with emphasis on technical contributions, methodology and evidence-based results.

## 2. Professional Positioning

**Target profile:** R&D Engineer in Advanced Instrumentation, Sensor Technologies & Applied Photonics for High-Tech Systems.

Priority technical domains:

1. Optical instrumentation, metrology and experimental test benches.
2. Photonics, optics and spectroscopy.
3. Sensors, detectors and scientific imaging.
4. Scientific instrumentation and advanced characterization.

The portfolio should communicate both scientific understanding and practical engineering capabilities.

## 3. Technical Environment

| Component | Technology |
|---|---|
| Operating system | Windows |
| Editor | Visual Studio Code |
| Terminal | PowerShell |
| Version control | Git |
| Source hosting | GitHub |
| Website hosting | GitHub Pages |
| Local preview | Live Server |
| Frontend | HTML and CSS |
| Documentation | Markdown |
| Production branch | `main` |

The website is a static project without a required backend or JavaScript framework.

## 4. Repository Structure

```text
research-engineering-portfolio/
├── index.html
├── README.md
├── assets/
│   ├── css/
│   │   ├── style.css
│   │   └── cea-liten.css
│   └── images/
│       └── cea-liten/
├── docs/
│   ├── ai-instructions.md
│   ├── development-log.md
│   └── project-context.md
└── projects/
    └── cea-liten.html
```

### File responsibilities

**`index.html`**
- Main portfolio page.
- Professional introduction and overview of research experience.
- Project cards and navigation.
- Entry point to individual project case studies.

**`assets/css/style.css`**
- Global design system.
- Shared typography, colors, layout and responsive styles.

**`assets/css/cea-liten.css`**
- Styles specific to the CEA-Liten case study.

**`assets/images/cea-liten/`**
- Scientific figures, schematics and visual assets for the CEA-Liten project.

**`projects/cea-liten.html`**
- Dedicated technical case study presenting the CEA-Liten research experience.

**`docs/`**
- Current project context.
- Chronological engineering development log.
- AI-assisted development instructions.

## 5. Git and Deployment Status

**Repository:** `felipequi/research-engineering-portfolio`  
**Visibility:** Public  
**Default branch:** `main`  
**Remote:** `origin`  
**Deployment:** GitHub Pages from `main` and `/(root)`

### Confirmed milestones

- Local Git repository initialized on 2026-11-11.
- Initial commit created: `a5a98c7`.
- GitHub repository created and connected.
- Initial push to GitHub completed.
- GitHub Pages configured and website deployed.
- CEA-Liten case study published.
- Homepage updated with a direct case-study link.
- Remote homepage change synchronized locally using `git pull origin main`.

### Relevant commits

- `c55fd7b` — Add CEA-Liten research case study.
- `3329001` — Update homepage navigation to the case study.

**Important:** The local repository status must be checked using `git status` before making changes. Documentation edits may not yet have been committed.

## 6. Website Structure

The main portfolio includes the following sections:

- About
- Projects
- Expertise
- Research
- Contact

The website uses a navy/teal visual identity.

### Published pages

**Homepage:**  
https://felipequi.github.io/research-engineering-portfolio/

**CEA-Liten case study:**  
https://felipequi.github.io/research-engineering-portfolio/projects/cea-liten.html

The homepage provides a direct link to the detailed CEA-Liten case study.

## 7. Scientific Content

### 7.1 CEA-Liten — Optical Fluorescence Imaging

**Status:** Published case study  
**Research period:** February–August 2026

Research internship investigating fluorescence-based detection of lithium plating on graphite battery anodes.

Key technical elements:

- Fluorescence spectroscopy and optical imaging.
- Fluorescent marker 4-HC.
- UV excitation at approximately 365 nm.
- sCMOS camera-based imaging.
- Optical experimental setup and associated instrumentation.
- Scientific image processing and exploratory intensity analysis using Python.
- Complementary spectroscopic investigations.

The case study should emphasize experimental engineering work, measurement methodology and appropriately qualified results.

**Scientific limitation:** Exploratory fluorescence observations must not be presented as a validated quantitative measurement of deposited lithium mass without supporting calibration and validation.

### 7.2 Photoluminescence Thermometry

Relevant experience includes:

- UV LED excitation.
- Photomultiplier-based detection.
- Luminescence lifetime measurements.
- Temperature calibration.
- Signal acquisition and analysis.

**Portfolio status:** Relevant experience identified; no separate published case-study page confirmed.

### 7.3 Materials Characterization

Relevant experience includes microscopy, materials characterization, experimental measurements and scientific data analysis.

**Portfolio status:** Relevant background; no separate published case-study page confirmed.

## 8. Scientific and Publication Constraints

- Publish only public or explicitly authorized research material.
- Avoid disclosing confidential industrial data or proprietary methods.
- Do not invent measurements, results, performance metrics or calibration data.
- Clearly distinguish observations, interpretations and validated conclusions.
- Preserve the original scientific meaning of figures and experimental results.
- Attribute external scientific figures and references appropriately.
- Obtain necessary publication permissions for materials originating from research institutions.
- Prioritize scientific accuracy over visual presentation or marketing language.

## 9. Engineering and Design Principles

- Maintain a clean, professional, research-oriented design.
- Prioritize readable content and scientific figures.
- Keep navigation simple and intuitive.
- Use semantic HTML and accessible markup.
- Maintain responsive layouts for desktop and mobile.
- Avoid unnecessary frameworks and dependencies.
- Reuse global CSS for shared components.
- Keep project-specific styles in dedicated files.
- Ensure that relative links work under the GitHub Pages repository path.

## 10. Development Workflow

Standard local workflow:

1. Open the repository in Visual Studio Code.
2. Check the working directory using `git status`.
3. Confirm the latest remote changes are available before editing.
4. Make focused changes to the appropriate files.
5. Preview the website locally using Live Server.
6. Verify affected content, links and layout.
7. Review changes using `git diff` and `git status`.
8. Stage intended files with `git add`.
9. Create a descriptive English commit.
10. Push commits using `git push origin main`.
11. Verify the public deployment.

When the remote repository has been modified directly through GitHub, synchronize the local branch before continuing.

Avoid destructive commands unless their consequences have been clearly explained.

## 11. Working Preferences

- Explain technical concepts in Spanish.
- Keep portfolio website content and technical documentation in English.
- Give precise, actionable instructions.
- Work one step at a time.
- Wait for `L`, `Listo` or `Continuar` before advancing.
- Clearly distinguish VS Code file edits from PowerShell terminal commands.
- Identify the exact file and location to modify.
- Explain what each Git command does.
- Do not assume commands succeeded without confirmation.
- Prefer simple, maintainable solutions over unnecessary complexity.
- Preserve existing content and functionality unless a change is explicitly requested.

## 12. Current Workflow State

**Last completed development milestone:** Publication and integration of the CEA-Liten case study.

**Current task:** Updating project documentation to reflect the deployed website and current repository structure.

### Documentation progress

- `development-log.md` — Updated locally; commit pending.
- `project-context.md` — Update prepared; local save pending.
- `ai-instructions.md` — Review and update pending.

### Next operational step

Finish reviewing and updating the three documentation files, then create a single documentation commit and push it to GitHub.

## 13. Future Priorities

### Short term

- Review website content from an R&D recruiter's perspective.
- Check desktop and mobile responsiveness.
- Verify all project images, captions and links.
- Improve scientific figure readability.
- Refine the presentation of personal engineering contributions.

### Medium term

- Develop additional technical case studies where appropriate.
- Improve project discoverability and metadata.
- Integrate relevant GitHub code repositories when suitable for public release.
- Maintain a consistent technical visual identity.
- Prepare the portfolio for professional applications and research opportunities.

## 14. Documentation Maintenance

This document describes the current state of the project.

Update it after significant architectural, technical or workflow changes.

Do not use it as a detailed chronological record; that responsibility belongs to `development-log.md`.

The three documentation files are maintained manually and do not update automatically when website source files change.

---

## Handoff Instructions

Before continuing development:

1. Read `README.md`.
2. Read `docs/project-context.md`.
3. Review the latest entries in `docs/development-log.md`.
4. Follow `docs/ai-instructions.md`.
5. Inspect the actual repository and Git status.
6. Confirm whether local and remote versions are synchronized.
7. Continue from the latest verified development state.

**Priority:** Scientific accuracy, professional presentation, maintainable code and reproducible development.
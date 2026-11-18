# Research & Engineering Portfolio — Project Context

**Author:** Juan Felipe Quintero  
**Last updated:** 2026-11-18  
**Project status:** Active development — portfolio deployed, academic background pages integrated and first R&D case study published  
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

The primary goal is to demonstrate engineering capabilities through documented experimental projects, emphasizing personal technical contributions, experimental methodology and evidence-based results.

## 2. Professional Positioning

**Target profile:** R&D Engineer specialized in Advanced Instrumentation, Sensor Technologies & Applied Photonics for High-Tech Systems.

Priority technical domains:

1. Optical instrumentation, metrology and experimental test benches.
2. Photonics, optics and spectroscopy.
3. Sensors, detectors and scientific imaging.
4. Materials and device characterization.
5. Computational imaging and intelligent sensing, when directly connected to physical measurement systems.

The portfolio should communicate scientific understanding, experimental problem-solving and practical engineering capabilities.

**Positioning principle:** Demonstrate what was designed, measured, characterized, analyzed or improved, rather than presenting only academic credentials or general technical interests.

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

Avoid introducing unnecessary dependencies or build tools.

## 4. Repository Structure

The working architecture includes:

```text
research-engineering-portfolio/
├── index.html
├── README.md
├── assets/
│   ├── css/
│   │   ├── style.css
│   │   ├── cea-liten.css
│   │   ├── imt-mines-albi.css
│   │   └── utp.css
│   └── images/
│       ├── home/
│       ├── education/
│       └── cea-liten/
├── education/
│   ├── imt-mines-albi.html
│   └── utp.html
├── projects/
│   ├── cea-liten.html
│   ├── ica-thermometry.html
│   └── institut-corrosion.html
└── docs/
    ├── academic/
    ├── ai-instructions.md
    ├── development-log.md
    └── project-context.md
```

The structure reflects the files and directories discussed during development. The actual repository tree remains the authoritative reference.

### File responsibilities

**`index.html`**

- Main portfolio homepage.
- Professional introduction and technical positioning.
- Research project overview and navigation.
- Academic Background section with dedicated institutional links.
- Entry point to individual project case studies.

**`assets/css/style.css`**

- Global visual design system.
- Typography, colors, navigation and shared components.
- Homepage layout, academic cards and responsive behavior.

**`assets/css/cea-liten.css`**

- Styles specific to the CEA-Liten case study.

**`assets/css/imt-mines-albi.css`**

- Styles specific to the IMT Mines Albi academic page.
- Academic sections, figures, institutional branding and spacing.

**`assets/css/utp.css`**

- Styles specific to the Universidad Tecnológica de Pereira academic page.

**`assets/images/home/`**

- Homepage photographs and institutional images.

**`assets/images/education/`**

- Academic figures and institutional visual resources.

**`assets/images/cea-liten/`**

- Scientific figures, experimental illustrations and case-study assets.

**`education/`**

- Dedicated institutional academic background pages.

**`projects/`**

- Individual research and engineering case studies.
- The existence of a local HTML page does not by itself establish publication or content-completion status.

**`docs/academic/`**

- Supporting academic documents and references.

**`docs/`**

- Current project context.
- Chronological engineering development log.
- AI-assisted development instructions.

## 5. Git and Deployment Status

**Repository:** `felipequi/research-engineering-portfolio`  
**Visibility:** Public  
**Production branch:** `main`  
**Remote:** `origin`  
**Hosting:** GitHub Pages  
**Deployment configuration:** `main` branch, `/(root)` folder, as previously configured.

### Confirmed development milestones

- Local Git repository initialized on 2026-11-11.
- Initial commit created: `a5a98c7`.
- GitHub repository connected and first website deployed.
- CEA-Liten research case study published.
- Homepage connected to the CEA-Liten case study.
- Dedicated academic pages developed for UTP and IMT Mines Albi.
- Homepage Academic Background navigation expanded.
- Homepage and academic page spacing refined.
- Academic image presentation improved.
- A GitHub Pages stylesheet caching discrepancy was resolved.

### Relevant commits

- `c55fd7b` — Add CEA-Liten research case study.
- `3329001` — Update homepage navigation to the case study.
- `3a1666f` — Refine academic pages and improve portfolio layout.

These commits are recorded from the development history. The latest remote commit and working-tree status should be checked directly before new operations.

### Deployment considerations

A successful local commit does not imply that changes have been uploaded.

A successful `git push` does not independently guarantee that GitHub Pages has completed deployment.

Verify synchronization and deployment separately.

The homepage stylesheet uses a version parameter to help prevent stale browser caching:

```html
<link rel="stylesheet" href="assets/css/style.css?v=3">
```

Increment the version parameter when necessary after significant stylesheet changes.

## 6. Website Structure and Visual Identity

The main portfolio includes:

- About.
- Academic Background.
- Projects.
- Expertise.
- Research.
- Contact.

### Design identity

The portfolio follows a minimal scientific and editorial visual direction.

Principal characteristics:

- Navy text and teal accents.
- White backgrounds and restrained borders.
- DM Sans and Manrope typography.
- Clear technical hierarchy.
- Compact but readable section spacing.
- Consistent scientific figures and image proportions.
- Responsive desktop and mobile layouts.

### Academic Background

The homepage contains two institutional cards:

**Universidad Tecnológica de Pereira**

- Engineering Physics education.
- Dedicated page: `education/utp.html`.

**IMT Mines Albi**

- French engineering double-degree program.
- Advanced Materials and Processes option.
- Instrumentation and Advanced Data Analysis pathway.
- Dedicated page: `education/imt-mines-albi.html`.

Each academic card provides internal navigation through its image, institutional title and dedicated detail link.

External links to official institutional resources are preserved separately.

### Academic page design

Academic pages use the shared global design system with independent stylesheets.

Design decisions include:

- Compact section spacing.
- Consistent heading hierarchy.
- Readable academic descriptions.
- Controlled figure dimensions.
- Responsive layouts.
- Institutional imagery and academic resources where appropriate.

Avoid duplicating academic content already clearly represented by a figure.

## 7. Research and Engineering Content

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
- Python-based image processing and exploratory intensity analysis.
- Complementary spectroscopic investigations.

The case study should emphasize experimental engineering, measurement methodology, technical contributions and appropriately qualified findings.

**Scientific limitation:** Exploratory fluorescence observations must not be presented as validated quantitative measurements of deposited lithium mass without supporting calibration and validation.

### 7.2 Photoluminescence Thermometry

Relevant experience includes:

- UV LED excitation.
- Photomultiplier-based detection.
- Luminescence lifetime measurements.
- Temperature calibration.
- Signal acquisition and analysis.

**Portfolio status:** A corresponding HTML page has been identified in the working architecture; its publication and completion status require verification.

### 7.3 Materials Characterization

Relevant experience includes:

- Materials characterization.
- Microscopy and experimental measurements.
- Scientific data analysis.
- Thin-film materials and related experimental techniques.

**Portfolio status:** Additional project pages have been identified in the working architecture; their publication and completion status require verification.

## 8. Academic Background

### Universidad Tecnológica de Pereira

**Program:** Ingeniería Física  
**Country:** Colombia

Relevant academic foundations:

- Solid-state physics.
- Electromagnetism.
- Optics.
- Experimental methods.
- Scientific computing.
- Materials characterization.

The academic page should distinguish coursework, research participation and completed academic qualifications.

### IMT Mines Albi

**Program:** Diplôme d’Ingénieur Généraliste — Grade de Master  
**Country:** France  
**Academic period:** 2024–2026

Academic focus:

- Advanced Materials and Processes for Future Transport.
- Instrumentation and Advanced Data Analysis.
- Experimental measurement methods.
- Imaging and characterization.
- Advanced scientific data analysis.

The dedicated page includes the engineering pathway, selected coursework, specialization information, academic mentorship and supporting resources.

Institutional academic figures and documents must be accurately attributed and used with appropriate permissions.

## 9. Scientific and Publication Constraints

- Publish only public or explicitly authorized research material.
- Avoid disclosing confidential industrial data or proprietary methods.
- Do not invent measurements, results, performance metrics or calibration data.
- Distinguish observations, interpretations and validated conclusions.
- Preserve the original scientific meaning of figures and experimental results.
- Attribute external scientific figures and references appropriately.
- Obtain necessary publication permissions for materials originating from research institutions.
- Prioritize scientific accuracy over visual presentation or promotional language.

## 10. Engineering and Design Principles

- Maintain a clean, professional, research-oriented design.
- Prioritize readable content and scientific figures.
- Keep navigation simple and intuitive.
- Use semantic HTML and accessible markup.
- Maintain responsive layouts for desktop and mobile.
- Avoid unnecessary frameworks and dependencies.
- Reuse global CSS for shared components.
- Keep page-specific styles in dedicated files.
- Verify relative links under the GitHub Pages repository path.
- Prefer targeted CSS corrections over accumulating conflicting overrides.
- Verify production appearance after deployment.

## 11. Development Workflow

Standard local workflow:

1. Open the repository in Visual Studio Code.
2. Check the working directory using `git status`.
3. Review remote synchronization when necessary.
4. Make focused changes to the appropriate files.
5. Preview the website locally using Live Server.
6. Verify affected content, links and layout.
7. Review changes using `git diff` and `git status`.
8. Stage only intended files.
9. Create a descriptive English commit.
10. Push commits using `git push origin main`.
11. Verify GitHub Pages deployment and browser rendering.

If remote changes were made directly through GitHub, inspect the local working tree before pulling.

Avoid destructive commands unless their consequences have been clearly explained and approved.

## 12. Working Preferences

- Explain technical concepts in Spanish.
- Keep website content and technical documentation in English.
- Give precise, actionable instructions.
- Work one step at a time.
- Wait for `L`, `Listo` or `Continuar` before advancing.
- Distinguish VS Code file edits from PowerShell terminal commands.
- Identify the exact file and location to modify.
- Explain the purpose of Git commands.
- Do not assume commands succeeded without confirmation.
- Prefer simple, maintainable solutions over unnecessary complexity.
- Preserve existing content and functionality unless a change is explicitly requested.

## 13. Current Workflow State

**Last development milestone discussed:** Academic Background integration and homepage visual refinement.

**Current task:** Update project documentation to reflect the expanded portfolio architecture and recent development decisions.

### Documentation status

- `development-log.md` — Updated content prepared; repository save and commit status not verified.
- `project-context.md` — Updated content prepared in this revision.
- `ai-instructions.md` — Revision required to reflect the expanded architecture.
- `README.md` — Review required for consistency with the current website.

### Next operational step

Save and review the updated documentation, confirm the repository's actual state and create a documentation commit when approved.

## 14. Future Priorities

### Short term

- Verify all academic pages and internal navigation on GitHub Pages.
- Check desktop and mobile responsiveness.
- Verify images, captions and academic resource links.
- Review the website from an R&D recruiter's perspective.
- Improve scientific figure readability.
- Refine the presentation of personal engineering contributions.

### Medium term

- Develop and refine additional technical case studies.
- Improve accessibility, metadata and discoverability.
- Integrate relevant GitHub code repositories when suitable for public release.
- Maintain a consistent technical visual identity.
- Prepare the portfolio for professional applications and research opportunities.

## 15. Documentation Maintenance

This document describes the current state of the project.

Update it after significant architectural, technical or workflow changes.

Do not use it as a detailed chronological record; that responsibility belongs to `development-log.md`.

The documentation files are maintained manually and do not update automatically when website source files change.

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
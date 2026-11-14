# Engineering Development Log

**Project:** Research & Engineering Portfolio  
**Author:** Juan Felipe Quintero  
**Development environment:** Windows · Visual Studio Code · Git · Live Server  
**Repository:** `felipequi/research-engineering-portfolio`  
**Website:** https://felipequi.github.io/research-engineering-portfolio/

---

## 2026-11-11 — Session 01: Initial Setup & Version Control

### Objective

Establish a structured local development environment, initialize version control and create the first reproducible checkpoint of the portfolio website.

### Activities completed

- Organized the project under `LIFE/06_PROFESIONAL/Portafolio/research-engineering-portfolio`.
- Opened the project in Visual Studio Code.
- Verified the HTML/CSS website using Live Server.
- Verified Git installation: `2.53.0.windows.1`.
- Selected GitHub account: `felipequi`.
- Configured the Git author identity using a GitHub `noreply` address.
- Initialized the local Git repository.
- Staged the initial website files.
- Created and verified the first commit.

### Commands and explanations

| Command | Purpose |
|---|---|
| `git --version` | Check the installed Git version |
| `git config --global user.name "Juan Felipe Quintero"` | Set the default commit author name |
| `git config --global user.email "134302004+felipequi@users.noreply.github.com"` | Set the default commit author email |
| `git init` | Initialize a local Git repository |
| `git status` | Inspect tracked, untracked and staged changes |
| `git add README.md index.html assets/` | Stage selected files |
| `git commit -m "Initial portfolio structure"` | Record the first project version |
| `git log --oneline` | View the condensed commit history |

### Results

**First commit:** `a5a98c7`  
**Initial branch:** `master`  
**Initial files:** `README.md`, `index.html`, `assets/style.css`  
**Changes:** 271 inserted lines across three files.

The repository was initialized locally before its first GitHub deployment.

### Technical concepts learned

- **Working directory:** Files currently being edited.
- **Staging area:** Changes selected for the next commit.
- **Commit:** A recorded snapshot of the project.
- **Branch:** An independent line of development.
- **Repository:** A version-controlled project and its history.

---

## 2026-11-11 — Session 02: First GitHub Deployment

### Objective

Publish the Research & Engineering Portfolio and verify its initial deployment.

### Activities completed

- Created the public GitHub repository `felipequi/research-engineering-portfolio`.
- Configured the remote repository as `origin`.
- Renamed the local default branch from `master` to `main`.
- Reviewed and committed updates to the project context and GitHub profile link.
- Pushed the local commit history using `git push -u origin main`.
- Enabled GitHub Pages using the `main` branch and `/(root)` folder.

### Verification

- GitHub successfully received the repository files and commits.
- The public website loaded with its HTML and CSS styling.
- The Projects navigation link worked correctly.

### Published website

https://felipequi.github.io/research-engineering-portfolio/

---

## 2026-11-14 — Session 03: CEA-Liten Case Study Publication

### Objective

Integrate and publish the first detailed R&D case study, demonstrating experimental instrumentation, optical fluorescence measurements and scientific data analysis.

### Project integrated

**CEA-Liten — Optical Fluorescence Imaging**

Research internship focused on investigating fluorescence-based methods for detecting lithium plating on graphite battery anodes.

Technical areas represented:

- Optical instrumentation and experimental setup development.
- Fluorescence spectroscopy.
- UV excitation and sCMOS imaging.
- Scientific image processing and quantitative analysis using Python.
- Experimental methodology and interpretation of preliminary results.

### Website architecture

The portfolio now uses the following structure:

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

### Activities completed

- Integrated the dedicated CEA-Liten case study page.
- Added scientific figures and experimental illustrations under `assets/images/cea-liten/`.
- Organized global and project-specific CSS files.
- Removed the obsolete `assets/style.css` file.
- Committed and pushed the new project files to GitHub.
- Verified that the dedicated case study was accessible through GitHub Pages.
- Updated the homepage to link directly to the case study.
- Synchronized the GitHub modification with the local repository.
- Removed the unnecessary local HTML backup after confirming successful publication.

### Git history

**Case study publication commit:** `c55fd7b`  
**Homepage navigation update:** `3329001`

Commands used:

```bash
git status
git commit -m "Add CEA-Liten research case study"
git push origin main
git pull origin main
```

### Deployment verification

**Homepage:**  
https://felipequi.github.io/research-engineering-portfolio/

**CEA-Liten case study:**  
https://felipequi.github.io/research-engineering-portfolio/projects/cea-liten.html

Verified outcomes:

- The homepage is publicly accessible.
- The dedicated CEA-Liten page is publicly accessible.
- The homepage link opens the case study.
- The remote homepage update was successfully downloaded using `git pull origin main`.
- The repository was synchronized without merge conflicts.

### Technical concepts reinforced

- **GitHub Pages:** Static website hosting directly from a GitHub repository.
- **Remote repository:** The GitHub-hosted version of the project.
- **`git push`:** Upload local commits to the remote repository.
- **`git pull`:** Retrieve and integrate remote changes.
- **Fast-forward:** Update a branch without creating a merge commit.
- **Untracked file:** A local file not included in Git version control.
- **Modular CSS:** Separating shared website styles from project-specific styles.
- **Relative paths:** Linking HTML pages, stylesheets and images within the repository.

---

## Current Project Status — 2026-11-14

**Development status:** Active  
**Hosting:** GitHub Pages  
**Production branch:** `main`  
**Published case studies:** 1  
**Primary published project:** CEA-Liten Optical Fluorescence Imaging

### Next development priorities

1. Review the website from the perspective of R&D recruiters and researchers.
2. Validate responsiveness on mobile and desktop.
3. Review figure legibility, scientific explanations and navigation.
4. Improve accessibility, metadata and presentation where necessary.
5. Maintain project documentation as the portfolio evolves.

---

## Documentation Maintenance

The `docs/` directory contains three complementary documents:

- **`project-context.md`:** Current project architecture, objectives, constraints and technical decisions.
- **`development-log.md`:** Chronological record of completed development activities.
- **`ai-instructions.md`:** Guidelines for AI-assisted development and maintenance.

These documents are maintained manually after significant development milestones. They are not automatically updated when website files change.
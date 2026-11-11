# Engineering Development Log

**Project:** Research & Engineering Portfolio  
**Author:** Juan Felipe Quintero  
**Development environment:** Windows · Visual Studio Code · Git · Live Server  
**Repository:** `research-engineering-portfolio`

---

## 2026-11-11 — Session 01: Initial Setup & Version Control

### 1. Objective

Establish a structured local development environment, initialize version control and create the first reproducible checkpoint of the portfolio website.

### 2. Activities completed

- Organized the project under `LIFE/06_PROFESIONAL/Portafolio/research-engineering-portfolio`.
- Opened the project in Visual Studio Code.
- Verified the HTML/CSS website using Live Server.
- Verified Git installation: `2.53.0.windows.1`.
- Selected GitHub account: `felipequi`.
- Configured the Git author identity using a GitHub `noreply` address.
- Initialized the local Git repository.
- Staged the initial website files.
- Created and verified the first commit.

### 3. Commands and explanations

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

### 4. Results

**First commit:** `a5a98c7`  
**Branch:** `master`  
**Files registered:** `README.md`, `index.html`, `assets/style.css`  
**Changes:** 271 inserted lines across three files.

The repository was initialized locally. No remote GitHub repository has been connected or published yet.

### 5. Technical concepts learned

- **Working directory:** Files currently being edited.
- **Staging area

## 2026-11-11 — First GitHub deployment

### Objective
Publish the Research & Engineering Portfolio and verify its initial deployment.

### Actions completed
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

### Next steps
- Continue testing website navigation and responsiveness.
- Review project content and technical descriptions.
- Maintain documentation as the portfolio evolves.
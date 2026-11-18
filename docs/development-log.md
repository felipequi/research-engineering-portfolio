## 2026-11-18 — Session 04: Academic Background Integration & Portfolio Refinement

### Objective

Expand the portfolio's academic background section with dedicated institutional pages, improve the visual consistency of the website, and synchronize the updated implementation with GitHub Pages.

### Academic pages developed

**Universidad Tecnológica de Pereira (UTP)**

- Created a dedicated academic background page at `education/utp.html`.
- Organized the presentation of the Engineering Physics academic pathway.
- Introduced institution-specific styling through `assets/css/utp.css`.
- Connected the academic page to the homepage.

**IMT Mines Albi**

- Created a dedicated academic background page at `education/imt-mines-albi.html`.
- Documented the French engineering double-degree pathway.
- Presented the Advanced Materials and Processes option and the Instrumentation and Advanced Data Analysis specialization.
- Organized selected coursework, academic mentorship and supporting resources.
- Integrated an institutional specialization figure.
- Introduced dedicated styling through `assets/css/imt-mines-albi.css`.
- Connected the academic page to the homepage.

### Homepage improvements

- Updated the Academic Background section to provide internal navigation to both institutional pages.
- Made university images and titles clickable.
- Added dedicated academic background links while preserving external institutional links.
- Refined academic card spacing, image proportions and link alignment.
- Reduced vertical spacing between major homepage sections.
- Preserved the website's established typography, color palette and editorial design.

### Academic page refinements

- Reduced vertical spacing between sections.
- Improved layout proportions and content density.
- Refined the presentation of academic figures.
- Adjusted the IMT Mines Albi specialization figure to avoid excessive image scaling and redundant module descriptions.
- Added styling provisions for the IMT Mines Albi institutional logo.

### Updated website architecture

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

The directory structure reflects the files discussed during development. Publication status should be verified separately for individual pages and assets.

### Git and GitHub synchronization

A local commit was created to record the academic page and homepage refinements.

**Commit:** `3a1666f`  
**Message:** `Refine academic pages and improve portfolio layout`

During deployment verification, the local repository initially reported:

```text
## main...origin/main [ahead 1]
```

This indicated that one local commit had not yet been pushed to the remote repository.

The required synchronization command was:

```bash
git push origin main
```

The subsequent deployment was reviewed through GitHub and the published website.

### GitHub Pages CSS cache issue

**Problem**

The published website initially displayed differences in spacing and image presentation compared with the local Live Server preview.

**Investigation**

The issue was consistent with the browser loading a previously cached stylesheet.

**Resolution**

A stylesheet version parameter was introduced in the homepage:

```html
<link rel="stylesheet" href="assets/css/style.css?v=3">
```

The versioned URL allowed the browser to request the updated CSS file.

**Verified result**

The owner confirmed that the published website displayed the expected styling after the cache-related adjustment.

### Technical concepts reinforced

- **Cache busting:** Changing an asset URL to encourage browsers to retrieve its updated version.
- **CSS cascade:** The process by which competing CSS rules determine the final appearance.
- **Deployment verification:** Confirming that published files match the intended local implementation.
- **Git branch synchronization:** Distinguishing local commits from commits available on the remote branch.
- **Page-specific CSS:** Maintaining independent stylesheets for individual academic pages.
- **Responsive image presentation:** Using aspect ratios and `object-fit` to control image proportions.

### Results

- Dedicated academic background pages developed for UTP and IMT Mines Albi.
- Homepage academic cards connected to their corresponding pages.
- Vertical spacing refined across the homepage and academic pages.
- Academic card image presentation improved.
- GitHub Pages styling discrepancy resolved through stylesheet cache busting.
- Portfolio architecture expanded to accommodate institutional academic documentation.

---

## Current Project Status — 2026-11-18

**Development status:** Active  
**Hosting:** GitHub Pages  
**Production branch:** `main`  
**Published R&D case studies verified in the development log:** 1 (CEA-Liten)  
**Academic pages developed:** 2 (UTP and IMT Mines Albi)

### Next development priorities

1. Review the full portfolio from the perspective of R&D engineering recruiters and research supervisors.
2. Verify desktop and mobile responsiveness across all pages.
3. Check internal navigation, images, academic resources and institutional links.
4. Improve scientific project presentation, figure legibility and accessibility.
5. Develop and refine additional technical case studies.
6. Maintain synchronized project documentation following significant development milestones.
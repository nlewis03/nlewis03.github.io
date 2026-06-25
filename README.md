# SpeakBirth — HCI Design Portfolio

A CSE 400 (Human-Computer Interaction) class project documenting the design process for **SpeakBirth**, a mobile app concept that addresses the Black maternal mortality crisis in the United States by helping Black mothers find culturally competent providers, navigate insurance benefits, and read honest equity-focused reviews of hospitals.

## Live website

Once GitHub Pages is enabled, the site will be live at:
`https://[your-github-username].github.io/[your-repo-name]/`

## Repository structure

```
.
├── index.html             # Home page — project intro and navigation
├── overview.html          # Project Overview — context, problem, goals, target users
├── design-process.html    # Design Process — research, personas, journey map, storyboards, iterations
├── prototyping.html       # Prototyping — tools, screens, feedback
├── evaluation.html        # Heuristic Evaluation — Nielsen's heuristics, issues, fixes
├── reflections.html       # Reflections and Conclusion
├── style.css              # Shared stylesheet for all pages
├── images/                # Image assets (storyboards, prototype screenshots, etc.)
└── README.md              # This file
```

## How to run the website

### Option 1: View locally
1. Clone or download this repository.
2. Open `index.html` in any modern web browser.
3. Navigate between pages using the top navigation bar.

### Option 2: View on GitHub Pages
1. Push the repository to GitHub.
2. Go to **Settings → Pages**.
3. Under "Build and deployment," set Source to "Deploy from a branch" and Branch to `main` (or `master`), folder `/ (root)`.
4. Save. Wait 1–2 minutes, then visit the URL shown.

## Section links

- [Home](index.html) — project overview and navigation
- [Project Overview](overview.html) — context, problem, design goals, target users
- [Design Process](design-process.html) — user research, personas, journey maps, storyboards, design iterations
- [Prototyping](prototyping.html) — tools used, screens, feedback
- [Heuristic Evaluation](evaluation.html) — Nielsen's 10 heuristics applied to the prototype
- [Reflections](reflections.html) — lessons learned and conclusion

## Adding images

To add storyboard, prototype, or journey map images:

1. Save image files to the `images/` folder (suggested names: `storyboard-1.png`, `storyboard-2.png`, `storyboard-3.png`, `prototype-1.png`, etc.).
2. In the relevant HTML file, find the `<div class="image-placeholder">` block.
3. Replace the whole block with an image tag, for example:
   ```html
   <img src="images/storyboard-1.png" alt="Storyboard 1" style="width: 100%; border-radius: 10px; margin-top: 16px;">
   ```

## Author

[Your Name] — [SU ID]
CSE 400, Fall 2025

## Acknowledgments

Research sources used in the design process include CDC and KFF maternal mortality data, a PMC qualitative study on obstetric racism, STAT News coverage of Black maternal health technology (including the Irth app), and a 2024 Women's Health journal study on mHealth perspectives among Black rural postpartum mothers.

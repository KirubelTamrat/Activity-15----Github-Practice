# Plan Document for Activity 14 Project and Repository

## 1. Project Plan — Activity 14 Reproducible Report

### Goals
- Create a reproducible PDF report using Quarto (QMD).
- Clearly organize the analysis with sections, narrative text, plots, and tables.
- Ensure the report can be re-run on any computer without modification.
- Follow STAT 184 requirements for YAML, narrative text, alt text, and code blocks.

### Needs
- The Activity 14 QMD file stored in this repository.
- The Activity 14 PDF created from that QMD file.
- Any data files referenced using **relative paths** (no absolute paths).
- Access to R, Quarto, and necessary R packages.

### Steps
1. Open the QMD file in RStudio or Visual Studio Code.
2. Verify YAML header includes title, author, date, PDF output, and execution options.
3. Check that narrative sections are complete and properly written.
4. Ensure code blocks are labeled, have fig-alt or tbl-cap, and follow a consistent style.
5. Render the QMD to a PDF using Quarto.
6. Upload the new PDF into the repo if changes were made.
7. Commit changes to a dev branch, then merge into main using a pull request.

---

## 2. Repository Plan — Organizing and Maintaining the Repo

### Goals
- Keep the repo organized and readable.
- Use branches to make changes safely.
- Use GitHub Issues to track tasks.
- Maintain meaningful commit messages.

### Needs
- A `main` branch that stays clean and holds final versions.
- A `dev` branch for updates or later corrections.
- At least two GitHub Issues describing tasks.
- GitHub pull requests linking issues and commits.

### Steps
1. Create Issues whenever changes are needed.
2. Switch to the `dev` branch to complete the work.
3. Make commits that reference the correct issue numbers (e.g., “closes #1”).
4. Push updates to GitHub.
5. Create a Pull Request from `dev` to `main`.
6. Add a clear PR title and description.
7. Merge the PR once everything looks correct.
8. Delete dev branch if desired (optional).
9. Repeat process if further improvements are made.

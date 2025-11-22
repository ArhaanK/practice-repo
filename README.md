# practice-repo

## Overview
This repository was created as part of **STAT 184 – GitHub Practice (Activity 15)**. Its purpose is to help me build comfort with GitHub workflows, Quarto documents, version control, and collaborative development practices. The repo contains a Quarto (`.qmd`) file and its rendered PDF output as part of the practice activity.

## Data Source
This project does not use external datasets. All content is generated directly as part of STAT 184 assignments and Quarto exercises.

## Project Plan

### 1. Plan for the Project
**Goals:**
- Demonstrate the ability to create, edit, and render Quarto documents.
- Practice committing, pushing, branching, and submitting pull requests on GitHub.
- Maintain an organized workflow that mirrors real collaborative data science projects.

**Needs:**
- A working `.qmd` file.
- Proper rendering to `.pdf`.
- Accurate and consistent commit history.
- A README explaining the project, plan, and repository structure.

**Steps:**
1. Create a Quarto Markdown file (`Activity_14.qmd`).
2. Add descriptive text, code chunks, and formatting.
3. Render the document to a PDF file.
4. Commit both the `.qmd` and `.pdf` files to a feature branch.
5. Push the branch to the remote repository.
6. Open a Pull Request and merge into `main`.

### 2. Plan for Setting Up and Maintaining the Repository
**Goals:**
- Build a clear, reproducible GitHub workflow.
- Use branches to manage work rather than committing directly to `main`.
- Keep files organized and commits meaningful.

**Needs:**
- A dedicated feature branch: `arhaank/quarto`.
- Consistent, descriptive commit messages.
- Pull Requests to merge changes safely.
- A documented repository structure.

**Steps:**
1. Create the branch `arhaank/quarto` to serve as the working branch.
2. Add and commit changes on this branch instead of on `main`.
3. Push updates with:  
   `git push --set-upstream origin arhaank/quarto`
4. When ready, open a Pull Request on GitHub.
5. Review and merge the PR into `main`.
6. Repeat this workflow for future updates to maintain a clean repo.

## Repository Organization
practice-repo/
│
├── Activity_14.qmd # Quarto source document
├── Activity_14.pdf # Rendered PDF output
├── README.md # Project documentation
│
└── Branches:
├── main # Stable branch
└── arhaank/quarto # Working branch for edits

The `arhaank/quarto` branch is where all Quarto work is completed locally before being pushed and merged into `main`.

## Contact Information
**Arhaan Keshwani**  
Email: ask6023@psu.edu
Penn State University

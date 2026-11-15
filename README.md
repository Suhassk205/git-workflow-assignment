# Git & GitHub Workflow Assignment

**Course Module:** Version Control & Software Testing  
**Student Name:** Suhas Kembhavi  
**GitHub Repository:** [https://github.com/Suhassk205/git-workflow-assignment](https://github.com/Suhassk205/git-workflow-assignment)  
**Submission Deliverable:** Combined Assignment PDF (Question 1 & Question 2)

---

## Repository Overview

This repository demonstrates a complete Git version control workflow executed entirely on a local machine and pushed to GitHub in accordance with the assignment guidelines:

1. **Step 1 - Local Repository Setup:** Initialized locally with `index.html` and `about.html`.
2. **Step 2 - Git Workflow Execution:**
   - Initial commit on `main`.
   - File modification and second commit on `main`.
   - Feature branch (`feature`) creation, switching, code modification, and feature commit.
   - Non-fast-forward merge (`git merge feature --no-ff`) back into `main`.
   - Verification with full ASCII commit tree graph (`git log --graph --oneline --all`).
3. **Step 3 - .gitignore Implementation:** Configured `.gitignore` to exclude `*.log` files and `temp/` folder.
4. **Step 4 - Undo Operation using Git:** Demonstrated commit undo via `git reset --hard HEAD~1` with verified before-and-after repository states.
5. **Step 5 - GitHub Remote Integration:** Connected local repository to this public GitHub repository and pushed all branches (`main` and `feature`).
6. **Step 6 - Command Documentation:** Provided comprehensive explanations for all Git commands in `git_commands.txt`.

---

## File Structure

```text
git-workflow-assignment/
├── .gitignore          # Ignores *.log and temp/
├── about.html          # Project about page with team & scope
├── git_commands.txt    # Step-by-step command reference & descriptions
├── index.html          # Main landing page with highlights
└── README.md           # Project summary and submission reference
```

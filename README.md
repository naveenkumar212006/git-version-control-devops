# Git & GitHub Version-Controlled DevOps Project

## Project Overview
This project demonstrates Git and GitHub best practices for managing a DevOps project. It covers repository initialization, branching strategies, commits, pull requests, merging, `.gitignore`, version tagging, and Markdown documentation.

## Objectives
- Initialize a local Git repository.
- Push the project to GitHub.
- Create and manage `main`, `dev`, and feature branches.
- Use meaningful commit messages.
- Merge changes through Pull Requests.
- Exclude unnecessary and sensitive files using `.gitignore`.
- Create version tags for releases.
- Document the workflow using Markdown.

## Tools Used
- Git
- GitHub
- macOS Terminal
- Markdown

## Repository Structure

```text
git-version-control-devops/
├── README.md
├── .gitignore
└── docs/
    └── branching-workflow.md
```

## Branching Strategy

| Branch | Purpose |
|---|---|
| `main` | Stable, reviewed project version |
| `dev` | Integration and testing of changes |
| `feature/docs-workflow` | New workflow documentation |

## Tasks Performed

1. Initialized a Git repository with `main`.
2. Created a GitHub repository and connected the remote.
3. Created and pushed the `dev` branch.
4. Created a feature branch from `dev`.
5. Added and committed workflow documentation.
6. Opened a Pull Request from the feature branch to `dev`.
7. Merged the approved changes into `dev`.
8. Opened a Pull Request from `dev` to `main`.
9. Merged the reviewed changes into `main`.
10. Created a Git version tag.
11. Verified repository status, branch history, and tags.

## Important Git Commands

```bash
git init -b main
git status
git add .
git commit -m "Initial project setup"
git branch
git switch -c dev
git switch -c feature/docs-workflow
git log --oneline --graph --all
git tag -a v1.0.0 -m "Version 1.0.0"
git push origin --tags
```

## Git Best Practices
- Use descriptive commit messages.
- Keep feature work isolated in separate branches.
- Review changes through Pull Requests.
- Never commit passwords, API keys, or secret files.
- Use `.gitignore` for local and generated files.
- Tag stable versions for easier tracking and rollback.

## Expected Outcome
A GitHub repository demonstrating a structured version-control workflow with branches, meaningful commits, Pull Requests, documentation, a `.gitignore` file, and a release tag.

## Author
Naveen Kumar A

**Project Category:** DevOps / Version Control  
**Status:** Update this field after completing and verifying all tasks.
cat > docs/branching-workflow.md <<'EOF'
# Git Branching Workflow

## Main Branch
The main branch contains stable project changes.

## Development Branch
The dev branch integrates features before release.

## Feature Branch
Feature branches are created from dev to develop individual changes.

## Pull Request Workflow
1. Create a feature branch from dev.
2. Make changes and commit them.
3. Push the feature branch to GitHub.
4. Open a Pull Request targeting dev.
5. Review and merge the changes.
6. Open a Pull Request from dev to main.
7. Merge after review.

## Version Tagging
Version tags identify stable releases.

Example:
git tag -a v1.0.0 -m "Release version 1.0.0"
EOF
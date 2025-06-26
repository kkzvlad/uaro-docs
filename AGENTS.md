# Guidelines for Codex Agents

This repository contains documentation for **uaRO World of Your Dream**. The site is built using **MkDocs** and all source files live in the `docs/` folder.

## Expectations
- Keep lines under 120 characters.
- Use standard Markdown; avoid stray shell prompts or unrelated console text in documentation.
- Place new images in `docs/img/` and reference them with relative paths.

## Checks
1. Build the site with MkDocs to ensure the configuration is valid:
   ```
   mkdocs build
   ```
   If the command fails because MkDocs is not installed, note this in the PR.
2. Review the output for warnings or errors. The build should complete without issues.

## Pull Request Notes
- Summarize what changed and mention whether `mkdocs build` ran successfully.
- Keep the working tree clean (`git status` should show no changes) before creating the PR.

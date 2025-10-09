# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a documentation site for **uaRO World of Your Dream**, a private Ragnarok Online game server. The site is built with **MkDocs** using the Material theme and is published at https://wiki.uaro.net.

All documentation source files are located in the `docs/` directory. The site includes:
- Server information, rules, and features
- Patch notes organized by year (`docs/patch-notes/2024/`, `docs/patch-notes/2025/`)
- Game guides (dungeons, quests, systems, events)
- Custom styling in `docs/css/custom.css` (uses REMs for accessibility, CSS variables for theme support)

## Build and Development Commands

### Build the site
```bash
mkdocs build
```
This validates the configuration and builds the static site. The build must complete without warnings or errors before submitting PRs.

### Serve locally (if needed)
```bash
mkdocs serve
```
This starts a local development server at `http://127.0.0.1:8000/`.

### Check git status
```bash
git status
```
The working tree should be clean before creating PRs.

## Documentation Standards

### Line Length
Keep all lines under **120 characters** for readability.

### Markdown Style
Use standard Markdown syntax. Avoid including shell prompts or unrelated console text in documentation.

### Admonitions Format
The site uses MkDocs admonitions for callout boxes. Preferred format:
```markdown
!!! note "Optional Title"
    Content here

!!! warning "Optional Title"
    Content here

!!! important "Optional Title"
    Content here
```

### Images
- Place new images in `docs/img/`
- Reference with relative paths: `![Alt text](img/filename.webp)`
- For specific layouts, use HTML: `<img src="img/filename.webp" alt="Alt text" align="left" />`

### Patch Notes Structure
- Individual patch files live in `docs/patch-notes/YYYY/patchesMMDDYYYY.md`
- The main index `docs/All_Patch_Notes.md` lists all patches with links
- Latest patch is marked with ⭐ in `All_Patch_Notes.md`
- Patches include standard sections: General, Quality of Life, Items, NPC, Commands, Skills, Fixes, etc.

## Repository Architecture

### Navigation (`mkdocs.yml`)
The navigation structure is defined in the `nav:` section of `mkdocs.yml`. When adding new pages:
1. Create the markdown file in `docs/`
2. Add the entry to the appropriate section in `nav:`
3. Use emoji prefixes for consistency (e.g., `🎉`, `🧵`, `⚔️`)

### Custom Styling
`docs/css/custom.css` contains page-specific styles:
- `.class-changes-table` for `Class_Changes.md`
- `#index-patch-notes` for `index.md` patch note tabs
- `#main-features-cards` for feature cards
- All styles use REM units (based on 16px) and CSS variables from the Material theme

### Theme Configuration
The site uses Material for MkDocs with:
- Dark/light mode toggle
- Navigation features: sections, expand, footer, table of contents integration
- Search with suggestions and highlighting
- Code blocks with syntax highlighting and copy buttons
- Multiple markdown extensions (see `markdown_extensions:` in `mkdocs.yml`)

## Pull Request Workflow

When creating PRs:
1. Run `mkdocs build` to validate changes
2. Verify no warnings or errors in build output
3. Ensure `git status` shows a clean working tree
4. Summarize changes and note whether `mkdocs build` succeeded
5. If MkDocs is not installed, note this in the PR description

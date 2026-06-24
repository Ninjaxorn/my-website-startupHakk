# CLAUDE.md

## Project

Personal portfolio website built with plain HTML and CSS — no frameworks, no build tools.

## Style

- Dark theme throughout
- Modern, clean aesthetic: generous whitespace, clear typography, subtle contrast
- No external CSS frameworks (no Tailwind, Bootstrap, etc.)

## File structure (expected as it grows)

```
index.html        # main entry point
css/style.css     # global styles
assets/           # images, fonts, icons
```

## Git workflow

- Commit messages are descriptive: explain what changed and why, not just what files were touched
- Keep changes small and focused — one logical change per commit
- Prefer `git add <specific-file>` over `git add .`

## Coding conventions

- Indent HTML with 2 spaces
- Group CSS by section (reset/base → layout → components → utilities)
- Use CSS custom properties for colors and repeated values
- No JavaScript unless explicitly needed

# Onflo Design Project

This project uses the Onflo Design System.
**Mode: design** — use the CSS class API only (e.g. `<button class="ds-button ds-button--filled">`).
Do not import `Ds*Component` classes or use `mat-*` directives.

@node_modules/@onflo/design-system/AGENT-GUIDE.md

---

## First-time setup

If `node_modules/` does not exist in this project, tell the user:

> "It looks like this project hasn't been set up yet. Run `/setup-project` and I'll walk you through it."

Do not attempt to build or generate any code until setup is complete.

---

## This is a design prototype

This project is for designers and PMs to prototype features using real Onflo components.
It is **not** a production engineering project.

- Prioritise working, realistic UI over engineering concerns
- No need for error handling, API integration, or production patterns
- Use static/mock data for all content
- If a feature needs reactive behavior beyond what static HTML can do, build a visual stand-in and mark the spot with: `<!-- TODO eng: wire [description] here -->`

---

## Visual reference

Open `node_modules/@onflo/design-system/preview/index.html` in a browser for the full
component catalog — every DS component, token, and layout pattern with live demos.

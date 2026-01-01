# Prosthetic Hand Website

Static HTML/CSS/JS site for the prosthetic hand build log and project status board.

## Structure
- `index.html`: Main landing page.
- `board.html`: Project status board view.
- `css/`: Shared and board-specific styles.
- `js/`: UI scripts and board rendering.
- `data/`: JSON data used by the status board.
- `partials/`: HTML fragments loaded at runtime (via `data-include`).
- `assets/images/`: Image library organized by usage (homepage, stages, contributors, status board).


## Run (local)
Serve the site using a simple HTTP server (required for fetch() and runtime includes):
    python3 -m http.server 8000


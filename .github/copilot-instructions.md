# Copilot Instructions for pranjal.github.io

## Project Overview
This repository hosts a personal GitHub Pages website. It's a static site built with HTML, CSS, and JavaScript, potentially using Jekyll for templating and Markdown for content.

## Architecture
- **Major Components**: Static pages (e.g., index.html, about.html), assets folder for media and certificates.
- **Service Boundaries**: No backend services; purely frontend static content.
- **Data Flows**: Static generation; no dynamic data processing.
- **Structural Decisions**: Minimal setup for quick deployment via GitHub Pages, favoring simplicity over complexity.

## Developer Workflows
- **Local Development**: Run `python -m http.server 8000` in the root directory to serve locally at http://localhost:8000.
- **Build/Deploy**: No build process; commit and push to main branch triggers GitHub Pages deployment.
- **Testing**: Open pages in browser for manual verification; no automated tests.
- **Debugging**: Use browser dev tools for HTML/CSS/JS issues; check GitHub Pages build logs for deployment errors.

## Conventions and Patterns
- **File Organization**: Place static assets in `assets/` (e.g., `assets/Certs/` for certificates).
- **Naming**: Use kebab-case for file names (e.g., `my-project.html`).
- **Content Creation**: Use Markdown for text-heavy pages if Jekyll is enabled later.
- **No Specific Frameworks**: Stick to vanilla HTML/CSS/JS to keep it lightweight.

## Integration Points
- **GitHub Pages**: Automatic deployment from main branch.
- **External Dependencies**: None; include via CDN if adding libraries (e.g., Bootstrap for CSS).

## Key Files
- [README.md](README.md): Basic project description.
- `assets/Certs/`: Directory for certificate files.

## Examples
- To add a new page: Create `portfolio.html` in root with `<html><head>...</head><body>...</body></html>`.
- To add a certificate: Upload to `assets/Certs/` and link with `<a href="assets/Certs/cert.pdf">View Cert</a>`.</content>
<parameter name="filePath">/workspaces/pranjal.github.io/.github/copilot-instructions.md
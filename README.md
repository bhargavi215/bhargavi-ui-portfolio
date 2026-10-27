# Bhargavi Velagapudi — Accessible UI Portfolio

An original portfolio demo inspired by common enterprise public-service UI patterns. All service requests are fictional and stored in browser memory. No backend connection is required for the interactive demo.

## Run
Open `index.html` in a modern browser. For a local development server, run `python -m http.server 8000` in this directory and visit `http://localhost:8000`.

## Contents
- `index.html`: semantic page structure, form, table, tabs, and accessible regions.
- `styles.css`: responsive styles and design tokens.
- `app.js`: search, filtering, validation, announcements, and code tabs.
- `api/Program.cs`: illustrative ASP.NET Core / Entity Framework API source; not a complete deployable API project.
- `api/schema.sql`: illustrative SQL Server schema.

## Accessibility verification
Test keyboard-only navigation, zoom/reflow, axe-core, and NVDA/JAWS. WCAG 2.1 AA and Section 508 compliance have **not** been independently certified. The code demonstrates practices, not a formal audit result.

## Security and ownership
This is a sample project, not code taken from an employer or public agency. The API snippet is educational only: add authentication, authorization, request validation, rate limiting, and appropriate security controls before production use.

## Publish
Upload the static site files to GitHub Pages, Netlify, or another static host. Publish the complete source to a public Git repository, then add both links to the resume before submitting.

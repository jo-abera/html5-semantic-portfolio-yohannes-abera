# HTML5 Semantic Portfolio

**Name:** Yohannes Abera


## Description

A single-page static portfolio built using **pure HTML5**, with no CSS or JavaScript. This project demonstrates semantic document structure, accessibility (ARIA) practices, and native HTML5 interactive elements as required by the HTML5 Fundamentals & Semantic Structure module.

## Live Site

*(Add your GitHub Pages URL here once enabled, e.g. `https://<your-username>.github.io/html5-semantic-portfolio-<your-name>/`)*

## Semantic Elements Implemented

- `<header>` — site-wide header and project-specific header
- `<nav>` — primary navigation and project sub-navigation
- `<main>` — single wrapper for dominant page content
- `<section>` — Hero, About, Skills, Projects, Contact
- `<article>` — About Me content, each project entry
- `<hgroup>` — project titles paired with subtitles
- `<figure>` / `<figcaption>` — profile image, project images, project videos
- `<time datetime="...">` — project completion dates, footer timestamp
- `<mark>` — highlighted project metrics
- `<aside>` — client information blocks
- `<address>` — client contact info, site contact info
- `<dl>` / `<dt>` / `<dd>` — skills list, technical specs
- `<details>` / `<summary>` — expandable technical specifications
- `<dialog>` — project summary modal with trigger `<button>`
- `<video>` / `<source>` / `<track>` — embedded video with captions track and fallback text
- `<footer>` — copyright and last-updated timestamp
- `<form>`, `<fieldset>`, `<legend>`, `<label>`, `<input>`, `<select>`, `<textarea>`, `<button>` — accessible contact form with labels tied to inputs via matching `id`/`for`

## Notes

- No `<style>` tags, external stylesheets, or inline `style` attributes are used, per assignment rules.
- No JavaScript is used. Note: native `<dialog>` elements typically require a small script (e.g. `dialog.showModal()`) to open interactively in a browser; per the "no JavaScript" constraint, the `<dialog>` and its trigger `<button>` are included to satisfy the semantic/markup requirement, but opening it interactively would need JS enabled separately if your instructor permits it. Confirm this point with your instructor if it affects grading.
- Placeholder image URLs (picsum.photos) and a sample video (MDN's cc0 sample) are used — replace with your own real project media before submitting.
- Replace all placeholder name, contact, and project details with your own real information.

## Setup Instructions (for submission)

1. Create a new **public** GitHub repository named `html5-semantic-portfolio-[your-name]`.
2. Initialize it with this `README.md`.
3. Place `index.html` at the repository root.
4. Commit incrementally (e.g., "Add head metadata", "Add hero section", "Add projects section", "Add contact form") — avoid one bulk final commit.
5. Push all commits to `main` before the deadline.
6. (Optional but recommended) Enable GitHub Pages in repo Settings → Pages, and add the live URL above.
7. Submit the repository URL through the course portal in the form:
   `https://github.com/<your-username>/<repository-name>`

# TechFest 2025 — Static Website

A clean, responsive, accessible multi-page event site for **TechFest 2025** (September 12–14, 2025). Built with **vanilla HTML5 + a single external CSS file**. **No JavaScript** or frameworks.

## How to Run
1. Clone or download this repository.
2. Open `index.html` in any modern desktop or mobile browser. That’s it.

## Project Structure

/
├─ index.html
├─ events.html
├─ schedule.html
├─ register.html
├─ gallery.html
├─ contact.html
├─ /assets
│  ├─ /css
│  │  └─ styles.css
│  └─ /img
│     ├─ img1.jpg
│     ├─ img2.jpg
│     ├─ img3.jpg
│     ├─ img4.jpg
│     ├─ img5.jpg
│     ├─ img6.jpg
│     ├─ img7.jpg
│     ├─ img8.jpg
│     └─ img9.jpg
└─ README.md


## Pages
- **Home (`index.html`)** — Event name/date, hero section, highlights, clear CTAs to **Register** and **Explore Events**.
- **Events (`events.html`)** — Semantic lists (`<ol>/<ul>`) of competitions with brief details and a link to register.
- **Schedule / Results (`schedule.html`)** — Accessible, responsive table with caption, headers, and sample rows. Horizontal scroll on small screens.
- **Registration (`register.html`)** — Full participant form with labels, required fields, basic HTML validation, and consent checkbox.
- **Gallery (`gallery.html`)** — Responsive CSS Grid gallery referencing images in `/assets/img/` with descriptive alt text.
- **Contact & FAQs (`contact.html`)** — Contact info, social links, previous-year gallery link, and FAQs using `<details><summary>`.

## Design & Accessibility
- **Mobile-first** layout with a max-width container and fluid spacing.
- **Single shared stylesheet**: `assets/css/styles.css`.
- **Consistent header/nav/footer** across all pages; active link is visually indicated.
- **Skip link** for keyboard users and visible **focus states**.
- **Semantic landmarks** (`header`, `nav`, `main`, `footer`, `section`, `article`).
- **High contrast** palette; readable typography.
- **Tables** with `<caption>`, `<thead>`, `scope="col"`, and responsive overflow.
- **Forms** with proper `label`/`for` bindings, hints, constraints, and a large accessible submit button.
- **Print styles** included to keep tables/forms legible when printed.

## Assets
All images under `/assets/img/` are **placeholders**. Replace them with real JPGs using the same filenames (suggested size ~1600×1000 or larger). Ensure each `<img>` has meaningful `alt` text.

## Development Notes
- **No JS**: All interactions rely on native HTML semantics and browser behavior.
- Keep styles simple and centralized in `assets/css/styles.css`.
- Use relative links only (works locally and when deployed to static hosts).
- Validate any edits with an HTML/CSS validator to avoid broken markup.

## Contribution / Commit Order
This project was organized in the following commit sequence:
1. **Scaffold** — `index.html` + `assets/css/styles.css`
2. **Events page** — `events.html`
3. **Schedule/Results** — `schedule.html`
4. **Registration** — `register.html`
5. **Gallery** — `gallery.html`
6. **Contact & FAQs** — `contact.html`
7. **Assets** — placeholder images under `/assets/img/`

## License
MIT — feel free to adapt for your institution or event.

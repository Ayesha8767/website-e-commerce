# bazaario — Amazon Homepage Clone

A fully responsive homepage clone inspired by Amazon's layout, built with **only HTML5 and CSS3** — no JavaScript, no frameworks, no icon libraries.

> Note: The Amazon name, logo, and product photography are trademarked/copyrighted, so this project uses a custom dummy brand ("bazaario") and generic placeholder imagery instead, while replicating the structure, spacing, and visual style as closely as possible.

## Project Structure

```
amazon-clone/
│
├── index.html
├── style.css
├── images/
└── README.md
```

## Tech Constraints

- HTML5 semantic elements only (`header`, `nav`, `main`, `section`, `article`, `figure`, `footer`, etc.)
- External CSS only — no inline styles, no `<style>` blocks
- No JavaScript, no Bootstrap/Tailwind/jQuery/React
- CSS-only dropdown menu using `:hover` / `:focus-within`
- Layout built with Flexbox (header/nav/footer bottom) and CSS Grid (cards/footer columns)

## Features

- Two-row responsive header: logo, delivery location, search bar, language selector, account & lists, returns & orders, cart
- Secondary nav row with a CSS-only hamburger dropdown
- Hero banner with decorative left/right arrows (visual only, no slider JS)
- Multiple CSS Grid card sections that wrap naturally (never force a single row)
- Horizontally scrollable "best sellers" product rows
- Dark themed multi-column footer with back-to-top, country/language selectors, and legal links
- Hover animations: lift, scale, underline reveal, button ripple, image zoom
- Fully responsive at 1200px / 992px / 768px / 576px breakpoints, no horizontal scroll or overlap

## Running Locally

Just open `index.html` in any browser — no build step or server required.

## Git Workflow Suggestion

```bash
git init
git add index.html
git commit -m "Add base HTML structure"
git add style.css
git commit -m "Add full CSS styling and responsiveness"
git add README.md
git commit -m "Add project documentation"
git branch -M main
git remote add origin <your-repo-url>
git push -u origin main
```

Then enable **GitHub Pages** in repo Settings → Pages → Source: `main` branch, `/ (root)`.

## Image Credits

Imagery is served live from [LoremFlickr](https://loremflickr.com), a free placeholder service that returns real photos matched to keyword tags (e.g. `golf,clubs`, `backpack,bag`) so each card's image matches its heading. Swap in your own licensed images inside `/images/` for production use.

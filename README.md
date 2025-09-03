
# Shera's Academic Website

This folder contains a simple, clean academic website modeled after minimalist faculty pages. It’s plain HTML/CSS (no build step) and works perfectly on GitHub Pages.

## Quick Start (GitHub Pages)

1. Create a new public repository on GitHub. Two easy options:
   - **username.github.io** (special repo name that auto-hosts your homepage), or
   - Any repo name + enable Pages from Settings → Pages (select "Deploy from branch", branch `main`, folder `/root`).

2. Upload the contents of this folder to the repo root (including `index.html` and the `assets` folder).

3. In **Settings → Pages**, select:
   - Source: `Deploy from branch`
   - Branch: `main`
   - Folder: `/` (root)

4. Save. Your site will be live at either **https://USERNAME.github.io/** or **https://USERNAME.github.io/REPO/** (depending on the option chosen) in about a minute.

## Customize

- Replace `assets/img/headshot-placeholder.png` with your photo (keep the same file name or update the `src` path in `index.html`).
- Update email in `index.html` (`mailto:youremail@u.northwestern.edu`).
- Add your real **Google Scholar** and **CV** URLs in the nav and hero buttons.
- Edit text in each HTML page to reflect your latest projects and preferences.
- If you prefer PDFs to open in a new tab, add `target="_blank"` to the links.

## Structure

- `index.html` — Home (name, title, bio, snapshot)
- `working-papers.html` — Job market paper and other WPs
- `publications.html` — Publications & in-progress
- `data.html` — Replication resources
- `assets/style.css` — Minimal styling
- `assets/img/headshot-placeholder.png` — Placeholder headshot

## Local Preview

Double-click `index.html` to open it in your browser locally. Links to the other pages will work as long as files are in the same folder structure.

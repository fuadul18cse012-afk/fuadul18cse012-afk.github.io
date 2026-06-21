# fuadul18cse012-afk.github.io

# Fuadul Hasan — Portfolio

Live site: [fuad71.me](https://fuad71.me/)

A single-page portfolio for a backend software engineer, designed around the tools of the trade — a typing terminal hero, a `git log`–styled experience timeline, and section headers styled like API routes.

## Preview

Open `index.html` in any browser, or visit the live site above.

## Tech Stack

- **HTML5 / CSS3** — no build step, no dependencies to install
- **Vanilla JavaScript** — terminal typing animation, scroll reveals, animated counters, mobile nav toggle
- **Google Fonts** — [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) for structure and labels, [Inter](https://fonts.google.com/specimen/Inter) for body copy

No frameworks, no package manager, no build process. It's one self-contained HTML file.

## Features

- **Typing terminal hero** — types out `whoami`, role, and contact info like a real shell session
- **Git-log experience timeline** — each role is a "commit," with the current job tagged `HEAD → main`
- **API-styled section headers** — `GET /projects → 200 OK` and similar, echoing the subject matter
- **Animated stat counters** — competitive programming ratings count up when scrolled into view
- **Scroll-triggered reveals** — sections fade and rise into place as you scroll
- **Active route highlighting** — the nav link for the section you're viewing lights up automatically
- **Responsive layout** — collapses to a single column with a hamburger nav under 720px
- **Accessible by default** — semantic `h1` for screen readers/SEO, visible focus states, and full support for `prefers-reduced-motion` (disables animation for users who request it)

## File Structure

```
.
├── index.html      # the entire site — markup, styles, and scripts in one file
└── README.md       # this file
```

## Deploying to fuad71.me

This is a static site, so any static host works. A few common options:

**GitHub Pages with a custom domain**
1. Push `index.html` to a GitHub repository.
2. In the repo, add a file named `CNAME` containing exactly: `fuad71.me`
3. Enable GitHub Pages in the repo settings (deploy from the `main` branch, root folder).
4. Point your domain's DNS to GitHub Pages (an `A` record to GitHub's IPs, or a `CNAME` record to `<username>.github.io` if using a subdomain).

**Netlify / Vercel / Cloudflare Pages**
Drag and drop the folder (or connect the repo) — these platforms detect `index.html` automatically and let you attach `fuad71.me` as a custom domain in their dashboard.

## Customizing

All content lives in plain HTML inside `index.html` — search for the section you want to edit (`<section id="projects">`, `<section id="experience">`, etc.) and update the text directly.

Colors, fonts, and spacing are controlled by CSS custom properties at the top of the `<style>` block:

```css
:root{
  --bg: #0e1217;       /* page background */
  --amber: #ffb454;    /* primary accent */
  --green: #7ee787;    /* secondary accent */
  --mono: 'JetBrains Mono', ui-monospace, monospace;
  --sans: 'Inter', system-ui, sans-serif;
}
```

Changing these values updates the whole site's palette and typography consistently.

## Contact

- Email: [fuadul202@gmail.com](mailto:fuadul202@gmail.com)
- Phone: [+880 1754 726519](tel:+8801754726519)
- Site: [fuad71.me](https://fuad71.me/)
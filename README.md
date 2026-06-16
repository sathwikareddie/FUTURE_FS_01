# Sathwika Dommata – Developer Portfolio

A clean, responsive, and professional portfolio website built with plain HTML, CSS, and JavaScript.

**Live Site:** _Add your deployment URL here_

---

## About

This portfolio was built as **Task 1** of the [Future Interns](https://futureinterns.com) Full Stack Web Development internship. It showcases real skills, projects, education, and contact information for Dommata Sathwika — B.Tech IT student at Joginpally B.R. Engineering College, Hyderabad.

---

## Features

- Animated typewriter hero with rotating roles
- Smooth scroll-triggered reveal animations
- Responsive design (mobile, tablet, desktop)
- Sticky navbar with scroll-aware styling
- Skills, education, and certifications sections
- Project showcase cards
- Functional contact form (opens the user's email client)
- SEO meta tags
- Reduced-motion support (`prefers-reduced-motion`)

---

## Tech Stack

| Layer    | Technology                     |
|----------|-------------------------------|
| Markup   | HTML5                          |
| Styling  | CSS3 (custom properties, Grid, Flexbox) |
| Scripting| Vanilla JavaScript (ES6+)      |
| Fonts    | Google Fonts (DM Serif Display + Inter) |

No frameworks, no build tools, no dependencies — just plain files.

---

## Project Structure

```
portfolio/
├── index.html   # Main page (hero, about, skills, projects, contact)
├── style.css    # All styles (tokens, layout, components, responsive)
├── script.js    # Typewriter, scroll reveal, nav, contact form
└── README.md    # This file
```

---

## Setup & Running Locally

No build step required.

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/<your-repo>.git
   cd <your-repo>
   ```

2. **Open in browser**
   - Double-click `index.html`, or
   - Use VS Code's **Live Server** extension for hot reload:
     ```
     Right-click index.html → Open with Live Server
     ```

That's it — no npm, no installs.

---

## Deployment

### Option 1 — GitHub Pages (recommended, free)

1. Push all files to a GitHub repository.
2. Go to **Settings → Pages**.
3. Under **Source**, select `main` branch and `/root`.
4. Click **Save**. GitHub will provide a URL: `https://<username>.github.io/<repo>/`

### Option 2 — Netlify (drag & drop)

1. Go to [netlify.com](https://netlify.com) and sign up.
2. Drag the entire `portfolio/` folder onto the Netlify dashboard.
3. Your site is live instantly with a `*.netlify.app` URL.
4. Optionally connect a custom domain.

### Option 3 — Vercel

1. Install the Vercel CLI: `npm i -g vercel`
2. Run `vercel` in the project folder and follow the prompts.

---

## Customisation Checklist

Before publishing, update these placeholders:

- [ ] Replace `href="#"` GitHub links in project cards with real repo URLs
- [ ] Add your GitHub username in the contact section
- [ ] Update the "More coming soon" card as you complete more projects
- [ ] (Optional) Replace the `mailto:` contact form with a service like [Formspree](https://formspree.io) for server-side email delivery

---

## License

This project is open source under the [MIT License](LICENSE).

---

*Built for the Future Interns Full Stack Web Development Internship – 2026*

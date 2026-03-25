# Shravan Kadam — Personal Portfolio

A modern, futuristic personal portfolio website built with pure HTML, CSS, and JavaScript. No frameworks, no dependencies — just clean, fast, production-ready code.

🔗 **Live Demo:** *(Deploy and add your link here)*

---

## Preview

> Dark theme · Electric green accent · Glassmorphism cards · Smooth animations · Fully responsive

---

## Features

- Typing animation on hero tagline
- Scroll-triggered fade-in sections
- Mouse-following glow blob effect
- Project cards with hover lift + glow border
- Fully responsive — mobile, tablet, desktop
- Smooth scroll navigation
- Mobile hamburger menu
- SEO meta tags included
- Zero external dependencies (fonts via Google Fonts only)

---

## Sections

| # | Section | Description |
|---|---------|-------------|
| 01 | Hero | Name, animated tagline, CTA buttons |
| 02 | About | Bio + stats (projects, deployments, startup) |
| 03 | Skills | Grouped by category with tag-style display |
| 04 | Projects | Cards with live/GitHub links and tech stack |
| 05 | Education | Degree, college, coursework |
| 06 | Contact | Email, phone, LinkedIn, GitHub + resume download |

---

## Tech Stack

- **HTML5** — semantic structure
- **CSS3** — custom properties, grid, flexbox, animations
- **Vanilla JavaScript** — typing effect, scroll observer, mouse tracking
- **Google Fonts** — Syne, DM Mono, Outfit

---

## Project Structure

```
portfolio/
├── index.html       # Main portfolio file (all-in-one)
├── resume.pdf       # Your resume (add this manually)
└── README.md        # This file
```

---

## Getting Started

### 1. Clone or Download

```bash
git clone https://github.com/Shravankadam02/portfolio.git
cd portfolio
```

Or simply download the `index.html` file.

### 2. Open Locally

Just open `index.html` in your browser — no build step, no setup needed.

```bash
open index.html
# or double-click the file
```

### 3. Add Your Resume

Place your resume PDF in the same folder and update this line in `index.html`:

```html
<!-- Find this line and update href -->
<a href="resume.pdf" class="resume-btn" download>
```

---

## Customization

### Update Your Info

All personal data is hardcoded in `index.html`. Search for these values to update:

| What to change | Search for |
|----------------|------------|
| Name | `Shravan Kadam` |
| Email | `shravankadam372@gmail.com` |
| Phone | `8483937455` |
| LinkedIn | `shravan-kadam` |
| GitHub | `Shravankadam02` |
| Location | `Nashik, Maharashtra` |

### Change Accent Color

Find this CSS variable at the top of the `<style>` block:

```css
--accent: #00e5a0;
```

Replace with any color you like. Popular alternatives:
- `#00b8ff` — cyan blue
- `#a78bfa` — soft purple
- `#f59e0b` — amber

### Add a New Project

Copy this block inside `.projects-grid` in `index.html`:

```html
<div class="project-card fade-in">
  <div class="project-header">
    <div class="project-icon">🚀</div>
    <div class="project-links">
      <a href="YOUR_LIVE_LINK" target="_blank" class="project-link" title="Live">
        <!-- live icon svg -->
      </a>
      <a href="YOUR_GITHUB_LINK" target="_blank" class="project-link" title="GitHub">
        <!-- github icon svg -->
      </a>
    </div>
  </div>
  <div>
    <span class="project-badge badge-web">Web App</span>
    <div class="project-name">Project Name</div>
  </div>
  <p class="project-desc">
    Short description of what the project does and the problem it solves.
  </p>
  <div class="project-tech">
    <span class="tech-tag">React</span>
    <span class="tech-tag">Node.js</span>
  </div>
</div>
```

**Badge options:**
```html
<span class="project-badge badge-startup">Startup</span>
<span class="project-badge badge-web">Web App</span>
<span class="project-badge badge-ml">ML · Python</span>
```

---

## Deployment

### Option 1 — Netlify Drop (Easiest, 60 seconds)

1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag and drop your `index.html` file
3. Done — you get a live URL instantly

### Option 2 — GitHub Pages (Free, permanent)

```bash
# Push to GitHub
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/Shravankadam02/portfolio.git
git push -u origin main
```

Then go to your repo → **Settings** → **Pages** → Source: `main` branch → Save.

Your portfolio will be live at:
```
https://shravankadam02.github.io/portfolio/
```

### Option 3 — Vercel

```bash
npm i -g vercel
vercel
```

---

## SEO

Basic SEO meta tags are already included:

```html
<meta name="description" content="Shravan Kadam — Engineering Student, Web Developer..." />
<meta name="keywords" content="Shravan Kadam, Web Developer, Engineering Student..." />
```

To improve further:
- Add Open Graph tags for social sharing previews
- Add a `favicon.ico`
- Submit your URL to Google Search Console after deploying

---

## Roadmap

- [ ] Add profile photo
- [ ] Upload resume PDF
- [ ] Add 4th+ project
- [ ] Add achievements / certifications as they come
- [ ] Add Open Graph meta for LinkedIn/WhatsApp preview
- [ ] Custom domain (e.g. `shravankadam.dev`)

---

## License

This project is open source and free to use for personal portfolio purposes.

---

## Author

**Shravan Kadam**
BE Information Technology · MET BKC, Nashik
[LinkedIn](https://www.linkedin.com/in/shravan-kadam) · [GitHub](https://github.com/Shravankadam02) · [Email](mailto:shravankadam372@gmail.com)

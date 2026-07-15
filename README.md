# Joe Faith, D.Eng. — Personal Website

[![Live site](https://img.shields.io/badge/Live_site-Visit-c7ff54?style=for-the-badge&labelColor=07110f)](https://hogred.github.io/joe-faith/)
[![Deploy to GitHub Pages](https://github.com/HogRed/joe-faith/actions/workflows/pages.yml/badge.svg)](https://github.com/HogRed/joe-faith/actions/workflows/pages.yml)

The personal website of **Joe Faith, D.Eng.**—an AI educator, researcher, and builder exploring how intelligent systems learn, how people learn with them, and how we can build a future where both flourish.

**[Explore the live website →](https://hogred.github.io/joe-faith/)**

## About the site

This single-page portfolio brings together Joe's work across four connected areas:

- **AI education** — preparing the next generation to understand and build intelligent systems
- **Applied research** — using transformer models to investigate chronic kidney disease progression
- **Responsible technology** — contributing to conversations at the intersection of AI, ethics, and faith
- **Ideas in public** — writing and teaching about machine learning, engineering, and the future of education

The visual direction combines an editorial portfolio with the atmosphere of a living research notebook: deep midnight tones, luminous data-inspired details, strong typography, and subtle motion.

## Highlights

- Responsive design for desktop, tablet, and mobile
- Lightweight, dependency-free HTML, CSS, and JavaScript
- Scroll-triggered transitions and interactive ambient effects
- Reduced-motion support for accessibility
- Semantic navigation and keyboard-friendly controls
- Direct links to research, articles, academic work, and social profiles
- Automatic deployment through GitHub Actions

## Updating content

Most content lives in [`index.html`](./index.html). The page is organized into clear sections:

| Section | Purpose |
| --- | --- |
| Hero | Core positioning and primary calls to action |
| Work | Featured teaching, research, and ethics initiatives |
| Field notes | Recent articles and public thinking |
| About | Biography, background, and quick facts |
| Contact | Links for following or starting a conversation |

Visual styles are in [`styles.css`](./styles.css), while navigation, reveal animations, the ambient cursor effect, and the current year are handled in [`script.js`](./script.js).

## Previewing locally

Because this is a static site, it can be opened directly in a browser. Running a small local server gives the most accurate preview:

```bash
python -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

## Deployment

Every push to the `main` branch runs [`.github/workflows/pages.yml`](./.github/workflows/pages.yml) and publishes the latest version to GitHub Pages.

```bash
git add .
git commit -m "Update website"
git push
```

The live site is available at **[hogred.github.io/joe-faith](https://hogred.github.io/joe-faith/)**.

## Project structure

```text
.
├── .github/workflows/pages.yml  # GitHub Pages deployment
├── .nojekyll                    # Serve the site without Jekyll processing
├── index.html                   # Page content and structure
├── styles.css                   # Visual system and responsive layout
├── script.js                    # Interaction and motion
└── README.md                    # Project documentation
```

## Connect

- [LinkedIn](https://www.linkedin.com/in/joe-faith-d-eng-554b89165/)
- [Harding University faculty profile](https://facultygallery.harding.edu/en/persons/joe-faith/)
- [ORCID](https://orcid.org/0009-0004-8445-9659)

---

Built as a home for ongoing work in AI, computer science education, research, and responsible technology.

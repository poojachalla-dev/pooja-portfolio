# Pooja Challa — AI/ML & Data Engineer Portfolio

A single-page personal portfolio site for Pooja Challa, showcasing a transition from front-end software engineering into AI/ML and data engineering. Built with plain HTML, CSS, and JavaScript, and deployed on Vercel.

**Live site:** [poojachalla-dev-pooja-portfolio.vercel.app](https://poojachalla-dev-pooja-portfolio.vercel.app/)

## Features

- **Hero section** with an animated intro, a downloadable resume PDF, and quick links to GitHub, LinkedIn, and email.
- **About** section summarizing experience and current focus areas.
- **Skills** grid covering languages, AI/ML tools, data engineering, visualization, prior front-end stack, and methodologies.
- **Engineering Philosophy** cards outlining how the work approach blends production-readiness, explainability, and continuous learning.
- **Experience** timeline of professional roles.
- **Projects** section that dynamically fetches and renders public repositories live from the GitHub REST API (sorted by most recently pushed, with language, star count, topics, and last-updated info).
- **Education & Certifications** including degrees and professional certificates (Google Data Analytics, Oracle Java SE 8, SAFe Agilist, Coursera/Stanford Machine Learning courses, and Andrew Ng's Machine Learning Certificate).
- **Contact** section with email, LinkedIn, GitHub, and Kaggle links.
- Scroll-triggered reveal animations and a responsive layout for mobile and desktop.

## Tech Stack

- HTML5 / CSS3 (custom properties, no framework)
- Vanilla JavaScript (no build step)
- [GitHub REST API](https://docs.github.com/en/rest) for live project listing
- Google Fonts (DM Serif Display, DM Mono, Outfit)
- [Vercel](https://vercel.com/) for hosting and deployment

## Project Structure

```
.
├── index.html      # Entire site: markup, styles, and scripts in one file
└── README.md
```

## Running Locally

No build tools or dependencies are required since this is a static, single-file site.

```bash
git clone https://github.com/poojachalla-dev/pooja-portfolio.git
cd pooja-portfolio
```

Then simply open `index.html` in a browser, or serve it locally:

```bash
npx serve .
```

## Deployment

This project is deployed on [Vercel](https://vercel.com/). Pushes to the main branch are automatically built and deployed.

To deploy manually with the Vercel CLI:

```bash
npm i -g vercel
vercel --prod
```

## Contact

- **Email:** [pooja.challa@outlook.com](mailto:pooja.challa@outlook.com)
- **LinkedIn:** [linkedin.com/in/poojachalla](https://www.linkedin.com/in/poojachalla)
- **GitHub:** [github.com/poojachalla-dev](https://github.com/poojachalla-dev)
- **Kaggle:** [kaggle.com/poojachalla10](https://www.kaggle.com/poojachalla10)

## License

This project is personal portfolio code. Feel free to use it as a structural reference, but please don't reuse the personal content, branding, or copy as-is.

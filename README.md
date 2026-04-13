# Karan Darji Portfolio

Professional portfolio website for Karan Darji, a cybersecurity architect focused on Zero Trust, SIEM/SOC engineering, endpoint hardening, and AI security governance.

Live site: [https://karandarjishack.github.io/](https://karandarjishack.github.io/)

## Overview

This repository contains a static personal website built for GitHub Pages. The site presents Karan's professional background, enterprise security experience, technical skills, certifications, selected projects, education, and contact information in a single responsive landing page.

The current implementation is intentionally lightweight:

- Single-file deployment with `index.html`
- Inline CSS and JavaScript for fast hosting on GitHub Pages
- Responsive layout for desktop and mobile
- SEO-ready metadata, Open Graph tags, and structured data
- Interactive UI elements including animated counters, section reveals, typed hero text, card tilt, and particle canvas effects

## Site Sections

- Hero introduction and value proposition
- About and cybersecurity focus areas
- Professional experience
- Technical skills
- Certifications
- Projects and research
- Education
- Contact and external profile links

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Font Awesome
- Google Fonts
- GitHub Pages
- HubSpot embed script

## Project Structure

```text
.
├── index.html
├── README.md
└── Karan-Darji-Resume.pdf
```

Notes:

- `index.html` contains the full site markup, styling, and behavior.
- `Karan-Darji-Resume.pdf` exists in the local project folder, but the live GitHub Pages repo may not include it unless it is explicitly added and linked.

## Running Locally

Because this is a static site, there is no build step.

Open `index.html` directly in a browser, or run a simple local server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment

This site is deployed through GitHub Pages from the `main` branch of:

`karandarjishack/karandarjishack.github.io`

Any committed changes pushed to `main` are published to:

[https://karandarjishack.github.io/](https://karandarjishack.github.io/)

## Maintenance Notes

When updating the site, review these items:

- Profile copy in the hero, about, experience, and project sections
- Contact links for GitHub, LinkedIn, Medium, and email
- SEO metadata in the `<head>` section
- JSON-LD structured data
- HubSpot script source and account ID
- GitHub Pages canonical URL

## Customization

Common edits are all handled in `index.html`:

- Update colors, spacing, and typography in the CSS variables near the top of the file
- Modify section content directly in the HTML
- Adjust animations and interactive behavior in the inline JavaScript near the bottom of the file
- Replace or expand project, certification, and experience entries as needed

## Professional Summary

The portfolio highlights work across:

- Enterprise security architecture
- SIEM and SOC engineering
- Zero Trust implementation
- Endpoint security at scale
- Vulnerability research and responsible disclosure
- AI security governance aligned to frameworks such as NIST and OWASP LLM Top 10

## Contact

- Email: `karandarji18@gmail.com`
- LinkedIn: [linkedin.com/in/karandarji18](https://www.linkedin.com/in/karandarji18/)
- GitHub: [github.com/karandarjishack](https://github.com/karandarjishack)
- Medium: [medium.com/@karandarjishack](https://medium.com/@karandarjishack)

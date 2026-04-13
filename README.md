# Karan Darji | Cybersecurity Architect Portfolio

[![Live Site](https://img.shields.io/badge/Live%20Site-karandarjishack.github.io-0a192f?style=for-the-badge&logo=githubpages)](https://karandarjishack.github.io/)
[![HTML5](https://img.shields.io/badge/HTML5-Static%20Site-E34F26?style=for-the-badge&logo=html5&logoColor=white)](./index.html)
[![CSS3](https://img.shields.io/badge/CSS3-Inline%20Styling-1572B6?style=for-the-badge&logo=css3&logoColor=white)](./index.html)
[![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111111)](./index.html)
[![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-222222?style=for-the-badge&logo=github)](https://karandarjishack.github.io/)

Professional portfolio site for **Karan Darji**, a cybersecurity architect focused on **Zero Trust**, **SIEM/SOC engineering**, **endpoint hardening**, **vulnerability research**, and **AI security governance**.

The site is built as a fast, single-page GitHub Pages experience that presents enterprise security work, technical depth, certifications, research, and contact channels in a format suitable for recruiters, hiring managers, consulting prospects, and collaborators.

## Live Website

**Production:** [https://karandarjishack.github.io/](https://karandarjishack.github.io/)

## Highlights

- Showcases security work spanning **285K+ endpoints secured**
- Highlights a **17% Microsoft Secure Score lift**
- Includes **4 Microsoft CVEs** from independent security research
- Features a **40% SOC triage time reduction** outcome
- Covers **AI security governance** across Claude, OpenAI, Gemini, and related enterprise workflows

## What This Repository Contains

This repository powers a responsive personal portfolio built for GitHub Pages. It is intentionally lightweight and deployment-friendly:

- **Single-file architecture** with markup, styles, and behavior in `index.html`
- **Responsive layout** for desktop and mobile
- **SEO-ready metadata** including canonical URL, Open Graph tags, Twitter card content, and JSON-LD structured data
- **Interactive frontend behavior** without a framework or build system
- **Direct GitHub Pages deployment** from the `main` branch

## Portfolio Sections

The site is organized into the following sections:

- Hero and professional positioning
- About and core cybersecurity domains
- Experience across enterprise security roles
- Skills and tooling
- Certifications and honors
- Projects and research
- Education
- Contact and external profiles

## Experience and Subject Areas Featured

The portfolio emphasizes work across:

- Enterprise security architecture
- Zero Trust identity and endpoint controls
- Microsoft security stack: Defender, Sentinel, Intune, Entra ID, Purview
- SIEM and SOC engineering with Splunk, Sentinel, and cross-platform telemetry
- Endpoint, mobile, email, and web security
- Vulnerability management and VAPT
- Cloud security across Azure and AWS
- AI governance, prompt injection risk, and enterprise LLM security controls

## UX and Technical Features

- Animated hero introduction with rotating typed statements
- Interactive particle canvas in the hero section
- Scroll-triggered reveal animations
- Animated achievement counters
- Tabbed experience section
- Hover tilt effects for certification and project cards
- Responsive desktop and mobile navigation
- Accessibility touches including skip link support and semantic landmarks

## Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Font Awesome
- Google Fonts
- HubSpot embed script
- GitHub Pages

## Repository Structure

```text
.
├── index.html
└── README.md
```

## Local Development

No build tooling is required.

Open the file directly in a browser:

```bash
open index.html
```

Or serve it locally:

```bash
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Deployment

This portfolio is published from:

```text
karandarjishack/karandarjishack.github.io
```

GitHub Pages deploys the site from the `main` branch. Any committed change pushed to `main` becomes the live site after GitHub Pages finishes publishing.

## Editing Guide

Most changes happen in `index.html`. Key update areas:

- **Branding and metadata**
  - `<title>`
  - meta description
  - canonical URL
  - Open Graph and Twitter metadata
  - JSON-LD person schema

- **Content sections**
  - `#hero`
  - `#about`
  - `#experience`
  - `#skills`
  - `#certifications`
  - `#projects`
  - `#education`
  - `#contact`

- **Styling**
  - CSS variables near the top of the file control colors, spacing, type scale, and motion behavior

- **Behavior**
  - Inline JavaScript near the bottom controls the loader, navigation, counters, animations, mobile menu, tabs, and particle canvas

## Maintenance Checklist

Before pushing updates, review:

- Career summary and metrics
- Experience bullets and project descriptions
- Certification list and dates
- Contact information and social links
- SEO metadata
- HubSpot script source
- External links for publications, CVEs, LinkedIn, GitHub, and Medium

## Why This Approach

This site uses a framework-free, single-file setup on purpose:

- minimal hosting overhead
- fast deployment through GitHub Pages
- easy edits without a build pipeline
- strong control over markup, animation, and metadata
- simple long-term maintenance for a personal brand site

## Contact

- Email: [karandarji18@gmail.com](mailto:karandarji18@gmail.com)
- LinkedIn: [linkedin.com/in/karandarji18](https://www.linkedin.com/in/karandarji18/)
- GitHub: [github.com/karandarjishack](https://github.com/karandarjishack)
- Medium: [medium.com/@karandarjishack](https://medium.com/@karandarjishack)

## License

This repository contains personal portfolio content and branding for Karan Darji. Reuse of the written content, identity, or presentation without permission is not intended.

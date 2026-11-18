# Manar Degachi — Developer Portfolio

A personal portfolio website showcasing my work, technical skills, experience, and certifications.

The portfolio presents my focus on **web and mobile application development**, with backend development and AI integration as complementary skills.

## Overview

This is a responsive, single-page portfolio built with plain HTML, CSS, and JavaScript. It uses a dark visual theme, animated details, and section-based navigation to bring professional information and selected projects together in one place.

### Portfolio sections

- **Introduction** — profile summary and quick links.
- **About** — education, background, languages, and current goals.
- **Domains** — mobile, frontend, backend, AI/LLM integration, databases, software testing, and cloud fundamentals.
- **Projects** — academic, internship, team, and personal projects.
- **Skills** — technologies and tools grouped by area.
- **Experience** — internships and other professional experience.
- **Certifications & Awards** — credentials and selected achievements.
- **Contact** — email, professional links, CV access, and a contact form.

## Featured projects

A selection of projects presented on the portfolio:

| Project | Description | Technologies |
|---|---|---|
| Raad — Delivery Platform | Ongoing academic project with mobile and web applications backed by an API. | Kotlin, React Native, Angular, FastAPI, Firebase |
| Vesta — Real-Estate Rental App | Rental listing application developed in Flutter and React Native, using a shared Firebase backend. | Flutter, React Native, Firebase, OpenStreetMap |
| LeakLens | Water-consumption analysis prototype that flags possible hidden leaks and explains its findings. | Flutter, FastAPI, MongoDB, HTML, CSS, JavaScript |
| Innera — Community Platform | Private community application with posts, comments, profiles, administration, workflow automation, and an AI assistant. | Angular, Firebase, Make.com |
| E-commerce Website | Full-stack shopping application with product, authentication, and cart flows. | Angular, Spring Boot, PostgreSQL, Redis |
| Building Reservation System | Application for managing building reservations. | Laravel, PHP, Livewire, Tailwind CSS, SQLite |

The website includes additional projects and links to selected repositories.

## Tech stack

- **Structure:** HTML5
- **Styling:** CSS3, responsive layouts, CSS animations
- **Interactivity:** Vanilla JavaScript
- **Typography:** Google Fonts — Cormorant Garamond, DM Sans, and DM Mono
- **Contact form:** Formspree
- **Hosting:** Static-site compatible; the repository includes a `.nojekyll` file for GitHub Pages compatibility.

No frontend framework, package manager, or build step is required.

## Repository structure

```text
Portfolio/
├── .github/
├── certificates/
│   ├── Atlassian_ITSM.pdf
│   ├── Career_Essentials_Cybersecurity.pdf
│   ├── Docker_Foundations.pdf
│   └── ...
├── .gitignore
├── .nojekyll
├── index.html
├── pdp.jpg
└── ManarDegachi_CV_Internship_PFE2027EN.pdf
```

## Run locally

1. Clone the repository:

   ```bash
   git clone https://github.com/manar09-code/Portfolio.git
   ```

2. Open the project folder.
3. Open `index.html` in your browser.

You can also use a local development server, such as the VS Code Live Server extension.

## Configuration notes

- The profile image is loaded from `./pdp.jpg`.
- Certificate proof documents are stored in the `certificates/` directory and referenced from the JavaScript certificate map in `index.html`.
- The contact form submits to Formspree. To use your own form endpoint, update the Formspree form ID in the contact-form script.
- Update the CV filename in the page if the PDF is renamed.

## Author

**Manar Degachi**  
Final-year IT student · Web & Mobile Application Development

- GitHub: [manar09-code](https://github.com/manar09-code)
- LinkedIn: [manar-degachi](https://linkedin.com/in/manar-degachi)
- Email: [manardg09@gmail.com](mailto:manardg09@gmail.com)

---

This repository contains the source code and assets for my personal portfolio.

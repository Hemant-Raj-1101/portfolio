# Hemant Raj | ECE Portfolio

A personal portfolio website for **Hemant Raj**, a B.Tech Electronics & Communication Engineering student at **VIT Bhopal University** (2025–29), interested in Embedded Systems, VLSI Design and AI-integrated engineering.

**Live site:** https://hemant-raj-1101.github.io

## Features

- Dark, futuristic UI with a glassmorphism look and animated particle background
- Custom cursor glow and animated grid background
- Typing animation cycling through role titles
- Scroll-reveal animations and active navigation highlighting
- Fully responsive layout with a hamburger menu on mobile
- Working contact form powered by EmailJS (no backend needed)

## Sections

Home (intro, photo, typed roles, GitHub and LinkedIn links), About (bio, stats, education timeline), Skills, Projects (featured project), Certs (Embedded Systems Design, VLSI Design Fundamentals, C/C++ Programming), Contact (details and message form).

## Featured Project

**Adaptive Risk-Aware Braking & Intelligent Driver Safety System**: an Arduino-based embedded safety system that monitors driver behaviour and environmental conditions in real time and decides warning intensity and braking response from a computed risk level.

- Alcohol detection (MQ-3), smoke detection (MQ-2)
- Drowsiness monitoring (IR) and accident detection (vibration sensor)
- Intelligent Driver Safety Score
- SD card blackbox logging, RGB indicators and LCD display

## Tech Stack

HTML5, CSS3, vanilla JavaScript, Canvas API (particles), IntersectionObserver (scroll reveal), EmailJS (contact form), Font Awesome, Orbitron and DM Sans fonts, hosted on GitHub Pages.

## Project Structure

```
index.html   (markup and content)
style.css    (styling and theme)
script.js    (animations, navigation, contact form)
README.md
```

## Run Locally

No build step. Clone the repo and open `index.html`, or run a local server:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000

## Customise

- **Content:** edit the text in `index.html`
- **Typed role titles:** edit the `roles` array in `script.js`
- **Colours and fonts:** edit the CSS variables at the top of `style.css`
- **Contact form:** replace the EmailJS public key in `index.html` and the service/template IDs in `script.js` with your own

## Contact

- Email: hemantraj1101@gmail.com
- GitHub: https://github.com/Hemant-Raj-1101
- LinkedIn: http://www.linkedin.com/in/hemant-raj-b54438380

Designed and built by Hemant Raj.

# Hemant Raj | ECE Portfolio

A personal portfolio website for **Hemant Raj**, a B.Tech Electronics & Communication Engineering student at **VIT Bhopal University** (2025–29), interested in Embedded Systems, VLSI Design and AI-integrated engineering.

**Live site:** https://hemant-raj-1101.github.io

---

## Features

- Dark, futuristic UI with a glassmorphism look and animated particle background
- Custom cursor glow and animated grid background
- Typing animation cycling through role titles
- Scroll-reveal animations and active navigation highlighting
- Fully responsive layout with a hamburger menu on mobile
- Working contact form powered by [EmailJS](https://www.emailjs.com/) (no backend needed)

## Sections

| Section | What it shows |
|---|---|
| Home | Intro, photo, typed role titles, GitHub and LinkedIn links |
| About | Bio, quick stats and education timeline |
| Skills | Programming, embedded and hardware, ECE domains, professional skills |
| Projects | Featured project details, features and technologies |
| Certs | Embedded Systems Design, VLSI Design Fundamentals, C/C++ Programming |
| Contact | Contact details and a message form |

## Featured Project

**Adaptive Risk-Aware Braking & Intelligent Driver Safety System**
An Arduino-based embedded safety system that monitors driver behaviour and environmental conditions in real time and decides warning intensity and braking response from a computed risk level.

- Alcohol detection (MQ-3), smoke detection (MQ-2)
- Drowsiness monitoring (IR) and accident detection (vibration sensor)
- Intelligent Driver Safety Score
- SD card blackbox logging, RGB indicators and LCD display

## Tech Stack

- **HTML5**, **CSS3**, **JavaScript (vanilla)**
- **Canvas API** for the particle background
- **IntersectionObserver** for scroll reveals
- **EmailJS** for the contact form
- **Font Awesome** icons, **Orbitron** and **DM Sans** fonts (Google Fonts)
- Hosted on **GitHub Pages**

## Project Structure

```
HemantRaj1101.github.io/
├── index.html   # Page markup and content
├── style.css    # Styling, theme and responsive rules
├── script.js    # Animations, navigation and contact form logic
└── README.md
```

## Run Locally

No build step is required.

```bash
git clone https://github.com/Hemant-Raj-1101/HemantRaj1101.github.io.git
cd HemantRaj1101.github.io
```

Then open `index.html` in your browser, or serve it with any static server:

```bash
python -m http.server 8000
# visit http://localhost:8000
```

## Customise

- **Content:** edit the text in `index.html`
- **Typed role titles:** edit the `roles` array in `script.js`
- **Colours and fonts:** edit the CSS variables at the top of `style.css`
- **Contact form:** replace the EmailJS public key in `index.html` and the service and template IDs in `script.js` with your own

## Contact

- Email: [hemantraj1101@gmail.com](mailto:hemantraj1101@gmail.com)
- GitHub: [Hemant-Raj-1101](https://github.com/Hemant-Raj-1101)
- LinkedIn: [hemant-raj-b54438380](http://www.linkedin.com/in/hemant-raj-b54438380)

---

Designed and built by Hemant Raj.

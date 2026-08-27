# atharvanikam.github.io

Personal portfolio site for **Atharva Nikam** — Mechatronics Engineer (M.Sc.), focused on EV powertrain and battery thermal simulation, MATLAB/Simulink modeling, and hardware validation.

**Live:** https://atharvaajaynikam4601-netizen.github.io/atharvanikam.github.io/

## Stack

Static site — vanilla HTML, CSS, and JavaScript. No build step, no framework, no dependencies. Fonts loaded from Google Fonts (Space Grotesk, Inter, JetBrains Mono); everything else is self-contained.

## Structure

```
index.html          Page markup and content (About, Experience, Projects, Skills, Contact)
style.css            Dark-theme design system, layout, animations
script.js             Scroll reveal, active-nav tracking, typed-text hero, stat counters, card tilt
assets/
  img/                Profile photo, project screenshots/charts
  resume/             Downloadable resume PDF
  cert/               Certificate PDF(s) linked from project cards
```

## Running locally

No build tools required — serve the directory with any static file server, e.g.:

```bash
python -m http.server 5173
```

then open `http://localhost:5173`.

## Deployment

Served directly via GitHub Pages from the `main` branch of this repository (root).

## Contact

- Email: atharvaajaynikam4601@gmail.com
- LinkedIn: https://www.linkedin.com/in/atharva--nikam/
- GitHub: https://github.com/atharvaajaynikam4601-netizen

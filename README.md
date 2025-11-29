# Harsh Singh — Portfolio

**React (Vite) portfolio** built with CSS Modules and Framer Motion.  
Dark theme, responsive design, project thumbnails and a contact form.  
This repo contains the full source and instructions to run locally and deploy.

---

## Live demo
(Replace with your Netlify/Vercel URL after deployment)

---

## Tech stack
- React (Vite)
- CSS Modules
- Framer Motion
- Deployed on Netlify (instructions below)

---

## Repo structure (important files)
harsh-portfolio/
├─ public/
│ └─ HarshResume.pdf
├─ src/
│ ├─ assets/
│ │ ├─ profile.jpg
│ │ └─ projects/
│ │ ├─ sensor-thumb.jpg
│ │ ├─ ar-thumb.jpg
│ │ └─ (other thumbs/screenshots)
│ ├─ components/
│ │ └─ ProjectModal.jsx
│ ├─ App.jsx
│ ├─ App.module.css
│ ├─ main.jsx
│ └─ index.css
├─ .gitignore
├─ _redirects
├─ package.json
└─ README.md

yaml
Copy code

---

## Run locally (development)
1. Install dependencies:
```bash
npm install
Start dev server:

bash
Copy code
npm run dev
Open: http://localhost:5173/

Build for production:

bash
Copy code
npm run build
Preview production build locally:

bash
Copy code
npm run preview

# Johair M. Tucodan — Portfolio

A complete responsive single-page portfolio built with React, TypeScript and Vite. All content and images are bundled locally. No backend, account or API key is required.

## Run locally

Install Node.js 22.13 or newer (a current LTS version is recommended). Extract the ZIP, open a terminal in the `johair-portfolio` folder, then run:

```sh
npm install
npm run dev
```

Open the local URL printed in the terminal (normally http://localhost:5173). This works from PowerShell, Command Prompt, macOS Terminal or Linux.

## Build and preview

```sh
npm run build
npm run preview
```

The production website is generated in `dist/`. To view the included prebuilt version without installing Node dependencies, run `python -m http.server 8000 --directory dist` if Python is installed, then visit http://localhost:8000. Use a local server rather than double-clicking index.html.

## Edit your portfolio

- `src/App.tsx`: your personal information, skills, projects and contact details. Reusable section and project components are in this file.
- `src/styles.css`: colors, layout, responsive breakpoints and animation. Main theme variables are at the top.
- `public/images/`: your original uploaded Roblox game screenshots. They are visually cropped with CSS, preserving image proportions.
- `public/favicon.svg`: the JT favicon.
- `index.html`: title and search-engine description.

Add your actual GitHub, LinkedIn or Roblox profile URLs to the `socialLinks` array in `src/App.tsx` to display them. Empty social profiles are hidden. No project links are invented.

DAMS and Lakbay visuals are labeled illustrative concepts, not actual screenshots. Replace these with your own screenshots when available. Roblox thumbnails use your supplied images.

## Contact form

The form validates required fields and opens a draft in the visitor's default email application. The visitor must review and send that draft. The site does not send, store or claim delivery of any messages. Direct email and phone links also work.

## Accessibility and behavior

Semantic sections, labeled form fields, visible keyboard focus, skip link, keyboard-accessible project tabs, mobile navigation with Escape-to-close, active navigation, smooth scrolling, scroll-to-top, and reduced-motion support are included. Skills have no artificial ratings.

## Validation

Both the React TypeScript source and production build were checked. Images were verified against the supplied originals. Desktop, tablet and mobile breakpoints are included. Automated browser-based visual testing was unavailable in the build environment.

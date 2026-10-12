# Responsive Design Tokens & Mobile-First CSS Architecture

Pulse Studio is a responsive dashboard demo built with semantic HTML, CSS custom properties, CSS Grid, Flexbox, and vanilla JavaScript.

## Features
- Reusable design tokens for brand colors, surfaces, typography, spacing, radii, shadows, blur, and transitions.
- Light/dark theme via CSS variables and persisted preference.
- Mobile-first breakpoints at 540px, 768px, 1024px, and 1280px.
- Grid-based statistics and panels; Flexbox for navigation, headings, and controls.
- Glass-like surfaces, soft shadows, responsive navigation, reduced-motion support, and visible keyboard focus.
- Create-task dialog with validation and focus return; sample activity actions.

## Run locally
1. Extract the ZIP and open this folder in VS Code.
2. Open `index.html` in a browser, or use VS Code Live Server.
3. Resize to 320px, 375px, 540px, 768px, 1024px, and 1440px.

## Files
- `index.html` — dashboard markup
- `css/style.css` — design tokens and responsive styles
- `js/app.js` — theme, navigation, dialog, and activity interactions
- `screenshots/README.md` — screenshot evidence instructions

## Verification checklist
- [ ] Test navigation and keyboard controls.
- [ ] Toggle both themes.
- [ ] Submit an empty/short task name and confirm validation.
- [ ] Create a task and confirm it appears in activity.
- [ ] Check 320px, 375px, 768px, 1024px, and desktop widths.
- [ ] Confirm no horizontal page scrollbar at mobile sizes.
- [ ] Check contrast in both themes and capture genuine mobile/tablet/desktop screenshots.

## Limitations
This is a front-end demonstration with sample data. It has no backend or database, and new activity is not persisted after refresh. Verify browser rendering, contrast, and mobile overflow before claiming those checks have passed.

## Push to GitHub
```bash
git init
git add .
git commit -m "Build responsive design token dashboard"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```
Replace the example URL with your actual repository. If a remote already exists, run `git remote -v` before adding another.

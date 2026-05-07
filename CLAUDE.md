# Bella Page — SDN 3 Kesiman Graduation Checker

## Project Purpose
A single-page web app for SDN 3 Kesiman (Indonesian primary school) that lets students check their graduation status by entering their full name. The page displays a LULUS (pass) or BELUM LULUS (fail) result with animations.

## Tech Stack & Constraints
- Pure HTML/CSS/JS — single `index.html` file, no build tools, no npm
- Hosted on **GitHub Pages** — no external services, no backend, no APIs
- All assets must live in this repository
- Google Fonts (Poppins) is the only allowed external resource

## Language
- **Everything on the page must be in Indonesian (Bahasa Indonesia)**
- Student names are stored as-is (Indonesian/Balinese names)

## Data
- `const lulus` — array of student names who passed (~70 students)
- `const tidakLulus` — array of student names who did not pass (~7 students)
- Name matching is case-insensitive, trimmed, normalized whitespace
- Special "rajin" mode: if the input contains the word "rajin", the student is shown as LULUS regardless

## Current Features
- Starfield background animation
- Glassmorphism card UI (dark theme, cyan/purple gradient)
- Loading dots animation before showing result
- Confetti effect on LULUS result
- Enter key support for form submission

## Desired Improvements
- Better/richer animations for the LULUS (pass) result
- Better/richer animations for the BELUM LULUS (fail) result
- Both result states should have visually distinct and polished animated presentations

## Key Files
- `index.html` — entire app (HTML + CSS + JS in one file)

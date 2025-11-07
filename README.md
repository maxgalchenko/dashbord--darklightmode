# Dashboard — Dark/Light Mode

<div align="center">

![React](https://img.shields.io/badge/React-17-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Create React App](https://img.shields.io/badge/Create%20React%20App-4.0.1-09D3AC?style=for-the-badge&logo=create-react-app&logoColor=white)
![styled-components](https://img.shields.io/badge/styled--components-5.2-DB7093?style=for-the-badge&logo=styled-components&logoColor=white)
![React Router](https://img.shields.io/badge/React%20Router-5.2-CA4245?style=for-the-badge&logo=react-router&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

</div>

## Overview

A simple dashboard UI demonstrating dark/light and multi-theme switching using styled-components. Built with Create React App and React 17. Useful as a learning reference for themeable UI patterns.

## Key Features

- Multiple color themes (light, dark, darkBlue, purple, videoGame) with live switching
- Global theming via styled-components `ThemeProvider` and `GlobalStyles`
- Clean dashboard layout with sidebar, navigation, and deposits list

## Tech Stack

React 17, Create React App (react-scripts 4), styled-components 5, React Router 5, JavaScript (ES6+)

## Architecture

SPA organized under `src/` with presentational components in `components/` and layout in `containers/`. Theme state in `App` drives `ThemeProvider`; global styles applied via `GlobalStyles`. Assets in `public/` and `src/assets/`.

## Performance & Accessibility

Lightweight CRA app; CSS-in-JS theme variables to avoid reflow-heavy DOM updates. Basic a11y helpers (e.g., `.visually-hidden`), semantic HTML, and readable color contrast across themes.

## Quality

- Linting: ESLint (react-app) • Formatting: N/A
- Type safety: JavaScript (no TypeScript)
- Tests: Testing Library deps present; no tests included
- CI: Not configured

## Prerequisites

- Node.js: `>=14`

## Installation

```bash
git clone https://github.com/maxgalchenko/dashbord--darklightmode.git
cd dashbord--darklightmode
npm install
```

## Quick Start

```bash
npm start
# Production build
npm run build
# Serve the 'build' folder with any static server
```

Open http://localhost:3000

## Available Scripts

- `npm start` – Start the development server at http://localhost:3000
- `npm run build` – Build optimized production assets to `build/`
- `npm test` – Run tests in watch mode (no tests included)
- `npm run eject` – Eject CRA configuration (one-way)

---

<div align="center">

Built with ❤️ by [Maksym Galchenko](https://github.com/maxgalchenko)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/galchenko-max/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-green?style=for-the-badge&logo=web)](https://portfolio-green-six-29.vercel.app/)
[![Email](https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail)](mailto:galchenko.maksym@gmail.com)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

</div>

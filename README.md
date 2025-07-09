# Vanilla JS + TypeScript Bootstrap Starter

A minimal, modern starter template for building web pages and apps with **Vanilla JavaScript** and **TypeScript**.

---

## Major Features

- ⚡️ Fast dev server & build with [Vite](https://vitejs.dev/)
- 🟦 TypeScript support
- 🎨 Sass for advanced CSS
- 📋 Auto-formatting with [Prettier](https://prettier.io/) (format-on-save, VS Code ready)
- 🧹 Linting with [ESLint](https://eslint.org/) (modern JS/TS, browser globals)
- ♿ Accessibility (a11y) testing with [Pa11y CI](https://github.com/pa11y/pa11y-ci) (WCAG 2.1 AA)
- 🏷️ Semantic HTML and SEO checks with [HTMLHint](https://htmlhint.com/)
- 📑 Combined linting and accessibility reports (JSON/text output in `log/`)

---
## Pre requisites
Recommended Node Version: 20+

## Getting Started

1. **Install dependencies:**
   ```sh
   npm install
   ```
2. **Start the dev server:**
   ```sh
   npm run dev
   ```
3. **Build for production:**
   ```sh
   npm run build
   npm run preview
   ```
4. **Lint, HTMLHint, and Accessibility:**
   - `npm run lint` — Lint JS/TS
   - `npm run fmt` - Formatting
   - `npm run htmlhint` — Lint HTML
   - `npm run pa11y-ci` — Accessibility check
   - `npm run lint:all` — Run all checks
   - `npm run lint:logs` — Output reports to `log/`

---

## Project Structure

```
vanilla-js/
├── index.html             # Main HTML file
├── package.json           # Project metadata & scripts
├── package-lock.json      # Dependency lockfile
├── src/                   # Source code (TypeScript, styles)
├── tsconfig.json          # TypeScript config
├── eslint.config.js       # ESLint config
├── .htmlhintrc            # HTMLHint config
├── .pa11yci               # Pa11y CI config
├── .prettierrc            # Prettier config
├── .vscode/settings.json  # VS Code workspace settings
├── log/                   # Linting and accessibility reports
├── README.md              # Project documentation
├── LICENSE                # Project license
└── ...                    # Other config and dotfiles
```

---

## Deployment

This project is fully compatible with GitHub Pages and can be easily deployed there for free static site hosting.

---

## License

[MIT](./LICENSE)

# Vanilla JS + TypeScript Bootstrap Starter

A minimal, modern starter template for building web pages and apps with **Vanilla JavaScript** and **TypeScript**. This project structure is designed for real-world development, emphasizing maintainability, scalability, and best practices for modern web applications.

---

## Major Features

- ⚡️ Fast dev server & build with [Vite](https://vitejs.dev/)
- 🟦 TypeScript support
- 🎨 Sass for advanced CSS (modular, reusable structure)
- 📋 Auto-formatting with [Prettier](https://prettier.io/) (format-on-save, VS Code ready)
- 🧹 Linting with [ESLint](https://eslint.org/) (modern JS/TS, browser globals)
- ♿ Accessibility (a11y) testing with [Pa11y CI](https://github.com/pa11y/pa11y-ci) (WCAG 2.1 AA)
- 🏷️ Semantic HTML and SEO checks with [HTMLHint](https://htmlhint.com/)
- 📑 Combined linting and accessibility reports (JSON/text output in `log/`)

---

## Pre requisites

Recommended Node Version: 20+

---

## Editor Compatibility

- **VS Code**: Out-of-the-box support for format-on-save, Prettier, and workspace settings via `.vscode/settings.json`.
- **EditorConfig**: Ensures consistent indentation and line endings across all major editors (VS Code, WebStorm, Sublime, Atom, etc.).
- **Prettier**: Auto-formats code on save for all supported file types.
- **Other Editors**: Most modern editors support EditorConfig and Prettier via plugins or built-in features.

---

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
   - `npm run fmt` — Formatting
   - `npm run htmlhint` — Lint HTML
   - `npm run pa11y-ci` — Accessibility check
   - `npm run lint:all` — Run all checks
   - `npm run lint:logs` — Output reports to `log/`

---

## SASS File Structure for Real-World Reusability

The `src/styles/` directory is organized for scalable, maintainable styling in large projects:

```
src/styles/
├── index.scss        # Main entry point, imports all partials
├── _variables.scss   # Design tokens: colors, spacing, fonts, etc.
├── _mixins.scss      # Reusable mixins (media queries, helpers)
├── _reset.scss       # CSS reset/normalize
├── _components.scss  # (Optional) Component-level styles
├── _layout.scss      # (Optional) Layout/grid helpers
└── ...               # Add more partials as your project grows
```

- **index.scss**: Import all partials here; import only this file in your app entry.
- **\_variables.scss**: Central place for all design tokens for easy theming.
- **\_mixins.scss**: Store all mixins/functions for DRY code.
- **\_reset.scss**: Normalize browser styles for consistency.
- **\_components.scss, \_layout.scss**: Organize styles by responsibility for real-world scalability.

---

## Project Structure

```
vanilla-js/
├── index.html             # Main HTML file
├── package.json           # Project metadata & scripts
├── package-lock.json      # Dependency lockfile
├── src/                   # Source code (TypeScript, styles)
│   └── styles/            # SASS structure (see above)
├── tsconfig.json          # TypeScript config
├── eslint.config.js       # ESLint config
├── .htmlhintrc            # HTMLHint config
├── .pa11yci               # Pa11y CI config
├── .prettierrc            # Prettier config
├── .editorconfig          # EditorConfig rules
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

# Vanilla JS + TypeScript Bootstrap Starter

A minimal, modern starter template for building web pages and apps with **Vanilla JavaScript** and **TypeScript**. Powered by [Vite](https://vitejs.dev/) for lightning-fast development, [ESLint](https://eslint.org/) for code quality, and [Sass](https://sass-lang.com/) for styling.


## Features
- ⚡️ Fast dev server & build with Vite
- 🟦 TypeScript support out of the box
- 🧹 Linting with ESLint (flat config, browser globals, best practices)
- 🎨 Sass for advanced CSS
- 🗂 Simple, clean project structure


## Getting Started

### 1. Install dependencies
```sh
npm install
```

### 2. Start the development server
```sh
npm run dev
```
Visit [http://localhost:5173](http://localhost:5173) to see your app.

### 3. Build for production and preview
```sh
npm run build
npm run preview
```

### 4. Linting and formatting your code
```sh
npm run lint
npm run fmt
```

## Deployment

This project is fully compatible with GitHub Pages and can be easily deployed there for free static site hosting.

If you plan to deploy to GitHub Pages, update the `base` option in `vite.config.js` to match your repository name:

Always build before pushing your changes for latest deployment.
## Project Structure

```
vanilla-js/
├── index.html           # Main HTML file
├── package.json         # Project metadata & scripts
├── public/              # Static assets (served as-is, e.g., robots.txt, images)
├── assets/              # Optimized assets (processed by Vite/plugins)
├── src/                 # Source code (TypeScript, styles)
├── tsconfig.json        # TypeScript config
├── eslint.config.js     # ESLint config
├── README.md            # Project documentation
└── ...                  # Other config and lock files
├── LICENSE              # Project license
```


## License
[MIT](./LICENSE)
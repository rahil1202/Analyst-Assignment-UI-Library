# My UI Library Monorepo 🚀

This monorepo contains a simple UI library with a counter component using Snabbdom.

## Project Structure 📂

The project follows a monorepo structure using Lerna:

```plaintext
mono-repo/
  ├── packages/
  │   ├── ui-components/
  │   │   ├── src/
  │   │   │   ├── Counter.js
  │   │   │   └── App.js
  │   │   
  │   └── test/
  │   |    └── ui-library.test.js
  |   └── lib/
  │       └── ui-library.js
  |        ── index.js  
  |  
  ├── lerna.json
  ├── package.json
  ├── index.html
  └── app.js
```

## About Lerna 🛠️

[Lerna](https://lerna.js.org/) is a tool optimized for managing JavaScript projects with multiple packages. It optimizes the workflow around managing multi-package repositories with git and npm.

### Benefits of Lerna:
- **Monorepo Structure:** Allows managing multiple packages within a single repository.
- **Versioning:** Provides versioning for packages independently or in a unified manner.
- **Cross-Dependency Management:** Simplifies linking and testing across packages.

## About Snabbdom 🌐

[Snabbdom](https://github.com/snabbdom/snabbdom) is a fast, modular, and concise virtual DOM library for JavaScript. It provides efficient rendering and updating of UI components.

### Benefits of Snabbdom:
- **Performance:** Optimized for speed with a focus on minimal overhead.
- **Modularity:** Allows using only the necessary modules for a minimal bundle size.
- **Simple API:** Provides a clean and straightforward API for creating virtual DOM elements.
